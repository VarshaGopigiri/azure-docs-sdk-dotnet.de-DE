<Type Name="LoadBalancerInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner">
  <TypeSignature Language="C#" Value="public class LoadBalancerInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancerInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancerInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LoadBalancerInner = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="9a3d6-101">LoadBalancer-Ressource</span><span class="sxs-lookup"><span data-stu-id="9a3d6-101">LoadBalancer resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancerInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-102">Initialisiert eine neue Instanz der LoadBalancerInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-102">Initializes a new instance of the LoadBalancerInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancerInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku sku = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; loadBalancingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; inboundNatRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; inboundNatPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; outboundNatRules = null, string resourceGuid = null, string provisioningState = null, string etag = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; loadBalancingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; inboundNatRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; inboundNatPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; outboundNatRules, string resourceGuid, string provisioningState, string etag, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner},System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As LoadBalancerSku = null, Optional frontendIPConfigurations As IList(Of FrontendIPConfigurationInner) = null, Optional backendAddressPools As IList(Of BackendAddressPoolInner) = null, Optional loadBalancingRules As IList(Of LoadBalancingRuleInner) = null, Optional probes As IList(Of ProbeInner) = null, Optional inboundNatRules As IList(Of InboundNatRuleInner) = null, Optional inboundNatPools As IList(Of InboundNatPoolInner) = null, Optional outboundNatRules As IList(Of OutboundNatRuleInner) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null, Optional zones As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner (location, id, name, type, tags, sku, frontendIPConfigurations, backendAddressPools, loadBalancingRules, probes, inboundNatRules, inboundNatPools, outboundNatRules, resourceGuid, provisioningState, etag, zones)" />
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
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;" />
        <Parameter Name="inboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;" />
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt;" />
        <Parameter Name="outboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="frontendIPConfigurations">To be added.</param>
        <param name="backendAddressPools">To be added.</param>
        <param name="loadBalancingRules">To be added.</param>
        <param name="probes">To be added.</param>
        <param name="inboundNatRules">To be added.</param>
        <param name="inboundNatPools">To be added.</param>
        <param name="outboundNatRules">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <param name="zones">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of BackendAddressPoolInner)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.BackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-103">Ruft ab oder legt die Auflistung von Back-End-Adresspools, die von einem Lastenausgleich verwendet</span><span class="sxs-lookup"><span data-stu-id="9a3d6-103">Gets or sets collection of backend address pools used by a load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Etag" />
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
            <span data-ttu-id="9a3d6-104">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-104">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of FrontendIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-105">Ruft ab oder legt ihn fest-Objekt, das Front-End-IP-Adressen für den Lastenausgleich zu verwendende darstellt</span><span class="sxs-lookup"><span data-stu-id="9a3d6-105">Gets or sets object representing the frontend IPs to be used for the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPoolInner)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatPoolInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-106">Ruft ab oder legt ihn fest definiert einen externe Portbereich für eingehenden NAT-Datenverkehr an einen einzelnen Back-End-Port für NICs, die einem Lastenausgleichsmodul zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-106">Gets or sets defines an external port range for inbound NAT to a single backend port on NICs associated with a load balancer.</span></span>
            <span data-ttu-id="9a3d6-107">Eingehende NAT-Regeln werden für jede Netzwerkkarte, die das Lastenausgleichsmodul mit einer externen Port aus diesem Bereich zugeordneten automatisch erstellt.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-107">Inbound NAT rules are created automatically for each NIC associated with the Load Balancer using an external port from this range.</span></span>
            <span data-ttu-id="9a3d6-108">Definieren einen eingehende NAT-Pool für Ihr Lastenausgleichsmodul wird sich gegenseitig ausschließende mit Nat-Eingangsregeln definieren.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-108">Defining an Inbound NAT pool on your Load Balancer is mutually exclusive with defining inbound Nat rules.</span></span> <span data-ttu-id="9a3d6-109">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-109">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="9a3d6-110">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehenden NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-110">NICs that are associated with individual virtual machines cannot reference an inbound NAT pool.</span></span> <span data-ttu-id="9a3d6-111">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-111">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; InboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatRules As IList(Of InboundNatRuleInner)" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-112">Abrufen oder Festlegen der Auflistung der eingehenden NAT-Regeln, die von einem Lastenausgleich verwendet.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-112">Gets or sets collection of inbound NAT Rules used by a load balancer.</span></span> <span data-ttu-id="9a3d6-113">Definieren von NAT-Eingangsregeln für Ihr Lastenausgleichsmodul wird mit der Definition eines eingehenden NAT-Pools sich gegenseitig ausschließende.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-113">Defining inbound NAT rules on your load balancer is mutually exclusive with defining an inbound NAT pool.</span></span> <span data-ttu-id="9a3d6-114">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-114">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="9a3d6-115">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehende NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-115">NICs that are associated with individual virtual machines cannot reference an Inbound NAT pool.</span></span> <span data-ttu-id="9a3d6-116">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-116">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; LoadBalancingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancingRules As IList(Of LoadBalancingRuleInner)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-117">Ruft ab oder legt eine objektauflistung, die den Lastenausgleich Regeln ruft darstellt, die Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="9a3d6-117">Gets or sets object collection representing the load balancing rules Gets the provisioning</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; OutboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; OutboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.OutboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property OutboundNatRules As IList(Of OutboundNatRuleInner)" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.OutboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.OutboundNatRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-118">Ruft ab oder legt die Regeln für ausgehenden NAT.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-118">Gets or sets the outbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of ProbeInner)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-119">Ruft ab oder legt die Auflistung von Testobjekten, die in der Load Balancer verwendet</span><span class="sxs-lookup"><span data-stu-id="9a3d6-119">Gets or sets collection of probe objects used in the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ProvisioningState" />
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
            <span data-ttu-id="9a3d6-120">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-120">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="9a3d6-121">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="9a3d6-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a3d6-122">Abrufen oder festlegen die Ressource die lastenausgleichsressource GUID-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="9a3d6-122">Gets or sets the resource GUID property of the load balancer resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As LoadBalancerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>