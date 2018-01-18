<Type Name="ILoadBalancerBackend" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend">
  <TypeSignature Language="C#" Value="public interface ILoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.IHasBackendNics, Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancerBackend implements class Microsoft.Azure.Management.Network.Fluent.IHasBackendNics, class Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancerBackend&#xA;Implements IChildResource(Of ILoadBalancer), IHasBackendNics, IHasInner(Of BackendAddressPoolInner), IHasLoadBalancingRules, IHasParent(Of ILoadBalancer)" />
  <TypeSignature Language="F#" Value="type ILoadBalancerBackend = interface&#xA;    interface IHasInner&lt;BackendAddressPoolInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;&#xA;    interface IHasLoadBalancingRules&#xA;    interface IHasBackendNics" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasBackendNics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1eb57-101">Eine unveränderliche clientseitige Darstellung einer Back-End-Adressenpool des Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="1eb57-101">An immutable client-side representation of a load balancer backend address pool.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="1eb57-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="1eb57-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetVirtualMachineIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; GetVirtualMachineIds ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.ISet`1&lt;string&gt; GetVirtualMachineIds() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend.GetVirtualMachineIds" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVirtualMachineIds () As ISet(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetVirtualMachineIds : unit -&gt; System.Collections.Generic.ISet&lt;string&gt;" Usage="iLoadBalancerBackend.GetVirtualMachineIds " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1eb57-103">Eine Liste der IDs der virtuellen Computer verknüpft sind mit diesem Back-End-Ressource.</span><span class="sxs-lookup"><span data-stu-id="1eb57-103">A list of the resource IDs of the virtual machines associated with this backend.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>