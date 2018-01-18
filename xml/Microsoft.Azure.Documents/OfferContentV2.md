<Type Name="OfferContentV2" FullName="Microsoft.Azure.Documents.OfferContentV2">
  <TypeSignature Language="C#" Value="public sealed class OfferContentV2 : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OfferContentV2 extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.OfferContentV2" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OfferContentV2&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type OfferContentV2 = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c22d-101">Stellt die Content-Eigenschaften in den Standard-Tarif für den Azure-Cosmos-DB-Dienst gebunden.</span><span class="sxs-lookup"><span data-stu-id="5c22d-101">Represents content properties tied to the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferContentV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferContentV2.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c22d-102">Standardkonstruktor</span><span class="sxs-lookup"><span data-stu-id="5c22d-102">Default constructor.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5c22d-103">Die <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> stellt Inhalt Eigenschaften, die an der Standardpreisstufe für den Azure-Cosmos-DB-Dienst gebunden sind.</span><span class="sxs-lookup"><span data-stu-id="5c22d-103">The <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> class represents content properties tied to the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferContentV2 (int offerThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 offerThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferContentV2.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offerThroughput As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferContentV2 : int -&gt; Microsoft.Azure.Documents.OfferContentV2" Usage="new Microsoft.Azure.Documents.OfferContentV2 offerThroughput" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offerThroughput" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="offerThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="5c22d-104">Konstruktor akzeptiert Angebot Durchsatz.</span><span class="sxs-lookup"><span data-stu-id="5c22d-104">Constructor accepting offer throughput.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5c22d-105">Die <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> stellt Inhalt Eigenschaften, die an der Standardpreisstufe für den Azure-Cosmos-DB-Dienst gebunden sind.</span><span class="sxs-lookup"><span data-stu-id="5c22d-105">The <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> class represents content properties tied to the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OfferContentV2 (int offerThroughput, Nullable&lt;bool&gt; offerEnableRUPerMinuteThroughput);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 offerThroughput, valuetype System.Nullable`1&lt;bool&gt; offerEnableRUPerMinuteThroughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.OfferContentV2.#ctor(System.Int32,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (offerThroughput As Integer, offerEnableRUPerMinuteThroughput As Nullable(Of Boolean))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.OfferContentV2 : int * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Documents.OfferContentV2" Usage="new Microsoft.Azure.Documents.OfferContentV2 (offerThroughput, offerEnableRUPerMinuteThroughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="offerThroughput" Type="System.Int32" />
        <Parameter Name="offerEnableRUPerMinuteThroughput" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="offerThroughput">To be added.</param>
        <param name="offerEnableRUPerMinuteThroughput">To be added.</param>
        <summary>
            <span data-ttu-id="5c22d-106">Konstruktor akzeptiert bieten, Durchsatz und anfordern Einheiten (RU) / Minute Durchsatz aktiviert oder deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="5c22d-106">Constructor accepting offer throughput and Request Units(RU)/Minute throughput is enabled or disabled.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5c22d-107">Die <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> stellt Inhalt Eigenschaften, die an der Standardpreisstufe für den Azure-Cosmos-DB-Dienst gebunden sind.</span><span class="sxs-lookup"><span data-stu-id="5c22d-107">The <see cref="T:Microsoft.Azure.Documents.OfferContentV2" /> class represents content properties tied to the Standard pricing tier for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OfferIsRUPerMinuteThroughputEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OfferIsRUPerMinuteThroughputEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OfferIsRUPerMinuteThroughputEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.OfferContentV2.OfferIsRUPerMinuteThroughputEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OfferIsRUPerMinuteThroughputEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OfferIsRUPerMinuteThroughputEnabled : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Documents.OfferContentV2.OfferIsRUPerMinuteThroughputEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="offerIsRUPerMinuteThroughputEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c22d-108">Anfordern von Einheiten (RU) stellt / Minute Durchsatz wird aktiviert oder deaktiviert für die Auflistung in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="5c22d-108">Represents Request Units(RU)/Minute throughput is enabled/disabled for collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OfferThroughput">
      <MemberSignature Language="C#" Value="public int OfferThroughput { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OfferThroughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.OfferContentV2.OfferThroughput" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OfferThroughput As Integer" />
      <MemberSignature Language="F#" Value="member this.OfferThroughput : int" Usage="Microsoft.Azure.Documents.OfferContentV2.OfferThroughput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, PropertyName="offerThroughput")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c22d-109">Stellt anpassbare Durchsatz, die vom Benutzer für seine Auflistung in der Azure-Cosmos-DB-Dienst ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="5c22d-109">Represents customizable throughput chosen by user for his collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>