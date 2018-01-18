<Type Name="BackupLongTermRetentionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupLongTermRetentionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupLongTermRetentionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f0d56-101">Erweiterungsmethoden für BackupLongTermRetentionPoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="f0d56-101">Extension methods for BackupLongTermRetentionPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As BackupLongTermRetentionPolicy) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-106">der Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-106">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0d56-107">Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f0d56-107">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-108">Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-108">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-113">der Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-113">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0d56-114">Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f0d56-114">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0d56-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0d56-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-116">Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-116">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As BackupLongTermRetentionPolicy) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-121">der Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-121">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0d56-122">Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f0d56-122">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-123">Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-123">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-125">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-125">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-126">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-126">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-127">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-127">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-128">der Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-128">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0d56-129">Die erforderlichen Parameter, um eine Aufbewahrungsrichtlinie für Sicherungen langfristig zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="f0d56-129">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0d56-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0d56-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-131">Erstellt oder aktualisiert eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-131">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy Get (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy Get(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupLongTermRetentionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As BackupLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-133">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-134">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-135">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-135">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-136">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="f0d56-136">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-137">Gibt eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-137">Returns a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.BackupLongTermRetentionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0d56-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0d56-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0d56-139">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="f0d56-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f0d56-140">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="f0d56-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f0d56-141">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="f0d56-141">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f0d56-142">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="f0d56-142">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0d56-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0d56-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0d56-144">Gibt eine langfristige Sicherung Aufbewahrungsrichtlinie für die Datenbank</span><span class="sxs-lookup"><span data-stu-id="f0d56-144">Returns a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>