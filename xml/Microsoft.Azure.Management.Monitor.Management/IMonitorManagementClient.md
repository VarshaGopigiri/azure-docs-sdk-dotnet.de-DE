<Type Name="IMonitorManagementClient" FullName="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient">
  <TypeSignature Language="C#" Value="public interface IMonitorManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMonitorManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMonitorManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IMonitorManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="38e0e-101">Monitor-Verwaltungsclient</span><span class="sxs-lookup"><span data-stu-id="38e0e-101">Monitor Management Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-102">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="38e0e-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations ActionGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations ActionGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.ActionGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActionGroups As IActionGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.ActionGroups : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.ActionGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-103">Ruft die IActionGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-103">Gets the IActionGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityLogAlerts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations ActivityLogAlerts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations ActivityLogAlerts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.ActivityLogAlerts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityLogAlerts As IActivityLogAlertsOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityLogAlerts : Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.ActivityLogAlerts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IActivityLogAlertsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-104">Ruft die IActivityLogAlertsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-104">Gets the IActivityLogAlertsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertRuleIncidents">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations AlertRuleIncidents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations AlertRuleIncidents" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AlertRuleIncidents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlertRuleIncidents As IAlertRuleIncidentsOperations" />
      <MemberSignature Language="F#" Value="member this.AlertRuleIncidents : Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AlertRuleIncidents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-105">Ruft die IAlertRuleIncidentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-105">Gets the IAlertRuleIncidentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IAlertRulesOperations AlertRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IAlertRulesOperations AlertRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AlertRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlertRules As IAlertRulesOperations" />
      <MemberSignature Language="F#" Value="member this.AlertRules : Microsoft.Azure.Management.Monitor.Management.IAlertRulesOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AlertRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IAlertRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-106">Ruft die IAlertRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-106">Gets the IAlertRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoscaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations AutoscaleSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations AutoscaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AutoscaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoscaleSettings As IAutoscaleSettingsOperations" />
      <MemberSignature Language="F#" Value="member this.AutoscaleSettings : Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.AutoscaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IAutoscaleSettingsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-107">Ruft die IAutoscaleSettingsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-107">Gets the IAutoscaleSettingsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-108">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="38e0e-108">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-109">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="38e0e-109">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-110">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="38e0e-110">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations DiagnosticSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations DiagnosticSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DiagnosticSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticSettings As IDiagnosticSettingsOperations" />
      <MemberSignature Language="F#" Value="member this.DiagnosticSettings : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DiagnosticSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-111">Ruft die IDiagnosticSettingsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-111">Gets the IDiagnosticSettingsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticSettingsCategory">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations DiagnosticSettingsCategory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations DiagnosticSettingsCategory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DiagnosticSettingsCategory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticSettingsCategory As IDiagnosticSettingsCategoryOperations" />
      <MemberSignature Language="F#" Value="member this.DiagnosticSettingsCategory : Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.DiagnosticSettingsCategory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-112">Ruft die IDiagnosticSettingsCategoryOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-112">Gets the IDiagnosticSettingsCategoryOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-113">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="38e0e-113">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="38e0e-114">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="38e0e-114">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogProfiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations LogProfiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations LogProfiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.LogProfiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogProfiles As ILogProfilesOperations" />
      <MemberSignature Language="F#" Value="member this.LogProfiles : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.LogProfiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-115">Ruft die ILogProfilesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-115">Gets the ILogProfilesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-116">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="38e0e-116">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="38e0e-117">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="38e0e-117">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.Monitor.Management.IOperations" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-118">Ruft die IOperations ab.</span><span class="sxs-lookup"><span data-stu-id="38e0e-118">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-119">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="38e0e-119">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.IMonitorManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38e0e-120">Der Azure-Abonnement-Id.</span><span class="sxs-lookup"><span data-stu-id="38e0e-120">The Azure subscription Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>