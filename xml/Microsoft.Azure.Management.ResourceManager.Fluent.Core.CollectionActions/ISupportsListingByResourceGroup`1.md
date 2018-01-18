<Type Name="ISupportsListingByResourceGroup&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByResourceGroup&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsListingByResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsListingByResourceGroup`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByResourceGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsListingByResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsListingByResourceGroup&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByResourceGroup (string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByResourceGroup(string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByResourceGroup`1.ListByResourceGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByResourceGroup (resourceGroupName As String) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroup : string -&gt; seq&lt;'T&gt;" Usage="iSupportsListingByResourceGroup.ListByResourceGroup resourceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"> <span data-ttu-id="10b5a-101">der Name der Ressourcengruppe zum Auflisten der Ressourcen von</span><span class="sxs-lookup"><span data-stu-id="10b5a-101">the name of the resource group to list the resources from</span></span></param>
        <summary>
            <span data-ttu-id="10b5a-102">Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="10b5a-102">Lists resources of the specified type in the specified resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="10b5a-103">die Liste der Ressourcen</span><span class="sxs-lookup"><span data-stu-id="10b5a-103">the list of resources</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByResourceGroupAsync (string resourceGroupName, bool loadAllPages = true, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByResourceGroupAsync(string resourceGroupName, bool loadAllPages, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByResourceGroup`1.ListByResourceGroupAsync(System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupAsync : string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListingByResourceGroup.ListByResourceGroupAsync (resourceGroupName, loadAllPages, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadAllPages" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"> <span data-ttu-id="10b5a-104">der Name der Ressourcengruppe zum Auflisten der Ressourcen von</span><span class="sxs-lookup"><span data-stu-id="10b5a-104">the name of the resource group to list the resources from</span></span></param>
        <param name="loadAllPages">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="10b5a-105">Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="10b5a-105">Lists resources of the specified type in the specified resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="10b5a-106">die Liste der Ressourcen</span><span class="sxs-lookup"><span data-stu-id="10b5a-106">the list of resources</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>