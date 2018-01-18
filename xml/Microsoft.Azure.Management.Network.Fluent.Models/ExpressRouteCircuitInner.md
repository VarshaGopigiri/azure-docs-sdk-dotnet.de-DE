<Type Name="ExpressRouteCircuitInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2395e-101">ExpressRouteCircuit-Ressource</span><span class="sxs-lookup"><span data-stu-id="2395e-101">ExpressRouteCircuit resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2395e-102">Initialisiert eine neue Instanz der ExpressRouteCircuitInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2395e-102">Initializes a new instance of the ExpressRouteCircuitInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku sku = null, Nullable&lt;bool&gt; allowClassicOperations = null, string circuitProvisioningState = null, string serviceProviderProvisioningState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; authorizations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; peerings = null, string serviceKey = null, string serviceProviderNotes = null, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties serviceProviderProperties = null, string provisioningState = null, string gatewayManagerEtag = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku sku, valuetype System.Nullable`1&lt;bool&gt; allowClassicOperations, string circuitProvisioningState, string serviceProviderProvisioningState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; authorizations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; peerings, string serviceKey, string serviceProviderNotes, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties serviceProviderProperties, string provisioningState, string gatewayManagerEtag, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku,System.Nullable{System.Boolean},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner},System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As ExpressRouteCircuitSku = null, Optional allowClassicOperations As Nullable(Of Boolean) = null, Optional circuitProvisioningState As String = null, Optional serviceProviderProvisioningState As String = null, Optional authorizations As IList(Of ExpressRouteCircuitAuthorizationInner) = null, Optional peerings As IList(Of ExpressRouteCircuitPeeringInner) = null, Optional serviceKey As String = null, Optional serviceProviderNotes As String = null, Optional serviceProviderProperties As ExpressRouteCircuitServiceProviderProperties = null, Optional provisioningState As String = null, Optional gatewayManagerEtag As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku * Nullable&lt;bool&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner (location, id, name, type, tags, sku, allowClassicOperations, circuitProvisioningState, serviceProviderProvisioningState, authorizations, peerings, serviceKey, serviceProviderNotes, serviceProviderProperties, provisioningState, gatewayManagerEtag, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku" />
        <Parameter Name="allowClassicOperations" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="circuitProvisioningState" Type="System.String" />
        <Parameter Name="serviceProviderProvisioningState" Type="System.String" />
        <Parameter Name="authorizations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" />
        <Parameter Name="peerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;" />
        <Parameter Name="serviceKey" Type="System.String" />
        <Parameter Name="serviceProviderNotes" Type="System.String" />
        <Parameter Name="serviceProviderProperties" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="gatewayManagerEtag" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku"><span data-ttu-id="2395e-103">Die SKU.</span><span class="sxs-lookup"><span data-stu-id="2395e-103">The SKU.</span></span></param>
        <param name="allowClassicOperations"><span data-ttu-id="2395e-104">Klassische Vorgänge zulässig sind</span><span class="sxs-lookup"><span data-stu-id="2395e-104">Allow classic operations</span></span></param>
        <param name="circuitProvisioningState"><span data-ttu-id="2395e-105">Der Schaltkreisbereitstellungsstatus Zustand der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2395e-105">The CircuitProvisioningState state of the resource.</span></span></param>
        <param name="serviceProviderProvisioningState"><span data-ttu-id="2395e-106">Der ServiceProviderProvisioningState Zustand der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2395e-106">The ServiceProviderProvisioningState state of the resource.</span></span> <span data-ttu-id="2395e-107">Mögliche Werte sind "Nicht bereitgestellt", "Wird bereitgestellt", "Bereitgestellt" und "Aufhebens der Bereitstellung".</span><span class="sxs-lookup"><span data-stu-id="2395e-107">Possible values are 'NotProvisioned', 'Provisioning', 'Provisioned', and 'Deprovisioning'.</span></span> <span data-ttu-id="2395e-108">Folgende Werte sind möglich: "Nicht bereitgestellt", "Wird bereitgestellt", "Bereitgestellt", "Aufhebens der Bereitstellung"</span><span class="sxs-lookup"><span data-stu-id="2395e-108">Possible values include: 'NotProvisioned', 'Provisioning', 'Provisioned', 'Deprovisioning'</span></span></param>
        <param name="authorizations"><span data-ttu-id="2395e-109">Die Liste der autorisierungen.</span><span class="sxs-lookup"><span data-stu-id="2395e-109">The list of authorizations.</span></span></param>
        <param name="peerings"><span data-ttu-id="2395e-110">Die Liste der kann.</span><span class="sxs-lookup"><span data-stu-id="2395e-110">The list of peerings.</span></span></param>
        <param name="serviceKey"><span data-ttu-id="2395e-111">ServiceKey.</span><span class="sxs-lookup"><span data-stu-id="2395e-111">The ServiceKey.</span></span></param>
        <param name="serviceProviderNotes"><span data-ttu-id="2395e-112">Die ServiceProviderNotes.</span><span class="sxs-lookup"><span data-stu-id="2395e-112">The ServiceProviderNotes.</span></span></param>
        <param name="serviceProviderProperties"><span data-ttu-id="2395e-113">Die ServiceProviderProperties.</span><span class="sxs-lookup"><span data-stu-id="2395e-113">The ServiceProviderProperties.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="2395e-114">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="2395e-114">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="2395e-115">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="2395e-115">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="gatewayManagerEtag"><span data-ttu-id="2395e-116">Das GatewayManager Etag.</span><span class="sxs-lookup"><span data-stu-id="2395e-116">The GatewayManager Etag.</span></span></param>
        <param name="etag"><span data-ttu-id="2395e-117">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="2395e-117">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="2395e-118">Initialisiert eine neue Instanz der ExpressRouteCircuitInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2395e-118">Initializes a new instance of the ExpressRouteCircuitInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowClassicOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowClassicOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowClassicOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.AllowClassicOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowClassicOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowClassicOperations : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.AllowClassicOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowClassicOperations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-119">Ruft ab oder legt sie fest, klassische Vorgänge zulassen</span><span class="sxs-lookup"><span data-stu-id="2395e-119">Gets or sets allow classic operations</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorizations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; Authorizations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; Authorizations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Authorizations" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorizations As IList(Of ExpressRouteCircuitAuthorizationInner)" />
      <MemberSignature Language="F#" Value="member this.Authorizations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Authorizations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-120">Ruft ab oder legt die Liste der autorisierungen.</span><span class="sxs-lookup"><span data-stu-id="2395e-120">Gets or sets the list of authorizations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CircuitProvisioningState">
      <MemberSignature Language="C#" Value="public string CircuitProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CircuitProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.CircuitProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property CircuitProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.CircuitProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.CircuitProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.circuitProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-121">Abrufen oder Festlegen der Schaltkreisbereitstellungsstatus Zustand der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2395e-121">Gets or sets the CircuitProvisioningState state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2395e-122">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="2395e-122">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayManagerEtag">
      <MemberSignature Language="C#" Value="public string GatewayManagerEtag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayManagerEtag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.GatewayManagerEtag" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayManagerEtag As String" />
      <MemberSignature Language="F#" Value="member this.GatewayManagerEtag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.GatewayManagerEtag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayManagerEtag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-123">Ruft ab oder legt das GatewayManager Etag fest.</span><span class="sxs-lookup"><span data-stu-id="2395e-123">Gets or sets the GatewayManager Etag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; Peerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; Peerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Peerings" />
      <MemberSignature Language="VB.NET" Value="Public Property Peerings As IList(Of ExpressRouteCircuitPeeringInner)" />
      <MemberSignature Language="F#" Value="member this.Peerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Peerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-124">Ruft ab oder legt die Liste der kann.</span><span class="sxs-lookup"><span data-stu-id="2395e-124">Gets or sets the list of peerings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="2395e-125">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="2395e-125">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="2395e-126">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="2395e-126">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKey">
      <MemberSignature Language="C#" Value="public string ServiceKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceKey As String" />
      <MemberSignature Language="F#" Value="member this.ServiceKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-127">Ruft ab oder legt die ServiceKey.</span><span class="sxs-lookup"><span data-stu-id="2395e-127">Gets or sets the ServiceKey.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceProviderNotes">
      <MemberSignature Language="C#" Value="public string ServiceProviderNotes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceProviderNotes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderNotes" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceProviderNotes As String" />
      <MemberSignature Language="F#" Value="member this.ServiceProviderNotes : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderNotes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceProviderNotes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-128">Ruft ab oder legt die ServiceProviderNotes.</span><span class="sxs-lookup"><span data-stu-id="2395e-128">Gets or sets the ServiceProviderNotes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceProviderProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties ServiceProviderProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties ServiceProviderProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceProviderProperties As ExpressRouteCircuitServiceProviderProperties" />
      <MemberSignature Language="F#" Value="member this.ServiceProviderProperties : Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceProviderProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitServiceProviderProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-129">Ruft ab oder legt die ServiceProviderProperties.</span><span class="sxs-lookup"><span data-stu-id="2395e-129">Gets or sets the ServiceProviderProperties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceProviderProvisioningState">
      <MemberSignature Language="C#" Value="public string ServiceProviderProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceProviderProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceProviderProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ServiceProviderProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.ServiceProviderProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceProviderProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-130">Ruft ab oder legt die ServiceProviderProvisioningState Zustand der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2395e-130">Gets or sets the ServiceProviderProvisioningState state of the resource.</span></span> <span data-ttu-id="2395e-131">Mögliche Werte sind "Nicht bereitgestellt", "Wird bereitgestellt", "Bereitgestellt" und "Aufhebens der Bereitstellung".</span><span class="sxs-lookup"><span data-stu-id="2395e-131">Possible values are 'NotProvisioned', 'Provisioning', 'Provisioned', and 'Deprovisioning'.</span></span> <span data-ttu-id="2395e-132">Folgende Werte sind möglich: "Nicht bereitgestellt", "Wird bereitgestellt", "Bereitgestellt", "Aufhebens der Bereitstellung"</span><span class="sxs-lookup"><span data-stu-id="2395e-132">Possible values include: 'NotProvisioned', 'Provisioning', 'Provisioned', 'Deprovisioning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As ExpressRouteCircuitSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2395e-133">Ruft ab oder legt die SKU.</span><span class="sxs-lookup"><span data-stu-id="2395e-133">Gets or sets the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>