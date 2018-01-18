<Type Name="ContainerService" FullName="Microsoft.Azure.Management.Compute.Models.ContainerService">
  <TypeSignature Language="C#" Value="public class ContainerService : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerService extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerService" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerService&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ContainerService = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2162a-101">Containerdienst.</span><span class="sxs-lookup"><span data-stu-id="2162a-101">Container service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerService.#ctor" />
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
            <span data-ttu-id="2162a-102">Initialisiert eine neue Instanz der ContainerService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2162a-102">Initializes a new instance of the ContainerService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerService (string location, Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile masterProfile, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; agentPoolProfiles, Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile linuxProfile, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile orchestratorProfile = null, Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile customProfile = null, Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile servicePrincipalProfile = null, Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile windowsProfile = null, Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile diagnosticsProfile = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile masterProfile, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; agentPoolProfiles, class Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile linuxProfile, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, class Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile orchestratorProfile, class Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile customProfile, class Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile servicePrincipalProfile, class Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile windowsProfile, class Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile diagnosticsProfile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerService.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile},Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile,Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile,Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile,Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile,Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, masterProfile As ContainerServiceMasterProfile, agentPoolProfiles As IList(Of ContainerServiceAgentPoolProfile), linuxProfile As ContainerServiceLinuxProfile, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As String = null, Optional orchestratorProfile As ContainerServiceOrchestratorProfile = null, Optional customProfile As ContainerServiceCustomProfile = null, Optional servicePrincipalProfile As ContainerServiceServicePrincipalProfile = null, Optional windowsProfile As ContainerServiceWindowsProfile = null, Optional diagnosticsProfile As ContainerServiceDiagnosticsProfile = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerService : string * Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; * Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile * Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile * Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile * Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile * Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerService (location, masterProfile, agentPoolProfiles, linuxProfile, id, name, type, tags, provisioningState, orchestratorProfile, customProfile, servicePrincipalProfile, windowsProfile, diagnosticsProfile)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="masterProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile" />
        <Parameter Name="agentPoolProfiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt;" />
        <Parameter Name="linuxProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="orchestratorProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile" />
        <Parameter Name="customProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile" />
        <Parameter Name="servicePrincipalProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile" />
        <Parameter Name="windowsProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="2162a-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="2162a-103">Resource location</span></span></param>
        <param name="masterProfile"><span data-ttu-id="2162a-104">Eigenschaften der master-Agents.</span><span class="sxs-lookup"><span data-stu-id="2162a-104">Properties of master agents.</span></span></param>
        <param name="agentPoolProfiles"><span data-ttu-id="2162a-105">Eigenschaften des Agent-Pools.</span><span class="sxs-lookup"><span data-stu-id="2162a-105">Properties of the agent pool.</span></span></param>
        <param name="linuxProfile"><span data-ttu-id="2162a-106">Eigenschaften des virtuelle Linux-Computer.</span><span class="sxs-lookup"><span data-stu-id="2162a-106">Properties of Linux VMs.</span></span></param>
        <param name="id"><span data-ttu-id="2162a-107">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="2162a-107">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="2162a-108">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="2162a-108">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="2162a-109">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="2162a-109">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="2162a-110">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="2162a-110">Resource tags</span></span></param>
        <param name="provisioningState"><span data-ttu-id="2162a-111">der aktuelle Bereitstellung oder Bereitstellung Status, die nur in der Antwort angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="2162a-111">the current deployment or provisioning state, which only appears in the response.</span></span></param>
        <param name="orchestratorProfile"><span data-ttu-id="2162a-112">Eigenschaften der Orchestrator-Komponenten.</span><span class="sxs-lookup"><span data-stu-id="2162a-112">Properties of the orchestrator.</span></span></param>
        <param name="customProfile"><span data-ttu-id="2162a-113">Eigenschaften für benutzerdefinierte Clustern.</span><span class="sxs-lookup"><span data-stu-id="2162a-113">Properties for custom clusters.</span></span></param>
        <param name="servicePrincipalProfile"><span data-ttu-id="2162a-114">Eigenschaften für Dienstprinzipale Cluster.</span><span class="sxs-lookup"><span data-stu-id="2162a-114">Properties for cluster service principals.</span></span></param>
        <param name="windowsProfile"><span data-ttu-id="2162a-115">Eigenschaften des virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="2162a-115">Properties of Windows VMs.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="2162a-116">Eigenschaften des Diagnose-Agents.</span><span class="sxs-lookup"><span data-stu-id="2162a-116">Properties of the diagnostic agent.</span></span></param>
        <summary>
            <span data-ttu-id="2162a-117">Initialisiert eine neue Instanz der ContainerService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2162a-117">Initializes a new instance of the ContainerService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentPoolProfiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; AgentPoolProfiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; AgentPoolProfiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.AgentPoolProfiles" />
      <MemberSignature Language="VB.NET" Value="Public Property AgentPoolProfiles As IList(Of ContainerServiceAgentPoolProfile)" />
      <MemberSignature Language="F#" Value="member this.AgentPoolProfiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.AgentPoolProfiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.agentPoolProfiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-118">Abrufen oder Festlegen der Eigenschaften des Agent-Pools.</span><span class="sxs-lookup"><span data-stu-id="2162a-118">Gets or sets properties of the agent pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile CustomProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile CustomProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.CustomProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomProfile As ContainerServiceCustomProfile" />
      <MemberSignature Language="F#" Value="member this.CustomProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.CustomProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-119">Ruft ab oder legt Eigenschaften für benutzerdefinierte Cluster fest.</span><span class="sxs-lookup"><span data-stu-id="2162a-119">Gets or sets properties for custom clusters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As ContainerServiceDiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-120">Ruft ab oder legt Eigenschaften für die Diagnose-Agent fest.</span><span class="sxs-lookup"><span data-stu-id="2162a-120">Gets or sets properties of the diagnostic agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile LinuxProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile LinuxProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.LinuxProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxProfile As ContainerServiceLinuxProfile" />
      <MemberSignature Language="F#" Value="member this.LinuxProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.LinuxProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linuxProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceLinuxProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-121">Ruft ab oder legt Eigenschaften für virtuelle Linux-Computer fest.</span><span class="sxs-lookup"><span data-stu-id="2162a-121">Gets or sets properties of Linux VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile MasterProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile MasterProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.MasterProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterProfile As ContainerServiceMasterProfile" />
      <MemberSignature Language="F#" Value="member this.MasterProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.MasterProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.masterProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-122">Ruft ab oder legt die Eigenschaften der master-Agents.</span><span class="sxs-lookup"><span data-stu-id="2162a-122">Gets or sets properties of master agents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrchestratorProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile OrchestratorProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile OrchestratorProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.OrchestratorProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OrchestratorProfile As ContainerServiceOrchestratorProfile" />
      <MemberSignature Language="F#" Value="member this.OrchestratorProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.OrchestratorProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.orchestratorProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-123">Abrufen oder Festlegen der Eigenschaften der Orchestrator-Komponenten.</span><span class="sxs-lookup"><span data-stu-id="2162a-123">Gets or sets properties of the orchestrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2162a-124">Ruft die aktuelle Bereitstellung oder Bereitstellungsstatus wird nur in der Antwort angezeigt.</span><span class="sxs-lookup"><span data-stu-id="2162a-124">Gets the current deployment or provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile ServicePrincipalProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile ServicePrincipalProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.ServicePrincipalProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalProfile As ContainerServiceServicePrincipalProfile" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.ServicePrincipalProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.servicePrincipalProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-125">Ruft ab oder legt die Eigenschaften für Dienstprinzipale Cluster fest.</span><span class="sxs-lookup"><span data-stu-id="2162a-125">Gets or sets properties for cluster service principals.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="containerService.Validate " />
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
            <span data-ttu-id="2162a-126">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2162a-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2162a-127">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2162a-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile WindowsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile WindowsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerService.WindowsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsProfile As ContainerServiceWindowsProfile" />
      <MemberSignature Language="F#" Value="member this.WindowsProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerService.WindowsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.windowsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceWindowsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2162a-128">Ruft ab oder legt die Eigenschaften eines virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="2162a-128">Gets or sets properties of Windows VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>