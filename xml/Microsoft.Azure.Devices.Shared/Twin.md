<Type Name="Twin" FullName="Microsoft.Azure.Devices.Shared.Twin">
  <TypeSignature Language="C#" Value="public class Twin : Microsoft.Azure.Devices.Shared.IETagHolder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Twin extends System.Object implements class Microsoft.Azure.Devices.Shared.IETagHolder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.Twin" />
  <TypeSignature Language="VB.NET" Value="Public Class Twin&#xA;Implements IETagHolder" />
  <TypeSignature Language="F#" Value="type Twin = class&#xA;    interface IETagHolder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Shared.IETagHolder</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Devices.Shared.TwinJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a573f-101">Ziel-Darstellung</span><span class="sxs-lookup"><span data-stu-id="a573f-101">Twin Representation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Twin ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.Twin.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a573f-102">Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />.</span><span class="sxs-lookup"><span data-stu-id="a573f-102">Creates an instance of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Twin (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.Twin.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.Twin : string -&gt; Microsoft.Azure.Devices.Shared.Twin" Usage="new Microsoft.Azure.Devices.Shared.Twin deviceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="a573f-103">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="a573f-103">Device Id</span></span></param>
        <summary>
            <span data-ttu-id="a573f-104">Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />.</span><span class="sxs-lookup"><span data-stu-id="a573f-104">Creates an instance of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Devices.AuthenticationType&gt; AuthenticationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.AuthenticationType&gt; AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthenticationType As Nullable(Of AuthenticationType)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : Nullable&lt;Microsoft.Azure.Devices.AuthenticationType&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Devices.AuthenticationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-105">Authentifizierungstyp des entsprechenden Geräts</span><span class="sxs-lookup"><span data-stu-id="a573f-105">Corresponding Device's authentication type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudToDeviceMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CloudToDeviceMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CloudToDeviceMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.CloudToDeviceMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloudToDeviceMessageCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CloudToDeviceMessageCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.CloudToDeviceMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-106">Anzahl der Nachrichten, die an das entsprechende Gerät aus der Cloud gesendet</span><span class="sxs-lookup"><span data-stu-id="a573f-106">Number of messages sent to the corresponding Device from the Cloud</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Devices.DeviceConnectionState&gt; ConnectionState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.DeviceConnectionState&gt; ConnectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.ConnectionState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionState As Nullable(Of DeviceConnectionState)" />
      <MemberSignature Language="F#" Value="member this.ConnectionState : Nullable&lt;Microsoft.Azure.Devices.DeviceConnectionState&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.ConnectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Devices.DeviceConnectionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-107">Entsprechende Gerät ConnectionState</span><span class="sxs-lookup"><span data-stu-id="a573f-107">Corresponding Device's ConnectionState</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.Shared.Twin.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-108">Ermittelt und definiert die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Id.</span><span class="sxs-lookup"><span data-stu-id="a573f-108">Gets and sets the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Devices.Shared.Twin.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Devices.Shared.IETagHolder.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-109">Ziel des ETag</span><span class="sxs-lookup"><span data-stu-id="a573f-109">Twin's ETag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActivityTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastActivityTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastActivityTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.LastActivityTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActivityTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastActivityTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.LastActivityTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-110">Zeit, wenn das entsprechende Gerät zuletzt aktiv war</span><span class="sxs-lookup"><span data-stu-id="a573f-110">Time when the corresponding Device was last active</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.TwinProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Shared.TwinProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As TwinProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Devices.Shared.TwinProperties with get, set" Usage="Microsoft.Azure.Devices.Shared.Twin.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TwinProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-111">Ermittelt und definiert die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a573f-111">Gets and sets the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Devices.DeviceStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.DeviceStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of DeviceStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Devices.DeviceStatus&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Devices.DeviceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-112">Ruft das entsprechende Gerät Status ab.</span><span class="sxs-lookup"><span data-stu-id="a573f-112">Gets the corresponding Device's Status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusReason">
      <MemberSignature Language="C#" Value="public string StatusReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.StatusReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusReason As String" />
      <MemberSignature Language="F#" Value="member this.StatusReason : string" Usage="Microsoft.Azure.Devices.Shared.Twin.StatusReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-113">Deshalb ggf. für das entsprechende Gerät in angegeben werden<see cref="P:Microsoft.Azure.Devices.Shared.Twin.Status" /></span><span class="sxs-lookup"><span data-stu-id="a573f-113">Reason, if any, for the corresponding Device to be in specified <see cref="P:Microsoft.Azure.Devices.Shared.Twin.Status" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusUpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StatusUpdatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StatusUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.StatusUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusUpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StatusUpdatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Devices.Shared.Twin.StatusUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-114">Uhrzeit der Erstellung des entsprechenden Geräts <see cref="P:Microsoft.Azure.Devices.Shared.Twin.Status" /> zuletzt aktualisiert wurde</span><span class="sxs-lookup"><span data-stu-id="a573f-114">Time when the corresponding Device's <see cref="P:Microsoft.Azure.Devices.Shared.Twin.Status" /> was last updated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.TwinCollection Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Shared.TwinCollection Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As TwinCollection" />
      <MemberSignature Language="F#" Value="member this.Tags : Microsoft.Azure.Devices.Shared.TwinCollection with get, set" Usage="Microsoft.Azure.Devices.Shared.Twin.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.TwinCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-115">Ermittelt und definiert die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Tags.</span><span class="sxs-lookup"><span data-stu-id="a573f-115">Gets and sets the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToJson">
      <MemberSignature Language="C#" Value="public string ToJson (Newtonsoft.Json.Formatting formatting = Newtonsoft.Json.Formatting.None);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToJson(valuetype Newtonsoft.Json.Formatting formatting) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.Twin.ToJson(Newtonsoft.Json.Formatting)" />
      <MemberSignature Language="F#" Value="member this.ToJson : Newtonsoft.Json.Formatting -&gt; string" Usage="twin.ToJson formatting" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="formatting" Type="Newtonsoft.Json.Formatting" />
      </Parameters>
      <Docs>
        <param name="formatting"><span data-ttu-id="a573f-116">Optional.</span><span class="sxs-lookup"><span data-stu-id="a573f-116">Optional.</span></span> <span data-ttu-id="a573f-117">Formatierung für die Ausgabe JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="a573f-117">Formatting for the output JSON string.</span></span></param>
        <summary>
            <span data-ttu-id="a573f-118">Ruft das Ziel als JSON-Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="a573f-118">Gets the Twin as a JSON string</span></span>
            </summary>
        <returns><span data-ttu-id="a573f-119">JSON-Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="a573f-119">JSON string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Version : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Devices.Shared.Twin.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-120">Der Ziel-Version</span><span class="sxs-lookup"><span data-stu-id="a573f-120">Twin's Version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="X509Thumbprint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.X509Thumbprint X509Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.X509Thumbprint X509Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.Twin.X509Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property X509Thumbprint As X509Thumbprint" />
      <MemberSignature Language="F#" Value="member this.X509Thumbprint : Microsoft.Azure.Devices.X509Thumbprint" Usage="Microsoft.Azure.Devices.Shared.Twin.X509Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(null)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.X509Thumbprint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a573f-121">Entsprechende Gerät X509 Fingerabdruck</span><span class="sxs-lookup"><span data-stu-id="a573f-121">Corresponding Device's X509 thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>