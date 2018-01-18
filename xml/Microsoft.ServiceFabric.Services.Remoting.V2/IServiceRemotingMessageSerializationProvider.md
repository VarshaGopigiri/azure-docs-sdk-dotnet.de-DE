<Type Name="IServiceRemotingMessageSerializationProvider" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageSerializationProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="899b9-101">Definiert die Schnittstelle, die für das Bereitstellen von benutzerdefinierten Serialisierung für die Anforderung Remoting implementiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="899b9-101">Defines the interface that must be implemented for providing custom serialization for the remoting request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="iServiceRemotingMessageSerializationProvider.CreateMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="899b9-102">Erstellen Sie eine IServiceRemotingMessageBodyFactory zum Erstellen von Anforderung und den Antworttext, Remoting verwendet.</span><span class="sxs-lookup"><span data-stu-id="899b9-102">Create a IServiceRemotingMessageBodyFactory used for creating remoting request and response body.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequestMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; requestBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; requestBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateRequestMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRequestMessageSerializer (serviceInterfaceType As Type, requestBodyTypes As IEnumerable(Of Type)) As IServiceRemotingRequestMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateRequestMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer" Usage="iServiceRemotingMessageSerializationProvider.CreateRequestMessageSerializer (serviceInterfaceType, requestBodyTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="requestBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType"><span data-ttu-id="899b9-103">Dienst-Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="899b9-103">User service interface</span></span></param>
        <param name="requestBodyTypes"><span data-ttu-id="899b9-104">Parameter für alle Methoden in der serviceInterfaceType</span><span class="sxs-lookup"><span data-stu-id="899b9-104">Parameters for all the methods in the serviceInterfaceType</span></span></param>
        <summary>
            <span data-ttu-id="899b9-105">IServiceRemotingRequestMessageBodySerializer erstellt für eine ServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="899b9-105">Creates IServiceRemotingRequestMessageBodySerializer for a serviceInterface .</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; responseBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; responseBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateResponseMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateResponseMessageSerializer (serviceInterfaceType As Type, responseBodyTypes As IEnumerable(Of Type)) As IServiceRemotingResponseMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer" Usage="iServiceRemotingMessageSerializationProvider.CreateResponseMessageSerializer (serviceInterfaceType, responseBodyTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="responseBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType"><span data-ttu-id="899b9-106">Dienst-Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="899b9-106">User service interface</span></span></param>
        <param name="responseBodyTypes"><span data-ttu-id="899b9-107">Rückgabetypen für alle Methoden in der serviceInterfaceType</span><span class="sxs-lookup"><span data-stu-id="899b9-107">Return Types for all the methods in the serviceInterfaceType</span></span></param>
        <summary>
             <span data-ttu-id="899b9-108">IServiceRemotingResponseMessageBodySerializer erstellt für eine ServiceInterface.</span><span class="sxs-lookup"><span data-stu-id="899b9-108">Creates IServiceRemotingResponseMessageBodySerializer for a serviceInterface .</span></span>
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>