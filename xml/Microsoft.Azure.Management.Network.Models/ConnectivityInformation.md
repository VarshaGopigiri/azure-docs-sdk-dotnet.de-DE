<Type Name="ConnectivityInformation" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityInformation">
  <TypeSignature Language="C#" Value="public class ConnectivityInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityInformation" />
  <TypeSignature Language="F#" Value="type ConnectivityInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6d9e1-101">Informationen über den Verbindungsstatus.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-101">Information on the connectivity status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-102">Initialisiert eine neue Instanz der ConnectivityInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-102">Initializes a new instance of the ConnectivityInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityInformation (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt; hops = null, string connectionStatus = null, Nullable&lt;int&gt; avgLatencyInMs = null, Nullable&lt;int&gt; minLatencyInMs = null, Nullable&lt;int&gt; maxLatencyInMs = null, Nullable&lt;int&gt; probesSent = null, Nullable&lt;int&gt; probesFailed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt; hops, string connectionStatus, valuetype System.Nullable`1&lt;int32&gt; avgLatencyInMs, valuetype System.Nullable`1&lt;int32&gt; minLatencyInMs, valuetype System.Nullable`1&lt;int32&gt; maxLatencyInMs, valuetype System.Nullable`1&lt;int32&gt; probesSent, valuetype System.Nullable`1&lt;int32&gt; probesFailed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ConnectivityHop},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional hops As IList(Of ConnectivityHop) = null, Optional connectionStatus As String = null, Optional avgLatencyInMs As Nullable(Of Integer) = null, Optional minLatencyInMs As Nullable(Of Integer) = null, Optional maxLatencyInMs As Nullable(Of Integer) = null, Optional probesSent As Nullable(Of Integer) = null, Optional probesFailed As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityInformation : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityInformation" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityInformation (hops, connectionStatus, avgLatencyInMs, minLatencyInMs, maxLatencyInMs, probesSent, probesFailed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hops" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt;" />
        <Parameter Name="connectionStatus" Type="System.String" />
        <Parameter Name="avgLatencyInMs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minLatencyInMs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxLatencyInMs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="probesSent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="probesFailed" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="hops"><span data-ttu-id="6d9e1-103">Liste der Hops zwischen der Quelle und Ziel.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-103">List of hops between the source and the destination.</span></span></param>
        <param name="connectionStatus"><span data-ttu-id="6d9e1-104">Der Status der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-104">The connection status.</span></span> <span data-ttu-id="6d9e1-105">Folgende Werte sind möglich: "Unknown", "Verbunden", "Getrennt", "Heruntergestuft"</span><span class="sxs-lookup"><span data-stu-id="6d9e1-105">Possible values include: 'Unknown', 'Connected', 'Disconnected', 'Degraded'</span></span></param>
        <param name="avgLatencyInMs"><span data-ttu-id="6d9e1-106">Durchschnittliche Latenz in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-106">Average latency in milliseconds.</span></span></param>
        <param name="minLatencyInMs"><span data-ttu-id="6d9e1-107">Minimale Wartezeit in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-107">Minimum latency in milliseconds.</span></span></param>
        <param name="maxLatencyInMs"><span data-ttu-id="6d9e1-108">Maximale Wartezeit in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-108">Maximum latency in milliseconds.</span></span></param>
        <param name="probesSent"><span data-ttu-id="6d9e1-109">Gesamtanzahl der Prüfpunkte gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-109">Total number of probes sent.</span></span></param>
        <param name="probesFailed"><span data-ttu-id="6d9e1-110">Die Anzahl der fehlgeschlagenen Tests.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-110">Number of failed probes.</span></span></param>
        <summary>
            <span data-ttu-id="6d9e1-111">Initialisiert eine neue Instanz der ConnectivityInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-111">Initializes a new instance of the ConnectivityInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvgLatencyInMs">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AvgLatencyInMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AvgLatencyInMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.AvgLatencyInMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvgLatencyInMs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AvgLatencyInMs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.AvgLatencyInMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="avgLatencyInMs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-112">Ruft die durchschnittliche Latenz in Millisekunden.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-112">Gets average latency in milliseconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStatus">
      <MemberSignature Language="C#" Value="public string ConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStatus : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-113">Ruft den Status der Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-113">Gets the connection status.</span></span> <span data-ttu-id="6d9e1-114">Folgende Werte sind möglich: "Unknown", "Verbunden", "Getrennt", "Heruntergestuft"</span><span class="sxs-lookup"><span data-stu-id="6d9e1-114">Possible values include: 'Unknown', 'Connected', 'Disconnected', 'Degraded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hops">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt; Hops { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt; Hops" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.Hops" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Hops As IList(Of ConnectivityHop)" />
      <MemberSignature Language="F#" Value="member this.Hops : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.Hops" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hops")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityHop&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-115">Ruft die Liste der Hops zwischen der Quelle und Ziel.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-115">Gets list of hops between the source and the destination.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxLatencyInMs">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxLatencyInMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxLatencyInMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.MaxLatencyInMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxLatencyInMs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxLatencyInMs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.MaxLatencyInMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxLatencyInMs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-116">Ruft die maximale Wartezeit in Millisekunden ab.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-116">Gets maximum latency in milliseconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinLatencyInMs">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinLatencyInMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinLatencyInMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.MinLatencyInMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinLatencyInMs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinLatencyInMs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.MinLatencyInMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minLatencyInMs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-117">Ruft die minimale Wartezeit in Millisekunden ab.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-117">Gets minimum latency in milliseconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProbesFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProbesFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProbesFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ProbesFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProbesFailed As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProbesFailed : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ProbesFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="probesFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-118">Ruft die Anzahl der fehlgeschlagenen Tests.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-118">Gets number of failed probes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProbesSent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProbesSent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProbesSent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ProbesSent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProbesSent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProbesSent : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityInformation.ProbesSent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="probesSent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9e1-119">Ruft die Gesamtanzahl von Tests, die gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d9e1-119">Gets total number of probes sent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>