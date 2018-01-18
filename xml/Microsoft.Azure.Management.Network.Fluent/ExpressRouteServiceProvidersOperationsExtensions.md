<Type Name="ExpressRouteServiceProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteServiceProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteServiceProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteServiceProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="21236-101">Erweiterungsmethoden für ExpressRouteServiceProvidersOperations.</span><span class="sxs-lookup"><span data-stu-id="21236-101">Extension methods for ExpressRouteServiceProvidersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="21236-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="21236-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21236-103">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="21236-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21236-104">Ruft die verfügbaren express-Route-Dienstanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="21236-104">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteServiceProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteServiceProviderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteServiceProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="21236-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="21236-105">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="21236-106">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="21236-106">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21236-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="21236-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21236-108">Ruft die verfügbaren express-Route-Dienstanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="21236-108">Gets all the available express route service providers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>