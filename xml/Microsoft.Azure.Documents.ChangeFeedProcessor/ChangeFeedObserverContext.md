<Type Name="ChangeFeedObserverContext" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext">
  <TypeSignature Language="C#" Value="public class ChangeFeedObserverContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedObserverContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedObserverContext" />
  <TypeSignature Language="F#" Value="type ChangeFeedObserverContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e361-101">Das an der Kontext <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" /> Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="8e361-101">The context passed to <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" /> events.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedObserverContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FeedResponse">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.IFeedResponse&lt;Microsoft.Azure.Documents.Document&gt; FeedResponse { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Client.IFeedResponse`1&lt;class Microsoft.Azure.Documents.Document&gt; FeedResponse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext.FeedResponse" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FeedResponse As IFeedResponse(Of Document)" />
      <MemberSignature Language="F#" Value="member this.FeedResponse : Microsoft.Azure.Documents.Client.IFeedResponse&lt;Microsoft.Azure.Documents.Document&gt;" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext.FeedResponse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.IFeedResponse&lt;Microsoft.Azure.Documents.Document&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e361-102">Ruft die Antwort ab, aus der zugrunde liegenden <see cref="M:Microsoft.Azure.Documents.Linq.IDocumentQuery`1.ExecuteNextAsync(System.Threading.CancellationToken)" /> aufrufen.</span><span class="sxs-lookup"><span data-stu-id="8e361-102">Gets the response from the underlying <see cref="M:Microsoft.Azure.Documents.Linq.IDocumentQuery`1.ExecuteNextAsync(System.Threading.CancellationToken)" /> call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyRangeId">
      <MemberSignature Language="C#" Value="public string PartitionKeyRangeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyRangeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext.PartitionKeyRangeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyRangeId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyRangeId : string" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext.PartitionKeyRangeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e361-103">Ruft die Id der Partition für das aktuelle Ereignis ab.</span><span class="sxs-lookup"><span data-stu-id="8e361-103">Gets the id of the partition for current event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>