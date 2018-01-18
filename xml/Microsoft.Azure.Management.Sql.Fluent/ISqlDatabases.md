<Type Name="ISqlDatabases" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases">
  <TypeSignature Language="C#" Value="public interface ISqlDatabases : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlDatabases implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlDatabases&#xA;Implements IHasInner(Of IDatabasesOperations), IHasManager(Of ISqlManager), ISupportsBatchCreation(Of ISqlDatabase), ISupportsCreating(Of IBlank), ISupportsDeletingById, ISupportsDeletingByParent, ISupportsGettingById(Of ISqlDatabase)" />
  <TypeSignature Language="F#" Value="type ISqlDatabases = interface&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsGettingById&lt;ISqlDatabase&gt;&#xA;    interface ISupportsBatchCreation&lt;ISqlDatabase&gt;&#xA;    interface ISupportsDeletingByParent&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IHasInner&lt;IDatabasesOperations&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.Sql.Fluent.SqlDatabase.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="abfbf-101">Einstiegspunkt für einen SQL-datenbankverwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="abfbf-101">Entry point to SQL Database management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.GetBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (sqlServer As ISqlServer, name As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iSqlDatabases.GetBySqlServer (sqlServer, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlServer"><span data-ttu-id="abfbf-102">die Instanz von SQL Server.</span><span class="sxs-lookup"><span data-stu-id="abfbf-102">The instance of SQLServer.</span></span></param>
        <param name="name"><span data-ttu-id="abfbf-103">der Name der SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="abfbf-103">The name of SQLDatabase.</span></span></param>
        <summary>
            <span data-ttu-id="abfbf-104">Ruft die SQL-Datenbank basierend auf den SQL Server-Instanz und den Namen der SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="abfbf-104">Gets the SQLDatabase based on the SQLServer instance and SQLDatabase name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abfbf-105">Eine unveränderliche Darstellung der SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="abfbf-105">An immutable representation of the SQLDatabase.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetBySqlServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer (string resourceGroup, string sqlServerName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase GetBySqlServer(string resourceGroup, string sqlServerName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.GetBySqlServer(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBySqlServer (resourceGroup As String, sqlServerName As String, name As String) As ISqlDatabase" />
      <MemberSignature Language="F#" Value="abstract member GetBySqlServer : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase" Usage="iSqlDatabases.GetBySqlServer (resourceGroup, sqlServerName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup"><span data-ttu-id="abfbf-106">der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="abfbf-106">The name of resource group.</span></span></param>
        <param name="sqlServerName"><span data-ttu-id="abfbf-107">der Name der SQL Server.</span><span class="sxs-lookup"><span data-stu-id="abfbf-107">The name of SQLServer.</span></span></param>
        <param name="name"><span data-ttu-id="abfbf-108">der Name der SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="abfbf-108">The name of SQLDatabase.</span></span></param>
        <summary>
            <span data-ttu-id="abfbf-109">Ruft die SQL-Datenbank basierend auf der Name der Ressourcengruppe, SQL Server-Name und Name der SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="abfbf-109">Gets the SQLDatabase based on the resource group name, SQLServer name and SQLDatabase name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abfbf-110">Eine unveränderliche Darstellung der SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="abfbf-110">An immutable representation of the SQLDatabase.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer (Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer(class Microsoft.Azure.Management.Sql.Fluent.ISqlServer sqlServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.ListBySqlServer(Microsoft.Azure.Management.Sql.Fluent.ISqlServer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (sqlServer As ISqlServer) As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : Microsoft.Azure.Management.Sql.Fluent.ISqlServer -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iSqlDatabases.ListBySqlServer sqlServer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlServer" Type="Microsoft.Azure.Management.Sql.Fluent.ISqlServer" />
      </Parameters>
      <Docs>
        <param name="sqlServer"><span data-ttu-id="abfbf-111">die Instanz von SQL Server.</span><span class="sxs-lookup"><span data-stu-id="abfbf-111">The instance of SQLServer.</span></span></param>
        <summary>
            <span data-ttu-id="abfbf-112">Ruft die SQL-Datenbank basierend auf dem SQL Server ab.</span><span class="sxs-lookup"><span data-stu-id="abfbf-112">Gets the SQLDatabase based on the SQLServer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abfbf-113">Die Liste der SQLDatabases in einem SQLServer.</span><span class="sxs-lookup"><span data-stu-id="abfbf-113">The list of SQLDatabases in a SQLServer.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListBySqlServer">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer (string resourceGroupName, string sqlServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt; ListBySqlServer(string resourceGroupName, string sqlServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlDatabases.ListBySqlServer(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListBySqlServer (resourceGroupName As String, sqlServerName As String) As IReadOnlyList(Of ISqlDatabase)" />
      <MemberSignature Language="F#" Value="abstract member ListBySqlServer : string * string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;" Usage="iSqlDatabases.ListBySqlServer (resourceGroupName, sqlServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="sqlServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="abfbf-114">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</span><span class="sxs-lookup"><span data-stu-id="abfbf-114">The name of the resource group to list the resources from.</span></span></param>
        <param name="sqlServerName"><span data-ttu-id="abfbf-115">der Name der SQL Server.</span><span class="sxs-lookup"><span data-stu-id="abfbf-115">The name of SQLServer.</span></span></param>
        <summary>
            <span data-ttu-id="abfbf-116">Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe und SQLServer.</span><span class="sxs-lookup"><span data-stu-id="abfbf-116">Lists resources of the specified type in the specified resource group and SQLServer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="abfbf-117">Die Liste der SQLDatabases in einem SQLServer.</span><span class="sxs-lookup"><span data-stu-id="abfbf-117">The list of SQLDatabases in a SQLServer.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>