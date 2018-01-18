<Type Name="RemoteExceptionInformation" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation">
  <TypeSignature Language="C#" Value="public class RemoteExceptionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RemoteExceptionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class RemoteExceptionInformation" />
  <TypeSignature Language="F#" Value="type RemoteExceptionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RemoteExceptionInformation", Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f6c99-101">Stellt den Fehler von Webdiensten verwendet werden, um die Details der Ausnahme aus der Dienstreplikats an den Client übertragen.</span><span class="sxs-lookup"><span data-stu-id="f6c99-101">Represents the fault type used by Service Remoting to transfer the exception details from the Service Replica to the client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteExceptionInformation (byte[] data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (data As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation : byte[] -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation" Usage="new Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation data" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="data" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="f6c99-102">Die Daten an den Client gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="f6c99-102">The data to be sent to the client.</span></span></param>
        <summary>
            <span data-ttu-id="f6c99-103">Instanziiert die RemoteExceptionInformation-Objekt mit den Daten.</span><span class="sxs-lookup"><span data-stu-id="f6c99-103">Instantiates the RemoteExceptionInformation object with the data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public byte[] Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As Byte()" />
      <MemberSignature Language="F#" Value="member this.Data : byte[]" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="Data", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6c99-104">Serialisiert Ausnahme oder der Ausnahmemeldung als UTF8 codiert werden, wenn die Ausnahme nicht serialisiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="f6c99-104">Serialized exception or the exception message encoded as UTF8 if the exception cannot be serialized.</span></span>
            </summary>
        <value><span data-ttu-id="f6c99-105">Die Daten in der Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="f6c99-105">The data in the exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromException">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation FromException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation FromException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.FromException(System.Exception)" />
      <MemberSignature Language="F#" Value="static member FromException : Exception -&gt; Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.FromException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="f6c99-106">Die Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="f6c99-106">The exception.</span></span></param>
        <summary>
            <span data-ttu-id="f6c99-107">Gibt eine Methode, die die RemoteExceptionInformation nach einer Ausnahme erstellt.</span><span class="sxs-lookup"><span data-stu-id="f6c99-107">Indicates a method that constructs the RemoteExceptionInformation from an exception.</span></span>
            </summary>
        <returns><span data-ttu-id="f6c99-108">Gibt die RemoteExceptionInformation zurück.</span><span class="sxs-lookup"><span data-stu-id="f6c99-108">Returns the RemoteExceptionInformation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToException">
      <MemberSignature Language="C#" Value="public static bool ToException (Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation remoteExceptionInformation, out Exception result);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool ToException(class Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation remoteExceptionInformation, [out] class System.Exception&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.ToException(Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation,System.Exception@)" />
      <MemberSignature Language="F#" Value="static member ToException : Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation *  -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation.ToException (remoteExceptionInformation, result)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remoteExceptionInformation" Type="Microsoft.ServiceFabric.Services.Remoting.V1.RemoteExceptionInformation" />
        <Parameter Name="result" Type="System.Exception&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remoteExceptionInformation"><span data-ttu-id="f6c99-109">Die RemoteExceptionInformation.</span><span class="sxs-lookup"><span data-stu-id="f6c99-109">The RemoteExceptionInformation.</span></span></param>
        <param name="result"><span data-ttu-id="f6c99-110">Die Ausnahme von der Remoteseite.</span><span class="sxs-lookup"><span data-stu-id="f6c99-110">The exception from the remote side.</span></span></param>
        <summary>
            <span data-ttu-id="f6c99-111">Ruft die Ausnahme aus der RemoteExceptionInformation ab.</span><span class="sxs-lookup"><span data-stu-id="f6c99-111">Gets the exception from the RemoteExceptionInformation</span></span>
            </summary>
        <returns><span data-ttu-id="f6c99-112">"true", wenn eine Ausnahme aufgetreten ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="f6c99-112">true if there was a valid exception; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>