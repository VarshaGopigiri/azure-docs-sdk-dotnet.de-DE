<Type Name="IWithPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPort&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="53c3a-101">Der übergeordnete Typ.</span><span class="sxs-lookup"><span data-stu-id="53c3a-101">The parent type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="53c3a-102">Die Phase der Prüfpunkts Definition ermöglicht, die an den Port zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="53c3a-102">The stage of the probe definition allowing to specify the port to monitor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt; WithPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithPort`1.WithPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPort (port As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPort.WithPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="53c3a-103">eine Portnummer an.</span><span class="sxs-lookup"><span data-stu-id="53c3a-103">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="53c3a-104">Gibt die Portnummer für die Systemüberwachung aufrufen.</span><span class="sxs-lookup"><span data-stu-id="53c3a-104">Specifies the port number to call for health monitoring.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="53c3a-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="53c3a-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>