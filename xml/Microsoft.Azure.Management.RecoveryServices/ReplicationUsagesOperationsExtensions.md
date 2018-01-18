<Type Name="ReplicationUsagesOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ReplicationUsagesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReplicationUsagesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReplicationUsagesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ReplicationUsagesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f625-101">Erweiterungsmethoden für ReplicationUsagesOperations.</span><span class="sxs-lookup"><span data-stu-id="8f625-101">Extension methods for ReplicationUsagesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt; List (this Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt; List(class Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IReplicationUsagesOperations, resourceGroupName As String, vaultName As String) As IEnumerable(Of ReplicationUsage)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions.List (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8f625-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8f625-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8f625-103">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="8f625-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="8f625-104">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="8f625-104">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f625-105">Dadurch wird die Replikation Verwendungen des Tresors.</span><span class="sxs-lookup"><span data-stu-id="8f625-105">Fetches the replication usages of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions.ListAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.ReplicationUsagesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IReplicationUsagesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8f625-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8f625-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8f625-107">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="8f625-107">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="8f625-108">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="8f625-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8f625-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8f625-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8f625-110">Dadurch wird die Replikation Verwendungen des Tresors.</span><span class="sxs-lookup"><span data-stu-id="8f625-110">Fetches the replication usages of the vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>