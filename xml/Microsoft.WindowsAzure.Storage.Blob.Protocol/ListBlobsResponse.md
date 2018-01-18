<Type Name="ListBlobsResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse">
  <TypeSignature Language="C#" Value="public sealed class ListBlobsResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlobsResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlobsResponse&#xA;Inherits ResponseParsingBase(Of IListBlobEntry)" />
  <TypeSignature Language="F#" Value="type ListBlobsResponse = class&#xA;    inherit ResponseParsingBase&lt;IListBlobEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="830fc-101">Stellt Methoden zum Analysieren der Antwort Blob-Auflistungsvorgang bereit.</span><span class="sxs-lookup"><span data-stu-id="830fc-101">Provides methods for parsing the response from a blob listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListBlobsResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse stream" />
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
        <param name="stream"><span data-ttu-id="830fc-102">Der Stream, der analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="830fc-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="830fc-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="830fc-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blobs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Blobs As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="member this.Blobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="830fc-104">Ruft eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" /> aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="830fc-104">Gets an enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" /> from the response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-105">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span><span class="sxs-lookup"><span data-stu-id="830fc-105">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
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
            <span data-ttu-id="830fc-106">Ruft den Trennzeichen-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="830fc-106">Gets the Delimiter value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-107">Eine Zeichenfolge mit den Trennzeichen-Wert.</span><span class="sxs-lookup"><span data-stu-id="830fc-107">A string containing the Delimiter value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As BlobListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="830fc-108">Ruft den Kontext für die Auflistung aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="830fc-108">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-109">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="830fc-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
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
            <span data-ttu-id="830fc-110">Ruft den Marker-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="830fc-110">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-111">Eine Zeichenfolge mit den markerwert.</span><span class="sxs-lookup"><span data-stu-id="830fc-111">A string containing the Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
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
            <span data-ttu-id="830fc-112">Ruft den "maxresults"-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="830fc-112">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-113">Eine ganze Zahl, die mit dem Wert "maxresults".</span><span class="sxs-lookup"><span data-stu-id="830fc-113">An integer containing the MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
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
            <span data-ttu-id="830fc-114">Ruft ab oder legt den NextMarker-Wert aus der XML-Antwort, wenn die Auflistung nicht abgeschlossen war.</span><span class="sxs-lookup"><span data-stu-id="830fc-114">Gets or sets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-115">Eine Zeichenfolge, die den NextMarker-Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="830fc-115">A string containing the NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="listBlobsResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="830fc-116">Analysiert das Antwort-XML für ein Blob-Auflistungsvorgang an.</span><span class="sxs-lookup"><span data-stu-id="830fc-116">Parses the response XML for a blob listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="830fc-117">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span><span class="sxs-lookup"><span data-stu-id="830fc-117">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
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
            <span data-ttu-id="830fc-118">Ruft das Präfix Wertanbieter für die Auflistungsvorgang aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="830fc-118">Gets the Prefix value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="830fc-119">Eine Zeichenfolge, die mit dem Präfix-Wert.</span><span class="sxs-lookup"><span data-stu-id="830fc-119">A string containing the Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>