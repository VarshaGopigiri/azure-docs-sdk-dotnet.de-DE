<Type Name="PublicIPAddressesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PublicIPAddressesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PublicIPAddressesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PublicIPAddressesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f469d-101">Erweiterungsmethoden für PublicIPAddressesOperations.</span><span class="sxs-lookup"><span data-stu-id="f469d-101">Extension methods for PublicIPAddressesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-103">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f469d-104">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f469d-104">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f469d-105">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="f469d-105">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-107">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f469d-107">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-109">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f469d-110">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="f469d-110">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-112">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="f469d-112">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, publicIpAddressName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-114">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f469d-115">Der Name der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f469d-115">The name of the public IP address.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f469d-116">Parameter zum Erstellen oder aktualisieren öffentliche IP-Adresse Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="f469d-116">Parameters supplied to the create or update public IP address operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-118">Erstellt oder aktualisiert eine statische oder dynamische öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="f469d-118">Creates or updates a static or dynamic public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.DeleteAsync (operations, resourceGroupName, publicIpAddressName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-120">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f469d-121">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="f469d-121">The name of the subnet.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-122">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-123">Löscht die angegebene öffentliche IP-Adresse an.</span><span class="sxs-lookup"><span data-stu-id="f469d-123">Deletes the specified public IP address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.GetAsync (operations, resourceGroupName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-125">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-125">The name of the resource group.</span></span>
            </param>
        <param name="publicIpAddressName">
            <span data-ttu-id="f469d-126">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="f469d-126">The name of the subnet.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="f469d-127">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="f469d-127">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-129">Ruft die angegebene öffentliche IP-Adresse in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-129">Gets the specified public IP address in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetPublicIPAddressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; GetVirtualMachineScaleSetPublicIPAddressAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt; GetVirtualMachineScaleSetPublicIPAddressAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, string publicIpAddressName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetPublicIPAddressAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.GetVirtualMachineScaleSetPublicIPAddressAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, publicIpAddressName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;GetVirtualMachineScaleSetPublicIPAddressAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="publicIpAddressName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualMachineScaleSetName">To be added.</param>
        <param name="virtualmachineIndex">To be added.</param>
        <param name="networkInterfaceName">To be added.</param>
        <param name="ipConfigurationName">To be added.</param>
        <param name="publicIpAddressName">To be added.</param>
        <param name="expand">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-130">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-132">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f469d-132">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListAllNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f469d-134">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f469d-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-136">Ruft den öffentlichen IP-Adressen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="f469d-136">Gets all the public IP addresses in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f469d-138">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-138">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-140">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-140">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f469d-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f469d-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f469d-142">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f469d-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f469d-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f469d-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f469d-144">Ruft alle öffentliche IP-Adressen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="f469d-144">Gets all public IP addresses in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualMachineScaleSetName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetPublicIPAddressesNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string ipConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, ipConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="ipConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualMachineScaleSetName">To be added.</param>
        <param name="virtualmachineIndex">To be added.</param>
        <param name="networkInterfaceName">To be added.</param>
        <param name="ipConfigurationName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (this Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt; ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions.ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.PublicIPAddressesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMPublicIPAddressesNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddressesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>