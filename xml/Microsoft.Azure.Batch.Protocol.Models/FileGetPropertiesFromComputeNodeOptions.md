<Type Name="FileGetPropertiesFromComputeNodeOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions">
  <TypeSignature Language="C#" Value="public class FileGetPropertiesFromComputeNodeOptions : Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetPropertiesFromComputeNodeOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetPropertiesFromComputeNodeOptions&#xA;Implements ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type FileGetPropertiesFromComputeNodeOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions" />
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
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="dddf6-101">Zusätzliche Parameter für GetPropertiesFromComputeNode-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="dddf6-101">Additional parameters for GetPropertiesFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromComputeNodeOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.#ctor" />
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
            <span data-ttu-id="dddf6-102">Initialisiert eine neue Instanz der FileGetPropertiesFromComputeNodeOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dddf6-102">Initializes a new instance of the FileGetPropertiesFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromComputeNodeOptions (Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null, Nullable&lt;DateTime&gt; ifModifiedSince = null, Nullable&lt;DateTime&gt; ifUnmodifiedSince = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifModifiedSince, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifUnmodifiedSince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.#ctor(System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null, Optional ifModifiedSince As Nullable(Of DateTime) = null, Optional ifUnmodifiedSince As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions : Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions (timeout, clientRequestId, returnClientRequestId, ocpDate, ifModifiedSince, ifUnmodifiedSince)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifModifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifUnmodifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="dddf6-103">Die maximale Zeit, die der Server verarbeitet die Anforderung in Sekunden aufwenden kann.</span><span class="sxs-lookup"><span data-stu-id="dddf6-103">The maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="dddf6-104">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="dddf6-104">The default is 30 seconds.</span></span></param>
        <param name="clientRequestId"><span data-ttu-id="dddf6-105">Die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="dddf6-105">The caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span></param>
        <param name="returnClientRequestId"><span data-ttu-id="dddf6-106">Gibt an, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="dddf6-106">Whether the server should return the client-request-id in the response.</span></span></param>
        <param name="ocpDate"><span data-ttu-id="dddf6-107">Die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-107">The time the request was issued.</span></span> <span data-ttu-id="dddf6-108">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="dddf6-108">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span></param>
        <param name="ifModifiedSince"><span data-ttu-id="dddf6-109">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="dddf6-109">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="dddf6-110">Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-110">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span></param>
        <param name="ifUnmodifiedSince"><span data-ttu-id="dddf6-111">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="dddf6-111">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="dddf6-112">Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-112">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span></param>
        <summary>
            <span data-ttu-id="dddf6-113">Initialisiert eine neue Instanz der FileGetPropertiesFromComputeNodeOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dddf6-113">Initializes a new instance of the FileGetPropertiesFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ClientRequestId" />
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
            <span data-ttu-id="dddf6-114">Ruft ab oder legt die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="dddf6-114">Gets or sets the caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfModifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfModifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfModifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfModifiedSince" />
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
            <span data-ttu-id="dddf6-115">Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="dddf6-115">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="dddf6-116">Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-116">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfUnmodifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfUnmodifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfUnmodifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfUnmodifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfUnmodifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfUnmodifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfUnmodifiedSince" />
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
            <span data-ttu-id="dddf6-117">Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="dddf6-117">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="dddf6-118">Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-118">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.OcpDate" />
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
            <span data-ttu-id="dddf6-119">Ruft ab oder legt die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="dddf6-119">Gets or sets the time the request was issued.</span></span> <span data-ttu-id="dddf6-120">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="dddf6-120">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ReturnClientRequestId" />
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
            <span data-ttu-id="dddf6-121">Ruft ab oder legt sie fest, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="dddf6-121">Gets or sets whether the server should return the client-request-id in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.Timeout" />
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
            <span data-ttu-id="dddf6-122">Ruft ab oder legt die maximale Zeit, dass der Server konsolenmeldungen Verarbeitung der Anforderung in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="dddf6-122">Gets or sets the maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="dddf6-123">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="dddf6-123">The default is 30 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>