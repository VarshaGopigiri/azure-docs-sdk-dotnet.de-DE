<Type Name="ImageInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner">
  <TypeSignature Language="C#" Value="public class ImageInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ImageInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
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
            <span data-ttu-id="61b01-101">Beschreibt ein Bild an.</span><span class="sxs-lookup"><span data-stu-id="61b01-101">Describes an Image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61b01-102">Initialisiert eine neue Instanz der ImageInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61b01-102">Initializes a new instance of the ImageInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVirtualMachine = null, Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile storageProfile = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVirtualMachine, class Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile storageProfile, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sourceVirtualMachine As SubResource = null, Optional storageProfile As ImageStorageProfile = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner (location, id, name, type, tags, sourceVirtualMachine, storageProfile, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sourceVirtualMachine" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sourceVirtualMachine"><span data-ttu-id="61b01-103">Die ursprüngliche virtuelle Maschine aus dem Image erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="61b01-103">The source virtual machine from which Image is created.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="61b01-104">Das Speicherprofil.</span><span class="sxs-lookup"><span data-stu-id="61b01-104">The storage profile.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="61b01-105">Der Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="61b01-105">The provisioning state.</span></span></param>
        <summary>
            <span data-ttu-id="61b01-106">Initialisiert eine neue Instanz der ImageInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61b01-106">Initializes a new instance of the ImageInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61b01-107">Ruft den Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="61b01-107">Gets the provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.SourceVirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVirtualMachine As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVirtualMachine : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.SourceVirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceVirtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61b01-108">Ruft ab oder legt die ursprüngliche virtuelle Maschine, die aus dem Image erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="61b01-108">Gets or sets the source virtual machine from which Image is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As ImageStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61b01-109">Ruft ab oder legt das Speicherprofil.</span><span class="sxs-lookup"><span data-stu-id="61b01-109">Gets or sets the storage profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="imageInner.Validate " />
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
            <span data-ttu-id="61b01-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="61b01-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61b01-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="61b01-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>