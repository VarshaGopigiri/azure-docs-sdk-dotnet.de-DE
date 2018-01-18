<Type Name="Polygon" FullName="Microsoft.Azure.Documents.Spatial.Polygon">
  <TypeSignature Language="C#" Value="public sealed class Polygon : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Polygon extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Polygon" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Polygon&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Polygon)" />
  <TypeSignature Language="F#" Value="type Polygon = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Polygon&gt;" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Geometry</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="b2b2d-101">Polygon-Geometry-Klasse in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-101">Polygon geometry class in the Azure Cosmos DB service.</span></span>
            </para>
      <para>
            <span data-ttu-id="b2b2d-102">Ein Polygon wird durch die Menge der "Polygon-Ringe" dargestellt.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-102">A polygon is represented by the set of "polygon rings".</span></span> <span data-ttu-id="b2b2d-103">Jeder Ring wird geschlossen, Zeile Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-103">Each ring is closed line string.</span></span>
            <span data-ttu-id="b2b2d-104">Erste Ring definiert externe Ring betrachtet.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-104">First ring defines external ring.</span></span> <span data-ttu-id="b2b2d-105">Alle nachfolgenden Ringe definieren "Löcher" in der externe Ring betrachtet.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-105">All subsequent rings define "holes" in the external ring.</span></span>
            </para>
      <para>
            <span data-ttu-id="b2b2d-106">Ringe müssen angegeben werden, mit der linken Regel: Durchlaufen des Rings in der Reihenfolge seiner Punkte sollten dazu führen, interne Fläche des Polygons wird auf der linken Seite.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-106">Rings must be specified using Left Hand Rule: traversing the ring in the order of its points, should result in internal area of the polygon being to the left side.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="b2b2d-107">In diesem Beispiel wird gezeigt, wie ein Polygon definieren, die kleine Teilmenge der Erde behandelt werden:</span><span class="sxs-lookup"><span data-stu-id="b2b2d-107">This example shows how to define a polygon which covers small portion of the Earth:</span></span>
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
                    new[]
                    {
                        new Position(20.0, 20.0),
                        new Position(30.0, 20.0),
                        new Position(30.0, 30.0),
                        new Position(20.0, 30.0)
                        new Position(20.0, 20.0)
                    });
            ]]></code></example>
    <example>
            <span data-ttu-id="b2b2d-108">In diesem Beispiel wird gezeigt, wie ein Polygon definieren, die Bereich umfasst mehr als eine Hemisphäre: (Beachten Sie, dass nur die Reihenfolge von Koordinaten umgekehrt wurde).</span><span class="sxs-lookup"><span data-stu-id="b2b2d-108">This example shows how to define a polygon which covers area more than one hemisphere: (Notice that only order of coordinates was reversed).</span></span>
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
            new[]
                    {
                    new Position(20.0, 20.0),
                        new Position(20.0, 30.0),
                        new Position(30.0, 30.0),
                        new Position(30.0, 20.0)
                        new Position(20.0, 20.0)
                        });
                    ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rings As IList(Of LinearRing))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon rings" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
      </Parameters>
      <Docs>
        <param name="rings">
          <para>
            <span data-ttu-id="b2b2d-109">Polygon-Ringe.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-109">Polygon rings.</span></span>
            </para>
          <para>
            <span data-ttu-id="b2b2d-110">Erste Ring ist externe Ring betrachtet.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-110">First ring is external ring.</span></span> <span data-ttu-id="b2b2d-111">Folgende Ringe definieren "Löcher" in den Polygon-.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-111">Following rings define 'holes' in the polygon.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="b2b2d-112">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-112">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (externalRingPositions As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon externalRingPositions" />
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
        <Parameter Name="externalRingPositions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="externalRingPositions">
            <span data-ttu-id="b2b2d-113">Externe Ring polygonkoordinaten.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-113">External polygon ring coordinates.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b2d-114">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> -Klasse, aus der externe Ring betrachtet (Polygons enthält keine Lücken) im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class, from external ring (the polygon contains no holes) in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing},Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon (rings, geometryParams)" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="rings">
            <span data-ttu-id="b2b2d-115">Polygon-Ringe.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-115">Polygon rings.</span></span>
            </param>
        <param name="geometryParams">
            <span data-ttu-id="b2b2d-116">Zusätzliche Geometry-Parameter.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-116">Additional geometry parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b2b2d-117">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-117">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Polygon other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Polygon other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(Microsoft.Azure.Documents.Spatial.Polygon)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Polygon) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Polygon -&gt; bool" Usage="polygon.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
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
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Polygon" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="b2b2d-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />zu vergleichende <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span></span></param>
        <summary>
            <span data-ttu-id="b2b2d-119">Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> ist gleich der <paramref name="other" /> im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-119">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> is equal to the <paramref name="other" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="b2b2d-120"><c>"true"</c> Wenn die Objekte gleich sind.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-120"><c>true</c> if objects are equal.</span></span> <span data-ttu-id="b2b2d-121"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-121"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="polygon.Equals obj" />
      <MemberType>Method</MemberType>
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
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="b2b2d-122">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-122">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="b2b2d-123">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-123">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2b2d-124">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="b2b2d-124">true if the specified object is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="polygon.GetHashCode " />
      <MemberType>Method</MemberType>
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
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2b2d-125">Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Typ im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-125">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> type in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b2b2d-126">Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-126">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rings As ReadOnlyCollection(Of LinearRing)" />
      <MemberSignature Language="F#" Value="member this.Rings : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" Usage="Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty("coordinates", Order=1, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2b2d-127">Ruft die Polygon-Ringe in der Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-127">Gets the polygon rings in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b2b2d-128">Polygon-Ringe.</span><span class="sxs-lookup"><span data-stu-id="b2b2d-128">Polygon rings.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>