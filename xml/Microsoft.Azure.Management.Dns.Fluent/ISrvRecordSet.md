<Type Name="ISrvRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSet">
  <TypeSignature Language="C#" Value="public interface ISrvRecordSet : Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet,Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISrvRecordSet implements class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet, class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISrvRecordSet&#xA;Implements IChildResource(Of IDnsZone), IDnsRecordSet, IExternalChildResource(Of IDnsRecordSet, IDnsZone), IHasInner(Of RecordSetInner), IHasParent(Of IDnsZone), IRefreshable(Of IDnsRecordSet)" />
  <TypeSignature Language="F#" Value="type ISrvRecordSet = interface&#xA;    interface IDnsRecordSet&#xA;    interface IExternalChildResource&lt;IDnsRecordSet, IDnsZone&gt;&#xA;    interface IChildResource&lt;IDnsZone&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IDnsZone&gt;&#xA;    interface IRefreshable&lt;IDnsRecordSet&gt;&#xA;    interface IHasInner&lt;RecordSetInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet</InterfaceName>
    </Interface>
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
            <span data-ttu-id="04616-101">Eine unveränderliche clientseitige Darstellung eines Datensatzes SVR (Dienst), die in Azure DNS-Zone festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="04616-101">An immutable client-side representation of an SVR (service) record set in Azure DNS Zone.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Records">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; Records { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt; Records" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSet.Records" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Records As IReadOnlyList(Of SrvRecord)" />
      <MemberSignature Language="F#" Value="member this.Records : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSet.Records" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Dns.Fluent.Models.SrvRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04616-102">Ruft die SRV-Einträge in diesen Datensatz ab.</span><span class="sxs-lookup"><span data-stu-id="04616-102">Gets the SRV records in this record set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>