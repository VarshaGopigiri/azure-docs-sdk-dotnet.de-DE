<Type Name="VirtualMachineSizesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineSizesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineSizesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineSizesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c7d38-101">Erweiterungsmethoden für VirtualMachineSizesOperations.</span><span class="sxs-lookup"><span data-stu-id="c7d38-101">Extension methods for VirtualMachineSizesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineSizesOperations, location As String) As IEnumerable(Of VirtualMachineSize)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions.List (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7d38-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c7d38-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="c7d38-103">Der Speicherort der virtual-Machine-Größen abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="c7d38-103">The location upon which virtual-machine-sizes is queried.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d38-104">Listet alle verfügbaren VM-Größen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="c7d38-104">Lists all available virtual machine sizes for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineSizesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineSizesOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7d38-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c7d38-105">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="c7d38-106">Der Speicherort der virtual-Machine-Größen abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="c7d38-106">The location upon which virtual-machine-sizes is queried.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7d38-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c7d38-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7d38-108">Listet alle verfügbaren VM-Größen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="c7d38-108">Lists all available virtual machine sizes for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>