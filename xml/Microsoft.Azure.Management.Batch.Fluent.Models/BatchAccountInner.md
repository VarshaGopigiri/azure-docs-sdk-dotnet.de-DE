<Type Name="BatchAccountInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner">
  <TypeSignature Language="C#" Value="public class BatchAccountInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BatchAccountInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="395d1-101">Enthält Informationen zu einem Azure Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="395d1-101">Contains information about an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="395d1-102">Initialisiert eine neue Instanz der BatchAccountInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="395d1-102">Initializes a new instance of the BatchAccountInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string accountEndpoint = null, Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState.Invalid, Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt; poolAllocationMode = null, Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference keyVaultReference = null, Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties autoStorage = null, int dedicatedCoreQuota = 0, int lowPriorityCoreQuota = 0, int poolQuota = 0, int activeJobAndJobScheduleQuota = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string accountEndpoint, valuetype Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt; poolAllocationMode, class Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference keyVaultReference, class Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties autoStorage, int32 dedicatedCoreQuota, int32 lowPriorityCoreQuota, int32 poolQuota, int32 activeJobAndJobScheduleQuota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState,System.Nullable{Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode},Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference,Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties,System.Int32,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState * Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt; * Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference * Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties * int * int * int * int -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner (location, id, name, type, tags, accountEndpoint, provisioningState, poolAllocationMode, keyVaultReference, autoStorage, dedicatedCoreQuota, lowPriorityCoreQuota, poolQuota, activeJobAndJobScheduleQuota)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accountEndpoint" Type="System.String" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState" />
        <Parameter Name="poolAllocationMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt;" />
        <Parameter Name="keyVaultReference" Type="Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference" />
        <Parameter Name="autoStorage" Type="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties" />
        <Parameter Name="dedicatedCoreQuota" Type="System.Int32" />
        <Parameter Name="lowPriorityCoreQuota" Type="System.Int32" />
        <Parameter Name="poolQuota" Type="System.Int32" />
        <Parameter Name="activeJobAndJobScheduleQuota" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="accountEndpoint">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="poolAllocationMode">To be added.</param>
        <param name="keyVaultReference">To be added.</param>
        <param name="autoStorage">To be added.</param>
        <param name="dedicatedCoreQuota">To be added.</param>
        <param name="lowPriorityCoreQuota">To be added.</param>
        <param name="poolQuota">To be added.</param>
        <param name="activeJobAndJobScheduleQuota">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountEndpoint">
      <MemberSignature Language="C#" Value="public string AccountEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.AccountEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.AccountEndpoint : string" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.AccountEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="395d1-103">Ruft den Endpunkt, der von diesem Konto verwendet wird, für die Interaktion mit der Batch-Dienste ab.</span><span class="sxs-lookup"><span data-stu-id="395d1-103">Gets the endpoint used by this account to interact with the Batch services.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveJobAndJobScheduleQuota">
      <MemberSignature Language="C#" Value="public int ActiveJobAndJobScheduleQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveJobAndJobScheduleQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.ActiveJobAndJobScheduleQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.ActiveJobAndJobScheduleQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeJobAndJobScheduleQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="395d1-104">Ruft ab oder legt die aktive Aufträge und die Auftrag-Zeitplan-Kontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="395d1-104">Gets or sets the active job and job schedule quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties AutoStorage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoStorage As AutoStorageProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.AutoStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="395d1-105">Ruft ab oder legt die Eigenschaften und den Status des Auto-Speicherkonto, die dem Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="395d1-105">Gets or sets the properties and status of any auto storage account associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DedicatedCoreQuota">
      <MemberSignature Language="C#" Value="public int DedicatedCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DedicatedCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.DedicatedCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DedicatedCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.DedicatedCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dedicatedCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference KeyVaultReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference KeyVaultReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.KeyVaultReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultReference As KeyVaultReference" />
      <MemberSignature Language="F#" Value="member this.KeyVaultReference : Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.KeyVaultReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.KeyVaultReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowPriorityCoreQuota">
      <MemberSignature Language="C#" Value="public int LowPriorityCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LowPriorityCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.LowPriorityCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LowPriorityCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.LowPriorityCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.LowPriorityCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lowPriorityCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolAllocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt; PoolAllocationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt; PoolAllocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.PoolAllocationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolAllocationMode As Nullable(Of PoolAllocationMode)" />
      <MemberSignature Language="F#" Value="member this.PoolAllocationMode : Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.PoolAllocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolAllocationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Fluent.Models.PoolAllocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolQuota">
      <MemberSignature Language="C#" Value="public int PoolQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PoolQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.PoolQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.PoolQuota : int" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.PoolQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="395d1-106">Ruft ab oder legt das poolkontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="395d1-106">Gets or sets the pool quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="395d1-107">Ruft ab oder legt den Bereitstellungsstatus der Ressource.</span><span class="sxs-lookup"><span data-stu-id="395d1-107">Gets or sets the provisioned state of the resource.</span></span> <span data-ttu-id="395d1-108">Folgende Werte sind möglich: "Ungültig", "erstellen", "Löschen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="395d1-108">Possible values include: 'Invalid', 'Creating', 'Deleting', 'Succeeded', 'Failed', 'Cancelled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="batchAccountInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="395d1-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="395d1-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="395d1-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="395d1-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>