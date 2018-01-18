<Type Name="VirtualMachineCaptureParameters" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters">
  <TypeSignature Language="C#" Value="public class VirtualMachineCaptureParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineCaptureParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineCaptureParameters" />
  <TypeSignature Language="F#" Value="type VirtualMachineCaptureParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79f5a-101">Parameter des virtuellen Computers zu erfassen.</span><span class="sxs-lookup"><span data-stu-id="79f5a-101">Capture Virtual Machine parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineCaptureParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="79f5a-102">Initialisiert eine neue Instanz der VirtualMachineCaptureParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79f5a-102">Initializes a new instance of the VirtualMachineCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineCaptureParameters (string vhdPrefix, string destinationContainerName, bool overwriteVhds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vhdPrefix, string destinationContainerName, bool overwriteVhds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.#ctor(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vhdPrefix As String, destinationContainerName As String, overwriteVhds As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters : string * string * bool -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters (vhdPrefix, destinationContainerName, overwriteVhds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vhdPrefix" Type="System.String" />
        <Parameter Name="destinationContainerName" Type="System.String" />
        <Parameter Name="overwriteVhds" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="vhdPrefix"><span data-ttu-id="79f5a-103">Präfix der erfasste virtuelle Festplatte.</span><span class="sxs-lookup"><span data-stu-id="79f5a-103">The captured virtual hard disk's name prefix.</span></span></param>
        <param name="destinationContainerName"><span data-ttu-id="79f5a-104">Der Name des Ziel-Container.</span><span class="sxs-lookup"><span data-stu-id="79f5a-104">The destination container name.</span></span></param>
        <param name="overwriteVhds"><span data-ttu-id="79f5a-105">Gibt an, ob die virtuelle Zielfestplatte, bei einem Konflikt zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="79f5a-105">Specifies whether to overwrite the destination virtual hard disk, in case of conflict.</span></span></param>
        <summary>
            <span data-ttu-id="79f5a-106">Initialisiert eine neue Instanz der VirtualMachineCaptureParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79f5a-106">Initializes a new instance of the VirtualMachineCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationContainerName">
      <MemberSignature Language="C#" Value="public string DestinationContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.DestinationContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationContainerName As String" />
      <MemberSignature Language="F#" Value="member this.DestinationContainerName : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.DestinationContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationContainerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79f5a-107">Ruft ab oder legt den Namen der Ziel-Container.</span><span class="sxs-lookup"><span data-stu-id="79f5a-107">Gets or sets the destination container name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverwriteVhds">
      <MemberSignature Language="C#" Value="public bool OverwriteVhds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OverwriteVhds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.OverwriteVhds" />
      <MemberSignature Language="VB.NET" Value="Public Property OverwriteVhds As Boolean" />
      <MemberSignature Language="F#" Value="member this.OverwriteVhds : bool with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.OverwriteVhds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="overwriteVhds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79f5a-108">Gibt an, ob die virtuelle Zielfestplatte, bei einem Konflikt überschreibt, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="79f5a-108">Gets or sets specifies whether to overwrite the destination virtual hard disk, in case of conflict.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineCaptureParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="79f5a-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="79f5a-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="79f5a-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="79f5a-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VhdPrefix">
      <MemberSignature Language="C#" Value="public string VhdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VhdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.VhdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.VhdPrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters.VhdPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhdPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79f5a-111">Abrufen oder Festlegen der erfasste virtuelle Festplatte Namenspräfix.</span><span class="sxs-lookup"><span data-stu-id="79f5a-111">Gets or sets the captured virtual hard disk's name prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>