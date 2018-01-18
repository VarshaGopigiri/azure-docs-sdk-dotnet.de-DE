<Type Name="ListContainersResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse">
  <TypeSignature Language="C#" Value="public sealed class ListContainersResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListContainersResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListContainersResponse&#xA;Inherits ResponseParsingBase(Of BlobContainerEntry)" />
  <TypeSignature Language="F#" Value="type ListContainersResponse = class&#xA;    inherit ResponseParsingBase&lt;BlobContainerEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c2e8-101">Stellt Methoden zum Analysieren der Antwort ein containerauflistungsvorgang bereit.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-101">Provides methods for parsing the response from a container listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListContainersResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="1c2e8-102">Der Stream, der analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="1c2e8-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Containers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt; Containers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt; Containers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Containers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Containers As IEnumerable(Of BlobContainerEntry)" />
      <MemberSignature Language="F#" Value="member this.Containers : seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Containers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-104">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> Objekte aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-104">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-105">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-105">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As ListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-106">Ruft den Kontext für die Auflistung aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-106">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-107">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.ListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-107">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.ListingContext" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-108">Ruft den Marker-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-108">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-109">Eine Zeichenfolge mit den markerwert.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-109">A string containing the Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-110">Ruft den "maxresults"-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-110">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-111">Eine ganze Zahl, die mit dem Wert "maxresults".</span><span class="sxs-lookup"><span data-stu-id="1c2e8-111">An integer containing the MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-112">Ruft ab oder legt den NextMarker-Wert aus der XML-Antwort, wenn die Auflistung nicht abgeschlossen war.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-112">Gets or sets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-113">Eine Zeichenfolge, die den NextMarker-Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-113">A string containing the NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of BlobContainerEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;" Usage="listContainersResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-114">Analysiert das Antwort-XML für ein containerauflistungsvorgang an.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-114">Parses the response XML for a container listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="1c2e8-115">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-115">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobContainerEntry" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListContainersResponse.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c2e8-116">Ruft das Präfix Wertanbieter für die Auflistungsvorgang aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-116">Gets the Prefix value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="1c2e8-117">Eine Zeichenfolge, die mit dem Präfix-Wert.</span><span class="sxs-lookup"><span data-stu-id="1c2e8-117">A string containing the Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>