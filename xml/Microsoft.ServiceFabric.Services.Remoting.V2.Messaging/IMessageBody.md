<Type Name="IMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody">
  <TypeSignature Language="C#" Value="public interface IMessageBody : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageBody implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageBody&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IMessageBody = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4c441-101">Definiert eine Schnittstelle, die implementiert werden muss, um Nachrichtentext für die serialisierte Meldung bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="4c441-101">Defines an interface that must be implemented to provide message body for the serialized Message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetReceivedBuffer">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetReceivedBuffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream GetReceivedBuffer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody.GetReceivedBuffer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReceivedBuffer () As Stream" />
      <MemberSignature Language="F#" Value="abstract member GetReceivedBuffer : unit -&gt; System.IO.Stream" Usage="iMessageBody.GetReceivedBuffer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c441-102">Ruft den empfangenen Stream</span><span class="sxs-lookup"><span data-stu-id="4c441-102">Get the Received Stream</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSendBuffers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; GetSendBuffers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; GetSendBuffers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IMessageBody.GetSendBuffers" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSendBuffers () As IEnumerable(Of ArraySegment(Of Byte))" />
      <MemberSignature Language="F#" Value="abstract member GetSendBuffers : unit -&gt; seq&lt;ArraySegment&lt;byte&gt;&gt;" Usage="iMessageBody.GetSendBuffers " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c441-103">Ruft die Send-Puffer</span><span class="sxs-lookup"><span data-stu-id="4c441-103">Gets the Send Buffers</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>