<Type Name="ServerBusyException" FullName="Microsoft.Azure.ServiceBus.ServerBusyException">
  <TypeSignature Language="C#" Value="public sealed class ServerBusyException : Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServerBusyException extends Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ServerBusyException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServerBusyException&#xA;Inherits ServiceBusException" />
  <TypeSignature Language="F#" Value="type ServerBusyException = class&#xA;    inherit ServiceBusException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ServiceBusException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f8faa-101">Die Ausnahme, die ausgelöst wird, wenn ein Server ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="f8faa-101">The exception that is thrown when a server is busy.</span></span>  <span data-ttu-id="f8faa-102">Aufrufer sollten warten Sie einen Moment und wiederholen Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f8faa-102">Callers should wait a while and retry the operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerBusyException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServerBusyException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServerBusyException : string -&gt; Microsoft.Azure.ServiceBus.ServerBusyException" Usage="new Microsoft.Azure.ServiceBus.ServerBusyException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerBusyException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServerBusyException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServerBusyException : string * Exception -&gt; Microsoft.Azure.ServiceBus.ServerBusyException" Usage="new Microsoft.Azure.ServiceBus.ServerBusyException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <param name="innerException">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>