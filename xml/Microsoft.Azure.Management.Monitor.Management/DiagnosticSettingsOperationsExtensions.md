<Type Name="DiagnosticSettingsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DiagnosticSettingsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DiagnosticSettingsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DiagnosticSettingsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DiagnosticSettingsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c1eb-101">Erweiterungsmethoden für DiagnosticSettingsOperations.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-101">Extension methods for DiagnosticSettingsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource CreateOrUpdate (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource parameters, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource CreateOrUpdate(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource parameters, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDiagnosticSettingsOperations, resourceUri As String, parameters As DiagnosticSettingsResource, name As String) As DiagnosticSettingsResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.CreateOrUpdate (operations, resourceUri, parameters, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-103">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-103">The identifier of the resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c1eb-104">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-104">Parameters supplied to the operation.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-105">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-105">The name of the diagnostic setting.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-106">Erstellt oder aktualisiert die diagnoseeinstellungen für die angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-106">Creates or updates diagnostic settings for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource parameters, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource parameters, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.CreateOrUpdateAsync (operations, resourceUri, parameters, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-108">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-108">The identifier of the resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9c1eb-109">Parameter für den Vorgang bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-109">Parameters supplied to the operation.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-110">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-110">The name of the diagnostic setting.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c1eb-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-112">Erstellt oder aktualisiert die diagnoseeinstellungen für die angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-112">Creates or updates diagnostic settings for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.Delete(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDiagnosticSettingsOperations, resourceUri As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.Delete (operations, resourceUri, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-114">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-114">The identifier of the resource.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-115">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-115">The name of the diagnostic setting.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-116">Löscht die vorhandene diagnoseeinstellungen für die angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-116">Deletes existing diagnostic settings for the specified resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.DeleteAsync (operations, resourceUri, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-118">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-118">The identifier of the resource.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-119">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-119">The name of the diagnostic setting.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c1eb-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-121">Löscht die vorhandene diagnoseeinstellungen für die angegebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-121">Deletes existing diagnostic settings for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource Get (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource Get(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDiagnosticSettingsOperations, resourceUri As String, name As String) As DiagnosticSettingsResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.Get (operations, resourceUri, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-123">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-123">The identifier of the resource.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-124">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-124">The name of the diagnostic setting.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-125">Ruft die diagnoseeinstellungen für die aktive für die angegebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-125">Gets the active diagnostic settings for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.GetAsync (operations, resourceUri, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-127">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-127">The identifier of the resource.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="9c1eb-128">Der Name der diagnoseeinstellung.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-128">The name of the diagnostic setting.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c1eb-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-130">Ruft die diagnoseeinstellungen für die aktive für die angegebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-130">Gets the active diagnostic settings for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection List (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection List(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDiagnosticSettingsOperations, resourceUri As String) As DiagnosticSettingsResourceCollection" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.List (operations, resourceUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-132">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-132">The identifier of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-133">Ruft die Liste der aktiven diagnoseeinstellungen für die angegebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-133">Gets the active diagnostic settings list for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection&gt; ListAsync (this Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection&gt; ListAsync(class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations operations, string resourceUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions.ListAsync (operations, resourceUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.DiagnosticSettingsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResourceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c1eb-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="9c1eb-135">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-135">The identifier of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c1eb-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c1eb-137">Ruft die Liste der aktiven diagnoseeinstellungen für die angegebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9c1eb-137">Gets the active diagnostic settings list for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>