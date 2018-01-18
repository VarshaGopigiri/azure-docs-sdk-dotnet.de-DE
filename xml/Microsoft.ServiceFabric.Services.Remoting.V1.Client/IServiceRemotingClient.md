<Type Name="IServiceRemotingClient" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingClient : Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingClient implements class Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingClient&#xA;Implements ICommunicationClient" />
  <TypeSignature Language="F#" Value="type IServiceRemotingClient = interface&#xA;    interface ICommunicationClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.ICommunicationClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="95c1e-101">Definiert die Schnittstelle, die implementiert werden muss, um einen Client für die Kommunikation mit Webdiensten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="95c1e-101">Defines the interface that must be implemented to provide a client for Service Remoting communication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingClient.RequestResponseAsync (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="95c1e-102">Die Nachrichtenheader.</span><span class="sxs-lookup"><span data-stu-id="95c1e-102">The message headers.</span></span></param>
        <param name="requestBody"><span data-ttu-id="95c1e-103">Der Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="95c1e-103">The message body.</span></span></param>
        <summary>
            <span data-ttu-id="95c1e-104">Sendet eine Nachricht an den Dienst und ruft eine Antwort zurück.</span><span class="sxs-lookup"><span data-stu-id="95c1e-104">Sends a message to the service and gets a response back.</span></span>
            </summary>
        <returns><span data-ttu-id="95c1e-105">Gibt den Antworttext zurück.</span><span class="sxs-lookup"><span data-stu-id="95c1e-105">Returns the response body.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendOneWay">
      <MemberSignature Language="C#" Value="public void SendOneWay (Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendOneWay(class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Client.IServiceRemotingClient.SendOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendOneWay (messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member SendOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingClient.SendOneWay (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="messageHeaders"><span data-ttu-id="95c1e-106">Die Nachrichtenheader.</span><span class="sxs-lookup"><span data-stu-id="95c1e-106">The message headers.</span></span></param>
        <param name="requestBody"><span data-ttu-id="95c1e-107">Der Nachrichtentext.</span><span class="sxs-lookup"><span data-stu-id="95c1e-107">The message body.</span></span></param>
        <summary>
            <span data-ttu-id="95c1e-108">Sendet eine unidirektionale Nachricht an den Dienst an.</span><span class="sxs-lookup"><span data-stu-id="95c1e-108">Sends a one-way message to the service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>