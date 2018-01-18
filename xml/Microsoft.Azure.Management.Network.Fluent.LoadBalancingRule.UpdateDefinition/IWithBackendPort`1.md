<Type Name="IWithBackendPort&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithBackendPort&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendPort&lt;ReturnT&gt; : Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithFloatingIP&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithIdleTimeoutInMinutes&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithLoadDistribution&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithProbe&lt;ReturnT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendPort`1&lt;ReturnT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach`1&lt;!ReturnT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach`1&lt;!ReturnT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithFloatingIP`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithIdleTimeoutInMinutes`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithLoadDistribution`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithProbe`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithBackendPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendPort(Of ReturnT)&#xA;Implements IInUpdate(Of ReturnT), IWithAttach(Of ReturnT), IWithBackendPort(Of IWithAttach(Of ReturnT)), IWithFloatingIP(Of IWithAttach(Of ReturnT)), IWithFloatingIP(Of ReturnT), IWithIdleTimeoutInMinutes(Of ReturnT), IWithLoadDistribution(Of ReturnT), IWithProbe(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithBackendPort&lt;'ReturnT&gt; = interface&#xA;    interface IWithBackendPort&lt;IWithAttach&lt;'ReturnT&gt;&gt;&#xA;    interface IWithAttach&lt;'ReturnT&gt;&#xA;    interface IInUpdate&lt;'ReturnT&gt;&#xA;    interface IWithFloatingIP&lt;'ReturnT&gt;&#xA;    interface IWithFloatingIP&lt;IWithAttach&lt;'ReturnT&gt;&gt;&#xA;    interface IWithIdleTimeoutInMinutes&lt;'ReturnT&gt;&#xA;    interface IWithLoadDistribution&lt;'ReturnT&gt;&#xA;    interface IWithProbe&lt;'ReturnT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithAttach&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithFloatingIP&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithIdleTimeoutInMinutes&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithLoadDistribution&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IWithProbe&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ReturnT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="4746c-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="4746c-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="4746c-102">Die Phase einer für den Netzwerklastenausgleich Regeldefinition an den Back-End-Port zum Senden des Lastenausgleich Datenverkehrs zulassen.</span><span class="sxs-lookup"><span data-stu-id="4746c-102">The stage of a load balancing rule definition allowing to specify the backend port to send the load-balanced traffic to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>