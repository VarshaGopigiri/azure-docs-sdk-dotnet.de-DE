<Type Name="PerformanceCounterTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry">
  <TypeSignature Language="C#" Value="public sealed class PerformanceCounterTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PerformanceCounterTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PerformanceCounterTelemetry&#xA;Implements ISupportProperties, ITelemetry" />
  <TypeSignature Language="F#" Value="type PerformanceCounterTelemetry = class&#xA;    interface ITelemetry&#xA;    interface ISupportProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetry</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportProperties</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Use MetricTelemetry instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="45d32-101">Die Klasse, die Informationen zu Leistungsindikatoren darstellt.</span><span class="sxs-lookup"><span data-stu-id="45d32-101">The class that represents information about performance counters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerformanceCounterTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45d32-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="45d32-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PerformanceCounterTelemetry (string categoryName, string counterName, string instanceName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string categoryName, string counterName, string instanceName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.#ctor(System.String,System.String,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (categoryName As String, counterName As String, instanceName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry : string * string * string * double -&gt; Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry (categoryName, counterName, instanceName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="categoryName" Type="System.String" />
        <Parameter Name="counterName" Type="System.String" />
        <Parameter Name="instanceName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="categoryName"><span data-ttu-id="45d32-103">Name der Kategorie.</span><span class="sxs-lookup"><span data-stu-id="45d32-103">Category name.</span></span></param>
        <param name="counterName"><span data-ttu-id="45d32-104">Name des Leistungsindikators.</span><span class="sxs-lookup"><span data-stu-id="45d32-104">Performance counter name.</span></span></param>
        <param name="instanceName"><span data-ttu-id="45d32-105">Der Instanzname.</span><span class="sxs-lookup"><span data-stu-id="45d32-105">Instance name.</span></span></param>
        <param name="value"><span data-ttu-id="45d32-106">Leistungsindikatorwert.</span><span class="sxs-lookup"><span data-stu-id="45d32-106">Performance counter value.</span></span></param>
        <summary>
            <span data-ttu-id="45d32-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="45d32-107">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CategoryName">
      <MemberSignature Language="C#" Value="public string CategoryName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CategoryName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.CategoryName" />
      <MemberSignature Language="VB.NET" Value="Public Property CategoryName As String" />
      <MemberSignature Language="F#" Value="member this.CategoryName : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.CategoryName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-108">Ruft ab oder legt den Namen der Kategorie.</span><span class="sxs-lookup"><span data-stu-id="45d32-108">Gets or sets the category name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Context" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-109">Ruft das aktuelle Element der Telemetrie zugeordneten Kontext.</span><span class="sxs-lookup"><span data-stu-id="45d32-109">Gets the context associated with the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CounterName">
      <MemberSignature Language="C#" Value="public string CounterName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CounterName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.CounterName" />
      <MemberSignature Language="VB.NET" Value="Public Property CounterName As String" />
      <MemberSignature Language="F#" Value="member this.CounterName : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.CounterName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-110">Ruft ab oder legt den Namen des Leistungsindikators.</span><span class="sxs-lookup"><span data-stu-id="45d32-110">Gets or sets the counter name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry&#xA;override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="performanceCounterTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceName">
      <MemberSignature Language="C#" Value="public string InstanceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.InstanceName" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceName As String" />
      <MemberSignature Language="F#" Value="member this.InstanceName : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.InstanceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-111">Ruft ab oder legt den Namen der Instanz.</span><span class="sxs-lookup"><span data-stu-id="45d32-111">Gets or sets the instance name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
      <MemberSignature Language="VB.NET" Value="Sub Sanitize () Implements ITelemetry.Sanitize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45d32-112">Bereinigt die Eigenschaften, die auf Einschränkungen basieren.</span><span class="sxs-lookup"><span data-stu-id="45d32-112">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Properties" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportProperties.Properties</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-113">Ruft ein Wörterbuch von anwendungsdefinierten Eigenschaftennamen und Werten, die zusätzliche Informationen über diese Ausnahme ab.</span><span class="sxs-lookup"><span data-stu-id="45d32-113">Gets a dictionary of application-defined property names and values providing additional information about this exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-114">Ruft ab oder legt den Wert an, der absolute Reihenfolge der Telemetrie-Elements definiert.</span><span class="sxs-lookup"><span data-stu-id="45d32-114">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-115">Ruft ab oder legt Datum und Uhrzeit, wann Telemetrie aufgezeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="45d32-115">Gets or sets date and time when telemetry was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public double Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Double" />
      <MemberSignature Language="F#" Value="member this.Value : double with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.PerformanceCounterTelemetry.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45d32-116">Ruft ab oder legt den Wert des Indikators.</span><span class="sxs-lookup"><span data-stu-id="45d32-116">Gets or sets the counter value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>