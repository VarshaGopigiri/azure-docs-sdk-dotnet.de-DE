<Type Name="BlobDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties">
  <TypeSignature Language="C#" Value="public class BlobDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobDataSourceProperties" />
  <TypeSignature Language="F#" Value="type BlobDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdd79-101">Die Eigenschaften, die eine Blob-Datenquelle zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="fdd79-101">The properties that are associated with a blob data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-102">Initialisiert eine neue Instanz der BlobDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fdd79-102">Initializes a new instance of the BlobDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobDataSourceProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties (storageAccounts, container, pathPattern, dateFormat, timeFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="pathPattern" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccounts"><span data-ttu-id="fdd79-103">Eine Liste mit mindestens ein Azure-Speicherkonten.</span><span class="sxs-lookup"><span data-stu-id="fdd79-103">A list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="fdd79-104">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fdd79-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="container"><span data-ttu-id="fdd79-105">Der Name eines Containers im zugeordneten Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="fdd79-105">The name of a container within the associated Storage account.</span></span> <span data-ttu-id="fdd79-106">Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdd79-106">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="fdd79-107">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fdd79-107">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="pathPattern"><span data-ttu-id="fdd79-108">Das Muster für den Blob-Pfad.</span><span class="sxs-lookup"><span data-stu-id="fdd79-108">The blob path pattern.</span></span> <span data-ttu-id="fdd79-109">Regulärer Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="fdd79-109">Not a regular expression.</span></span> <span data-ttu-id="fdd79-110">Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdd79-110">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="fdd79-111">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.</span><span class="sxs-lookup"><span data-stu-id="fdd79-111">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span></param>
        <param name="dateFormat"><span data-ttu-id="fdd79-112">Das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="fdd79-112">The date format.</span></span> <span data-ttu-id="fdd79-113">Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="fdd79-113">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span></param>
        <param name="timeFormat"><span data-ttu-id="fdd79-114">Das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="fdd79-114">The time format.</span></span> <span data-ttu-id="fdd79-115">Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="fdd79-115">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span></param>
        <summary>
            <span data-ttu-id="fdd79-116">Initialisiert eine neue Instanz der BlobDataSourceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fdd79-116">Initializes a new instance of the BlobDataSourceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-117">Ruft ab oder legt den Namen eines Containers im zugeordneten Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="fdd79-117">Gets or sets the name of a container within the associated Storage account.</span></span> <span data-ttu-id="fdd79-118">Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdd79-118">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="fdd79-119">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fdd79-119">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-120">Ruft ab oder legt das Datumsformat.</span><span class="sxs-lookup"><span data-stu-id="fdd79-120">Gets or sets the date format.</span></span> <span data-ttu-id="fdd79-121">Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="fdd79-121">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPattern">
      <MemberSignature Language="C#" Value="public string PathPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-122">Abrufen oder Festlegen der Blob-Pfad-Muster.</span><span class="sxs-lookup"><span data-stu-id="fdd79-122">Gets or sets the blob path pattern.</span></span> <span data-ttu-id="fdd79-123">Regulärer Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="fdd79-123">Not a regular expression.</span></span> <span data-ttu-id="fdd79-124">Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="fdd79-124">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="fdd79-125">Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.</span><span class="sxs-lookup"><span data-stu-id="fdd79-125">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-126">Ruft ab oder legt eine Liste von einem oder mehreren Azure-Speicher-Konten.</span><span class="sxs-lookup"><span data-stu-id="fdd79-126">Gets or sets a list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="fdd79-127">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="fdd79-127">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobDataSourceProperties.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdd79-128">Ruft ab oder legt das Zeitformat.</span><span class="sxs-lookup"><span data-stu-id="fdd79-128">Gets or sets the time format.</span></span> <span data-ttu-id="fdd79-129">Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</span><span class="sxs-lookup"><span data-stu-id="fdd79-129">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>