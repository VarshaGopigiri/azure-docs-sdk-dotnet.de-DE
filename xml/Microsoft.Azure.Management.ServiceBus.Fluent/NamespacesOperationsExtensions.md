<Type Name="NamespacesOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NamespacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NamespacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NamespacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NamespacesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f0be9-101">Erweiterungsmethoden für NamespacesOperations.</span><span class="sxs-lookup"><span data-stu-id="f0be9-101">Extension methods for NamespacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-104">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-104">The namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0be9-105">Parameter, die zum Erstellen einer namespaceressource angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f0be9-105">Parameters supplied to create a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-107">Erstellt oder aktualisiert einen Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-107">Creates or updates a service namespace.</span></span> <span data-ttu-id="f0be9-108">Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich.</span><span class="sxs-lookup"><span data-stu-id="f0be9-108">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="f0be9-109">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="f0be9-109">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639408.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-111">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-112">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-112">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-114">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-114">Deletes an existing namespace.</span></span> <span data-ttu-id="f0be9-115">Dieser Vorgang entfernt auch alle zugeordnete Ressourcen unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-115">This operation also removes all associated resources under the namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639389.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityMethodAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityMethodAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityMethodAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CheckNameAvailabilityMethodAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityMethodAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CheckNameAvailabilityMethodAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CheckNameAvailabilityMethodAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-116">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="f0be9-117">Der Name, überprüfen Sie die Verfügbarkeit der Namespace-Namen und den Namespacenamen können nur Buchstaben, Zahlen und Bindestriche enthalten.</span><span class="sxs-lookup"><span data-stu-id="f0be9-117">The Name to check the namespce name availability and The namespace name can contain only letters, numbers, and hyphens.</span></span> <span data-ttu-id="f0be9-118">Der Namespace muss mit einem Buchstaben beginnen und mit einem Buchstaben oder einer Ziffer enden.</span><span class="sxs-lookup"><span data-stu-id="f0be9-118">The namespace must start with a letter, and it must end with a letter or number.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-120">Überprüfen Sie die Verfügbarkeit des Namespacenamens erteilen.</span><span class="sxs-lookup"><span data-stu-id="f0be9-120">Check the give namespace name availability.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-122">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-122">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-123">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-123">The namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0be9-124">Parameter, die zum Erstellen einer namespaceressource angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f0be9-124">Parameters supplied to create a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-126">Erstellt oder aktualisiert einen Dienstnamespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-126">Creates or updates a service namespace.</span></span> <span data-ttu-id="f0be9-127">Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich.</span><span class="sxs-lookup"><span data-stu-id="f0be9-127">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="f0be9-128">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="f0be9-128">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639408.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, rights, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-130">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-130">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-131">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-131">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="f0be9-132">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="f0be9-132">The authorizationrule name.</span></span>
            </param>
        <param name="rights">
            <span data-ttu-id="f0be9-133">Die Rechte, die in der Regel zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="f0be9-133">The rights associated with the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-135">Erstellt oder aktualisiert eine Autorisierungsregel für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-135">Creates or updates an authorization rule for a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639410.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-137">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-137">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-138">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-138">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-140">Löscht einen vorhandenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-140">Deletes an existing namespace.</span></span> <span data-ttu-id="f0be9-141">Dieser Vorgang entfernt auch alle zugeordnete Ressourcen unter dem Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-141">This operation also removes all associated resources under the namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639389.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-143">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-143">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-144">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-144">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="f0be9-145">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="f0be9-145">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-147">Löscht eine Namespace-Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="f0be9-147">Deletes a namespace authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639417.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-149">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-149">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-150">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-150">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-152">Ruft eine Beschreibung für den angegebenen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-152">Gets a description for the specified namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639379.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-154">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-154">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-155">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-155">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="f0be9-156">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="f0be9-156">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-158">Ruft eine Autorisierungsregel für einen Namespace nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="f0be9-158">Gets an authorization rule for a namespace by rule name.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639392.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-159">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-161">Ruft die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der Ressourcengruppen ab.</span><span class="sxs-lookup"><span data-stu-id="f0be9-161">Gets all the available namespaces within the subscription, irrespective of the resource groups.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-163">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-163">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-164">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-164">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-166">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-166">Gets the authorization rules for a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-167">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0be9-168">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f0be9-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-170">Ruft die Autorisierungsregeln für einen Namespace.</span><span class="sxs-lookup"><span data-stu-id="f0be9-170">Gets the authorization rules for a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639376.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-172">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-172">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-174">Ruft die verfügbaren Namespaces innerhalb einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f0be9-174">Gets the available namespaces within a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0be9-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f0be9-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-178">Ruft die verfügbaren Namespaces innerhalb einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="f0be9-178">Gets the available namespaces within a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListKeysAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-180">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-180">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-181">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-181">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="f0be9-182">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="f0be9-182">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-184">Ruft die primären und sekundären Verbindungszeichenfolgen für den Namespace an.</span><span class="sxs-lookup"><span data-stu-id="f0be9-184">Gets the primary and secondary connection strings for the namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639398.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-185">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f0be9-186">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f0be9-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-188">Ruft die verfügbaren Namespaces innerhalb des Abonnements, unabhängig von der Ressourcengruppen ab.</span><span class="sxs-lookup"><span data-stu-id="f0be9-188">Gets all the available namespaces within the subscription, irrespective of the resource groups.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639412.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, string authorizationRuleName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * string * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, authorizationRuleName, policykey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="policykey" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-190">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-190">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-191">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-191">The namespace name</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="f0be9-192">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="f0be9-192">The authorizationrule name.</span></span>
            </param>
        <param name="policykey">
            <span data-ttu-id="f0be9-193">Schlüssel, der neu generiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="f0be9-193">Key that needs to be regenerated.</span></span> <span data-ttu-id="f0be9-194">Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</span><span class="sxs-lookup"><span data-stu-id="f0be9-194">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-196">Generiert den primären oder sekundären Verbindungszeichenfolgen für den Namespace an.</span><span class="sxs-lookup"><span data-stu-id="f0be9-196">Regenerates the primary or secondary connection strings for the namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt718977.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; UpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt; UpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions.UpdateAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.NamespacesOperationsExtensions/&lt;UpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceModelInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.INamespacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.NamespaceUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f0be9-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f0be9-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f0be9-198">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f0be9-198">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="f0be9-199">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="f0be9-199">The namespace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f0be9-200">Parameter, die zum Aktualisieren einer namespaceressource angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f0be9-200">Parameters supplied to update a namespace resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f0be9-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f0be9-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f0be9-202">Aktualisiert einen Dienstnamespace an.</span><span class="sxs-lookup"><span data-stu-id="f0be9-202">Updates a service namespace.</span></span> <span data-ttu-id="f0be9-203">Nach der Erstellung ist das ressourcenmanifest des Namespaces unveränderlich.</span><span class="sxs-lookup"><span data-stu-id="f0be9-203">Once created, this namespace's resource manifest is immutable.</span></span> <span data-ttu-id="f0be9-204">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="f0be9-204">This operation is idempotent.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>