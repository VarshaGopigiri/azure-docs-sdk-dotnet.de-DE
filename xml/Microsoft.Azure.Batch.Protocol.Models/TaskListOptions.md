<Type Name="TaskListOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions">
  <TypeSignature Language="C#" Value="public class TaskListOptions : Microsoft.Azure.Batch.Protocol.Models.IODataExpand, Microsoft.Azure.Batch.Protocol.Models.IODataFilter, Microsoft.Azure.Batch.Protocol.Models.IODataSelect, Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskListOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IODataExpand, class Microsoft.Azure.Batch.Protocol.Models.IODataFilter, class Microsoft.Azure.Batch.Protocol.Models.IODataSelect, class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskListOptions&#xA;Implements IODataExpand, IODataFilter, IODataSelect, ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type TaskListOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions&#xA;    interface IODataSelect&#xA;    interface IODataFilter&#xA;    interface IODataExpand" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataExpand</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataFilter</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IODataSelect</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="019b9-101">Zusätzliche Parameter für den List-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="019b9-101">Additional parameters for List operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="019b9-102">Initialisiert eine neue Instanz der TaskListOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="019b9-102">Initializes a new instance of the TaskListOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListOptions (string filter = null, string select = null, string expand = null, Nullable&lt;int&gt; maxResults = null, Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filter, string select, string expand, valuetype System.Nullable`1&lt;int32&gt; maxResults, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filter As String = null, Optional select As String = null, Optional expand As String = null, Optional maxResults As Nullable(Of Integer) = null, Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskListOptions : string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskListOptions (filter, select, expand, maxResults, timeout, clientRequestId, returnClientRequestId, ocpDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="019b9-103">Eine OData-$filter-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-103">An OData $filter clause.</span></span> <span data-ttu-id="019b9-104">Weitere Informationen zum Erstellen dieser Filter finden Sie unter https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-tasks.</span><span class="sxs-lookup"><span data-stu-id="019b9-104">For more information on constructing this filter, see https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-tasks.</span></span></param>
        <param name="select"><span data-ttu-id="019b9-105">Eine OData-$select-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-105">An OData $select clause.</span></span></param>
        <param name="expand"><span data-ttu-id="019b9-106">Ein OData-$expand-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-106">An OData $expand clause.</span></span></param>
        <param name="maxResults"><span data-ttu-id="019b9-107">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="019b9-107">The maximum number of items to return in the response.</span></span> <span data-ttu-id="019b9-108">Es kann maximal 1.000 Aufgaben zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="019b9-108">A maximum of 1000 tasks can be returned.</span></span></param>
        <param name="timeout"><span data-ttu-id="019b9-109">Die maximale Zeit, die der Server verarbeitet die Anforderung in Sekunden aufwenden kann.</span><span class="sxs-lookup"><span data-stu-id="019b9-109">The maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="019b9-110">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="019b9-110">The default is 30 seconds.</span></span></param>
        <param name="clientRequestId"><span data-ttu-id="019b9-111">Die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="019b9-111">The caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span></param>
        <param name="returnClientRequestId"><span data-ttu-id="019b9-112">Gibt an, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="019b9-112">Whether the server should return the client-request-id in the response.</span></span></param>
        <param name="ocpDate"><span data-ttu-id="019b9-113">Die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="019b9-113">The time the request was issued.</span></span> <span data-ttu-id="019b9-114">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="019b9-114">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span></param>
        <summary>
            <span data-ttu-id="019b9-115">Initialisiert eine neue Instanz der TaskListOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="019b9-115">Initializes a new instance of the TaskListOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-116">Ruft ab oder legt die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="019b9-116">Gets or sets the caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public string Expand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Expand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Expand" />
      <MemberSignature Language="VB.NET" Value="Public Property Expand As String" />
      <MemberSignature Language="F#" Value="member this.Expand : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Expand" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataExpand.Expand</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-117">Ruft ab oder legt einen OData $expand-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-117">Gets or sets an OData $expand clause.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Filter" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataFilter.Filter</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-118">Ruft ab oder legt eine OData-$filter-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-118">Gets or sets an OData $filter clause.</span></span> <span data-ttu-id="019b9-119">Weitere Informationen zum Erstellen dieser Filter finden Sie unter https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-tasks.</span><span class="sxs-lookup"><span data-stu-id="019b9-119">For more information on constructing this filter, see https://docs.microsoft.com/en-us/rest/api/batchservice/odata-filters-in-batch#list-tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-120">Ruft ab oder legt die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="019b9-120">Gets or sets the maximum number of items to return in the response.</span></span>
            <span data-ttu-id="019b9-121">Es kann maximal 1.000 Aufgaben zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="019b9-121">A maximum of 1000 tasks can be returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.OcpDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-122">Ruft ab oder legt die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="019b9-122">Gets or sets the time the request was issued.</span></span> <span data-ttu-id="019b9-123">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="019b9-123">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-124">Ruft ab oder legt sie fest, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="019b9-124">Gets or sets whether the server should return the client-request-id in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Select" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IODataSelect.Select</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-125">Ruft ab oder legt eine OData-$select-Klausel.</span><span class="sxs-lookup"><span data-stu-id="019b9-125">Gets or sets an OData $select clause.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="019b9-126">Ruft ab oder legt die maximale Zeit, dass der Server konsolenmeldungen Verarbeitung der Anforderung in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="019b9-126">Gets or sets the maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="019b9-127">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="019b9-127">The default is 30 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>