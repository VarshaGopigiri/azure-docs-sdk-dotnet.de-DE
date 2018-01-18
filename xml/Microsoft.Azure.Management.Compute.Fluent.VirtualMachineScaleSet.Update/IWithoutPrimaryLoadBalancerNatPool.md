<Type Name="IWithoutPrimaryLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithoutPrimaryLoadBalancerNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithoutPrimaryLoadBalancerNatPool" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithoutPrimaryLoadBalancerNatPool" />
  <TypeSignature Language="F#" Value="type IWithoutPrimaryLoadBalancerNatPool = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1f2ee-101">Eine Phase der VM-Skalierungsgruppe festgelegt Update ermöglicht die Zuordnungen zwischen der primären Schnittstelle Netzwerkkonfiguration und die angegebenen eingehenden NAT-Pools des Lastenausgleichs entfernt.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-101">A stage of the virtual machine scale set update allowing to remove the associations between the primary network interface configuration and the specified inbound NAT pools of the load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrimaryInternalLoadBalancerNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancerNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool.WithoutPrimaryInternalLoadBalancerNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancerNatPools (ParamArray natPoolNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancerNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerNatPool.WithoutPrimaryInternalLoadBalancerNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="natPoolNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="natPoolNames"><span data-ttu-id="1f2ee-102">Die Namen der vorhandenen eingehenden NAT-Pools.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-102">The names of existing inbound NAT pools.</span></span></param>
        <summary>
            <span data-ttu-id="1f2ee-103">Entfernt die Zuordnungen zwischen der primären Schnittstelle Netzwerkkonfiguration und die angegebenen eingehenden NAT-Pools des internen Lastenausgleichs an.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-103">Removes the associations between the primary network interface configuration and the specified inbound NAT pools of the internal load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1f2ee-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancerNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancerNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool.WithoutPrimaryInternetFacingLoadBalancerNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancerNatPools (ParamArray natPoolNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancerNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancerNatPool.WithoutPrimaryInternetFacingLoadBalancerNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="natPoolNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="natPoolNames"><span data-ttu-id="1f2ee-105">Die Namen der vorhandenen eingehenden NAT-Pools.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-105">The names of existing inbound NAT pools.</span></span></param>
        <summary>
            <span data-ttu-id="1f2ee-106">Entfernt die Zuordnungen zwischen der primären Netzwerkschnittstellenkonfiguration und der angegebenen eingehenden NAT-Pools mit ein Lastenausgleichsmodul Internetzugriff an.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-106">Removes the associations between the primary network interface configuration and the specified inbound NAT pools of an Internet-facing load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1f2ee-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="1f2ee-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>