<Type Name="IDnsRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet">
  <TypeSignature Language="C#" Value="public interface IDnsRecordSet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet,Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDnsRecordSet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDnsRecordSet&#xA;Implements IChildResource(Of IDnsZone), IExternalChildResource(Of IDnsRecordSet, IDnsZone), IHasInner(Of RecordSetInner), IHasParent(Of IDnsZone), IRefreshable(Of IDnsRecordSet)" />
  <TypeSignature Language="F#" Value="type IDnsRecordSet = interface&#xA;    interface IExternalChildResource&lt;IDnsRecordSet, IDnsZone&gt;&#xA;    interface IChildResource&lt;IDnsZone&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IDnsZone&gt;&#xA;    interface IRefreshable&lt;IDnsRecordSet&gt;&#xA;    interface IHasInner&lt;RecordSetInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet,Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3e37c-101">Eine unveränderliche clientseitige Darstellung eines Datensatzes, die in Azure DNS-Zone festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="3e37c-101">An immutable client-side representation of a record set in Azure DNS Zone.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e37c-102">Ruft die Metadaten, die diesem Datensatz Satz zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3e37c-102">Gets the metadata associated with this record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecordType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.Models.RecordType RecordType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType RecordType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.RecordType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecordType As RecordType" />
      <MemberSignature Language="F#" Value="member this.RecordType : Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.RecordType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.Models.RecordType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e37c-103">Ruft den Typ der Datensätze in diesen Datensatz ab.</span><span class="sxs-lookup"><span data-stu-id="3e37c-103">Gets the type of records in this record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public long TimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToLive As Long" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : int64" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e37c-104">Ruft die Gültigkeitsdauer (TTL), der Datensätze in dieser Datensatzgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3e37c-104">Gets TTL of the records in this record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>