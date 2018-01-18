<Type Name="ITrafficManagerExternalEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerExternalEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerExternalEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerExternalEndpoint&#xA;Implements IChildResource(Of ITrafficManagerProfile), IExternalChildResource(Of ITrafficManagerEndpoint, ITrafficManagerProfile), IHasInner(Of EndpointInner), IHasParent(Of ITrafficManagerProfile), IRefreshable(Of ITrafficManagerEndpoint), ITrafficManagerEndpoint" />
  <TypeSignature Language="F#" Value="type ITrafficManagerExternalEndpoint = interface&#xA;    interface ITrafficManagerEndpoint&#xA;    interface IExternalChildResource&lt;ITrafficManagerEndpoint, ITrafficManagerProfile&gt;&#xA;    interface IChildResource&lt;ITrafficManagerProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ITrafficManagerProfile&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6b89b-101">Eine unveränderliche clientseitige Darstellung einen externen Endpunkt für Azure Traffic Manager-Profil.</span><span class="sxs-lookup"><span data-stu-id="6b89b-101">An immutable client-side representation of an Azure traffic manager profile external endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b89b-102">Ruft den vollqualifizierten DNS-Namen des externen Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="6b89b-102">Gets the fully qualified DNS name of the external endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceTrafficLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region SourceTrafficLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region SourceTrafficLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint.SourceTrafficLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceTrafficLocation As Region" />
      <MemberSignature Language="F#" Value="member this.SourceTrafficLocation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint.SourceTrafficLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b89b-103">Ruft den Speicherort des Datenverkehrs, der der Endpunkt verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6b89b-103">Gets the location of the traffic that the endpoint handles.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>