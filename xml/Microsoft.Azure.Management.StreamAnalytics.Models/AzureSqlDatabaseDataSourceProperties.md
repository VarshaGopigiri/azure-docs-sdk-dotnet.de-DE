<Type Name="AzureSqlDatabaseDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties">
  <TypeSignature Language="C#" Value="public class AzureSqlDatabaseDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlDatabaseDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlDatabaseDataSourceProperties" />
  <TypeSignature Language="F#" Value="type AzureSqlDatabaseDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="57315-101">Die Eigenschaften, die mit einer Azure SQL-Datenbank-Datenquelle zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="57315-101">The properties that are associated with an Azure SQL database data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlDatabaseDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57315-102">Initialisiert eine neue Instanz der AzureSqlDatabaseDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="57315-102">Initializes a new instance of the AzureSqlDatabaseDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlDatabaseDataSourceProperties (string server = null, string database = null, string user = null, string password = null, string table = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string database, string user, string password, string table) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional server As String = null, Optional database As String = null, Optional user As String = null, Optional password As String = null, Optional table As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties (server, database, user, password, table)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="user" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="server"><span data-ttu-id="57315-103">Der Name des SQL Servers mit der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-103">The name of the SQL server containing the Azure SQL database.</span></span> <span data-ttu-id="57315-104">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="database"><span data-ttu-id="57315-105">Der Name der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-105">The name of the Azure SQL database.</span></span> <span data-ttu-id="57315-106">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="user"><span data-ttu-id="57315-107">Der Benutzername, der für die Verbindung zur Azure SQL-Datenbank verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="57315-107">The user name that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="57315-108">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="password"><span data-ttu-id="57315-109">Das Kennwort, das für die Verbindung zur Azure SQL-Datenbank verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="57315-109">The password that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="57315-110">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-110">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="table"><span data-ttu-id="57315-111">Der Name der Tabelle in der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-111">The name of the table in the Azure SQL database.</span></span> <span data-ttu-id="57315-112">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="57315-113">Initialisiert eine neue Instanz der AzureSqlDatabaseDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="57315-113">Initializes a new instance of the AzureSqlDatabaseDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="database")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57315-114">Ruft ab oder legt den Namen der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-114">Gets or sets the name of the Azure SQL database.</span></span> <span data-ttu-id="57315-115">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-115">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57315-116">Ruft ab oder legt das Kennwort fest, das für die Verbindung zur Azure SQL-Datenbank verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="57315-116">Gets or sets the password that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="57315-117">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-117">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Server" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="server")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57315-118">Ruft ab oder legt den Namen des SQL Servers mit der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-118">Gets or sets the name of the SQL server containing the Azure SQL database.</span></span> <span data-ttu-id="57315-119">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-119">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Table" />
      <MemberSignature Language="VB.NET" Value="Public Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57315-120">Ruft ab oder legt den Namen der Tabelle in der Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="57315-120">Gets or sets the name of the table in the Azure SQL database.</span></span>
            <span data-ttu-id="57315-121">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-121">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="User">
      <MemberSignature Language="C#" Value="public string User { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string User" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.User" />
      <MemberSignature Language="VB.NET" Value="Public Property User As String" />
      <MemberSignature Language="F#" Value="member this.User : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureSqlDatabaseDataSourceProperties.User" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="user")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57315-122">Ruft ab oder legt den Benutzernamen, der für die Verbindung zur Azure SQL-Datenbank verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="57315-122">Gets or sets the user name that will be used to connect to the Azure SQL database.</span></span> <span data-ttu-id="57315-123">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="57315-123">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>