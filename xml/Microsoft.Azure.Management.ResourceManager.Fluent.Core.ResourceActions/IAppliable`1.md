<Type Name="IAppliable&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IAppliable&lt;T&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppliable`1&lt;T&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppliable(Of T)&#xA;Implements IIndexable" />
  <TypeSignature Language="F#" Value="type IAppliable&lt;'T&gt; = interface&#xA;    interface IIndexable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Apply">
      <MemberSignature Language="C#" Value="public T Apply ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Apply() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1.Apply" />
      <MemberSignature Language="VB.NET" Value="Public Function Apply () As T" />
      <MemberSignature Language="F#" Value="abstract member Apply : unit -&gt; 'T" Usage="iAppliable.Apply " />
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
            <span data-ttu-id="4131c-101">Führen Sie die updateanforderung.</span><span class="sxs-lookup"><span data-stu-id="4131c-101">Execute the update request.</span></span>
            </summary>
        <returns><span data-ttu-id="4131c-102">die aktualisierte Ressource</span><span class="sxs-lookup"><span data-stu-id="4131c-102">the updated resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; ApplyAsync (System.Threading.CancellationToken cancellationToken = null, bool multiThreaded = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; ApplyAsync(valuetype System.Threading.CancellationToken cancellationToken, bool multiThreaded) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1.ApplyAsync(System.Threading.CancellationToken,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ApplyAsync : System.Threading.CancellationToken * bool -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iAppliable.ApplyAsync (cancellationToken, multiThreaded)" />
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
        <Parameter Name="multiThreaded" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4131c-103">das Abbruchtoken, das das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="4131c-103">cancellationToken the cancellation token</span></span></param>
        <param name="multiThreaded"><span data-ttu-id="4131c-104">Multithreading verwenden, die Multi-threading</span><span class="sxs-lookup"><span data-stu-id="4131c-104">multiThreaded use mutli-threading</span></span></param>
        <summary>
            <span data-ttu-id="4131c-105">Führen Sie die updateanforderung asynchron.</span><span class="sxs-lookup"><span data-stu-id="4131c-105">Execute the update request asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="4131c-106">Das Handle für den REST-Aufruf</span><span class="sxs-lookup"><span data-stu-id="4131c-106">the handle to the REST call</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>