<Type Name="NetworkInterfaceLoadBalancersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkInterfaceLoadBalancersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkInterfaceLoadBalancersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkInterfaceLoadBalancersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceLoadBalancersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions.ListAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="networkInterfaceName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfaceLoadBalancersOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceLoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>