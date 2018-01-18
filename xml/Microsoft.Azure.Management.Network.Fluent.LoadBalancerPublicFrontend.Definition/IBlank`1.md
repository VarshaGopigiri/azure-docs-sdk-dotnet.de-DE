<Type Name="IBlank&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IBlank&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IBlank&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithPublicIPAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBlank`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithPublicIPAddress`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IBlank`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBlank(Of ParentT)&#xA;Implements IWithExistingPublicIPAddress(Of IWithAttach(Of IWithCreate)), IWithNewPublicIPAddress(Of IWithAttach(Of IWithCreate)), IWithNewPublicIPAddressNoDnsLabel(Of IWithAttach(Of IWithCreate)), IWithPublicIPAddress(Of IWithAttach(Of IWithCreate)), IWithPublicIPAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IBlank&lt;'ParentT&gt; = interface&#xA;    interface IWithPublicIPAddress&lt;'ParentT&gt;&#xA;    interface IWithPublicIPAddress&lt;IWithAttach&lt;IWithCreate&gt;&gt;&#xA;    interface IWithExistingPublicIPAddress&lt;IWithAttach&lt;IWithCreate&gt;&gt;&#xA;    interface IWithNewPublicIPAddress&lt;IWithAttach&lt;IWithCreate&gt;&gt;&#xA;    interface IWithNewPublicIPAddressNoDnsLabel&lt;IWithAttach&lt;IWithCreate&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerPublicFrontend.Definition.IWithPublicIPAddress&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="d4dbc-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="d4dbc-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d4dbc-102">Die erste Phase der öffentliche Front-End-Definition.</span><span class="sxs-lookup"><span data-stu-id="d4dbc-102">The first stage of a public frontend definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>