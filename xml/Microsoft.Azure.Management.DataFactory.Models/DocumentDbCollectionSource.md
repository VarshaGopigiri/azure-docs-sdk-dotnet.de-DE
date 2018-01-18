<Type Name="DocumentDbCollectionSource" FullName="Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource">
  <TypeSignature Language="C#" Value="public class DocumentDbCollectionSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentDbCollectionSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentDbCollectionSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type DocumentDbCollectionSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf6fd-101">Kopieren-Aktivität Dokument Datenbanksammlung Quelle.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-101">A copy activity Document Database Collection source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbCollectionSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.#ctor" />
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
            <span data-ttu-id="cf6fd-102">Initialisiert eine neue Instanz der DocumentDbCollectionSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-102">Initializes a new instance of the DocumentDbCollectionSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbCollectionSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null, object nestingSeparator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query, object nestingSeparator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional query As Object = null, Optional nestingSeparator As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource (additionalProperties, sourceRetryCount, sourceRetryWait, query, nestingSeparator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
        <Parameter Name="nestingSeparator" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="cf6fd-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="cf6fd-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="cf6fd-104">Anzahl von Wiederholungsversuchen Quelle.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-104">Source retry count.</span></span> <span data-ttu-id="cf6fd-105">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="cf6fd-106">Warten Sie Quelle, versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-106">Source retry wait.</span></span> <span data-ttu-id="cf6fd-107">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="query"><span data-ttu-id="cf6fd-108">Dokumente-Abfrage.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-108">Documents query.</span></span> <span data-ttu-id="cf6fd-109">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="nestingSeparator"><span data-ttu-id="cf6fd-110">Trennzeichen für geschachtelte Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-110">Nested properties separator.</span></span> <span data-ttu-id="cf6fd-111">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-111">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="cf6fd-112">Initialisiert eine neue Instanz der DocumentDbCollectionSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-112">Initializes a new instance of the DocumentDbCollectionSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public object NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As Object" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nestingSeparator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf6fd-113">Ruft ab, oder legt ihn fest geschachtelte Eigenschaften Trennzeichen.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-113">Gets or sets nested properties separator.</span></span> <span data-ttu-id="cf6fd-114">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-114">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DocumentDbCollectionSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf6fd-115">Ruft ab, oder legt ihn fest Dokumente Abfrage.</span><span class="sxs-lookup"><span data-stu-id="cf6fd-115">Gets or sets documents query.</span></span> <span data-ttu-id="cf6fd-116">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="cf6fd-116">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>