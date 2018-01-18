<Type Name="DeploymentOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="edbe5-101">Erweiterungsmethoden für DeploymentOperations.</span><span class="sxs-lookup"><span data-stu-id="edbe5-101">Extension methods for DeploymentOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation Get (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation Get(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDeploymentOperations, resourceGroupName As String, deploymentName As String, operationId As String) As DeploymentOperation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.Get (operations, resourceGroupName, deploymentName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edbe5-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="edbe5-103">The name of the resource group.</span></span> <span data-ttu-id="edbe5-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="edbe5-104">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="edbe5-105">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="edbe5-105">The name of the deployment.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="edbe5-106">Die ID des Vorgangs zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="edbe5-106">The ID of the operation to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-107">Ruft eine Bereitstellungen-Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-107">Gets a deployments operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edbe5-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="edbe5-109">The name of the resource group.</span></span> <span data-ttu-id="edbe5-110">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="edbe5-110">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="edbe5-111">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="edbe5-111">The name of the deployment.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="edbe5-112">Die ID des Vorgangs zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="edbe5-112">The ID of the operation to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="edbe5-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="edbe5-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-114">Ruft eine Bereitstellungen-Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-114">Gets a deployments operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; List (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; List(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDeploymentOperations, resourceGroupName As String, deploymentName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of DeploymentOperation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.List (operations, resourceGroupName, deploymentName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edbe5-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="edbe5-116">The name of the resource group.</span></span> <span data-ttu-id="edbe5-117">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="edbe5-117">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="edbe5-118">Der Name der Bereitstellung mit dem Vorgang zum Abrufen.</span><span class="sxs-lookup"><span data-stu-id="edbe5-118">The name of the deployment with the operation to get.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="edbe5-119">Die Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="edbe5-119">The number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-120">Ruft alle Bereitstellungsvorgänge für eine Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-120">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListAsync (operations, resourceGroupName, deploymentName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edbe5-122">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="edbe5-122">The name of the resource group.</span></span> <span data-ttu-id="edbe5-123">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="edbe5-123">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="edbe5-124">Der Name der Bereitstellung mit dem Vorgang zum Abrufen.</span><span class="sxs-lookup"><span data-stu-id="edbe5-124">The name of the deployment with the operation to get.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="edbe5-125">Die Anzahl der zurückzugebenden Ergebnisseite.</span><span class="sxs-lookup"><span data-stu-id="edbe5-125">The number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="edbe5-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="edbe5-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-127">Ruft alle Bereitstellungsvorgänge für eine Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-127">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDeploymentOperations, nextPageLink As String) As IPage(Of DeploymentOperation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-128">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="edbe5-129">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="edbe5-129">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-130">Ruft alle Bereitstellungsvorgänge für eine Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-130">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edbe5-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edbe5-131">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="edbe5-132">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="edbe5-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="edbe5-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="edbe5-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edbe5-134">Ruft alle Bereitstellungsvorgänge für eine Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="edbe5-134">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>