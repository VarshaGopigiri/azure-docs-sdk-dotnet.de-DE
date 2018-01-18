<Type Name="ClientRequestIdProvider" FullName="Microsoft.Azure.Batch.ClientRequestIdProvider">
  <TypeSignature Language="C#" Value="public class ClientRequestIdProvider : Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientRequestIdProvider extends Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ClientRequestIdProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientRequestIdProvider&#xA;Inherits RequestInterceptor" />
  <TypeSignature Language="F#" Value="type ClientRequestIdProvider = class&#xA;    inherit RequestInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71333-101">Enthält eine Funktion zum Generieren einer Clientanforderungs-Id für die festzulegende als Interceptor <see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />.</span><span class="sxs-lookup"><span data-stu-id="71333-101">Interceptor which contains a function used to generate a client request id to set as <see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />.</span></span>
            <span data-ttu-id="71333-102">Wenn mehrere dieses Instanzen Festlegen der letzten Wins.</span><span class="sxs-lookup"><span data-stu-id="71333-102">If there are multiple instances of this then the last set wins.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientRequestIdProvider (Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,Guid&gt; generateClientRequestIdFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.Batch.Protocol.IBatchRequest, valuetype System.Guid&gt; generateClientRequestIdFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ClientRequestIdProvider.#ctor(System.Func{Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (generateClientRequestIdFunc As Func(Of IBatchRequest, Guid))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ClientRequestIdProvider : Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest, Guid&gt; -&gt; Microsoft.Azure.Batch.ClientRequestIdProvider" Usage="new Microsoft.Azure.Batch.ClientRequestIdProvider generateClientRequestIdFunc" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="generateClientRequestIdFunc" Type="System.Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="generateClientRequestIdFunc">
            <span data-ttu-id="71333-103">Eine Funktion verwendet, um die Clientanforderungs-Id zu generieren.  Diese Funktion kann für einen bestimmten Vorgang aufgrund von Wiederholungsversuchen mehr als einmal aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="71333-103">A function used to generate the client request id.  This function may be called more than once for any given operation due to retries.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71333-104">Initialisiert eine neue <see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" /> für die Verwendung in Client-Anforderungs-Id der Anforderung festlegen.</span><span class="sxs-lookup"><span data-stu-id="71333-104">Initializes a new <see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" /> for use in setting the client request id of a request.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>