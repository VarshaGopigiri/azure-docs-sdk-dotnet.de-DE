<Type Name="IWithProtocol&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithProtocol&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithProtocol&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasProtocol.Definition.IWithProtocol&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProtocol`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasProtocol.Definition.IWithProtocol`2&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithProtocol`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProtocol(Of ParentT)&#xA;Implements IWithProtocol(Of IWithTimeout(Of ParentT), ApplicationGatewayProtocol)" />
  <TypeSignature Language="F#" Value="type IWithProtocol&lt;'ParentT&gt; = interface&#xA;    interface IWithProtocol&lt;IWithTimeout&lt;'ParentT&gt;, ApplicationGatewayProtocol&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasProtocol.Definition.IWithProtocol&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;,Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="ebec3-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="ebec3-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ebec3-102">Phase der eine Anwendung Gateway Prüfpunkt Update festlegen, dass das Protokoll des Prüfpunkts angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ebec3-102">Stage of an application gateway probe update allowing to specify the protocol of the probe.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHttp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt; WithHttp ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1&lt;!ParentT&gt; WithHttp() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithProtocol`1.WithHttp" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttp () As IWithTimeout(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttp : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;'ParentT&gt;" Usage="iWithProtocol.WithHttp " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ebec3-103">Gibt HTTP als Protokoll Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="ebec3-103">Specifies HTTP as the probe protocol.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ebec3-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="ebec3-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithHttps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt; WithHttps ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1&lt;!ParentT&gt; WithHttps() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithProtocol`1.WithHttps" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttps () As IWithTimeout(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttps : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;'ParentT&gt;" Usage="iWithProtocol.WithHttps " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ebec3-105">Gibt an, HTTPS als die Prüfpunkt-Protokoll.</span><span class="sxs-lookup"><span data-stu-id="ebec3-105">Specifies HTTPS as the probe protocol.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ebec3-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="ebec3-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>