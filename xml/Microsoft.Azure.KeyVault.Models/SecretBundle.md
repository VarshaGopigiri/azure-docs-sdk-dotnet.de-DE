<Type Name="SecretBundle" FullName="Microsoft.Azure.KeyVault.Models.SecretBundle">
  <TypeSignature Language="C#" Value="public class SecretBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecretBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SecretBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class SecretBundle" />
  <TypeSignature Language="F#" Value="type SecretBundle = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d56e9-101">Ein Wert, der Id und der zugehörigen Attribute besteht eine geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="d56e9-101">A secret consisting of a value, id and its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-102">Initialisiert eine neue Instanz der SecretBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d56e9-102">Initializes a new instance of the SecretBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretBundle (string value = null, string id = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string kid = null, Nullable&lt;bool&gt; managed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, string id, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string kid, valuetype System.Nullable`1&lt;bool&gt; managed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretBundle.#ctor(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As String = null, Optional id As String = null, Optional contentType As String = null, Optional attributes As SecretAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional kid As String = null, Optional managed As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SecretBundle : string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.KeyVault.Models.SecretBundle" Usage="new Microsoft.Azure.KeyVault.Models.SecretBundle (value, id, contentType, attributes, tags, kid, managed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="d56e9-103">Der geheime Wert.</span><span class="sxs-lookup"><span data-stu-id="d56e9-103">The secret value.</span></span></param>
        <param name="id"><span data-ttu-id="d56e9-104">Der Id.</span><span class="sxs-lookup"><span data-stu-id="d56e9-104">The secret id.</span></span></param>
        <param name="contentType"><span data-ttu-id="d56e9-105">Der Inhaltstyp des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="d56e9-105">The content type of the secret.</span></span></param>
        <param name="attributes"><span data-ttu-id="d56e9-106">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="d56e9-106">The secret management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="d56e9-107">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="d56e9-107">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="kid"><span data-ttu-id="d56e9-108">Wenn es sich um einen geheimen Schlüssel Sichern eines Zertifikats KV handelt, gibt dieses Feld den entsprechenden Schlüssel des Zertifikats KV sichern.</span><span class="sxs-lookup"><span data-stu-id="d56e9-108">If this is a secret backing a KV certificate, then this field specifies the corresponding key backing the KV certificate.</span></span></param>
        <param name="managed"><span data-ttu-id="d56e9-109">"True", wenn der geheime Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="d56e9-109">True if the secret's lifetime is managed by key vault.</span></span> <span data-ttu-id="d56e9-110">Wenn es sich um einen geheimen Sicherungsspeicher handelt werden "true" ein Zertifikat, klicken Sie dann verwaltet.</span><span class="sxs-lookup"><span data-stu-id="d56e9-110">If this is a secret backing a certificate, then managed will be true.</span></span></param>
        <summary>
            <span data-ttu-id="d56e9-111">Initialisiert eine neue Instanz der SecretBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d56e9-111">Initializes a new instance of the SecretBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SecretAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SecretAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As SecretAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SecretAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.SecretAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-112">Ruft ab oder legt die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="d56e9-112">Gets or sets the secret management attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-113">Ruft ab oder legt den Inhaltstyp des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="d56e9-113">Gets or sets the content type of the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-114">Ruft ab oder legt die Id für den geheimen.</span><span class="sxs-lookup"><span data-stu-id="d56e9-114">Gets or sets the secret id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-115">Ruft ab, ob dies ein geheimer Schlüssel Sichern eines Zertifikats KV dieses Feld den entsprechenden Schlüssel sichern das Zertifikat KV gibt.</span><span class="sxs-lookup"><span data-stu-id="d56e9-115">Gets if this is a secret backing a KV certificate, then this field specifies the corresponding key backing the KV certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Managed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Managed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Managed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Managed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Managed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Managed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Managed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-116">Ruft "true", wenn der geheime Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="d56e9-116">Gets true if the secret's lifetime is managed by key vault.</span></span> <span data-ttu-id="d56e9-117">Wenn es sich um einen geheimen Sicherungsspeicher handelt werden "true" ein Zertifikat, klicken Sie dann verwaltet.</span><span class="sxs-lookup"><span data-stu-id="d56e9-117">If this is a secret backing a certificate, then managed will be true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.SecretIdentifier SecretIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.SecretIdentifier SecretIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.SecretIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretIdentifier As SecretIdentifier" />
      <MemberSignature Language="F#" Value="member this.SecretIdentifier : Microsoft.Azure.KeyVault.SecretIdentifier" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.SecretIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.SecretIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-118">Der Bezeichner für die geheimes Schlüsselobjekt</span><span class="sxs-lookup"><span data-stu-id="d56e9-118">The identifier for secret object</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-119">Ruft ab oder legt Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="d56e9-119">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretBundle.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="secretBundle.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretBundle.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretBundle.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d56e9-120">Ruft ab oder legt den Wert für den geheimen fest.</span><span class="sxs-lookup"><span data-stu-id="d56e9-120">Gets or sets the secret value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>