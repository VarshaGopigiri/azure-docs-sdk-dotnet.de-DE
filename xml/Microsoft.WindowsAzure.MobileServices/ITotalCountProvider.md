<Type Name="ITotalCountProvider" FullName="Microsoft.WindowsAzure.MobileServices.ITotalCountProvider">
  <TypeSignature Language="C#" Value="public interface ITotalCountProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITotalCountProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.ITotalCountProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITotalCountProvider" />
  <TypeSignature Language="F#" Value="type ITotalCountProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Use IQueryResultEnumerable interface")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9cbd6-101">Die ITotalCountProvider-Schnittstelle stellt die Gesamtanzahl für alle Datensätze, die zurückgegeben worden wären wird vom Client oder Server angegebenen Take Paging/Limit-Klausel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9cbd6-101">The ITotalCountProvider interface provides the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>  <span data-ttu-id="9cbd6-102">Wenn Sie die Abfrage aufrufen. RequestTotalCount(), können Sie das Ergebnis (gibt an, ob es eine Sequenz oder eine Liste handelt) in ITotalCountProvider umwandeln.</span><span class="sxs-lookup"><span data-stu-id="9cbd6-102">If you call query.RequestTotalCount(), you can cast the result (whether its a sequence or a list) to ITotalCountProvider.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.ITotalCountProvider.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="Microsoft.WindowsAzure.MobileServices.ITotalCountProvider.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9cbd6-103">Ruft die Gesamtanzahl für alle Datensätze, die zurückgegeben worden wären wird vom Client oder Server angegebenen Take Paging/Limit-Klausel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9cbd6-103">Gets the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>