<Type Name="VirtualMachineImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineImagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="946db-101">Erweiterungsmethoden für VirtualMachineImagesOperations.</span><span class="sxs-lookup"><span data-stu-id="946db-101">Extension methods for VirtualMachineImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineImage Get (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineImage Get(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineImagesOperations, location As String, publisherName As String, offer As String, skus As String, version As String) As VirtualMachineImage" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineImage" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.Get (operations, location, publisherName, offer, skus, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineImage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-103">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-103">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-104">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-104">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-105">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-105">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="946db-106">Ein gültiges Bild SKU.</span><span class="sxs-lookup"><span data-stu-id="946db-106">A valid image SKU.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="946db-107">Ein gültiges Bild SKU-Version.</span><span class="sxs-lookup"><span data-stu-id="946db-107">A valid image SKU version.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-108">Ruft ein Image eines virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="946db-108">Gets a virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImage&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImage&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.GetAsync (operations, location, publisherName, offer, skus, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-109">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-110">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-110">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-111">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-111">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-112">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-112">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="946db-113">Ein gültiges Bild SKU.</span><span class="sxs-lookup"><span data-stu-id="946db-113">A valid image SKU.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="946db-114">Ein gültiges Bild SKU-Version.</span><span class="sxs-lookup"><span data-stu-id="946db-114">A valid image SKU version.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="946db-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="946db-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-116">Ruft ein Image eines virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="946db-116">Gets a virtual machine image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineImagesOperations, location As String, publisherName As String, offer As String, skus As String, Optional odataQuery As ODataQuery(Of VirtualMachineImageResource) = null) As IList(Of VirtualMachineImageResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.List (operations, location, publisherName, offer, skus, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-117">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-118">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-118">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-119">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-119">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-120">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-120">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="946db-121">Ein gültiges Bild SKU.</span><span class="sxs-lookup"><span data-stu-id="946db-121">A valid image SKU.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="946db-122">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="946db-122">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-123">Ruft eine Liste aller VM-Image-Versionen für den angegebenen Speicherort, Verleger, Angebot und SKU ab.</span><span class="sxs-lookup"><span data-stu-id="946db-123">Gets a list of all virtual machine image versions for the specified location, publisher, offer, and SKU.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, string skus, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListAsync (operations, location, publisherName, offer, skus, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="skus" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-124">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-125">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-125">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-126">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-126">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-127">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-127">A valid image publisher offer.</span></span>
            </param>
        <param name="skus">
            <span data-ttu-id="946db-128">Ein gültiges Bild SKU.</span><span class="sxs-lookup"><span data-stu-id="946db-128">A valid image SKU.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="946db-129">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="946db-129">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="946db-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="946db-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-131">Ruft eine Liste aller VM-Image-Versionen für den angegebenen Speicherort, Verleger, Angebot und SKU ab.</span><span class="sxs-lookup"><span data-stu-id="946db-131">Gets a list of all virtual machine image versions for the specified location, publisher, offer, and SKU.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOffers">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListOffers (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListOffers(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListOffers(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOffers (operations As IVirtualMachineImagesOperations, location As String, publisherName As String) As IList(Of VirtualMachineImageResource)" />
      <MemberSignature Language="F#" Value="static member ListOffers : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListOffers (operations, location, publisherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-132">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-133">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-133">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-134">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-134">A valid image publisher.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-135">Ruft bietet eine Liste der VM-Image für die angegebene Position und Verleger.</span><span class="sxs-lookup"><span data-stu-id="946db-135">Gets a list of virtual machine image offers for the specified location and publisher.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListOffersAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListOffersAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListOffersAsync(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOffersAsync : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListOffersAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions/&lt;ListOffersAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-136">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-137">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-137">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-138">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-138">A valid image publisher.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="946db-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="946db-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-140">Ruft bietet eine Liste der VM-Image für die angegebene Position und Verleger.</span><span class="sxs-lookup"><span data-stu-id="946db-140">Gets a list of virtual machine image offers for the specified location and publisher.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPublishers">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListPublishers (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListPublishers(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListPublishers(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPublishers (operations As IVirtualMachineImagesOperations, location As String) As IList(Of VirtualMachineImageResource)" />
      <MemberSignature Language="F#" Value="static member ListPublishers : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListPublishers (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-141">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-142">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-142">The name of a supported Azure region.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-143">Ruft eine Liste der VM-Image-Verleger für den angegebenen Azure-Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="946db-143">Gets a list of virtual machine image publishers for the specified Azure location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPublishersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListPublishersAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListPublishersAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListPublishersAsync(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPublishersAsync : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListPublishersAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions/&lt;ListPublishersAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-144">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-145">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-145">The name of a supported Azure region.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="946db-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="946db-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-147">Ruft eine Liste der VM-Image-Verleger für den angegebenen Azure-Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="946db-147">Gets a list of virtual machine image publishers for the specified Azure location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkus">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListSkus (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt; ListSkus(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListSkus(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSkus (operations As IVirtualMachineImagesOperations, location As String, publisherName As String, offer As String) As IList(Of VirtualMachineImageResource)" />
      <MemberSignature Language="F#" Value="static member ListSkus : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListSkus (operations, location, publisherName, offer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-148">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-149">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-149">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-150">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-150">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-151">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-151">A valid image publisher offer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-152">Ruft eine Liste von SKUs Abbild eines virtuellen Computers für den angegebenen Speicherort, den Verleger und den Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-152">Gets a list of virtual machine image SKUs for the specified location, publisher, and offer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListSkusAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt; ListSkusAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations operations, string location, string publisherName, string offer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListSkusAsync(Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions.ListSkusAsync (operations, location, publisherName, offer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineImagesOperationsExtensions/&lt;ListSkusAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineImageResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="offer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="946db-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="946db-153">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="946db-154">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="946db-154">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName">
            <span data-ttu-id="946db-155">Der Verleger ein gültiges Bild.</span><span class="sxs-lookup"><span data-stu-id="946db-155">A valid image publisher.</span></span>
            </param>
        <param name="offer">
            <span data-ttu-id="946db-156">Ein gültiges Bild Verleger Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-156">A valid image publisher offer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="946db-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="946db-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="946db-158">Ruft eine Liste von SKUs Abbild eines virtuellen Computers für den angegebenen Speicherort, den Verleger und den Angebot.</span><span class="sxs-lookup"><span data-stu-id="946db-158">Gets a list of virtual machine image SKUs for the specified location, publisher, and offer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>