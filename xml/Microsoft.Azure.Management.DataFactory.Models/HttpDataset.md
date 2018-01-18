<Type Name="HttpDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.HttpDataset">
  <TypeSignature Language="C#" Value="public class HttpDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HttpDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type HttpDataset = class&#xA;    inherit Dataset" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Dataset</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("HttpFile")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9d55f-101">Eine Datei in einen HTTP-Web-Server.</span><span class="sxs-lookup"><span data-stu-id="9d55f-101">A file in an HTTP web server.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-102">Initialisiert eine neue Instanz der HttpDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d55f-102">Initializes a new instance of the HttpDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object relativeUrl = null, object requestMethod = null, object requestBody = null, object additionalHeaders = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object relativeUrl, object requestMethod, object requestBody, object additionalHeaders, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional relativeUrl As Object = null, Optional requestMethod As Object = null, Optional requestBody As Object = null, Optional additionalHeaders As Object = null, Optional format As DatasetStorageFormat = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HttpDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.HttpDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.HttpDataset (linkedServiceName, additionalProperties, description, structure, parameters, relativeUrl, requestMethod, requestBody, additionalHeaders, format, compression)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="relativeUrl" Type="System.Object" />
        <Parameter Name="requestMethod" Type="System.Object" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="additionalHeaders" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="9d55f-103">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="9d55f-103">Linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="9d55f-104">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="9d55f-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="9d55f-105">Beschreibung des Datasets.</span><span class="sxs-lookup"><span data-stu-id="9d55f-105">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="9d55f-106">Spalten, die die Struktur des Datasets zu definieren.</span><span class="sxs-lookup"><span data-stu-id="9d55f-106">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="9d55f-107">Typ: Array (oder Ausdruck mit ResultType-Array), ItemType: DatasetDataElement.</span><span class="sxs-lookup"><span data-stu-id="9d55f-107">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="9d55f-108">Parameter für das Dataset.</span><span class="sxs-lookup"><span data-stu-id="9d55f-108">Parameters for dataset.</span></span></param>
        <param name="relativeUrl"><span data-ttu-id="9d55f-109">Die relative URL basierend auf der URL in die HttpLinkedService bezieht sich auf eine HTTP-Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-109">The relative URL based on the URL in the HttpLinkedService refers to an HTTP file Type: string (or Expression with resultType string).</span></span></param>
        <param name="requestMethod"><span data-ttu-id="9d55f-110">Die HTTP-Methode für die HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-110">The HTTP method for the HTTP request.</span></span>
            <span data-ttu-id="9d55f-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="requestBody"><span data-ttu-id="9d55f-112">Der Text der HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-112">The body for the HTTP request.</span></span> <span data-ttu-id="9d55f-113">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalHeaders"><span data-ttu-id="9d55f-114">Die Header für die HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-114">The headers for the HTTP Request.</span></span>
            <span data-ttu-id="9d55f-115">z. B. Request-header-name-1:request-header-value-1... request-header-name-n:request-header-value-n Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-115">e.g. request-header-name-1:request-header-value-1 ... request-header-name-n:request-header-value-n Type: string (or Expression with resultType string).</span></span></param>
        <param name="format"><span data-ttu-id="9d55f-116">Das Format der Dateien.</span><span class="sxs-lookup"><span data-stu-id="9d55f-116">The format of files.</span></span></param>
        <param name="compression"><span data-ttu-id="9d55f-117">Die datenkomprimierungsmethode für Dateien verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="9d55f-117">The data compression method used on files.</span></span></param>
        <summary>
            <span data-ttu-id="9d55f-118">Initialisiert eine neue Instanz der HttpDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d55f-118">Initializes a new instance of the HttpDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalHeaders">
      <MemberSignature Language="C#" Value="public object AdditionalHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.AdditionalHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalHeaders As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalHeaders : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.AdditionalHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalHeaders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-119">Ruft ab oder legt die Header für die HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-119">Gets or sets the headers for the HTTP Request.</span></span> <span data-ttu-id="9d55f-120">z. B. Request-header-name-1:request-header-value-1... request-header-name-n:request-header-value-n Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-120">e.g. request-header-name-1:request-header-value-1 ... request-header-name-n:request-header-value-n Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetCompression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-121">Ruft ab oder legt die datenkomprimierungsmethode für Dateien verwendet.</span><span class="sxs-lookup"><span data-stu-id="9d55f-121">Gets or sets the data compression method used on files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-122">Ruft ab oder legt das Format der Dateien.</span><span class="sxs-lookup"><span data-stu-id="9d55f-122">Gets or sets the format of files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeUrl">
      <MemberSignature Language="C#" Value="public object RelativeUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RelativeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RelativeUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeUrl As Object" />
      <MemberSignature Language="F#" Value="member this.RelativeUrl : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RelativeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.relativeUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-123">Ruft ab oder legt fest, die die relative URL basierend auf der URL in die HttpLinkedService bezieht sich auf eine HTTP-Dateityp: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-123">Gets or sets the relative URL based on the URL in the HttpLinkedService refers to an HTTP file Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestBody">
      <MemberSignature Language="C#" Value="public object RequestBody { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestBody" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestBody As Object" />
      <MemberSignature Language="F#" Value="member this.RequestBody : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestBody")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-124">Ruft ab oder legt den Text der HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-124">Gets or sets the body for the HTTP request.</span></span> <span data-ttu-id="9d55f-125">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestMethod">
      <MemberSignature Language="C#" Value="public object RequestMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RequestMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestMethod As Object" />
      <MemberSignature Language="F#" Value="member this.RequestMethod : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HttpDataset.RequestMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.requestMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-126">Ruft ab oder legt den HTTP-Methode für die HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9d55f-126">Gets or sets the HTTP method for the HTTP request.</span></span> <span data-ttu-id="9d55f-127">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="9d55f-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HttpDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="httpDataset.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d55f-128">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9d55f-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9d55f-129">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9d55f-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>