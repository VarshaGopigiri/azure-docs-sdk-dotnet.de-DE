<Type Name="VaultProperties" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties">
  <TypeSignature Language="C#" Value="public class VaultProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultProperties" />
  <TypeSignature Language="F#" Value="type VaultProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e686-101">Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="8e686-101">Properties of the vault</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e686-102">Initialisiert eine neue Instanz der VaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8e686-102">Initializes a new instance of the VaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties (Guid tenantId, Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku sku, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; accessPolicies, string vaultUri = null, Nullable&lt;bool&gt; enabledForDeployment = null, Nullable&lt;bool&gt; enabledForDiskEncryption = null, Nullable&lt;bool&gt; enabledForTemplateDeployment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid tenantId, class Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; accessPolicies, string vaultUri, valuetype System.Nullable`1&lt;bool&gt; enabledForDeployment, valuetype System.Nullable`1&lt;bool&gt; enabledForDiskEncryption, valuetype System.Nullable`1&lt;bool&gt; enabledForTemplateDeployment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.#ctor(System.Guid,Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku,System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties : Guid * Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties (tenantId, sku, accessPolicies, vaultUri, enabledForDeployment, enabledForDiskEncryption, enabledForTemplateDeployment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" />
        <Parameter Name="accessPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt;" />
        <Parameter Name="vaultUri" Type="System.String" />
        <Parameter Name="enabledForDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForDiskEncryption" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForTemplateDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="tenantId"><span data-ttu-id="8e686-103">Die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8e686-103">The Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span></param>
        <param name="sku"><span data-ttu-id="8e686-104">SKU-Informationen</span><span class="sxs-lookup"><span data-stu-id="8e686-104">SKU details</span></span></param>
        <param name="accessPolicies"><span data-ttu-id="8e686-105">Ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen.</span><span class="sxs-lookup"><span data-stu-id="8e686-105">An array of 0 to 16 identities that have access to the key vault.</span></span> <span data-ttu-id="8e686-106">Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.</span><span class="sxs-lookup"><span data-stu-id="8e686-106">All identities in the array must use the same tenant ID as the key vault's tenant ID.</span></span></param>
        <param name="vaultUri"><span data-ttu-id="8e686-107">Der URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche.</span><span class="sxs-lookup"><span data-stu-id="8e686-107">The URI of the vault for performing operations on keys and secrets.</span></span></param>
        <param name="enabledForDeployment"><span data-ttu-id="8e686-108">Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.</span><span class="sxs-lookup"><span data-stu-id="8e686-108">Property to specify whether Azure Virtual Machines are permitted to retrieve certificates stored as secrets from the key vault.</span></span></param>
        <param name="enabledForDiskEncryption"><span data-ttu-id="8e686-109">Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="8e686-109">Property to specify whether Azure Disk Encryption is permitted to retrieve secrets from the vault and unwrap keys.</span></span></param>
        <param name="enabledForTemplateDeployment"><span data-ttu-id="8e686-110">Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="8e686-110">Property to specify whether Azure Resource Manager is permitted to retrieve secrets from the key vault.</span></span></param>
        <summary>
            <span data-ttu-id="8e686-111">Initialisiert eine neue Instanz der VaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8e686-111">Initializes a new instance of the VaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; AccessPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; AccessPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.AccessPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessPolicies As IList(Of AccessPolicyEntry)" />
      <MemberSignature Language="F#" Value="member this.AccessPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.AccessPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accessPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.AccessPolicyEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-112">Ruft ab oder legt ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen.</span><span class="sxs-lookup"><span data-stu-id="8e686-112">Gets or sets an array of 0 to 16 identities that have access to the key vault.</span></span> <span data-ttu-id="8e686-113">Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.</span><span class="sxs-lookup"><span data-stu-id="8e686-113">All identities in the array must use the same tenant ID as the key vault's tenant ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-114">Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.</span><span class="sxs-lookup"><span data-stu-id="8e686-114">Gets or sets property to specify whether Azure Virtual Machines are permitted to retrieve certificates stored as secrets from the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDiskEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDiskEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDiskEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDiskEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDiskEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDiskEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-115">Ruft ab, oder legt ihn fest Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="8e686-115">Gets or sets property to specify whether Azure Disk Encryption is permitted to retrieve secrets from the vault and unwrap keys.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForTemplateDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForTemplateDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForTemplateDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForTemplateDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForTemplateDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForTemplateDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-116">Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="8e686-116">Gets or sets property to specify whether Azure Resource Manager is permitted to retrieve secrets from the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-117">Ruft ab oder legt ihn fest SKU-details</span><span class="sxs-lookup"><span data-stu-id="8e686-117">Gets or sets SKU details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-118">Ruft ab oder legt die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8e686-118">Gets or sets the Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="vaultProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e686-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8e686-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e686-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8e686-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VaultUri">
      <MemberSignature Language="C#" Value="public string VaultUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.VaultUri" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultUri As String" />
      <MemberSignature Language="F#" Value="member this.VaultUri : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultProperties.VaultUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vaultUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e686-121">Ruft ab oder legt den URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche fest.</span><span class="sxs-lookup"><span data-stu-id="8e686-121">Gets or sets the URI of the vault for performing operations on keys and secrets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>