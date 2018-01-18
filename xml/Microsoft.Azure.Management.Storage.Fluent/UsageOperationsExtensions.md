<Type Name="UsageOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.Fluent.UsageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.UsageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2666-101">Erweiterungsmethoden für UsageOperations.</span><span class="sxs-lookup"><span data-stu-id="a2666-101">Extension methods for UsageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.Fluent.IUsageOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.Fluent.IUsageOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.UsageOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.Fluent.IUsageOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.Fluent.IUsageOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.UsageOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.UsageOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IUsageOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a2666-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a2666-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2666-103">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a2666-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2666-104">Ruft den aktuellen Verwendungszähler und den Grenzwert für die Ressourcen für das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="a2666-104">Gets the current usage count and the limit for the resources under the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>