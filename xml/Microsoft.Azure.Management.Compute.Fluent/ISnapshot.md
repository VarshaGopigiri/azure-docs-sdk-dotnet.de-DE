<Type Name="ISnapshot" FullName="Microsoft.Azure.Management.Compute.Fluent.ISnapshot">
  <TypeSignature Language="C#" Value="public interface ISnapshot : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.ISnapshot&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISnapshot implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ISnapshot&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISnapshot&#xA;Implements IGroupableResource(Of IComputeManager, SnapshotInner), IHasInner(Of SnapshotInner), IHasManager(Of IComputeManager), IRefreshable(Of ISnapshot), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ISnapshot = interface&#xA;    interface IGroupableResource&lt;IComputeManager, SnapshotInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;SnapshotInner&gt;&#xA;    interface IRefreshable&lt;ISnapshot&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.ISnapshot&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.Snapshot.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f211d-101">Eine unveränderliche clientseitige Darstellung von Azure verwaltet Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f211d-101">An immutable client-side representation of an Azure managed snapshot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreationMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption CreationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.CreationMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationMethod As DiskCreateOption" />
      <MemberSignature Language="F#" Value="member this.CreationMethod : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOption" Usage="Microsoft.Azure.Management.Compute.Fluent.ISnapshot.CreationMethod" />
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
            <span data-ttu-id="f211d-102">Ruft die Methode zum Erstellen der Momentaufnahme ab.</span><span class="sxs-lookup"><span data-stu-id="f211d-102">Gets the snapshot creation method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccess">
      <MemberSignature Language="C#" Value="public string GrantAccess (int accessDurationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GrantAccess(int32 accessDurationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.GrantAccess(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GrantAccess (accessDurationInSeconds As Integer) As String" />
      <MemberSignature Language="F#" Value="abstract member GrantAccess : int -&gt; string" Usage="iSnapshot.GrantAccess accessDurationInSeconds" />
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
        <param name="accessDurationInSeconds"><span data-ttu-id="f211d-103">Der Zugriff für Beispielsammlung in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f211d-103">The access duration in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="f211d-104">Gewährt Zugriff auf die Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f211d-104">Grants access to the snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f211d-105">Der schreibgeschützte SAS URI mit der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="f211d-105">The read-only SAS URI to the snapshot.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GrantAccessAsync (int accessDurationInSeconds, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GrantAccessAsync(int32 accessDurationInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.GrantAccessAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GrantAccessAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iSnapshot.GrantAccessAsync (accessDurationInSeconds, cancellationToken)" />
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
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OSType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ISnapshot.OSType" />
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
            <span data-ttu-id="f211d-106">Ruft den Typ des Betriebssystems in der Momentaufnahme ab.</span><span class="sxs-lookup"><span data-stu-id="f211d-106">Gets the type of operating system in the snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccess">
      <MemberSignature Language="C#" Value="public void RevokeAccess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RevokeAccess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.RevokeAccess" />
      <MemberSignature Language="VB.NET" Value="Public Sub RevokeAccess ()" />
      <MemberSignature Language="F#" Value="abstract member RevokeAccess : unit -&gt; unit" Usage="iSnapshot.RevokeAccess " />
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
            <span data-ttu-id="f211d-107">Widerrufen Sie Zugriff auf die Momentaufnahme gewährt.</span><span class="sxs-lookup"><span data-stu-id="f211d-107">Revoke access granted to the snapshot.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RevokeAccessAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RevokeAccessAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.RevokeAccessAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RevokeAccessAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSnapshot.RevokeAccessAsync cancellationToken" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.SizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.SizeInGB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.ISnapshot.SizeInGB" />
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
            <span data-ttu-id="f211d-108">Ruft die Größe des Datenträgers in GB ab.</span><span class="sxs-lookup"><span data-stu-id="f211d-108">Gets disk size in GB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As DiskSkuTypes" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.DiskSkuTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.ISnapshot.Sku" />
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
            <span data-ttu-id="f211d-109">Ruft den Typ der Momentaufnahme-SKU.</span><span class="sxs-lookup"><span data-stu-id="f211d-109">Gets the snapshot SKU type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.ISnapshot.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As CreationSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" Usage="Microsoft.Azure.Management.Compute.Fluent.ISnapshot.Source" />
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
            <span data-ttu-id="f211d-110">Ruft die Details der Quelle aus der Momentaufnahme erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="f211d-110">Gets the details of the source from which snapshot is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>