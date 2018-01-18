<Type Name="IServicePrincipals" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipals">
  <TypeSignature Language="C#" Value="public interface IServicePrincipals : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipal.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePrincipals implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipal.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipals" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePrincipals&#xA;Implements IBeta, IHasInner(Of IServicePrincipalsOperations), IHasManager(Of GraphRbacManager), ISupportsCreating(Of IBlank), ISupportsDeletingById, ISupportsGettingById(Of IServicePrincipal), ISupportsGettingByName(Of IServicePrincipal), ISupportsListing(Of IServicePrincipal)" />
  <TypeSignature Language="F#" Value="type IServicePrincipals = interface&#xA;    interface IBeta&#xA;    interface ISupportsListing&lt;IServicePrincipal&gt;&#xA;    interface ISupportsGettingById&lt;IServicePrincipal&gt;&#xA;    interface ISupportsGettingByName&lt;IServicePrincipal&gt;&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface IHasManager&lt;GraphRbacManager&gt;&#xA;    interface IHasInner&lt;IServicePrincipalsOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.ServicePrincipal.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipalsOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.GraphRbacManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f7ea2-101">Einstiegspunkt für einen Prinzipal dienstverwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="f7ea2-101">Entry point to service principal management API.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f7ea2-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="f7ea2-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members></Members>
</Type>