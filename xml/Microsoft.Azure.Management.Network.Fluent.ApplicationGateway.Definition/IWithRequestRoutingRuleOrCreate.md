<Type Name="IWithRequestRoutingRuleOrCreate" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRequestRoutingRuleOrCreate">
  <TypeSignature Language="C#" Value="public interface IWithRequestRoutingRuleOrCreate : Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate, Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRequestRoutingRule, Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRequestRoutingRuleOrCreate implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithAuthenticationCertificate, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithAuthenticationCertificateBeta, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackendHttpConfig, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithDisabledSslProtocol, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithDisabledSslProtocolBeta, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithExistingSubnet, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithInstanceCount, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithListener, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateFrontend, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateIPAddress, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithProbe, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicFrontend, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicIPAddress, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRedirectConfiguration, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRedirectConfigurationBeta, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRequestRoutingRule, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize, class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert, class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRequestRoutingRuleOrCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRequestRoutingRuleOrCreate&#xA;Implements IBeta, ICreatable(Of IApplicationGateway), IDefinitionWithTags(Of IWithCreate), IWithCreate, IWithExistingPublicIPAddress(Of IWithCreate), IWithNewPublicIPAddressNoDnsLabel(Of IWithCreate), IWithPrivateIPAddress(Of IWithCreate), IWithPublicIPAddressNoDnsLabel(Of IWithCreate), IWithRequestRoutingRule, IWithSubnet(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithRequestRoutingRuleOrCreate = interface&#xA;    interface IWithRequestRoutingRule&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IApplicationGateway&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithSize&#xA;    interface IWithInstanceCount&#xA;    interface IWithSslCert&#xA;    interface IWithFrontendPort&#xA;    interface IWithListener&#xA;    interface IWithBackendHttpConfig&#xA;    interface IWithBackend&#xA;    interface IWithExistingSubnet&#xA;    interface IWithSubnet&lt;IWithCreate&gt;&#xA;    interface IWithPrivateIPAddress&#xA;    interface IWithPrivateIPAddress&lt;IWithCreate&gt;&#xA;    interface IWithPrivateFrontend&#xA;    interface IWithPublicFrontend&#xA;    interface IWithPublicIPAddress&#xA;    interface IWithPublicIPAddressNoDnsLabel&lt;IWithCreate&gt;&#xA;    interface IWithExistingPublicIPAddress&lt;IWithCreate&gt;&#xA;    interface IWithNewPublicIPAddressNoDnsLabel&lt;IWithCreate&gt;&#xA;    interface IWithProbe&#xA;    interface IWithDisabledSslProtocol&#xA;    interface IWithDisabledSslProtocolBeta&#xA;    interface IBeta&#xA;    interface IWithAuthenticationCertificate&#xA;    interface IWithAuthenticationCertificateBeta&#xA;    interface IWithRedirectConfiguration&#xA;    interface IWithRedirectConfigurationBeta&#xA;    interface IWithAvailabilityZone" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithRequestRoutingRule</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="fdccd-101">Die Phase einer Anwendung Gateway Definition Möglichkeit zum Hinzufügen von mehr anfordern Routingregeln, oder starten die optionale Einstellungen angeben oder das Anwendungsgateway erstellen.</span><span class="sxs-lookup"><span data-stu-id="fdccd-101">The stage of an application gateway definition allowing to continue adding more request routing rules, or start specifying optional settings, or create the application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>