<Type Name="ISqlManagementClient" FullName="Microsoft.Azure.Management.Sql.ISqlManagementClient">
  <TypeSignature Language="C#" Value="public interface ISqlManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ISqlManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ISqlManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2023e-101">Azure SQL-datenbankverwaltungs-API bietet eine Reihe von Webdiensten, die Interaktion mit Azure SQL-Datenbank-Dienste für die Verwaltung Ihrer Rest.</span><span class="sxs-lookup"><span data-stu-id="2023e-101">The Azure SQL Database management API provides a RESTful set of web services that interact with Azure SQL Database services to manage your databases.</span></span> <span data-ttu-id="2023e-102">Der API können Sie zum Erstellen, abrufen, aktualisieren und Löschen von Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="2023e-102">The API enables you to create, retrieve, update, and delete databases.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-103">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="2023e-103">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupLongTermRetentionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations BackupLongTermRetentionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations BackupLongTermRetentionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.BackupLongTermRetentionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupLongTermRetentionPolicies As IBackupLongTermRetentionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupLongTermRetentionPolicies : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.BackupLongTermRetentionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-104">Ruft die IBackupLongTermRetentionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-104">Gets the IBackupLongTermRetentionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupLongTermRetentionVaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations BackupLongTermRetentionVaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations BackupLongTermRetentionVaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.BackupLongTermRetentionVaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupLongTermRetentionVaults As IBackupLongTermRetentionVaultsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupLongTermRetentionVaults : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.BackupLongTermRetentionVaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-105">Ruft die IBackupLongTermRetentionVaultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-105">Gets the IBackupLongTermRetentionVaultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-106">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="2023e-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ICapabilitiesOperations Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ICapabilitiesOperations Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As ICapabilitiesOperations" />
      <MemberSignature Language="F#" Value="member this.Capabilities : Microsoft.Azure.Management.Sql.ICapabilitiesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ICapabilitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-107">Ruft die ICapabilitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-107">Gets the ICapabilitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-108">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="2023e-108">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseBlobAuditingPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations DatabaseBlobAuditingPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations DatabaseBlobAuditingPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseBlobAuditingPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseBlobAuditingPolicies As IDatabaseBlobAuditingPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseBlobAuditingPolicies : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseBlobAuditingPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-109">Ruft die IDatabaseBlobAuditingPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-109">Gets the IDatabaseBlobAuditingPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseOperations DatabaseOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseOperations DatabaseOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseOperations As IDatabaseOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseOperations : Microsoft.Azure.Management.Sql.IDatabaseOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-110">Ruft die IDatabaseOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-110">Gets the IDatabaseOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabasesOperations Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabasesOperations Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.Databases : Microsoft.Azure.Management.Sql.IDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-111">Ruft die IDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-111">Gets the IDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseThreatDetectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations DatabaseThreatDetectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations DatabaseThreatDetectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseThreatDetectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseThreatDetectionPolicies As IDatabaseThreatDetectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseThreatDetectionPolicies : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseThreatDetectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-112">Ruft die IDatabaseThreatDetectionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-112">Gets the IDatabaseThreatDetectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations DatabaseUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations DatabaseUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsages As IDatabaseUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsages : Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DatabaseUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-113">Ruft die IDatabaseUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-113">Gets the IDatabaseUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations DataMaskingPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations DataMaskingPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DataMaskingPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingPolicies As IDataMaskingPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DataMaskingPolicies : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DataMaskingPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-114">Ruft die IDataMaskingPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-114">Gets the IDataMaskingPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations DataMaskingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations DataMaskingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DataMaskingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingRules As IDataMaskingRulesOperations" />
      <MemberSignature Language="F#" Value="member this.DataMaskingRules : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DataMaskingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-115">Ruft die IDataMaskingRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-115">Gets the IDataMaskingRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-116">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="2023e-116">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations ElasticPoolActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations ElasticPoolActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPoolActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolActivities As IElasticPoolActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolActivities : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPoolActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-117">Ruft die IElasticPoolActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-117">Gets the IElasticPoolActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolDatabaseActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations ElasticPoolDatabaseActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations ElasticPoolDatabaseActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPoolDatabaseActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolDatabaseActivities As IElasticPoolDatabaseActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolDatabaseActivities : Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPoolDatabaseActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-118">Ruft die IElasticPoolDatabaseActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-118">Gets the IElasticPoolDatabaseActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolsOperations ElasticPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolsOperations ElasticPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPools As IElasticPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPools : Microsoft.Azure.Management.Sql.IElasticPoolsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ElasticPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-119">Ruft die IElasticPoolsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-119">Gets the IElasticPoolsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionProtectors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations EncryptionProtectors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations EncryptionProtectors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.EncryptionProtectors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionProtectors As IEncryptionProtectorsOperations" />
      <MemberSignature Language="F#" Value="member this.EncryptionProtectors : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.EncryptionProtectors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-120">Ruft die IEncryptionProtectorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-120">Gets the IEncryptionProtectorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IFailoverGroupsOperations FailoverGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations FailoverGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.FailoverGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroups As IFailoverGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.FailoverGroups : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.FailoverGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IFailoverGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-121">Ruft die IFailoverGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-121">Gets the IFailoverGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IFirewallRulesOperations FirewallRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IFirewallRulesOperations FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirewallRules As IFirewallRulesOperations" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : Microsoft.Azure.Management.Sql.IFirewallRulesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IFirewallRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-122">Ruft die IFirewallRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-122">Gets the IFirewallRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-123">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="2023e-123">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="2023e-124">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="2023e-124">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoBackupPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations GeoBackupPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations GeoBackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.GeoBackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoBackupPolicies As IGeoBackupPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.GeoBackupPolicies : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.GeoBackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-125">Ruft die IGeoBackupPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-125">Gets the IGeoBackupPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-126">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="2023e-126">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="2023e-127">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="2023e-127">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.Sql.IOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-128">Ruft die IOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-128">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedElasticPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations RecommendedElasticPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations RecommendedElasticPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.RecommendedElasticPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedElasticPools As IRecommendedElasticPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.RecommendedElasticPools : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.RecommendedElasticPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-129">Ruft die IRecommendedElasticPoolsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-129">Gets the IRecommendedElasticPoolsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverableDatabases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations RecoverableDatabases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations RecoverableDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.RecoverableDatabases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoverableDatabases As IRecoverableDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.RecoverableDatabases : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.RecoverableDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-130">Ruft die IRecoverableDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-130">Gets the IRecoverableDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationLinks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IReplicationLinksOperations ReplicationLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IReplicationLinksOperations ReplicationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ReplicationLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationLinks As IReplicationLinksOperations" />
      <MemberSignature Language="F#" Value="member this.ReplicationLinks : Microsoft.Azure.Management.Sql.IReplicationLinksOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ReplicationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IReplicationLinksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-131">Ruft die IReplicationLinksOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-131">Gets the IReplicationLinksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorableDroppedDatabases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations RestorableDroppedDatabases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations RestorableDroppedDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.RestorableDroppedDatabases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorableDroppedDatabases As IRestorableDroppedDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.RestorableDroppedDatabases : Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.RestorableDroppedDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-132">Ruft die IRestorableDroppedDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-132">Gets the IRestorableDroppedDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRestorePointsOperations RestorePoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRestorePointsOperations RestorePoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.RestorePoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePoints As IRestorePointsOperations" />
      <MemberSignature Language="F#" Value="member this.RestorePoints : Microsoft.Azure.Management.Sql.IRestorePointsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.RestorePoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRestorePointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-133">Ruft die IRestorePointsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-133">Gets the IRestorePointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-134">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="2023e-134">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerAzureADAdministrators">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations ServerAzureADAdministrators { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations ServerAzureADAdministrators" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerAzureADAdministrators" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerAzureADAdministrators As IServerAzureADAdministratorsOperations" />
      <MemberSignature Language="F#" Value="member this.ServerAzureADAdministrators : Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerAzureADAdministrators" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-135">Ruft die IServerAzureADAdministratorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-135">Gets the IServerAzureADAdministratorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCommunicationLinks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations ServerCommunicationLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations ServerCommunicationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerCommunicationLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerCommunicationLinks As IServerCommunicationLinksOperations" />
      <MemberSignature Language="F#" Value="member this.ServerCommunicationLinks : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerCommunicationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-136">Ruft die IServerCommunicationLinksOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-136">Gets the IServerCommunicationLinksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerConnectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations ServerConnectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations ServerConnectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerConnectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerConnectionPolicies As IServerConnectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerConnectionPolicies : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerConnectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-137">Ruft die IServerConnectionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-137">Gets the IServerConnectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerDnsAliases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations ServerDnsAliases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations ServerDnsAliases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerDnsAliases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerDnsAliases As IServerDnsAliasesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerDnsAliases : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerDnsAliases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-138">Ruft die IServerDnsAliasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-138">Gets the IServerDnsAliasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerKeysOperations ServerKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerKeysOperations ServerKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerKeys As IServerKeysOperations" />
      <MemberSignature Language="F#" Value="member this.ServerKeys : Microsoft.Azure.Management.Sql.IServerKeysOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerKeysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-139">Ruft die IServerKeysOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-139">Gets the IServerKeysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Servers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServersOperations Servers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServersOperations Servers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.Servers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Servers As IServersOperations" />
      <MemberSignature Language="F#" Value="member this.Servers : Microsoft.Azure.Management.Sql.IServersOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.Servers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-140">Ruft die IServersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-140">Gets the IServersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerUsagesOperations ServerUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerUsagesOperations ServerUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerUsages As IServerUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerUsages : Microsoft.Azure.Management.Sql.IServerUsagesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServerUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-141">Ruft die IServerUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-141">Gets the IServerUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceObjectives">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServiceObjectivesOperations ServiceObjectives { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServiceObjectivesOperations ServiceObjectives" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServiceObjectives" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceObjectives As IServiceObjectivesOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceObjectives : Microsoft.Azure.Management.Sql.IServiceObjectivesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServiceObjectives" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServiceObjectivesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-142">Ruft die IServiceObjectivesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-142">Gets the IServiceObjectivesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IServiceTierAdvisorsOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-143">Ruft die IServiceTierAdvisorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-143">Gets the IServiceTierAdvisorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-144">Die Abonnement-ID, die ein Azure-Abonnement identifiziert.</span><span class="sxs-lookup"><span data-stu-id="2023e-144">The subscription ID that identifies an Azure subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations SubscriptionUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations SubscriptionUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SubscriptionUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionUsages As ISubscriptionUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.SubscriptionUsages : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SubscriptionUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-145">Ruft die ISubscriptionUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-145">Gets the ISubscriptionUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncAgents">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncAgentsOperations SyncAgents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncAgentsOperations SyncAgents" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncAgents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncAgents As ISyncAgentsOperations" />
      <MemberSignature Language="F#" Value="member this.SyncAgents : Microsoft.Azure.Management.Sql.ISyncAgentsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncAgents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncAgentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-146">Ruft die ISyncAgentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-146">Gets the ISyncAgentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncGroupsOperations SyncGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncGroupsOperations SyncGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncGroups As ISyncGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.SyncGroups : Microsoft.Azure.Management.Sql.ISyncGroupsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-147">Ruft die ISyncGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-147">Gets the ISyncGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncMembers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncMembersOperations SyncMembers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncMembersOperations SyncMembers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncMembers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncMembers As ISyncMembersOperations" />
      <MemberSignature Language="F#" Value="member this.SyncMembers : Microsoft.Azure.Management.Sql.ISyncMembersOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.SyncMembers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncMembersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-148">Ruft die ISyncMembersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-148">Gets the ISyncMembersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryptionActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations TransparentDataEncryptionActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations TransparentDataEncryptionActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.TransparentDataEncryptionActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryptionActivities As ITransparentDataEncryptionActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryptionActivities : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.TransparentDataEncryptionActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-149">Ruft die ITransparentDataEncryptionActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-149">Gets the ITransparentDataEncryptionActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations TransparentDataEncryptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations TransparentDataEncryptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.TransparentDataEncryptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryptions As ITransparentDataEncryptionsOperations" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryptions : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.TransparentDataEncryptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-150">Ruft die ITransparentDataEncryptionsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-150">Gets the ITransparentDataEncryptionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations VirtualNetworkRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations VirtualNetworkRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.ISqlManagementClient.VirtualNetworkRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkRules As IVirtualNetworkRulesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkRules : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" Usage="Microsoft.Azure.Management.Sql.ISqlManagementClient.VirtualNetworkRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2023e-151">Ruft die IVirtualNetworkRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="2023e-151">Gets the IVirtualNetworkRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>