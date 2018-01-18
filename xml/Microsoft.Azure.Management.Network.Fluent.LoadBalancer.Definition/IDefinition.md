<Type Name="IDefinition" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IDefinition">
  <TypeSignature Language="C#" Value="public interface IDefinition : Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IBlank, Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool, Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule, Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup, Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat, Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNatOrCreate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinition implements class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IBlank, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithBackend, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndNatChoice, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithFrontend, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatPool, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithInboundNatRule, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNatOrCreate, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLoadBalancingRule, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithPrivateFrontend, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithProbe, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithPublicFrontend, class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithSku, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinition&#xA;Implements IBeta, IBlank, ICreatable(Of ILoadBalancer), IDefinitionWithRegion(Of IWithGroup), IDefinitionWithTags(Of IWithCreate), IWithCreatableResourceGroup(Of IWithLBRuleOrNat), IWithCreateAndInboundNatPool, IWithCreateAndInboundNatRule, IWithExistingResourceGroup(Of IWithLBRuleOrNat), IWithGroup, IWithGroup(Of IWithLBRuleOrNat), IWithLBRuleOrNat, IWithLBRuleOrNatOrCreate, IWithNewResourceGroup(Of IWithLBRuleOrNat)" />
  <TypeSignature Language="F#" Value="type IDefinition = interface&#xA;    interface IBlank&#xA;    interface IDefinitionWithRegion&lt;IWithGroup&gt;&#xA;    interface IWithGroup&#xA;    interface IWithGroup&lt;IWithLBRuleOrNat&gt;&#xA;    interface IWithExistingResourceGroup&lt;IWithLBRuleOrNat&gt;&#xA;    interface IWithNewResourceGroup&lt;IWithLBRuleOrNat&gt;&#xA;    interface IWithCreatableResourceGroup&lt;IWithLBRuleOrNat&gt;&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;ILoadBalancer&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithBackend&#xA;    interface IWithFrontend&#xA;    interface IWithPublicFrontend&#xA;    interface IWithPrivateFrontend&#xA;    interface IWithProbe&#xA;    interface IWithSku&#xA;    interface IBeta&#xA;    interface IWithLoadBalancingRule&#xA;    interface IWithLBRuleOrNat&#xA;    interface IWithInboundNatRule&#xA;    interface IWithInboundNatPool&#xA;    interface IWithLBRuleOrNatOrCreate&#xA;    interface IWithCreateAndNatChoice&#xA;    interface IWithCreateAndInboundNatPool&#xA;    interface IWithCreateAndInboundNatRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IBlank</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatPool</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreateAndInboundNatRule</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNatOrCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithLBRuleOrNat&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="471a3-101">Die Gesamtheit der Load Balancer-Definition.</span><span class="sxs-lookup"><span data-stu-id="471a3-101">The entirety of the load balancer definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>