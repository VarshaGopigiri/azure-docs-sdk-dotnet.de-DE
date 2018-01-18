<Type Name="IRoute" FullName="Microsoft.Azure.Management.Network.Fluent.IRoute">
  <TypeSignature Language="C#" Value="public interface IRoute : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRoute implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRoute&#xA;Implements IChildResource(Of IRouteTable), IHasInner(Of RouteInner), IHasParent(Of IRouteTable)" />
  <TypeSignature Language="F#" Value="type IRoute = interface&#xA;    interface IHasInner&lt;RouteInner&gt;&#xA;    interface IChildResource&lt;IRouteTable&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IRouteTable&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IRouteTable&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="230aa-101">Eine unveränderliche clientseitige Darstellung einer Route einer Route-Tabelle.</span><span class="sxs-lookup"><span data-stu-id="230aa-101">An immutable client-side representation of a route of a route table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IRoute.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string" Usage="Microsoft.Azure.Management.Network.Fluent.IRoute.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="230aa-102">Ruft das Ziel-Adresspräfix, mithilfe der CIDR-Notation für die Route gilt ausgedrückt.</span><span class="sxs-lookup"><span data-stu-id="230aa-102">Gets the destination address prefix, expressed using the CIDR notation, to which the route applies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIPAddress">
      <MemberSignature Language="C#" Value="public string NextHopIPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IRoute.NextHopIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHopIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.NextHopIPAddress : string" Usage="Microsoft.Azure.Management.Network.Fluent.IRoute.NextHopIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="230aa-103">Ruft die IP-Adresse des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="230aa-103">Gets the IP address of the next hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType NextHopType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IRoute.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHopType As RouteNextHopType" />
      <MemberSignature Language="F#" Value="member this.NextHopType : Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" Usage="Microsoft.Azure.Management.Network.Fluent.IRoute.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="230aa-104">Ruft den Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="230aa-104">Gets the type of the next hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>