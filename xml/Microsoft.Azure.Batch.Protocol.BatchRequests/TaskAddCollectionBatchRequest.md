<Type Name="TaskAddCollectionBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest">
  <TypeSignature Language="C#" Value="public class TaskAddCollectionBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddCollectionBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddCollectionBatchRequest&#xA;Inherits BatchRequest(Of IList(Of TaskAddParameter), TaskAddCollectionOptions, AzureOperationResponse(Of TaskAddCollectionResult, TaskAddCollectionHeaders))" />
  <TypeSignature Language="F#" Value="type TaskAddCollectionBatchRequest = class&#xA;    inherit BatchRequest&lt;IList&lt;TaskAddParameter&gt;, TaskAddCollectionOptions, AzureOperationResponse&lt;TaskAddCollectionResult, TaskAddCollectionHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="54382-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den TaskAddCollection-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="54382-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the TaskAddCollection operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddCollectionBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="54382-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="54382-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="54382-103">Die Parameter zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="54382-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="54382-104">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="54382-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="54382-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="54382-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskAddCollectionBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>