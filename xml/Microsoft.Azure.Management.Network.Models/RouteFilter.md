<Type Name="RouteFilter" FullName="Microsoft.Azure.Management.Network.Models.RouteFilter">
  <TypeSignature Language="C#" Value="public class RouteFilter : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteFilter extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.RouteFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteFilter&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RouteFilter = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6d8c2-101">Route-Filter-Ressource.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-101">Route Filter Resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.RouteFilter.#ctor" />
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
            <span data-ttu-id="6d8c2-102">Initialisiert eine neue Instanz der Klasse RouteFilter an.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-102">Initializes a new instance of the RouteFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteFilter (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; rules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; peerings = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; rules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; peerings, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.RouteFilter.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.RouteFilterRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional rules As IList(Of RouteFilterRule) = null, Optional peerings As IList(Of ExpressRouteCircuitPeering) = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.RouteFilter : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="new Microsoft.Azure.Management.Network.Models.RouteFilter (id, name, type, location, tags, rules, peerings, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" />
        <Parameter Name="peerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="6d8c2-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="6d8c2-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="6d8c2-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="6d8c2-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="6d8c2-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="6d8c2-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-107">Resource tags.</span></span></param>
        <param name="rules"><span data-ttu-id="6d8c2-108">Die Auflistung von RouteFilterRules innerhalb eines Filters Route enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-108">Collection of RouteFilterRules contained within a route filter.</span></span></param>
        <param name="peerings"><span data-ttu-id="6d8c2-109">Eine Auflistung von Verweisen auf express Route Circuit kann.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-109">A collection of references to express route circuit peerings.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="6d8c2-110">Der Bereitstellungsstatus der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-110">The provisioning state of the resource.</span></span> <span data-ttu-id="6d8c2-111">Mögliche Werte sind: "Aktualisieren", "Löschen", "Succeeded" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="6d8c2-111">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="6d8c2-112">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-112">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="6d8c2-113">Initialisiert eine neue Instanz der Klasse RouteFilter an.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-113">Initializes a new instance of the RouteFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteFilter.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Models.RouteFilter.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d8c2-114">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-114">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; Peerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; Peerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteFilter.Peerings" />
      <MemberSignature Language="VB.NET" Value="Public Property Peerings As IList(Of ExpressRouteCircuitPeering)" />
      <MemberSignature Language="F#" Value="member this.Peerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteFilter.Peerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d8c2-115">Ruft ab oder legt eine Auflistung von Verweisen auf express Route Circuit kann.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-115">Gets or sets a collection of references to express route circuit peerings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteFilter.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.RouteFilter.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d8c2-116">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-116">Gets the provisioning state of the resource.</span></span> <span data-ttu-id="6d8c2-117">Mögliche Werte sind: "Aktualisieren", "Löschen", "Succeeded" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="6d8c2-117">Possible values are: 'Updating', 'Deleting', 'Succeeded' and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.RouteFilter.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of RouteFilterRule)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.RouteFilter.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d8c2-118">Abrufen oder Festlegen der Auflistung von RouteFilterRules innerhalb eines Filters Route enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="6d8c2-118">Gets or sets collection of RouteFilterRules contained within a route filter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>