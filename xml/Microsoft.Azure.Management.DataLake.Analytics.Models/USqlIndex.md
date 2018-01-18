<Type Name="USqlIndex" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex">
  <TypeSignature Language="C#" Value="public class USqlIndex" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlIndex extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlIndex" />
  <TypeSignature Language="F#" Value="type USqlIndex = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d6af-101">Ein Data Lake Analytics U-SQL-Tabelle Index Katalogelement.</span><span class="sxs-lookup"><span data-stu-id="4d6af-101">A Data Lake Analytics catalog U-SQL table index item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlIndex ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-102">Initialisiert eine neue Instanz der USqlIndex-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d6af-102">Initializes a new instance of the USqlIndex class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlIndex (string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; indexKeys = null, System.Collections.Generic.IList&lt;string&gt; columns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo distributionInfo = null, Nullable&lt;Guid&gt; partitionFunction = null, System.Collections.Generic.IList&lt;string&gt; partitionKeyList = null, System.Collections.Generic.IList&lt;string&gt; streamNames = null, Nullable&lt;bool&gt; isColumnstore = null, Nullable&lt;int&gt; indexId = null, Nullable&lt;bool&gt; isUnique = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; indexKeys, class System.Collections.Generic.IList`1&lt;string&gt; columns, class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo distributionInfo, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionFunction, class System.Collections.Generic.IList`1&lt;string&gt; partitionKeyList, class System.Collections.Generic.IList`1&lt;string&gt; streamNames, valuetype System.Nullable`1&lt;bool&gt; isColumnstore, valuetype System.Nullable`1&lt;int32&gt; indexId, valuetype System.Nullable`1&lt;bool&gt; isUnique) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo,System.Nullable{System.Guid},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional indexKeys As IList(Of USqlDirectedColumn) = null, Optional columns As IList(Of String) = null, Optional distributionInfo As USqlDistributionInfo = null, Optional partitionFunction As Nullable(Of Guid) = null, Optional partitionKeyList As IList(Of String) = null, Optional streamNames As IList(Of String) = null, Optional isColumnstore As Nullable(Of Boolean) = null, Optional indexId As Nullable(Of Integer) = null, Optional isUnique As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo * Nullable&lt;Guid&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex (name, indexKeys, columns, distributionInfo, partitionFunction, partitionKeyList, streamNames, isColumnstore, indexId, isUnique)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="indexKeys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="distributionInfo" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" />
        <Parameter Name="partitionFunction" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="partitionKeyList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="streamNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isColumnstore" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="indexId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isUnique" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4d6af-103">der Name des Indexes in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="4d6af-103">the name of the index in the table.</span></span></param>
        <param name="indexKeys"><span data-ttu-id="4d6af-104">die Liste der gesteuerte Spalten im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-104">the list of directed columns in the index</span></span></param>
        <param name="columns"><span data-ttu-id="4d6af-105">die Liste der Spalten im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-105">the list of columns in the index</span></span></param>
        <param name="distributionInfo"><span data-ttu-id="4d6af-106">die Verteilungen Informationen des Indexes</span><span class="sxs-lookup"><span data-stu-id="4d6af-106">the distributions info of the index</span></span></param>
        <param name="partitionFunction"><span data-ttu-id="4d6af-107">die Partitionsfunktions-ID für den Index.</span><span class="sxs-lookup"><span data-stu-id="4d6af-107">partition function ID for the index.</span></span></param>
        <param name="partitionKeyList"><span data-ttu-id="4d6af-108">die Liste der Partition Schlüssel im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-108">the list of partion keys in the index</span></span></param>
        <param name="streamNames"><span data-ttu-id="4d6af-109">die Liste der vollständige Pfade zu den Streams, die diesen Index in der DataLake-Konto enthalten.</span><span class="sxs-lookup"><span data-stu-id="4d6af-109">the list of full paths to the streams that contain this index in the DataLake account.</span></span></param>
        <param name="isColumnstore"><span data-ttu-id="4d6af-110">der Schalter, der angibt, ob dieser Index ein columnstore-Index ist.</span><span class="sxs-lookup"><span data-stu-id="4d6af-110">the switch indicating if this index is a columnstore index.</span></span></param>
        <param name="indexId"><span data-ttu-id="4d6af-111">die ID der dieser Index innerhalb der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="4d6af-111">the ID of this index within the table.</span></span></param>
        <param name="isUnique"><span data-ttu-id="4d6af-112">der Schalter, der angibt, ob dieser Index ein eindeutiger Index ist.</span><span class="sxs-lookup"><span data-stu-id="4d6af-112">the switch indicating if this index is a unique index.</span></span></param>
        <summary>
            <span data-ttu-id="4d6af-113">Initialisiert eine neue Instanz der USqlIndex-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4d6af-113">Initializes a new instance of the USqlIndex class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Columns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.Columns" />
      <MemberSignature Language="VB.NET" Value="Public Property Columns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-114">Ruft ab oder legt die Liste der Spalten im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-114">Gets or sets the list of columns in the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistributionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo DistributionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo DistributionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.DistributionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property DistributionInfo As USqlDistributionInfo" />
      <MemberSignature Language="F#" Value="member this.DistributionInfo : Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.DistributionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distributionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-115">Ruft ab oder legt die Verteilungen Informationen des Indexes</span><span class="sxs-lookup"><span data-stu-id="4d6af-115">Gets or sets the distributions info of the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IndexId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IndexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IndexId" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IndexId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IndexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-116">Ruft ab oder legt die ID dieser Index innerhalb der Tabelle fest.</span><span class="sxs-lookup"><span data-stu-id="4d6af-116">Gets or sets the ID of this index within the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; IndexKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; IndexKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IndexKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexKeys As IList(Of USqlDirectedColumn)" />
      <MemberSignature Language="F#" Value="member this.IndexKeys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IndexKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-117">Ruft ab oder legt die Liste der gesteuerte Spalten im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-117">Gets or sets the list of directed columns in the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsColumnstore">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsColumnstore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsColumnstore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IsColumnstore" />
      <MemberSignature Language="VB.NET" Value="Public Property IsColumnstore As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsColumnstore : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IsColumnstore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isColumnstore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-118">Ruft ab oder legt den Switch, der angibt, ob dieser Index ein columnstore-Index ist.</span><span class="sxs-lookup"><span data-stu-id="4d6af-118">Gets or sets the switch indicating if this index is a columnstore index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUnique">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUnique { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUnique" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IsUnique" />
      <MemberSignature Language="VB.NET" Value="Public Property IsUnique As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUnique : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.IsUnique" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isUnique")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-119">Abrufen oder festlegen den Switch, der angibt, ob dieser Index ein eindeutiger Index ist.</span><span class="sxs-lookup"><span data-stu-id="4d6af-119">Gets or sets the switch indicating if this index is a unique index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4d6af-120">Ruft ab oder legt den Namen des Indexes in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="4d6af-120">Gets or sets the name of the index in the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionFunction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PartitionFunction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PartitionFunction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.PartitionFunction" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionFunction As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PartitionFunction : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.PartitionFunction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionFunction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-121">Ruft ab oder legt die Partitionsfunktions-ID für den Index.</span><span class="sxs-lookup"><span data-stu-id="4d6af-121">Gets or sets partition function ID for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PartitionKeyList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PartitionKeyList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.PartitionKeyList" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.PartitionKeyList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKeyList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-122">Ruft ab oder legt die Liste der Partition Schlüssel im index</span><span class="sxs-lookup"><span data-stu-id="4d6af-122">Gets or sets the list of partion keys in the index</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; StreamNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; StreamNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.StreamNames" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.StreamNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex.StreamNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="streamNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4d6af-123">Ruft ab oder legt die Liste der vollständige Pfade, die Datenströme, die diesen Index in der DataLake-Konto enthalten.</span><span class="sxs-lookup"><span data-stu-id="4d6af-123">Gets or sets the list of full paths to the streams that contain this index in the DataLake account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>