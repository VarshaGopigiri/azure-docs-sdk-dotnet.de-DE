<Type Name="SnapshotUpdateInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner">
  <TypeSignature Language="C#" Value="public class SnapshotUpdateInner : Microsoft.Azure.Management.Compute.Fluent.Models.ResourceUpdate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SnapshotUpdateInner extends Microsoft.Azure.Management.Compute.Fluent.Models.ResourceUpdate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SnapshotUpdateInner&#xA;Inherits ResourceUpdate" />
  <TypeSignature Language="F#" Value="type SnapshotUpdateInner = class&#xA;    inherit ResourceUpdate" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.Models.ResourceUpdate</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="24c7f-101">Snapshot-Update-Ressource.</span><span class="sxs-lookup"><span data-stu-id="24c7f-101">Snapshot update resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotUpdateInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24c7f-102">Initialisiert eine neue Instanz der SnapshotUpdateInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="24c7f-102">Initializes a new instance of the SnapshotUpdateInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnapshotUpdateInner (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku sku = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings encryptionSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku sku, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings encryptionSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner (tags, sku, osType, diskSizeGB, encryptionSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" />
      </Parameters>
      <Docs>
        <param name="tags">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="osType">To be added.</param>
        <param name="diskSizeGB">To be added.</param>
        <param name="encryptionSettings">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24c7f-103">Ruft ab oder legt fest, ob creationData.createOption leer ist, dieses Feld ist obligatorisch und gibt die Größe der virtuellen Festplatte erstellen an.</span><span class="sxs-lookup"><span data-stu-id="24c7f-103">Gets or sets if creationData.createOption is Empty, this field is mandatory and it indicates the size of the VHD to create.</span></span> <span data-ttu-id="24c7f-104">Wenn dieses Feld nach Updates oder Erstellung mit anderen Optionen vorhanden ist, gibt es eine Größe an.</span><span class="sxs-lookup"><span data-stu-id="24c7f-104">If this field is present for updates or creation with other options, it indicates a resize.</span></span> <span data-ttu-id="24c7f-105">Ändert die Größe sind nur zulässig, wenn der Datenträger nicht an einen ausgeführten virtuellen Computer angefügt ist und nur Sie den Datenträger vergrößern kann.</span><span class="sxs-lookup"><span data-stu-id="24c7f-105">Resizes are only allowed if the disk is not attached to a running VM, and can only increase the disk's size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As EncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24c7f-106">Ruft ab oder legt ihn fest verschlüsselungseinstellungen für Datenträger oder einer Momentaufnahme</span><span class="sxs-lookup"><span data-stu-id="24c7f-106">Gets or sets encryption settings for disk or snapshot</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24c7f-107">Ruft ab oder legt den Betriebssystemtyp.</span><span class="sxs-lookup"><span data-stu-id="24c7f-107">Gets or sets the Operating System type.</span></span> <span data-ttu-id="24c7f-108">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="24c7f-108">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="snapshotUpdateInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24c7f-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="24c7f-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="24c7f-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="24c7f-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>