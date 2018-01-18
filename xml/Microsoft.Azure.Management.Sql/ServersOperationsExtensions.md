<Type Name="ServersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServersOperationsExtensions = class" />
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
            <span data-ttu-id="fe642-101">Erweiterungsmethoden für ServersOperations.</span><span class="sxs-lookup"><span data-stu-id="fe642-101">Extension methods for ServersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As Server) As Server" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-105">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-106">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-106">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-107">Erstellt oder aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-107">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-109">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-110">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-111">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-111">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-112">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-112">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-114">Erstellt oder aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-114">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IServersOperations, resourceGroupName As String, serverName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-116">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-118">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-118">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-119">Löscht einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-119">Deletes a server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-121">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-122">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-123">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-123">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-125">Löscht einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-125">Deletes a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server BeginUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server BeginUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As ServerUpdate) As Server" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-127">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-128">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-129">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-129">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-130">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-130">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-131">Aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-131">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-133">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-134">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-135">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-135">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-136">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-136">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-138">Aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-138">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse CheckNameAvailability (this Microsoft.Azure.Management.Sql.IServersOperations operations, Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse CheckNameAvailability(class Microsoft.Azure.Management.Sql.IServersOperations operations, class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Sql.IServersOperations,Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IServersOperations, parameters As CheckNameAvailabilityRequest) As CheckNameAvailabilityResponse" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Sql.IServersOperations * Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest -&gt; Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-139">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-140">Die Parameter für die Verfügbarkeit des Namens anfordern.</span><span class="sxs-lookup"><span data-stu-id="fe642-140">The parameters to request for name availability.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-141">Bestimmt, ob eine Ressource mit dem angegebenen Namen erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fe642-141">Determines whether a resource can be created with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, class Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Sql.IServersOperations,Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Sql.IServersOperations * Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CheckNameAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.CheckNameAvailabilityRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-142">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-143">Die Parameter für die Verfügbarkeit des Namens anfordern.</span><span class="sxs-lookup"><span data-stu-id="fe642-143">The parameters to request for name availability.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-145">Bestimmt, ob eine Ressource mit dem angegebenen Namen erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="fe642-145">Determines whether a resource can be created with the specified name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As Server) As Server" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-147">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-148">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-149">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-149">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-150">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-150">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-151">Erstellt oder aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-151">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.Server parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.Server parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Server,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.Server * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Server" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-153">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-153">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-154">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-154">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-155">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-155">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-156">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-156">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-158">Erstellt oder aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-158">Creates or updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServersOperations, resourceGroupName As String, serverName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Delete (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-160">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-161">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-162">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-162">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-163">Löscht einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-163">Deletes a server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-165">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-167">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-167">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-169">Löscht einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-169">Deletes a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server Get (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server Get(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServersOperations, resourceGroupName As String, serverName As String) As Server" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServersOperations * string * string -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Get (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-171">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-172">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-173">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-173">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-174">Ruft einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-174">Gets a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-176">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-177">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-178">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-178">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-180">Ruft einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-180">Gets a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; List (this Microsoft.Azure.Management.Sql.IServersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; List(class Microsoft.Azure.Management.Sql.IServersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.List(Microsoft.Azure.Management.Sql.IServersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IServersOperations) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Sql.IServersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-181">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-182">Ruft eine Liste aller Server in das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-182">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.IServersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-183">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-184">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-185">Ruft eine Liste aller Server in das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-185">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroup (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroup(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IServersOperations, resourceGroupName As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-187">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-188">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-189">Ruft eine Liste von Servern in einer Ressource Gruppen ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-189">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-191">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-191">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-192">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-192">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-194">Ruft eine Liste von Servern in einer Ressource Gruppen ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-194">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IServersOperations, nextPageLink As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe642-196">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fe642-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-197">Ruft eine Liste von Servern in einer Ressource Gruppen ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-197">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe642-199">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fe642-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-200">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-201">Ruft eine Liste von Servern in einer Ressource Gruppen ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-201">Gets a list of servers in a resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; ListNext (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; ListNext(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNext(Microsoft.Azure.Management.Sql.IServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IServersOperations, nextPageLink As String) As IPage(Of Server)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Sql.IServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe642-203">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fe642-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-204">Ruft eine Liste aller Server in das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-204">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fe642-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fe642-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-208">Ruft eine Liste aller Server in das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fe642-208">Gets a list of all servers in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.Server Update (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.Server Update(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Update(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IServersOperations, resourceGroupName As String, serverName As String, parameters As ServerUpdate) As Server" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate -&gt; Microsoft.Azure.Management.Sql.Models.Server" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.Update (operations, resourceGroupName, serverName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.Server</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-210">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-210">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-211">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-211">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-212">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-212">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-213">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-213">The requested server resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-214">Aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-214">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt; UpdateAsync (this Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.Server&gt; UpdateAsync(class Microsoft.Azure.Management.Sql.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ServerUpdate parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Sql.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Sql.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Models.ServerUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;" Usage="Microsoft.Azure.Management.Sql.ServersOperationsExtensions.UpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServersOperationsExtensions/&lt;UpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.Server&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fe642-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fe642-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fe642-216">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fe642-216">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fe642-217">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe642-217">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fe642-218">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="fe642-218">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fe642-219">Der Status der angeforderten Ressource.</span><span class="sxs-lookup"><span data-stu-id="fe642-219">The requested server resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fe642-220">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fe642-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe642-221">Aktualisiert einen Server.</span><span class="sxs-lookup"><span data-stu-id="fe642-221">Updates a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>