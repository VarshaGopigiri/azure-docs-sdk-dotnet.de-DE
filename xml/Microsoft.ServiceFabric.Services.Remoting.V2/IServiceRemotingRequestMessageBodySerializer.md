<Type Name="IServiceRemotingRequestMessageBodySerializer" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestMessageBodySerializer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestMessageBodySerializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestMessageBodySerializer" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestMessageBodySerializer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf5ce-101">Definiert die Schnittstelle, die implementiert werden muss, um ein Serialisierungsprogramm/Deserialisierer für Remoting-Nachrichtentext bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="bf5ce-101">Defines the interface that must be implemented to provide a serializer/deserializer for remoting request message body.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody Deserialize (Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody Deserialize(class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer.Deserialize(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Public Function Deserialize (messageBody As IncomingMessageBody) As IServiceRemotingRequestMessageBody" />
      <MemberSignature Language="F#" Value="abstract member Deserialize : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" Usage="iServiceRemotingRequestMessageBodySerializer.Deserialize messageBody" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody" />
      </Parameters>
      <Docs>
        <param name="messageBody"></param>
        <summary>
            <span data-ttu-id="bf5ce-102">Deserialisiert IncomingMessageBody zu IServiceRemotingRequestMessageBody</span><span class="sxs-lookup"><span data-stu-id="bf5ce-102">Deserializes IncomingMessageBody to IServiceRemotingRequestMessageBody</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody Serialize (Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody serviceRemotingRequestMessageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody Serialize(class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody serviceRemotingRequestMessageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer.Serialize(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Public Function Serialize (serviceRemotingRequestMessageBody As IServiceRemotingRequestMessageBody) As OutgoingMessageBody" />
      <MemberSignature Language="F#" Value="abstract member Serialize : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody" Usage="iServiceRemotingRequestMessageBodySerializer.Serialize serviceRemotingRequestMessageBody" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceRemotingRequestMessageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
      </Parameters>
      <Docs>
        <param name="serviceRemotingRequestMessageBody"></param>
        <summary>
            <span data-ttu-id="bf5ce-103">Serialisiert IServiceRemotingRequestMessageBody zu OutgoingMessageBody</span><span class="sxs-lookup"><span data-stu-id="bf5ce-103">Serializes IServiceRemotingRequestMessageBody to OutgoingMessageBody</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>