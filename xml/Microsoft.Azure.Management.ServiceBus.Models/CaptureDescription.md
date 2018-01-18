<Type Name="CaptureDescription" FullName="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription">
  <TypeSignature Language="C#" Value="public class CaptureDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CaptureDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class CaptureDescription" />
  <TypeSignature Language="F#" Value="type CaptureDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="35050-101">Eigenschaften zum Konfigurieren der Capture-Beschreibung für den eventhub</span><span class="sxs-lookup"><span data-stu-id="35050-101">Properties to configure capture description for eventhub</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaptureDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35050-102">Initialisiert eine neue Instanz der CaptureDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35050-102">Initializes a new instance of the CaptureDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaptureDescription (Nullable&lt;bool&gt; enabled = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; encoding = null, Nullable&lt;int&gt; intervalInSeconds = null, Nullable&lt;int&gt; sizeLimitInBytes = null, Microsoft.Azure.Management.ServiceBus.Models.Destination destination = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; encoding, valuetype System.Nullable`1&lt;int32&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int32&gt; sizeLimitInBytes, class Microsoft.Azure.Management.ServiceBus.Models.Destination destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.ServiceBus.Models.Destination)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.ServiceBus.Models.Destination -&gt; Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription" Usage="new Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription (enabled, encoding, intervalInSeconds, sizeLimitInBytes, destination)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="encoding" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt;" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sizeLimitInBytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="destination" Type="Microsoft.Azure.Management.ServiceBus.Models.Destination" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="35050-103">Ein Wert, der angibt, ob die Beschreibung des Capture aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="35050-103">A value that indicates whether capture description is enabled.</span></span> </param>
        <param name="encoding"><span data-ttu-id="35050-104">Listet die möglichen Werte für das Codierungsformat von Capture-Beschreibung an.</span><span class="sxs-lookup"><span data-stu-id="35050-104">Enumerates the possible values for the encoding format of capture description.</span></span> <span data-ttu-id="35050-105">Folgende Werte sind möglich: "Avro", "AvroDeflate"</span><span class="sxs-lookup"><span data-stu-id="35050-105">Possible values include: 'Avro', 'AvroDeflate'</span></span></param>
        <param name="intervalInSeconds"><span data-ttu-id="35050-106">Die Zeitfenster können Sie die Häufigkeit, mit denen die Erfassung des Azure-Blobs ausgeführt, sollte der Wert zwischen 60 und 900 Sekunden, festlegen</span><span class="sxs-lookup"><span data-stu-id="35050-106">The time window allows you to set the frequency with which the capture to Azure Blobs will happen, value should between 60 to 900 seconds</span></span></param>
        <param name="sizeLimitInBytes"><span data-ttu-id="35050-107">Das Fenster der Größe definiert, die Menge der Daten in Ihren Event Hub vor einem Vorgang Capture aufgebaut, Wert muss zwischen 10485760 und 524288000 bytes</span><span class="sxs-lookup"><span data-stu-id="35050-107">The size window defines the amount of data built up in your Event Hub before an capture operation, value should be between 10485760 and 524288000 bytes</span></span></param>
        <param name="destination"><span data-ttu-id="35050-108">Eigenschaften des Ziels, wo Capture gespeichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="35050-108">Properties of Destination where capture will be stored.</span></span> <span data-ttu-id="35050-109">(Speicherkonto, Blob-Namen)</span><span class="sxs-lookup"><span data-stu-id="35050-109">(Storage Account, Blob Names)</span></span></param>
        <summary>
            <span data-ttu-id="35050-110">Initialisiert eine neue Instanz der CaptureDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="35050-110">Initializes a new instance of the CaptureDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.Destination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.Destination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As Destination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.ServiceBus.Models.Destination with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.Destination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35050-111">Ruft ab oder legt die Eigenschaften des Ziels, wo Capture gespeichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="35050-111">Gets or sets properties of Destination where capture will be stored.</span></span> <span data-ttu-id="35050-112">(Speicherkonto, Blob-Namen)</span><span class="sxs-lookup"><span data-stu-id="35050-112">(Storage Account, Blob Names)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35050-113">Ruft ab oder legt einen Wert, der angibt, ob die Beschreibung des Capture aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="35050-113">Gets or sets a value that indicates whether capture description is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As Nullable(Of EncodingCaptureDescription)" />
      <MemberSignature Language="F#" Value="member this.Encoding : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35050-114">Ruft ab oder legt Listet die möglichen Werte für das Codierungsformat von Capture-Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="35050-114">Gets or sets enumerates the possible values for the encoding format of capture description.</span></span> <span data-ttu-id="35050-115">Folgende Werte sind möglich: "Avro", "AvroDeflate"</span><span class="sxs-lookup"><span data-stu-id="35050-115">Possible values include: 'Avro', 'AvroDeflate'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35050-116">Ruft ab oder legt die Zeit Fenster ermöglicht es Ihnen, legen Sie die Häufigkeit, mit denen die Erfassung des Azure-Blobs ausgeführt, sollte der Wert zwischen 60 und 900 Sekunden, fest</span><span class="sxs-lookup"><span data-stu-id="35050-116">Gets or sets the time window allows you to set the frequency with which the capture to Azure Blobs will happen, value should between 60 to 900 seconds</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeLimitInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SizeLimitInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SizeLimitInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.SizeLimitInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeLimitInBytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SizeLimitInBytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.SizeLimitInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeLimitInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35050-117">Ruft ab oder legt die Fenstergröße aufgebaut Datenmenge in Ihren Event Hub vor einem Capture-Vorgang definiert, sollte Wert zwischen 10485760 und 524288000 Bytes sein.</span><span class="sxs-lookup"><span data-stu-id="35050-117">Gets or sets the size window defines the amount of data built up in your Event Hub before an capture operation, value should be between 10485760 and 524288000 bytes</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="captureDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35050-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="35050-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="35050-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="35050-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>