<Type Name="MetricSpecification" FullName="Microsoft.Azure.Management.Network.Models.MetricSpecification">
  <TypeSignature Language="C#" Value="public class MetricSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.MetricSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricSpecification" />
  <TypeSignature Language="F#" Value="type MetricSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0187e-101">Beschreibung der Metriken-Spezifikation.</span><span class="sxs-lookup"><span data-stu-id="0187e-101">Description of metrics specification.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.MetricSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0187e-102">Initialisiert eine neue Instanz der MetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0187e-102">Initializes a new instance of the MetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricSpecification (string name = null, string displayName = null, string displayDescription = null, string unit = null, string aggregationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt; availabilities = null, Nullable&lt;bool&gt; enableRegionalMdmAccount = null, Nullable&lt;bool&gt; fillGapWithZero = null, string metricFilterPattern = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt; dimensions = null, Nullable&lt;bool&gt; isInternal = null, string sourceMdmAccount = null, string sourceMdmNamespace = null, string resourceIdDimensionNameOverride = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string displayDescription, string unit, string aggregationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Availability&gt; availabilities, valuetype System.Nullable`1&lt;bool&gt; enableRegionalMdmAccount, valuetype System.Nullable`1&lt;bool&gt; fillGapWithZero, string metricFilterPattern, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Dimension&gt; dimensions, valuetype System.Nullable`1&lt;bool&gt; isInternal, string sourceMdmAccount, string sourceMdmNamespace, string resourceIdDimensionNameOverride) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.MetricSpecification.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Availability},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Dimension},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional displayDescription As String = null, Optional unit As String = null, Optional aggregationType As String = null, Optional availabilities As IList(Of Availability) = null, Optional enableRegionalMdmAccount As Nullable(Of Boolean) = null, Optional fillGapWithZero As Nullable(Of Boolean) = null, Optional metricFilterPattern As String = null, Optional dimensions As IList(Of Dimension) = null, Optional isInternal As Nullable(Of Boolean) = null, Optional sourceMdmAccount As String = null, Optional sourceMdmNamespace As String = null, Optional resourceIdDimensionNameOverride As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.MetricSpecification : string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.MetricSpecification" Usage="new Microsoft.Azure.Management.Network.Models.MetricSpecification (name, displayName, displayDescription, unit, aggregationType, availabilities, enableRegionalMdmAccount, fillGapWithZero, metricFilterPattern, dimensions, isInternal, sourceMdmAccount, sourceMdmNamespace, resourceIdDimensionNameOverride)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="displayDescription" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="aggregationType" Type="System.String" />
        <Parameter Name="availabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt;" />
        <Parameter Name="enableRegionalMdmAccount" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="fillGapWithZero" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="metricFilterPattern" Type="System.String" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt;" />
        <Parameter Name="isInternal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="sourceMdmAccount" Type="System.String" />
        <Parameter Name="sourceMdmNamespace" Type="System.String" />
        <Parameter Name="resourceIdDimensionNameOverride" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0187e-103">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-103">The name of the metric.</span></span></param>
        <param name="displayName"><span data-ttu-id="0187e-104">Der Anzeigename der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-104">The display name of the metric.</span></span></param>
        <param name="displayDescription"><span data-ttu-id="0187e-105">Die Beschreibung der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-105">The description of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="0187e-106">Einheiten der Metrik, die in angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="0187e-106">Units the metric to be displayed in.</span></span></param>
        <param name="aggregationType"><span data-ttu-id="0187e-107">Der Aggregationstyp.</span><span class="sxs-lookup"><span data-stu-id="0187e-107">The aggregation type.</span></span></param>
        <param name="availabilities"><span data-ttu-id="0187e-108">Liste der Verfügbarkeit.</span><span class="sxs-lookup"><span data-stu-id="0187e-108">List of availability.</span></span></param>
        <param name="enableRegionalMdmAccount"><span data-ttu-id="0187e-109">Gibt an, ob regionalen MDM-Konto aktiviert.</span><span class="sxs-lookup"><span data-stu-id="0187e-109">Whether regional MDM account enabled.</span></span></param>
        <param name="fillGapWithZero"><span data-ttu-id="0187e-110">Gibt an, ob würde Lücken mit Nullen gefüllt werden soll.</span><span class="sxs-lookup"><span data-stu-id="0187e-110">Whether gaps would be filled with zeros.</span></span></param>
        <param name="metricFilterPattern"><span data-ttu-id="0187e-111">Muster für den Filter der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-111">Pattern for the filter of the metric.</span></span></param>
        <param name="dimensions"><span data-ttu-id="0187e-112">Liste der Dimensionen.</span><span class="sxs-lookup"><span data-stu-id="0187e-112">List of dimensions.</span></span></param>
        <param name="isInternal"><span data-ttu-id="0187e-113">Gibt an, ob die Metrik intern verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="0187e-113">Whether the metric is internal.</span></span></param>
        <param name="sourceMdmAccount"><span data-ttu-id="0187e-114">Die Quelle MDM-Konto.</span><span class="sxs-lookup"><span data-stu-id="0187e-114">The source MDM account.</span></span></param>
        <param name="sourceMdmNamespace"><span data-ttu-id="0187e-115">Die Quelle MDM-Namespace.</span><span class="sxs-lookup"><span data-stu-id="0187e-115">The source MDM namespace.</span></span></param>
        <param name="resourceIdDimensionNameOverride"><span data-ttu-id="0187e-116">Die Ressource Dimensionsname Id außer Kraft setzen.</span><span class="sxs-lookup"><span data-stu-id="0187e-116">The resource Id dimension name override.</span></span></param>
        <summary>
            <span data-ttu-id="0187e-117">Initialisiert eine neue Instanz der MetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0187e-117">Initializes a new instance of the MetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregationType">
      <MemberSignature Language="C#" Value="public string AggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.AggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregationType As String" />
      <MemberSignature Language="F#" Value="member this.AggregationType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.AggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-118">Ruft ab oder legt den Aggregationstyp.</span><span class="sxs-lookup"><span data-stu-id="0187e-118">Gets or sets the aggregation type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Availabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt; Availabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Availability&gt; Availabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.Availabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Availabilities As IList(Of Availability)" />
      <MemberSignature Language="F#" Value="member this.Availabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.Availabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Availability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-119">Ruft ab oder legt die Liste der Verfügbarkeit.</span><span class="sxs-lookup"><span data-stu-id="0187e-119">Gets or sets list of availability.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Dimension&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of Dimension)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Dimension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-120">Ruft ab oder legt die Liste der Dimensionen.</span><span class="sxs-lookup"><span data-stu-id="0187e-120">Gets or sets list of dimensions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayDescription">
      <MemberSignature Language="C#" Value="public string DisplayDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.DisplayDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayDescription As String" />
      <MemberSignature Language="F#" Value="member this.DisplayDescription : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.DisplayDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-121">Ruft ab oder legt die Beschreibung der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-121">Gets or sets the description of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-122">Ruft ab oder legt den Anzeigenamen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-122">Gets or sets the display name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRegionalMdmAccount">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableRegionalMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableRegionalMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.EnableRegionalMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRegionalMdmAccount As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableRegionalMdmAccount : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.EnableRegionalMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableRegionalMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-123">Ruft ab oder legt fest, ob Land/Region MDM-Konto aktiviert.</span><span class="sxs-lookup"><span data-stu-id="0187e-123">Gets or sets whether regional MDM account enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FillGapWithZero">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; FillGapWithZero { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; FillGapWithZero" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.FillGapWithZero" />
      <MemberSignature Language="VB.NET" Value="Public Property FillGapWithZero As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.FillGapWithZero : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.FillGapWithZero" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fillGapWithZero")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-124">Ruft ab oder legt fest, ob Lücken mit Nullen gefüllt werden würde.</span><span class="sxs-lookup"><span data-stu-id="0187e-124">Gets or sets whether gaps would be filled with zeros.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInternal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsInternal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsInternal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.IsInternal" />
      <MemberSignature Language="VB.NET" Value="Public Property IsInternal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsInternal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.IsInternal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isInternal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-125">Ruft ab oder legt fest, ob die Metrik intern verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="0187e-125">Gets or sets whether the metric is internal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricFilterPattern">
      <MemberSignature Language="C#" Value="public string MetricFilterPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricFilterPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.MetricFilterPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricFilterPattern As String" />
      <MemberSignature Language="F#" Value="member this.MetricFilterPattern : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.MetricFilterPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricFilterPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-126">Ruft ab, oder legt ihn fest-Musters für den Filter der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-126">Gets or sets pattern for the filter of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-127">Ruft ab oder legt den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="0187e-127">Gets or sets the name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceIdDimensionNameOverride">
      <MemberSignature Language="C#" Value="public string ResourceIdDimensionNameOverride { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceIdDimensionNameOverride" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.ResourceIdDimensionNameOverride" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceIdDimensionNameOverride As String" />
      <MemberSignature Language="F#" Value="member this.ResourceIdDimensionNameOverride : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.ResourceIdDimensionNameOverride" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceIdDimensionNameOverride")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-128">Abrufen oder Festlegen der Ressourcen-Id Dimension Namen überschreiben.</span><span class="sxs-lookup"><span data-stu-id="0187e-128">Gets or sets the resource Id dimension name override.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmAccount">
      <MemberSignature Language="C#" Value="public string SourceMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.SourceMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmAccount As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmAccount : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.SourceMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-129">Ruft ab oder legt die Quelle MDM-Konto fest.</span><span class="sxs-lookup"><span data-stu-id="0187e-129">Gets or sets the source MDM account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmNamespace">
      <MemberSignature Language="C#" Value="public string SourceMdmNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.SourceMdmNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmNamespace As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmNamespace : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.SourceMdmNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-130">Abrufen oder festlegen den Quelle MDM-Namespace.</span><span class="sxs-lookup"><span data-stu-id="0187e-130">Gets or sets the source MDM namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.MetricSpecification.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.MetricSpecification.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0187e-131">Ruft ab oder legt Einheiten die Metrik, die in angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="0187e-131">Gets or sets units the metric to be displayed in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>