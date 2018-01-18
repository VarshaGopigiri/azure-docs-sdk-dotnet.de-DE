<Type Name="BatchRequest&lt;TOptions,TResponse&gt;" FullName="Microsoft.Azure.Batch.Protocol.BatchRequest&lt;TOptions,TResponse&gt;">
  <TypeSignature Language="C#" Value="public class BatchRequest&lt;TOptions,TResponse&gt; : Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;TOptions,TResponse&gt; where TOptions : IOptionsnew() where TResponse : IAzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchRequest`2&lt;.ctor (class Microsoft.Azure.Batch.Protocol.Models.IOptions) TOptions, (class Microsoft.Rest.Azure.IAzureOperationResponse) TResponse&gt; extends Microsoft.Azure.Batch.Protocol.BatchRequestBase`2&lt;!TOptions, !TResponse&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequest`2" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchRequest(Of TOptions, TResponse)&#xA;Inherits BatchRequestBase(Of TOptions, TResponse)" />
  <TypeSignature Language="F#" Value="type BatchRequest&lt;'Options, 'Response (requires 'Options :&gt; IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; IAzureOperationResponse)&gt; = class&#xA;    inherit BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; IAzureOperationResponse)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TOptions">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IOptions</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TResponse">
      <Constraints>
        <InterfaceName>Microsoft.Rest.Azure.IAzureOperationResponse</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;TOptions,TResponse&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">TOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">TResponse</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TOptions"><span data-ttu-id="6804b-101">Der Typ der Parameter übergeben außerhalb der Hauptteil der Anforderung mit der Anforderung verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="6804b-101">The type of the parameters passed outside the request body associated with the request.</span></span></typeparam>
    <typeparam name="TResponse"><span data-ttu-id="6804b-102">Der Antworttyp aus der Anforderung erwartet.</span><span class="sxs-lookup"><span data-stu-id="6804b-102">The response type expected from the request.</span></span></typeparam>
    <summary>
            <span data-ttu-id="6804b-103">Stellt die erforderlichen Informationen an einen bestimmten Aufruf mit keinen Anforderungstext an der Batch-Dienst-REST-API vornehmen.</span><span class="sxs-lookup"><span data-stu-id="6804b-103">Represents the information required to make a particular call with no request body to the Batch service REST API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequest`2.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequest&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; (restClient, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restClient"><span data-ttu-id="6804b-104">Der REST-Client verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6804b-104">The REST client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6804b-105">Das CancellationToken verwenden.</span><span class="sxs-lookup"><span data-stu-id="6804b-105">The cancellationToken to use.</span></span></param>
        <summary>
            <span data-ttu-id="6804b-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequest`2" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6804b-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequest`2" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>