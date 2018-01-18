<Type Name="IRouteTable" FullName="Microsoft.Azure.Management.Network.Fluent.IRouteTable">
  <TypeSignature Language="C#" Value="public interface IRouteTable : Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRouteTable implements class Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IRouteTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRouteTable&#xA;Implements IGroupableResource(Of INetworkManager, RouteTableInner), IHasAssociatedSubnets, IHasInner(Of RouteTableInner), IHasManager(Of INetworkManager), IRefreshable(Of IRouteTable), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IRouteTable = interface&#xA;    interface IGroupableResource&lt;INetworkManager, RouteTableInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;RouteTableInner&gt;&#xA;    interface IRefreshable&lt;IRouteTable&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasAssociatedSubnets" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasAssociatedSubnets</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0e52a-101">Der Einstiegspunkt für die Verwaltung der Route.</span><span class="sxs-lookup"><span data-stu-id="0e52a-101">Entry point for route table management.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.IRoute&gt; Routes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.IRoute&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IRouteTable.Routes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Routes As IReadOnlyDictionary(Of String, IRoute)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.IRoute&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IRouteTable.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.IRoute&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0e52a-102">Ruft die dieser Routingtabelle Routen ab.</span><span class="sxs-lookup"><span data-stu-id="0e52a-102">Gets the routes of this route table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>