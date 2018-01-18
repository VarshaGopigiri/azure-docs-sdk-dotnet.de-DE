<Type Name="SecurityPINsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SecurityPINsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SecurityPINsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SecurityPINsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SecurityPINsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f69dd-101">Erweiterungsmethoden für SecurityPINsOperations.</span><span class="sxs-lookup"><span data-stu-id="f69dd-101">Extension methods for SecurityPINsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation Get (this Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations operations, string vaultName, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation Get(class Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations operations, string vaultName, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISecurityPINsOperations, vaultName As String, resourceGroupName As String) As TokenInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions.Get (operations, vaultName, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f69dd-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f69dd-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f69dd-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="f69dd-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f69dd-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f69dd-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f69dd-105">Abrufen der Sicherheits-PIN an.</span><span class="sxs-lookup"><span data-stu-id="f69dd-105">Get the security PIN.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations operations, string vaultName, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations operations, string vaultName, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.SecurityPINsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.ISecurityPINsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f69dd-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f69dd-106">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="f69dd-107">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="f69dd-107">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f69dd-108">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f69dd-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f69dd-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f69dd-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f69dd-110">Abrufen der Sicherheits-PIN an.</span><span class="sxs-lookup"><span data-stu-id="f69dd-110">Get the security PIN.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>