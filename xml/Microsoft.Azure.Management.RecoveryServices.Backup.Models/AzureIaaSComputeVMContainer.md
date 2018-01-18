<Type Name="AzureIaaSComputeVMContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer">
  <TypeSignature Language="C#" Value="public class AzureIaaSComputeVMContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSComputeVMContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSComputeVMContainer&#xA;Inherits IaaSVMContainer" />
  <TypeSignature Language="F#" Value="type AzureIaaSComputeVMContainer = class&#xA;    inherit IaaSVMContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Compute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8f8d0-101">IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements einen Azure-Ressourcen-Manager virtuellen Computer darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-101">IaaS VM workload-specific backup item representing an Azure Resource Manager virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f8d0-102">Initialisiert eine neue Instanz der AzureIaaSComputeVMContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-102">Initializes a new instance of the AzureIaaSComputeVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, string virtualMachineId = null, string virtualMachineVersion = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, string virtualMachineId, string virtualMachineVersion, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional virtualMachineId As String = null, Optional virtualMachineVersion As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, virtualMachineId, virtualMachineVersion, resourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="8f8d0-103">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="8f8d0-104">Typ der Sicherung Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="8f8d0-105">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="8f8d0-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="8f8d0-106">Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="8f8d0-107">Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="8f8d0-108">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-108">Type of the container.</span></span> <span data-ttu-id="8f8d0-109">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-109">The value of this property for: 1.</span></span> <span data-ttu-id="8f8d0-110">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="8f8d0-111">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="8f8d0-112">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="8f8d0-113">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="8f8d0-114">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="8f8d0-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="8f8d0-115">Vollständig qualifiziert ARM-Url des virtuellen Computers von diesem Container Azure IaaS-VM dargestellt.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-115">Fully qualified ARM url of the virtual machine represented by this Azure IaaS VM container.</span></span></param>
        <param name="virtualMachineVersion"><span data-ttu-id="8f8d0-116">Gibt an, ob der Container eine Classic oder einer Azure-Ressourcen-Manager-VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-116">Specifies whether the container represents a Classic or an Azure Resource Manager VM.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="8f8d0-117">Der Ressourcengruppenname der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-117">Resource group name of Recovery Services Vault.</span></span></param>
        <summary>
            <span data-ttu-id="8f8d0-118">Initialisiert eine neue Instanz der AzureIaaSComputeVMContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f8d0-118">Initializes a new instance of the AzureIaaSComputeVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>