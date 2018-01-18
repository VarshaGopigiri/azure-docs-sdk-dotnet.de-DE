<Type Name="IFirewallRules" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules">
  <TypeSignature Language="C#" Value="public interface IFirewallRules" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFirewallRules" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFirewallRules" />
  <TypeSignature Language="F#" Value="type IFirewallRules = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04503-101">Der Einstiegspunkt für FirewallRules auf dem SQL Server zugreifen.</span><span class="sxs-lookup"><span data-stu-id="04503-101">Entry point to access FirewallRules from the SQL Server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Define">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank Define (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank Define(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Define(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Define (firewallRuleName As String) As IBlank" />
      <MemberSignature Language="F#" Value="abstract member Define : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank" Usage="iFirewallRules.Define firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IBlank</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName"><span data-ttu-id="04503-102">Der Name der Firewallregel erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="04503-102">Name of the firewall rule to be created.</span></span></param>
        <summary>
            <span data-ttu-id="04503-103">Erstellt eine neue Firewallregel in SQL Server.</span><span class="sxs-lookup"><span data-stu-id="04503-103">Creates a new firewall rule in SQL Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="04503-104">Gibt eine Stufe aus, um die Argumente der Firewallregel angeben.</span><span class="sxs-lookup"><span data-stu-id="04503-104">Returns a stage to specify arguments of the firewall rule.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Delete(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (firewallRuleName As String)" />
      <MemberSignature Language="F#" Value="abstract member Delete : string -&gt; unit" Usage="iFirewallRules.Delete firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName"><span data-ttu-id="04503-105">Der Name der Firewallregel löschen.</span><span class="sxs-lookup"><span data-stu-id="04503-105">Name of the firewall rule to delete.</span></span></param>
        <summary>
            <span data-ttu-id="04503-106">Löschen Sie die angegebenen Firewallregel auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="04503-106">Delete specified firewall rule in the server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.DeleteAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iFirewallRules.DeleteAsync (firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName"><span data-ttu-id="04503-107">Der Name der Firewallregel löschen.</span><span class="sxs-lookup"><span data-stu-id="04503-107">Name of the firewall rule to delete.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="04503-108">Löschen Sie die angegebenen Firewallregel auf dem Server.</span><span class="sxs-lookup"><span data-stu-id="04503-108">Delete specified firewall rule in the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="04503-109">Observable-Objekt für den Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="04503-109">Observable for the delete operation.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule Get (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule Get(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.Get(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (firewallRuleName As String) As ISqlFirewallRule" />
      <MemberSignature Language="F#" Value="abstract member Get : string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule" Usage="iFirewallRules.Get firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName"><span data-ttu-id="04503-110">Der Name der Firewallregel abgerufen.</span><span class="sxs-lookup"><span data-stu-id="04503-110">Name of the firewall rule to get.</span></span></param>
        <summary>
            <span data-ttu-id="04503-111">Ruft eine bestimmte Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="04503-111">Gets a particular firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="04503-112">Gibt die SqlFirewall-Regel mit SQL Server zurück.</span><span class="sxs-lookup"><span data-stu-id="04503-112">Returns the SqlFirewall rule with in the SQL Server.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.FirewallRules.IFirewallRules.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IReadOnlyList(Of ISqlFirewallRule)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;" Usage="iFirewallRules.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04503-113">Gibt die Firewallregeln für den Server zurück.</span><span class="sxs-lookup"><span data-stu-id="04503-113">Returns all the firewall rules for the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="04503-114">Liste von Firewallregeln für den Server.</span><span class="sxs-lookup"><span data-stu-id="04503-114">List of firewall rules for the server.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>