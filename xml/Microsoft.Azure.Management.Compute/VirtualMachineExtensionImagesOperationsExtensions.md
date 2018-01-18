<Type Name="VirtualMachineExtensionImagesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionImagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionImagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionImagesOperationsExtensions = class" />
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
            <span data-ttu-id="5e7b7-101">Erweiterungsmethoden für VirtualMachineExtensionImagesOperations.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-101">Extension methods for VirtualMachineExtensionImagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage Get (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage Get(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String, type As String, version As String) As VirtualMachineExtensionImage" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.Get (operations, location, publisherName, type, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-103">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-103">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <summary>
            <span data-ttu-id="5e7b7-104">Ruft die Abbild eines virtuellen Computers-Erweiterung ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-104">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.GetAsync (operations, location, publisherName, type, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-106">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-106">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="version"></param>
        <param name="cancellationToken">
            <span data-ttu-id="5e7b7-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e7b7-108">Ruft die Abbild eines virtuellen Computers-Erweiterung ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-108">Gets a virtual machine extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListTypes (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListTypes(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypes(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypes (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String) As IList(Of VirtualMachineExtensionImage)" />
      <MemberSignature Language="F#" Value="static member ListTypes : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypes (operations, location, publisherName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-109">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-110">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-110">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <summary>
            <span data-ttu-id="5e7b7-111">Ruft eine Liste der VM-Image Erweiterungstypen ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-111">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListTypesAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListTypesAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListTypesAsync (operations, location, publisherName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListTypesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-112">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-113">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-113">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="cancellationToken">
            <span data-ttu-id="5e7b7-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e7b7-115">Ruft eine Liste der VM-Image Erweiterungstypen ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-115">Gets a list of virtual machine extension image types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVersions">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListVersions (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; ListVersions(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersions(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVersions (operations As IVirtualMachineExtensionImagesOperations, location As String, publisherName As String, type As String, Optional odataQuery As ODataQuery(Of VirtualMachineExtensionImage) = null) As IList(Of VirtualMachineExtensionImage)" />
      <MemberSignature Language="F#" Value="static member ListVersions : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersions (operations, location, publisherName, type, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-116">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-117">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-117">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="5e7b7-118">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-118">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e7b7-119">Ruft eine Liste der virtuellen Maschine Erweiterung Bildversionen ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-119">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListVersionsAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt; ListVersionsAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations operations, string location, string publisherName, string type, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVersionsAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions.ListVersionsAsync (operations, location, publisherName, type, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionImagesOperationsExtensions/&lt;ListVersionsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionImagesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="publisherName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionImage&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e7b7-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-120">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="5e7b7-121">Der Name einer unterstützten Azure-Region.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-121">The name of a supported Azure region.</span></span>
            </param>
        <param name="publisherName"></param>
        <param name="type"></param>
        <param name="odataQuery">
            <span data-ttu-id="5e7b7-122">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-122">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5e7b7-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e7b7-124">Ruft eine Liste der virtuellen Maschine Erweiterung Bildversionen ab.</span><span class="sxs-lookup"><span data-stu-id="5e7b7-124">Gets a list of virtual machine extension image versions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>