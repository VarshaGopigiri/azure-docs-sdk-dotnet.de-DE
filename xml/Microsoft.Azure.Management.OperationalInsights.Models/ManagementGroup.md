<Type Name="ManagementGroup" FullName="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup">
  <TypeSignature Language="C#" Value="public class ManagementGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroup" />
  <TypeSignature Language="F#" Value="type ManagementGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="368e5-101">Eine Verwaltungsgruppe, die mit einem Arbeitsbereich verbunden ist</span><span class="sxs-lookup"><span data-stu-id="368e5-101">A management group that is connected to a workspace</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="368e5-102">Initialisiert eine neue Instanz der Klasse ManagementGroup wird aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="368e5-102">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup (Nullable&lt;int&gt; serverCount = null, Nullable&lt;bool&gt; isGateway = null, string name = null, string id = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; dataReceived = null, string version = null, string sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; serverCount, valuetype System.Nullable`1&lt;bool&gt; isGateway, string name, string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; dataReceived, string version, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.#ctor(System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serverCount As Nullable(Of Integer) = null, Optional isGateway As Nullable(Of Boolean) = null, Optional name As String = null, Optional id As String = null, Optional created As Nullable(Of DateTime) = null, Optional dataReceived As Nullable(Of DateTime) = null, Optional version As String = null, Optional sku As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup : Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup (serverCount, isGateway, name, id, created, dataReceived, version, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serverCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isGateway" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="dataReceived" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serverCount"><span data-ttu-id="368e5-103">Die Anzahl der Server, die mit der Verwaltungsgruppe verbunden werden.</span><span class="sxs-lookup"><span data-stu-id="368e5-103">The number of servers connected to the management group.</span></span></param>
        <param name="isGateway"><span data-ttu-id="368e5-104">Ruft ab oder legt einen Wert, der angibt, ob die Verwaltungsgruppe ein Gateway ist.</span><span class="sxs-lookup"><span data-stu-id="368e5-104">Gets or sets a value indicating whether the management group is a gateway.</span></span></param>
        <param name="name"><span data-ttu-id="368e5-105">Der Name der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="368e5-105">The name of the management group.</span></span></param>
        <param name="id"><span data-ttu-id="368e5-106">Die eindeutige ID der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="368e5-106">The unique ID of the management group.</span></span></param>
        <param name="created"><span data-ttu-id="368e5-107">Der DateTime-Wert, dass die Verwaltungsgruppe erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="368e5-107">The datetime that the management group was created.</span></span></param>
        <param name="dataReceived"><span data-ttu-id="368e5-108">Die letzte "DateTime", dass die Verwaltungsgruppe Daten empfangen.</span><span class="sxs-lookup"><span data-stu-id="368e5-108">The last datetime that the management group received data.</span></span></param>
        <param name="version"><span data-ttu-id="368e5-109">Die Version von System Center, die die Verwaltungsgruppe verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="368e5-109">The version of System Center that is managing the management group.</span></span></param>
        <param name="sku"><span data-ttu-id="368e5-110">Die SKU von System Center, die die Verwaltungsgruppe verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="368e5-110">The SKU of System Center that is managing the management group.</span></span></param>
        <summary>
            <span data-ttu-id="368e5-111">Initialisiert eine neue Instanz der Klasse ManagementGroup wird aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="368e5-111">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Created" />
      <MemberSignature Language="VB.NET" Value="Public Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-112">Abrufen oder Festlegen der "DateTime", dass die Verwaltungsgruppe erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="368e5-112">Gets or sets the datetime that the management group was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DataReceived { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DataReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.DataReceived" />
      <MemberSignature Language="VB.NET" Value="Public Property DataReceived As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DataReceived : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.DataReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataReceived")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-113">Ruft ab oder legt den letzten DateTime-Wert, dass die Verwaltungsgruppe Daten empfangen.</span><span class="sxs-lookup"><span data-stu-id="368e5-113">Gets or sets the last datetime that the management group received data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-114">Ruft ab oder legt die eindeutige ID der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="368e5-114">Gets or sets the unique ID of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsGateway">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsGateway { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsGateway" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.IsGateway" />
      <MemberSignature Language="VB.NET" Value="Public Property IsGateway As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsGateway : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.IsGateway" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isGateway")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-115">Ruft ab oder legt einen Wert, der angibt, ob die Verwaltungsgruppe ein Gateway ist.</span><span class="sxs-lookup"><span data-stu-id="368e5-115">Gets or sets a value indicating whether the management group is a gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-116">Ruft ab oder legt den Namen der Verwaltungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="368e5-116">Gets or sets the name of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ServerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ServerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.ServerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ServerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.ServerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-117">Ruft ab oder legt die Anzahl der Server mit der Verwaltungsgruppe verbunden.</span><span class="sxs-lookup"><span data-stu-id="368e5-117">Gets or sets the number of servers connected to the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-118">Ruft ab, oder legt ihn fest-SKU von System Center, die die Verwaltungsgruppe verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="368e5-118">Gets or sets the SKU of System Center that is managing the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="368e5-119">Ruft ab oder legt die Version von System Center, die die Verwaltungsgruppe verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="368e5-119">Gets or sets the version of System Center that is managing the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>