<Type Name="IWithTtl&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTtl&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTtl&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTtl`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTtl`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTtl(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTtl&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="28f84-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="28f84-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="28f84-102">Die Phase des Datensatzes festgelegt Definition ermöglicht die Zeit Gültigkeitsdauer (TTL) für die Datensätze in dieser Datensatzgruppe angeben.</span><span class="sxs-lookup"><span data-stu-id="28f84-102">The stage of the record set definition allowing to specify the Time To Live (TTL) for the records in this record set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeToLive">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;ParentT&gt; WithTimeToLive (long ttlInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach`1&lt;!ParentT&gt; WithTimeToLive(int64 ttlInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithTtl`1.WithTimeToLive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeToLive (ttlInSeconds As Long) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeToLive : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTtl.WithTimeToLive ttlInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttlInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="ttlInSeconds"><span data-ttu-id="28f84-103">Die Gültigkeitsdauer in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="28f84-103">TTL in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="28f84-104">Gibt an, die für die Gültigkeitsdauer für die Datensätze im Recordset.</span><span class="sxs-lookup"><span data-stu-id="28f84-104">Specifies the Time To Live for the records in the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="28f84-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="28f84-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>