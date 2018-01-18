<Type Name="ServiceTierAdvisorsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceTierAdvisorsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceTierAdvisorsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServiceTierAdvisorsOperationsExtensions = class" />
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
            <span data-ttu-id="05dec-101">Erweiterungsmethoden für ServiceTierAdvisorsOperations.</span><span class="sxs-lookup"><span data-stu-id="05dec-101">Extension methods for ServiceTierAdvisorsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor Get (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor Get(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServiceTierAdvisorsOperations, resourceGroupName As String, serverName As String, databaseName As String, serviceTierAdvisorName As String) As ServiceTierAdvisor" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="05dec-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="05dec-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="05dec-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="05dec-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="05dec-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="05dec-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="05dec-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="05dec-105">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="05dec-106">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-106">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="05dec-107">Der Name des dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="05dec-107">The name of service tier advisor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="05dec-108">Ruft eine dienstebenenratgeber ab.</span><span class="sxs-lookup"><span data-stu-id="05dec-108">Gets a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, serviceTierAdvisorName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="05dec-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="05dec-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="05dec-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="05dec-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="05dec-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="05dec-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="05dec-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="05dec-112">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="05dec-113">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-113">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="05dec-114">Der Name des dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="05dec-114">The name of service tier advisor.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="05dec-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="05dec-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="05dec-116">Ruft eine dienstebenenratgeber ab.</span><span class="sxs-lookup"><span data-stu-id="05dec-116">Gets a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabase">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ListByDatabase (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ListByDatabase(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabase(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatabase (operations As IServiceTierAdvisorsOperations, resourceGroupName As String, serverName As String, databaseName As String) As IEnumerable(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="static member ListByDatabase : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabase (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="05dec-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="05dec-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="05dec-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="05dec-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="05dec-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="05dec-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="05dec-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="05dec-120">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="05dec-121">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-121">The name of database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="05dec-122">Gibt service Tier Ratgeber für die angegebene Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-122">Returns service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; ListByDatabaseAsync (this Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt; ListByDatabaseAsync(class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabaseAsync(Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDatabaseAsync : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions.ListByDatabaseAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServiceTierAdvisorsOperationsExtensions/&lt;ListByDatabaseAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="05dec-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="05dec-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="05dec-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="05dec-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="05dec-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="05dec-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="05dec-126">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="05dec-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="05dec-127">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-127">The name of database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="05dec-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="05dec-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="05dec-129">Gibt service Tier Ratgeber für die angegebene Datenbank.</span><span class="sxs-lookup"><span data-stu-id="05dec-129">Returns service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>