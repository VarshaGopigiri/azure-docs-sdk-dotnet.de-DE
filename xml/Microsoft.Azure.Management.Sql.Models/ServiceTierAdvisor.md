<Type Name="ServiceTierAdvisor" FullName="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor">
  <TypeSignature Language="C#" Value="public class ServiceTierAdvisor : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceTierAdvisor extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceTierAdvisor&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServiceTierAdvisor = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1ff7d-101">Stellt eine Dienstebenenratgeber dar.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-101">Represents a Service Tier Advisor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTierAdvisor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-102">Initialisiert eine neue Instanz der ServiceTierAdvisor-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-102">Initializes a new instance of the ServiceTierAdvisor class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceTierAdvisor (string id = null, string name = null, string type = null, Nullable&lt;DateTime&gt; observationPeriodStart = null, Nullable&lt;DateTime&gt; observationPeriodEnd = null, Nullable&lt;double&gt; activeTimeRatio = null, Nullable&lt;double&gt; minDtu = null, Nullable&lt;double&gt; avgDtu = null, Nullable&lt;double&gt; maxDtu = null, Nullable&lt;double&gt; maxSizeInGB = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt; serviceLevelObjectiveUsageMetrics = null, string currentServiceLevelObjective = null, Nullable&lt;Guid&gt; currentServiceLevelObjectiveId = null, string usageBasedRecommendationServiceLevelObjective = null, Nullable&lt;Guid&gt; usageBasedRecommendationServiceLevelObjectiveId = null, string databaseSizeBasedRecommendationServiceLevelObjective = null, Nullable&lt;Guid&gt; databaseSizeBasedRecommendationServiceLevelObjectiveId = null, string disasterPlanBasedRecommendationServiceLevelObjective = null, Nullable&lt;Guid&gt; disasterPlanBasedRecommendationServiceLevelObjectiveId = null, string overallRecommendationServiceLevelObjective = null, Nullable&lt;Guid&gt; overallRecommendationServiceLevelObjectiveId = null, double confidence = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodEnd, valuetype System.Nullable`1&lt;float64&gt; activeTimeRatio, valuetype System.Nullable`1&lt;float64&gt; minDtu, valuetype System.Nullable`1&lt;float64&gt; avgDtu, valuetype System.Nullable`1&lt;float64&gt; maxDtu, valuetype System.Nullable`1&lt;float64&gt; maxSizeInGB, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt; serviceLevelObjectiveUsageMetrics, string currentServiceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceLevelObjectiveId, string usageBasedRecommendationServiceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; usageBasedRecommendationServiceLevelObjectiveId, string databaseSizeBasedRecommendationServiceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; databaseSizeBasedRecommendationServiceLevelObjectiveId, string disasterPlanBasedRecommendationServiceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; disasterPlanBasedRecommendationServiceLevelObjectiveId, string overallRecommendationServiceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; overallRecommendationServiceLevelObjectiveId, float64 confidence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.#ctor(System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SloUsageMetric},System.String,System.Nullable{System.Guid},System.String,System.Nullable{System.Guid},System.String,System.Nullable{System.Guid},System.String,System.Nullable{System.Guid},System.String,System.Nullable{System.Guid},System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional observationPeriodStart As Nullable(Of DateTime) = null, Optional observationPeriodEnd As Nullable(Of DateTime) = null, Optional activeTimeRatio As Nullable(Of Double) = null, Optional minDtu As Nullable(Of Double) = null, Optional avgDtu As Nullable(Of Double) = null, Optional maxDtu As Nullable(Of Double) = null, Optional maxSizeInGB As Nullable(Of Double) = null, Optional serviceLevelObjectiveUsageMetrics As IList(Of SloUsageMetric) = null, Optional currentServiceLevelObjective As String = null, Optional currentServiceLevelObjectiveId As Nullable(Of Guid) = null, Optional usageBasedRecommendationServiceLevelObjective As String = null, Optional usageBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid) = null, Optional databaseSizeBasedRecommendationServiceLevelObjective As String = null, Optional databaseSizeBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid) = null, Optional disasterPlanBasedRecommendationServiceLevelObjective As String = null, Optional disasterPlanBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid) = null, Optional overallRecommendationServiceLevelObjective As String = null, Optional overallRecommendationServiceLevelObjectiveId As Nullable(Of Guid) = null, Optional confidence As Double = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor : string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt; * string * Nullable&lt;Guid&gt; * string * Nullable&lt;Guid&gt; * string * Nullable&lt;Guid&gt; * string * Nullable&lt;Guid&gt; * string * Nullable&lt;Guid&gt; * double -&gt; Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor" Usage="new Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor (id, name, type, observationPeriodStart, observationPeriodEnd, activeTimeRatio, minDtu, avgDtu, maxDtu, maxSizeInGB, serviceLevelObjectiveUsageMetrics, currentServiceLevelObjective, currentServiceLevelObjectiveId, usageBasedRecommendationServiceLevelObjective, usageBasedRecommendationServiceLevelObjectiveId, databaseSizeBasedRecommendationServiceLevelObjective, databaseSizeBasedRecommendationServiceLevelObjectiveId, disasterPlanBasedRecommendationServiceLevelObjective, disasterPlanBasedRecommendationServiceLevelObjectiveId, overallRecommendationServiceLevelObjective, overallRecommendationServiceLevelObjectiveId, confidence)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="observationPeriodStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="observationPeriodEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="activeTimeRatio" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="minDtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="avgDtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxDtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxSizeInGB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="serviceLevelObjectiveUsageMetrics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt;" />
        <Parameter Name="currentServiceLevelObjective" Type="System.String" />
        <Parameter Name="currentServiceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="usageBasedRecommendationServiceLevelObjective" Type="System.String" />
        <Parameter Name="usageBasedRecommendationServiceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseSizeBasedRecommendationServiceLevelObjective" Type="System.String" />
        <Parameter Name="databaseSizeBasedRecommendationServiceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="disasterPlanBasedRecommendationServiceLevelObjective" Type="System.String" />
        <Parameter Name="disasterPlanBasedRecommendationServiceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="overallRecommendationServiceLevelObjective" Type="System.String" />
        <Parameter Name="overallRecommendationServiceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="confidence" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1ff7d-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="1ff7d-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="1ff7d-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="1ff7d-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-105">Resource type.</span></span></param>
        <param name="observationPeriodStart"><span data-ttu-id="1ff7d-106">Beobachtung beginnt (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1ff7d-106">The observation period start (ISO8601 format).</span></span></param>
        <param name="observationPeriodEnd"><span data-ttu-id="1ff7d-107">Beobachtung beginnt (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1ff7d-107">The observation period start (ISO8601 format).</span></span></param>
        <param name="activeTimeRatio"><span data-ttu-id="1ff7d-108">Die ActiveTimeRatio für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-108">The activeTimeRatio for service tier advisor.</span></span></param>
        <param name="minDtu"><span data-ttu-id="1ff7d-109">Ruft ab oder legt MinDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-109">Gets or sets minDtu for service tier advisor.</span></span></param>
        <param name="avgDtu"><span data-ttu-id="1ff7d-110">Ruft ab oder legt AvgDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-110">Gets or sets avgDtu for service tier advisor.</span></span></param>
        <param name="maxDtu"><span data-ttu-id="1ff7d-111">Ruft ab oder legt MaxDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-111">Gets or sets maxDtu for service tier advisor.</span></span></param>
        <param name="maxSizeInGB"><span data-ttu-id="1ff7d-112">Ruft ab oder legt MaxSizeInGB für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-112">Gets or sets maxSizeInGB for service tier advisor.</span></span></param>
        <param name="serviceLevelObjectiveUsageMetrics"><span data-ttu-id="1ff7d-113">Ruft ab oder legt die ServiceLevelObjectiveUsageMetrics für den dienstebenenratgeber fest.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-113">Gets or sets serviceLevelObjectiveUsageMetrics for the service tier advisor.</span></span></param>
        <param name="currentServiceLevelObjective"><span data-ttu-id="1ff7d-114">Ruft ab oder legt CurrentServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-114">Gets or sets currentServiceLevelObjective for service tier advisor.</span></span></param>
        <param name="currentServiceLevelObjectiveId"><span data-ttu-id="1ff7d-115">Ruft ab oder legt CurrentServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-115">Gets or sets currentServiceLevelObjectiveId for service tier advisor.</span></span></param>
        <param name="usageBasedRecommendationServiceLevelObjective"><span data-ttu-id="1ff7d-116">Ruft ab oder legt UsageBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-116">Gets or sets usageBasedRecommendationServiceLevelObjective for service tier advisor.</span></span></param>
        <param name="usageBasedRecommendationServiceLevelObjectiveId"><span data-ttu-id="1ff7d-117">Ruft ab oder legt UsageBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-117">Gets or sets usageBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span></param>
        <param name="databaseSizeBasedRecommendationServiceLevelObjective"><span data-ttu-id="1ff7d-118">Ruft ab oder legt DatabaseSizeBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-118">Gets or sets databaseSizeBasedRecommendationServiceLevelObjective for service tier advisor.</span></span></param>
        <param name="databaseSizeBasedRecommendationServiceLevelObjectiveId"><span data-ttu-id="1ff7d-119">Ruft ab oder legt DatabaseSizeBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-119">Gets or sets databaseSizeBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span></param>
        <param name="disasterPlanBasedRecommendationServiceLevelObjective"><span data-ttu-id="1ff7d-120">Ruft ab oder legt DisasterPlanBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-120">Gets or sets disasterPlanBasedRecommendationServiceLevelObjective for service tier advisor.</span></span></param>
        <param name="disasterPlanBasedRecommendationServiceLevelObjectiveId"><span data-ttu-id="1ff7d-121">Ruft ab oder legt DisasterPlanBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-121">Gets or sets disasterPlanBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span></param>
        <param name="overallRecommendationServiceLevelObjective"><span data-ttu-id="1ff7d-122">Ruft ab oder legt OverallRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-122">Gets or sets overallRecommendationServiceLevelObjective for service tier advisor.</span></span></param>
        <param name="overallRecommendationServiceLevelObjectiveId"><span data-ttu-id="1ff7d-123">Ruft ab oder legt OverallRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-123">Gets or sets overallRecommendationServiceLevelObjectiveId for service tier advisor.</span></span></param>
        <param name="confidence"><span data-ttu-id="1ff7d-124">Ruft ab, oder legt die Vertrauen für dienstebenenratgeber fest.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-124">Gets or sets confidence for service tier advisor.</span></span></param>
        <summary>
            <span data-ttu-id="1ff7d-125">Initialisiert eine neue Instanz der ServiceTierAdvisor-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-125">Initializes a new instance of the ServiceTierAdvisor class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveTimeRatio">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ActiveTimeRatio { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ActiveTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ActiveTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveTimeRatio As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ActiveTimeRatio : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ActiveTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeTimeRatio")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-126">Ruft die ActiveTimeRatio für dienstebenenratgeber ab.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-126">Gets the activeTimeRatio for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AvgDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AvgDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.AvgDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvgDtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AvgDtu : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.AvgDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.avgDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-127">Ruft ab oder legt AvgDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-127">Gets or sets avgDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Confidence">
      <MemberSignature Language="C#" Value="public double Confidence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Confidence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.Confidence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Confidence As Double" />
      <MemberSignature Language="F#" Value="member this.Confidence : double" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.Confidence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.confidence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-128">Ruft ab, oder legt die Vertrauen für dienstebenenratgeber fest.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-128">Gets or sets confidence for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string CurrentServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.CurrentServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.CurrentServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-129">Ruft ab oder legt CurrentServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-129">Gets or sets currentServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.CurrentServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceLevelObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.CurrentServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-130">Ruft ab oder legt CurrentServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-130">Gets or sets currentServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseSizeBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string DatabaseSizeBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseSizeBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseSizeBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseSizeBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseSizeBasedRecommendationServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-131">Ruft ab oder legt DatabaseSizeBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-131">Gets or sets databaseSizeBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseSizeBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DatabaseSizeBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseSizeBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DatabaseSizeBasedRecommendationServiceLevelObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DatabaseSizeBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseSizeBasedRecommendationServiceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-132">Ruft ab oder legt DatabaseSizeBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-132">Gets or sets databaseSizeBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisasterPlanBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string DisasterPlanBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisasterPlanBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisasterPlanBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.DisasterPlanBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disasterPlanBasedRecommendationServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-133">Ruft ab oder legt DisasterPlanBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-133">Gets or sets disasterPlanBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisasterPlanBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DisasterPlanBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisasterPlanBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DisasterPlanBasedRecommendationServiceLevelObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.DisasterPlanBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.disasterPlanBasedRecommendationServiceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-134">Ruft ab oder legt DisasterPlanBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-134">Gets or sets disasterPlanBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MaxDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxDtu : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MaxDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-135">Ruft ab oder legt MaxDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-135">Gets or sets maxDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxSizeInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MaxSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSizeInGB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInGB : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MaxSizeInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-136">Ruft ab oder legt MaxSizeInGB für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-136">Gets or sets maxSizeInGB for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MinDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinDtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinDtu : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.MinDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-137">Ruft ab oder legt MinDtu für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-137">Gets or sets minDtu for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ObservationPeriodEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-138">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1ff7d-138">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ObservationPeriodStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-139">Ruft die Beobachtung zeitraumstarts (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="1ff7d-139">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverallRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string OverallRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OverallRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.OverallRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverallRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.OverallRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.OverallRecommendationServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overallRecommendationServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-140">Ruft ab oder legt OverallRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-140">Gets or sets overallRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverallRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; OverallRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; OverallRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.OverallRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverallRecommendationServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.OverallRecommendationServiceLevelObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.OverallRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overallRecommendationServiceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-141">Ruft ab oder legt OverallRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-141">Gets or sets overallRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveUsageMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt; ServiceLevelObjectiveUsageMetrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt; ServiceLevelObjectiveUsageMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ServiceLevelObjectiveUsageMetrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjectiveUsageMetrics As IList(Of SloUsageMetric)" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveUsageMetrics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.ServiceLevelObjectiveUsageMetrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjectiveUsageMetrics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SloUsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-142">Ruft ab oder legt die ServiceLevelObjectiveUsageMetrics für den dienstebenenratgeber fest.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-142">Gets or sets serviceLevelObjectiveUsageMetrics for the service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageBasedRecommendationServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string UsageBasedRecommendationServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageBasedRecommendationServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.UsageBasedRecommendationServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageBasedRecommendationServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-143">Ruft ab oder legt UsageBasedRecommendationServiceLevelObjective für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-143">Gets or sets usageBasedRecommendationServiceLevelObjective for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageBasedRecommendationServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; UsageBasedRecommendationServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageBasedRecommendationServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.UsageBasedRecommendationServiceLevelObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor.UsageBasedRecommendationServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageBasedRecommendationServiceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ff7d-144">Ruft ab oder legt UsageBasedRecommendationServiceLevelObjectiveId für dienstebenenratgeber.</span><span class="sxs-lookup"><span data-stu-id="1ff7d-144">Gets or sets usageBasedRecommendationServiceLevelObjectiveId for service tier advisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>