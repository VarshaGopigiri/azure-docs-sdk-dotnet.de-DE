<Type Name="IDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.IDisk">
  <TypeSignature Language="C#" Value="public interface IDisk : Microsoft.Azure.Management.Compute.Fluent.IDiskBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDisk implements class Microsoft.Azure.Management.Compute.Fluent.IDiskBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDisk&#xA;Implements IBeta, IDiskBeta, IGroupableResource(Of IComputeManager, DiskInner), IHasInner(Of DiskInner), IHasManager(Of IComputeManager), IRefreshable(Of IDisk), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IDisk = interface&#xA;    interface IGroupableResource&lt;IComputeManager, DiskInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;DiskInner&gt;&#xA;    interface IRefreshable&lt;IDisk&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IDiskBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.IDiskBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="be964-101">Eine unveränderliche clientseitige Darstellung von Azure verwaltet Datenträger.</span><span class="sxs-lookup"><span data-stu-id="be964-101">An immutable client-side representation of an Azure managed disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreationMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.CreationMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationMethod As DiskCreateOption" />
      <MemberSignature Language="F#" Value="member this.CreationMethod : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.CreationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-102">Ruft die Methode zum Erstellen von Datenträger ab.</span><span class="sxs-lookup"><span data-stu-id="be964-102">Gets the disk creation method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccess">
      <MemberSignature Language="C#" Value="public string GrantAccess (int accessDurationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GrantAccess(int32 accessDurationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IDisk.GrantAccess(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GrantAccess (accessDurationInSeconds As Integer) As String" />
      <MemberSignature Language="F#" Value="abstract member GrantAccess : int -&gt; string" Usage="iDisk.GrantAccess accessDurationInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessDurationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="accessDurationInSeconds"><span data-ttu-id="be964-103">Der Zugriff für Beispielsammlung in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="be964-103">The access duration in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="be964-104">Gewährt den Zugriff auf den Datenträger.</span><span class="sxs-lookup"><span data-stu-id="be964-104">Grants access to the disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="be964-105">Die schreibgeschützte SAS-URI auf den Datenträger.</span><span class="sxs-lookup"><span data-stu-id="be964-105">The read-only SAS URI to the disk.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GrantAccessAsync (int accessDurationInSeconds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GrantAccessAsync(int32 accessDurationInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IDisk.GrantAccessAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GrantAccessAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iDisk.GrantAccessAsync (accessDurationInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessDurationInSeconds" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessDurationInSeconds">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAttachedToVirtualMachine">
      <MemberSignature Language="C#" Value="public bool IsAttachedToVirtualMachine { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAttachedToVirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.IsAttachedToVirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAttachedToVirtualMachine As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAttachedToVirtualMachine : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.IsAttachedToVirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-106">Ruft "true", wenn der Datenträger an einen virtuellen Computer ist, andernfalls "false" angefügt ist.</span><span class="sxs-lookup"><span data-stu-id="be964-106">Gets true if the disk is attached to a virtual machine, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OSType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-107">Ruft den Typ des Betriebssystems auf dem Datenträger.</span><span class="sxs-lookup"><span data-stu-id="be964-107">Gets the type of the operating system on the disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccess">
      <MemberSignature Language="C#" Value="public void RevokeAccess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RevokeAccess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IDisk.RevokeAccess" />
      <MemberSignature Language="VB.NET" Value="Public Sub RevokeAccess ()" />
      <MemberSignature Language="F#" Value="abstract member RevokeAccess : unit -&gt; unit" Usage="iDisk.RevokeAccess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="be964-108">Hebt den Zugriff auf den Datenträger gewährt.</span><span class="sxs-lookup"><span data-stu-id="be964-108">Revokes access granted to the disk.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RevokeAccessAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RevokeAccessAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IDisk.RevokeAccessAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RevokeAccessAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iDisk.RevokeAccessAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInGB">
      <MemberSignature Language="C#" Value="public int SizeInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.SizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.SizeInGB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.SizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-109">Ruft die Größe des Datenträgers in GB ab.</span><span class="sxs-lookup"><span data-stu-id="be964-109">Gets disk size in GB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As DiskSkuTypes" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-110">Ruft den Datenträger SKU ab.</span><span class="sxs-lookup"><span data-stu-id="be964-110">Gets the disk SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As CreationSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-111">Ruft die Details der Quelle, von der der Datenträger erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="be964-111">Gets the details of the source from which the disk is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IDisk.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IDisk.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be964-112">Ruft die Ressourcen-ID der virtuellen Maschine, die diesen Datenträger zugeordnet ist, oder Null, wenn der Datenträger im getrennten Zustand ist.</span><span class="sxs-lookup"><span data-stu-id="be964-112">Gets the resource ID of the virtual machine this disk is attached to, or null if the disk is in a detached state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>