<Type Name="Container" FullName="Microsoft.Azure.Management.ContainerInstance.Models.Container">
  <TypeSignature Language="C#" Value="public class Container" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Container extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.Container" />
  <TypeSignature Language="VB.NET" Value="Public Class Container" />
  <TypeSignature Language="F#" Value="type Container = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5ce31-101">Ein Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-101">A container instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Container ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-102">Initialisiert eine neue Instanz der Container-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ce31-102">Initializes a new instance of the Container class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Container (string name, string image, Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements resources, System.Collections.Generic.IList&lt;string&gt; command = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; ports = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; environmentVariables = null, Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView instanceView = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; volumeMounts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string image, class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements resources, class System.Collections.Generic.IList`1&lt;string&gt; command, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; ports, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; environmentVariables, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView instanceView, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; volumeMounts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.#ctor(System.String,System.String,Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort},System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable},Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, image As String, resources As ResourceRequirements, Optional command As IList(Of String) = null, Optional ports As IList(Of ContainerPort) = null, Optional environmentVariables As IList(Of EnvironmentVariable) = null, Optional instanceView As ContainerPropertiesInstanceView = null, Optional volumeMounts As IList(Of VolumeMount) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.Container : string * string * Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; * Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; -&gt; Microsoft.Azure.Management.ContainerInstance.Models.Container" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.Container (name, image, resources, command, ports, environmentVariables, instanceView, volumeMounts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="image" Type="System.String" />
        <Parameter Name="resources" Type="Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements" />
        <Parameter Name="command" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ports" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt;" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView" />
        <Parameter Name="volumeMounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5ce31-103">Der vom Benutzer bereitgestellte Name der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-103">The user-provided name of the container instance.</span></span></param>
        <param name="image"><span data-ttu-id="5ce31-104">Der Name des Bilds verwendet, um die Containerinstanz zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5ce31-104">The name of the image used to create the container instance.</span></span></param>
        <param name="resources"><span data-ttu-id="5ce31-105">Die ressourcenanforderungen der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-105">The resource requirements of the container instance.</span></span></param>
        <param name="command"><span data-ttu-id="5ce31-106">Die Befehle, die in die Containerinstanz in der Form Exec ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5ce31-106">The commands to execute within the container instance in exec form.</span></span></param>
        <param name="ports"><span data-ttu-id="5ce31-107">Die verfügbar gemachten Ports für die Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-107">The exposed ports on the container instance.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="5ce31-108">Die Umgebungsvariablen in der Containerinstanz festlegen.</span><span class="sxs-lookup"><span data-stu-id="5ce31-108">The environment variables to set in the container instance.</span></span></param>
        <param name="instanceView"><span data-ttu-id="5ce31-109">Die Instanzansicht der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-109">The instance view of the container instance.</span></span> <span data-ttu-id="5ce31-110">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="5ce31-110">Only valid in response.</span></span></param>
        <param name="volumeMounts"><span data-ttu-id="5ce31-111">Das Volume wird für die Containerinstanz verfügbar.</span><span class="sxs-lookup"><span data-stu-id="5ce31-111">The volume mounts available to the container instance.</span></span></param>
        <summary>
            <span data-ttu-id="5ce31-112">Initialisiert eine neue Instanz der Container-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ce31-112">Initializes a new instance of the Container class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Command">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Command { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Command" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Command" />
      <MemberSignature Language="VB.NET" Value="Public Property Command As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Command : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Command" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.command")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-113">Ermittelt oder definiert die Befehle, die in die Containerinstanz in der Form Exec ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5ce31-113">Gets or sets the commands to execute within the container instance in exec form.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentVariable)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.EnvironmentVariable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-114">Ruft ab oder legt die Umgebungsvariablen in der Containerinstanz festlegen.</span><span class="sxs-lookup"><span data-stu-id="5ce31-114">Gets or sets the environment variables to set in the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public string Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As String" />
      <MemberSignature Language="F#" Value="member this.Image : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-115">Ruft ab oder legt den Namen des Bilds verwendet, um die Containerinstanz zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5ce31-115">Gets or sets the name of the image used to create the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As ContainerPropertiesInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ContainerPropertiesInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-116">Ruft die Instanzansicht der Containerinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="5ce31-116">Gets the instance view of the container instance.</span></span> <span data-ttu-id="5ce31-117">In der Antwort nur gültig.</span><span class="sxs-lookup"><span data-stu-id="5ce31-117">Only valid in response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-118">Ruft ab oder legt den Benutzer bereitgestellten Namen der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-118">Gets or sets the user-provided name of the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; Ports { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; Ports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Ports" />
      <MemberSignature Language="VB.NET" Value="Public Property Ports As IList(Of ContainerPort)" />
      <MemberSignature Language="F#" Value="member this.Ports : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Ports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ports")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-119">Ruft ab oder legt den verfügbar gemachten Ports für die Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-119">Gets or sets the exposed ports on the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As ResourceRequirements" />
      <MemberSignature Language="F#" Value="member this.Resources : Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.ResourceRequirements</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-120">Ruft ab oder legt die ressourcenanforderungen der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-120">Gets or sets the resource requirements of the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Container.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="container.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-121">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5ce31-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5ce31-122">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5ce31-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumeMounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; VolumeMounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; VolumeMounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Container.VolumeMounts" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeMounts As IList(Of VolumeMount)" />
      <MemberSignature Language="F#" Value="member this.VolumeMounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Container.VolumeMounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeMounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.VolumeMount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ce31-123">Ruft ab oder legt die Volume-Mounts verfügbar auf die Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="5ce31-123">Gets or sets the volume mounts available to the container instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>