<Type Name="BackupEngineExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo">
  <TypeSignature Language="C#" Value="public class BackupEngineExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupEngineExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupEngineExtendedInfo" />
  <TypeSignature Language="F#" Value="type BackupEngineExtendedInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="95666-101">Weitere Informationen zu backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-101">Additional information on backup engine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95666-102">Initialisiert eine neue Instanz der BackupEngineExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95666-102">Initializes a new instance of the BackupEngineExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineExtendedInfo (string databaseName = null, Nullable&lt;int&gt; protectedItemsCount = null, Nullable&lt;int&gt; protectedServersCount = null, Nullable&lt;int&gt; diskCount = null, Nullable&lt;double&gt; usedDiskSpace = null, Nullable&lt;double&gt; availableDiskSpace = null, Nullable&lt;DateTime&gt; refreshedAt = null, Nullable&lt;int&gt; azureProtectedInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string databaseName, valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount, valuetype System.Nullable`1&lt;int32&gt; protectedServersCount, valuetype System.Nullable`1&lt;int32&gt; diskCount, valuetype System.Nullable`1&lt;float64&gt; usedDiskSpace, valuetype System.Nullable`1&lt;float64&gt; availableDiskSpace, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; refreshedAt, valuetype System.Nullable`1&lt;int32&gt; azureProtectedInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional databaseName As String = null, Optional protectedItemsCount As Nullable(Of Integer) = null, Optional protectedServersCount As Nullable(Of Integer) = null, Optional diskCount As Nullable(Of Integer) = null, Optional usedDiskSpace As Nullable(Of Double) = null, Optional availableDiskSpace As Nullable(Of Double) = null, Optional refreshedAt As Nullable(Of DateTime) = null, Optional azureProtectedInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo (databaseName, protectedItemsCount, protectedServersCount, diskCount, usedDiskSpace, availableDiskSpace, refreshedAt, azureProtectedInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="protectedServersCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="diskCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="usedDiskSpace" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="availableDiskSpace" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="refreshedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="azureProtectedInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="databaseName"><span data-ttu-id="95666-103">Der Datenbankname des Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="95666-103">Database name of backup engine.</span></span></param>
        <param name="protectedItemsCount"><span data-ttu-id="95666-104">Anzahl geschützter Elemente in der backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-104">Number of protected items in the backup engine.</span></span></param>
        <param name="protectedServersCount"><span data-ttu-id="95666-105">Die Anzahl von geschützten Servern in der backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-105">Number of protected servers in the backup engine.</span></span></param>
        <param name="diskCount"><span data-ttu-id="95666-106">Anzahl von Datenträgern in der backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-106">Number of disks in the backup engine.</span></span></param>
        <param name="usedDiskSpace"><span data-ttu-id="95666-107">Speicherplatz in dem Sicherungsmodul verwendet.</span><span class="sxs-lookup"><span data-stu-id="95666-107">Diskspace used in the backup engine.</span></span></param>
        <param name="availableDiskSpace"><span data-ttu-id="95666-108">Speicherplatz, die zurzeit in dem Sicherungsmodul verfügbar.</span><span class="sxs-lookup"><span data-stu-id="95666-108">Diskspace currently available in the backup engine.</span></span></param>
        <param name="refreshedAt"><span data-ttu-id="95666-109">Zeit, in dem Sicherungsmodul der letzten Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="95666-109">Last refresh time in the backup engine.</span></span></param>
        <param name="azureProtectedInstances"><span data-ttu-id="95666-110">Geschützte Instanzen in der backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-110">Protected instances in the backup engine.</span></span></param>
        <summary>
            <span data-ttu-id="95666-111">Initialisiert eine neue Instanz der BackupEngineExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95666-111">Initializes a new instance of the BackupEngineExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableDiskSpace">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AvailableDiskSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AvailableDiskSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AvailableDiskSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableDiskSpace As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AvailableDiskSpace : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AvailableDiskSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableDiskSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-112">Ruft ab, oder legt ihn fest in dem Sicherungsmodul derzeit verfügbaren Speicherplatz.</span><span class="sxs-lookup"><span data-stu-id="95666-112">Gets or sets diskspace currently available in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureProtectedInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AzureProtectedInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AzureProtectedInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AzureProtectedInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureProtectedInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AzureProtectedInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AzureProtectedInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureProtectedInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-113">Ruft ab, oder legt Sie geschützte Instanzen in der Sicherungsmodul fest.</span><span class="sxs-lookup"><span data-stu-id="95666-113">Gets or sets protected instances in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-114">Ruft ab, oder legt ihn fest Datenbankname des Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="95666-114">Gets or sets database name of backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DiskCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-115">Ruft ab oder legt die Anzahl von Datenträgern in der Sicherungsmodul fest.</span><span class="sxs-lookup"><span data-stu-id="95666-115">Gets or sets number of disks in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemsCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedItemsCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedItemsCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedItemsCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemsCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemsCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedItemsCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemsCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-116">Ruft ab oder legt Anzahl geschützter Elemente in der backup-Engine.</span><span class="sxs-lookup"><span data-stu-id="95666-116">Gets or sets number of protected items in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedServersCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedServersCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedServersCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedServersCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedServersCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedServersCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedServersCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedServersCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-117">Ruft ab oder legt die Anzahl von geschützten Servern in dem Sicherungsmodul fest.</span><span class="sxs-lookup"><span data-stu-id="95666-117">Gets or sets number of protected servers in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RefreshedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RefreshedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.RefreshedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RefreshedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.RefreshedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-118">Ruft ab, oder legt Sie Zeit der letzten Aktualisierung in das Sicherungsmodul fest.</span><span class="sxs-lookup"><span data-stu-id="95666-118">Gets or sets last refresh time in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsedDiskSpace">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; UsedDiskSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; UsedDiskSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.UsedDiskSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property UsedDiskSpace As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.UsedDiskSpace : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.UsedDiskSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usedDiskSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95666-119">Ruft ab, oder legt ihn fest Speicherplatz in dem Sicherungsmodul verwendet.</span><span class="sxs-lookup"><span data-stu-id="95666-119">Gets or sets diskspace used in the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>