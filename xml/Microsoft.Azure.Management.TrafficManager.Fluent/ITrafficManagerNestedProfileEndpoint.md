<Type Name="ITrafficManagerNestedProfileEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerNestedProfileEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerNestedProfileEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerNestedProfileEndpoint&#xA;Implements IChildResource(Of ITrafficManagerProfile), IExternalChildResource(Of ITrafficManagerEndpoint, ITrafficManagerProfile), IHasInner(Of EndpointInner), IHasParent(Of ITrafficManagerProfile), IRefreshable(Of ITrafficManagerEndpoint), ITrafficManagerEndpoint" />
  <TypeSignature Language="F#" Value="type ITrafficManagerNestedProfileEndpoint = interface&#xA;    interface ITrafficManagerEndpoint&#xA;    interface IExternalChildResource&lt;ITrafficManagerEndpoint, ITrafficManagerProfile&gt;&#xA;    interface IChildResource&lt;ITrafficManagerProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ITrafficManagerProfile&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
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
            <span data-ttu-id="13e5d-101">Eine unveränderliche clientseitige Darstellung einer Azure Traffic Manager-Profil geschachtelt profileendpunkt.</span><span class="sxs-lookup"><span data-stu-id="13e5d-101">An immutable client-side representation of an Azure traffic manager profile nested profile endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MinimumChildEndpointCount">
      <MemberSignature Language="C#" Value="public long MinimumChildEndpointCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinimumChildEndpointCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.MinimumChildEndpointCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumChildEndpointCount As Long" />
      <MemberSignature Language="F#" Value="member this.MinimumChildEndpointCount : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.MinimumChildEndpointCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13e5d-102">Ruft die Anzahl der untergeordneten Endpunkte online verschachtelten Profil als fehlerfrei berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="13e5d-102">Gets the number of child endpoints to be online to consider nested profile as healthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestedProfileId">
      <MemberSignature Language="C#" Value="public string NestedProfileId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NestedProfileId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.NestedProfileId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NestedProfileId As String" />
      <MemberSignature Language="F#" Value="member this.NestedProfileId : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.NestedProfileId" />
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
            <span data-ttu-id="13e5d-103">Ruft die geschachtelten Traffic Manager-Profil-Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="13e5d-103">Gets the nested traffic manager profile resource id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceTrafficLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region SourceTrafficLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region SourceTrafficLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.SourceTrafficLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceTrafficLocation As Region" />
      <MemberSignature Language="F#" Value="member this.SourceTrafficLocation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint.SourceTrafficLocation" />
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
            <span data-ttu-id="13e5d-104">Ruft den Speicherort des Datenverkehrs, der der Endpunkt verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="13e5d-104">Gets the location of the traffic that the endpoint handles.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>