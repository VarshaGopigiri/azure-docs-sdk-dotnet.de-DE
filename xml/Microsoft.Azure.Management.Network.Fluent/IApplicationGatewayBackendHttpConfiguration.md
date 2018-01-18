<Type Name="IApplicationGatewayBackendHttpConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayBackendHttpConfiguration : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta, Microsoft.Azure.Management.Network.Fluent.IHasPort, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayBackendHttpConfiguration implements class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta, class Microsoft.Azure.Management.Network.Fluent.IHasPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayBackendHttpConfiguration&#xA;Implements IApplicationGatewayBackendHttpConfigurationBeta, IBeta, IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayBackendHttpSettingsInner), IHasParent(Of IApplicationGateway), IHasPort, IHasProtocol(Of ApplicationGatewayProtocol)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayBackendHttpConfiguration = interface&#xA;    interface IHasInner&lt;ApplicationGatewayBackendHttpSettingsInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasProtocol&lt;ApplicationGatewayProtocol&gt;&#xA;    interface IHasPort&#xA;    interface IApplicationGatewayBackendHttpConfigurationBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfigurationBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c9eff-101">Eine unveränderliche clientseitige Darstellung von einem Anwendungsgateway-Back-End-HTTP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="c9eff-101">An immutable client-side representation of an application gateway's backend HTTP configuration.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="c9eff-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="c9eff-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CookieBasedAffinity">
      <MemberSignature Language="C#" Value="public bool CookieBasedAffinity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CookieBasedAffinity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.CookieBasedAffinity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CookieBasedAffinity As Boolean" />
      <MemberSignature Language="F#" Value="member this.CookieBasedAffinity : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.CookieBasedAffinity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eff-103">Ruft "true" zurück, wenn das Cookie Affinity (sticky Sessions) basierte ist aktiviert, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c9eff-103">Gets true if cookie based affinity (sticky sessions) is enabled, else false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe Probe { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.Probe" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Probe As IApplicationGatewayProbe" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public int RequestTimeout { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RequestTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.RequestTimeout : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayBackendHttpConfiguration.RequestTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9eff-104">Ruft den HTTP-Anforderungstimeout in Sekunden ab.</span><span class="sxs-lookup"><span data-stu-id="c9eff-104">Gets HTTP request timeout in seconds.</span></span> <span data-ttu-id="c9eff-105">Anforderungen schlagen fehl, wenn keine Antwort innerhalb der angegebenen Zeit empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="c9eff-105">Requests will fail if no response is received within the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>