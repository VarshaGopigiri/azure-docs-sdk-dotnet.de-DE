<Type Name="RequestResult" FullName="Microsoft.Azure.Batch.Common.RequestResult">
  <TypeSignature Language="C#" Value="public sealed class RequestResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.RequestResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestResult" />
  <TypeSignature Language="F#" Value="type RequestResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c3d3-101">Stellt das Ergebnis einer physischen Anforderung dar.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-101">Represents the result of a physical request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestResult (Microsoft.Azure.Batch.Common.RequestInformation requestInformation, Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Common.RequestInformation requestInformation, class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.RequestResult.#ctor(Microsoft.Azure.Batch.Common.RequestInformation,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.RequestResult : Microsoft.Azure.Batch.Common.RequestInformation * Exception -&gt; Microsoft.Azure.Batch.Common.RequestResult" Usage="new Microsoft.Azure.Batch.Common.RequestResult (requestInformation, exception)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestInformation" Type="Microsoft.Azure.Batch.Common.RequestInformation" />
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="requestInformation"><span data-ttu-id="7c3d3-102">Die Informationen der einzelnen Anforderung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-102">The information associated with the individual request.</span></span></param>
        <param name="exception"><span data-ttu-id="7c3d3-103">Die Ausnahme, die während der Ausführung der Anforderung (oder Null, wenn keine Ausnahme aufgetreten ist) erreicht.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-103">The exception hit during the execution of the request (or null if there was no exception).</span></span></param>
        <summary>
            <span data-ttu-id="7c3d3-104">Initialisiert eine neue <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" />.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-104">Initializes a new <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="Microsoft.Azure.Batch.Common.RequestResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c3d3-105">Ruft die Ausnahme, die während der Ausführung der Anforderung erreicht ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-105">Gets the exception hit during execution of the request, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.RequestInformation RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.RequestInformation RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestInformation" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.Azure.Batch.Common.RequestInformation" Usage="Microsoft.Azure.Batch.Common.RequestResult.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RequestInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c3d3-106">Ruft Informationen über die Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-106">Gets information about the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task Task { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Threading.Tasks.Task Task" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestResult.Task" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Task As Task" />
      <MemberSignature Language="F#" Value="member this.Task : System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.Common.RequestResult.Task" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c3d3-107">Ruft die <see cref="T:System.Threading.Tasks.Task" /> mit der Anforderung verknüpften Objekt.</span><span class="sxs-lookup"><span data-stu-id="7c3d3-107">Gets the <see cref="T:System.Threading.Tasks.Task" /> object associated with the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>