<Type Name="INetworkManager" FullName="Microsoft.Azure.Management.Network.Fluent.INetworkManager">
  <TypeSignature Language="C#" Value="public interface INetworkManager : Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkManager implements class Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManagerBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetworkManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkManager&#xA;Implements IBeta, IHasInner(Of INetworkManagementClient), IManager(Of INetworkManagementClient), INetworkManagerBeta" />
  <TypeSignature Language="F#" Value="type INetworkManager = interface&#xA;    interface INetworkManagerBeta&#xA;    interface IBeta&#xA;    interface IManager&lt;INetworkManagementClient&gt;&#xA;    interface IHasInner&lt;INetworkManagementClient&gt;&#xA;    interface IManagerBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.ApplicationGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationGateways As IApplicationGateways" />
      <MemberSignature Language="F#" Value="member this.ApplicationGateways : Microsoft.Azure.Management.Network.Fluent.IApplicationGateways" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.ApplicationGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-101">Einstiegspunkt für einen Gateway-anwendungsverwaltung.</span><span class="sxs-lookup"><span data-stu-id="84059-101">Entry point to application gateway management.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.LoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancers As ILoadBalancers" />
      <MemberSignature Language="F#" Value="member this.LoadBalancers : Microsoft.Azure.Management.Network.Fluent.ILoadBalancers" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.LoadBalancers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-102">Zurückgeben der Einstiegspunkt zur Verwaltung des Lastenausgleichsmoduls laden</span><span class="sxs-lookup"><span data-stu-id="84059-102">return entry point to load balancer management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As INetworkInterfaces" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-103">Kehren Sie Einstiegspunkt zur netzwerkverwaltung-Schnittstelle zurück</span><span class="sxs-lookup"><span data-stu-id="84059-103">return entry point to network interface management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Networks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworks Networks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworks Networks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.Networks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Networks As INetworks" />
      <MemberSignature Language="F#" Value="member this.Networks : Microsoft.Azure.Management.Network.Fluent.INetworks" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.Networks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-104">Einstiegspunkt zu des virtuellen Netzwerks zurückkehren</span><span class="sxs-lookup"><span data-stu-id="84059-104">return entry point to virtual network management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroups As INetworkSecurityGroups" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroups : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-105">Einstiegspunkt zur Verwaltung von Sicherheitsgruppen Netzwerk zurückzukehren</span><span class="sxs-lookup"><span data-stu-id="84059-105">return entry point to network security group management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddresses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.PublicIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddresses As IPublicIPAddresses" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddresses : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.PublicIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-106">Kehren Sie zur öffentlichen IP-Adressverwaltung Einstiegspunkt zurück</span><span class="sxs-lookup"><span data-stu-id="84059-106">return entry point to public IP address management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTables">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteTables RouteTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRouteTables RouteTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.RouteTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteTables As IRouteTables" />
      <MemberSignature Language="F#" Value="member this.RouteTables : Microsoft.Azure.Management.Network.Fluent.IRouteTables" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkManager.RouteTables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteTables</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84059-107">Einstiegspunkt für die Verwaltung der route</span><span class="sxs-lookup"><span data-stu-id="84059-107">Entry point to route table management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>