<Type Name="MetricFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter">
  <TypeSignature Language="C#" Value="public class MetricFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricFilter" />
  <TypeSignature Language="F#" Value="type MetricFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b5203-101">Die OData-Filter für Metriken verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b5203-101">The OData filters to be used for metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b5203-102">Initialisiert eine neue Instanz der MetricFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b5203-102">Initializes a new instance of the MetricFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricFilter (string category, Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter name = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string timeGrain = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter dimensions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string category, class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter name, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string timeGrain, class Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter dimensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As String, Optional name As MetricNameFilter = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional timeGrain As String = null, Optional dimensions As DimensionFilter = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter : string * Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter (category, name, startTime, endTime, timeGrain, dimensions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="dimensions" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" />
      </Parameters>
      <Docs>
        <param name="category"><span data-ttu-id="b5203-103">Gibt die Kategorie der Metriken gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b5203-103">Specifies the category of the metrics to be filtered.</span></span> <span data-ttu-id="b5203-104">Z. B. "CapacityUtilization".</span><span class="sxs-lookup"><span data-stu-id="b5203-104">E.g., "CapacityUtilization".</span></span> <span data-ttu-id="b5203-105">Gültige Werte sind diejenigen, die als das Feld "Kategorie" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="b5203-105">Valid values are the ones returned as the field "category" in the ListMetricDefinitions call.</span></span>
            <span data-ttu-id="b5203-106">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-106">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="name"><span data-ttu-id="b5203-107">Gibt den metrischen Namensfilter angeben des Namens der Metrik auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b5203-107">Specifies the metric name filter specifying the name of the metric to be filtered on.</span></span> <span data-ttu-id="b5203-108">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-108">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="startTime"><span data-ttu-id="b5203-109">Gibt die Startzeit des Zeitraums, der abgefragt werden.</span><span class="sxs-lookup"><span data-stu-id="b5203-109">Specifies the start time of the time range to be queried.</span></span> <span data-ttu-id="b5203-110">Nur 'Größer als oder gleich'-Operator wird für diese Eigenschaft unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-110">Only 'Greater Than Or Equal To' operator is supported for this property.</span></span></param>
        <param name="endTime"><span data-ttu-id="b5203-111">Gibt die Endzeit des Zeitraums, der abgefragt werden.</span><span class="sxs-lookup"><span data-stu-id="b5203-111">Specifies the end time of the time range to be queried.</span></span> <span data-ttu-id="b5203-112">Nur 'Less Than Or Equal To'-Operator wird für diese Eigenschaft unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-112">Only 'Less Than Or Equal To' operator is supported for this property.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="b5203-113">Gibt die Zeitgranularität der zurückzugebenden Metriken an.</span><span class="sxs-lookup"><span data-stu-id="b5203-113">Specifies the time granularity of the metrics to be returned.</span></span> <span data-ttu-id="b5203-114">Z. B. "P1D".</span><span class="sxs-lookup"><span data-stu-id="b5203-114">E.g., "P1D".</span></span> <span data-ttu-id="b5203-115">Gültige Werte sind diejenigen, die als das Feld "TimeGrain" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="b5203-115">Valid values are the ones returned as the field "timeGrain" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="b5203-116">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-116">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="dimensions"><span data-ttu-id="b5203-117">Gibt die Quelle (Dimension) der abzurufenden gefiltert werden.</span><span class="sxs-lookup"><span data-stu-id="b5203-117">Specifies the source(the dimension) of the metrics to be filtered.</span></span> <span data-ttu-id="b5203-118">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-118">Only 'Equality' operator is supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="b5203-119">Initialisiert eine neue Instanz der MetricFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b5203-119">Initializes a new instance of the MetricFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-120">Ruft ab oder legt gibt die Kategorie der Metriken gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b5203-120">Gets or sets specifies the category of the metrics to be filtered.</span></span>
            <span data-ttu-id="b5203-121">Z. B. "CapacityUtilization".</span><span class="sxs-lookup"><span data-stu-id="b5203-121">E.g., "CapacityUtilization".</span></span> <span data-ttu-id="b5203-122">Gültige Werte sind diejenigen, die als das Feld "Kategorie" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="b5203-122">Valid values are the ones returned as the field "category" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="b5203-123">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-123">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As DimensionFilter" />
      <MemberSignature Language="F#" Value="member this.Dimensions : Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-124">Gibt an der Quelle (Dimension) der abzurufenden gefiltert werden, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="b5203-124">Gets or sets specifies the source(the dimension) of the metrics to be filtered.</span></span> <span data-ttu-id="b5203-125">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-125">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-126">Ruft ab oder legt gibt die Endzeit des Zeitraums, der abgefragt werden.</span><span class="sxs-lookup"><span data-stu-id="b5203-126">Gets or sets specifies the end time of the time range to be queried.</span></span> <span data-ttu-id="b5203-127">Nur 'Less Than Or Equal To'-Operator wird für diese Eigenschaft unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-127">Only 'Less Than Or Equal To' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricNameFilter" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-128">Ruft ab oder legt gibt an, der metrikname Filter angeben des Namens der Metrik auf gefiltert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="b5203-128">Gets or sets specifies the metric name filter specifying the name of the metric to be filtered on.</span></span> <span data-ttu-id="b5203-129">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-129">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-130">Ruft ab oder legt gibt die Startzeit des Zeitraums, der abgefragt werden.</span><span class="sxs-lookup"><span data-stu-id="b5203-130">Gets or sets specifies the start time of the time range to be queried.</span></span> <span data-ttu-id="b5203-131">Nur 'Größer als oder gleich'-Operator wird für diese Eigenschaft unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-131">Only 'Greater Than Or Equal To' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5203-132">Ruft ab oder legt gibt die Zeitgranularität der zurückzugebenden Metriken an.</span><span class="sxs-lookup"><span data-stu-id="b5203-132">Gets or sets specifies the time granularity of the metrics to be returned.</span></span> <span data-ttu-id="b5203-133">Z. B. "P1D".</span><span class="sxs-lookup"><span data-stu-id="b5203-133">E.g., "P1D".</span></span> <span data-ttu-id="b5203-134">Gültige Werte sind diejenigen, die als das Feld "TimeGrain" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="b5203-134">Valid values are the ones returned as the field "timeGrain" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="b5203-135">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b5203-135">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b5203-136">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b5203-136">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5203-137">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b5203-137">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>