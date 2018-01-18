<Type Name="IRefreshable&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IRefreshable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRefreshable`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRefreshable(Of T)" />
  <TypeSignature Language="F#" Value="type IRefreshable&lt;'T&gt; = interface" />
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
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public T Refresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Refresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.Refresh" />
      <MemberSignature Language="VB.NET" Value="Public Function Refresh () As T" />
      <MemberSignature Language="F#" Value="abstract member Refresh : unit -&gt; 'T" Usage="iRefreshable.Refresh " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ceb16-101">Aktualisiert die Ressource mit Azure synchronisiert werden.</span><span class="sxs-lookup"><span data-stu-id="ceb16-101">Refreshes the resource to sync with Azure.</span></span>
            </summary>
        <returns><span data-ttu-id="ceb16-102">die aktualisierte Ressource</span><span class="sxs-lookup"><span data-stu-id="ceb16-102">the refreshed resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iRefreshable.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="ceb16-103">Aktualisiert die Ressource mit Azure synchronisiert werden.</span><span class="sxs-lookup"><span data-stu-id="ceb16-103">Refreshes the resource to sync with Azure.</span></span>
            </summary>
        <returns><span data-ttu-id="ceb16-104">die aktualisierte Ressource</span><span class="sxs-lookup"><span data-stu-id="ceb16-104">the refreshed resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>