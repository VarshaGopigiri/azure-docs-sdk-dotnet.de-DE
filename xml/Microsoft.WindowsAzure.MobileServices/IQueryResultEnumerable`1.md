<Type Name="IQueryResultEnumerable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IQueryResultEnumerable&lt;out T&gt; : System.Collections.Generic.IEnumerable&lt;out T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueryResultEnumerable`1&lt;+ T&gt; implements class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueryResultEnumerable(Of Out T)&#xA;Implements IEnumerable(Of Out T)" />
  <TypeSignature Language="F#" Value="type IQueryResultEnumerable&lt;'T&gt; = interface&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>Covariant</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="96a78-101">Die Schnittstelle IQueryResultEnumerable {T} bietet zusätzliche Informationen mit Antwort z. B. Summe und den nächsten Link-zurückgegeben</span><span class="sxs-lookup"><span data-stu-id="96a78-101">The IQueryResultEnumerable{T} interface provides extra details returned with response e.g. total count and next link</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;'T&gt;.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96a78-102">Ruft den Link zur nächsten Seite des Ergebnisses, das im Antwortheader zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="96a78-102">Gets the link to next page of result that is returned in response headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;'T&gt;.TotalCount" />
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
            <span data-ttu-id="96a78-103">Ruft die Gesamtanzahl für alle Datensätze, die zurückgegeben worden wären wird vom Client oder Server angegebenen Take Paging/Limit-Klausel ignoriert.</span><span class="sxs-lookup"><span data-stu-id="96a78-103">Gets the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>