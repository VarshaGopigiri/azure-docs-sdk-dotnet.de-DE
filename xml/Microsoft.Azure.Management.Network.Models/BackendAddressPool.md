<Type Name="BackendAddressPool" FullName="Microsoft.Azure.Management.Network.Models.BackendAddressPool">
  <TypeSignature Language="C#" Value="public class BackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackendAddressPool extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BackendAddressPool" />
  <TypeSignature Language="VB.NET" Value="Public Class BackendAddressPool&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type BackendAddressPool = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f9893-101">Back-End-IP-Adresspool.</span><span class="sxs-lookup"><span data-stu-id="f9893-101">Pool of backend IP addresses.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BackendAddressPool.#ctor" />
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
            <span data-ttu-id="f9893-102">Initialisiert eine neue Instanz der BackendAddressPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f9893-102">Initializes a new instance of the BackendAddressPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPool (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; backendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; loadBalancingRules = null, Microsoft.Azure.Management.Network.Models.SubResource outboundNatRule = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; backendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; loadBalancingRules, class Microsoft.Azure.Management.Network.Models.SubResource outboundNatRule, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BackendAddressPool.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional backendIPConfigurations As IList(Of NetworkInterfaceIPConfiguration) = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional outboundNatRule As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BackendAddressPool : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * Microsoft.Azure.Management.Network.Models.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BackendAddressPool" Usage="new Microsoft.Azure.Management.Network.Models.BackendAddressPool (id, backendIPConfigurations, loadBalancingRules, outboundNatRule, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="backendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="outboundNatRule" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f9893-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="f9893-103">Resource ID.</span></span></param>
        <param name="backendIPConfigurations"><span data-ttu-id="f9893-104">Ruft die Auflistung von Verweisen auf die IP-Adressen im Netzwerkschnittstellen definiert.</span><span class="sxs-lookup"><span data-stu-id="f9893-104">Gets collection of references to IP addresses defined in network interfaces.</span></span></param>
        <param name="loadBalancingRules"><span data-ttu-id="f9893-105">Ruft den Regeln Lastenausgleich, die diesen Back-End-Adresspool verwenden.</span><span class="sxs-lookup"><span data-stu-id="f9893-105">Gets load balancing rules that use this backend address pool.</span></span></param>
        <param name="outboundNatRule"><span data-ttu-id="f9893-106">Ruft die ausgehende Regeln, die diesen Back-End-Adresspool verwenden.</span><span class="sxs-lookup"><span data-stu-id="f9893-106">Gets outbound rules that use this backend address pool.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f9893-107">Abrufen der Bereitstellungsstatus der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="f9893-107">Get provisioning state of the public IP resource.</span></span> <span data-ttu-id="f9893-108">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="f9893-108">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="f9893-109">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="f9893-109">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="f9893-110">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="f9893-110">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="f9893-111">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="f9893-111">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="f9893-112">Initialisiert eine neue Instanz der BackendAddressPool-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f9893-112">Initializes a new instance of the BackendAddressPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; BackendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; BackendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.BackendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfigurations As IList(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.BackendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9893-113">Ruft die Auflistung von Verweisen auf die IP-Adressen im Netzwerkschnittstellen definiert.</span><span class="sxs-lookup"><span data-stu-id="f9893-113">Gets collection of references to IP addresses defined in network interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.Etag" />
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
            <span data-ttu-id="f9893-114">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="f9893-114">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9893-115">Ruft den Regeln Lastenausgleich, die diesen Back-End-Adresspool verwenden.</span><span class="sxs-lookup"><span data-stu-id="f9893-115">Gets load balancing rules that use this backend address pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9893-116">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="f9893-116">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="f9893-117">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="f9893-117">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource OutboundNatRule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource OutboundNatRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.OutboundNatRule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundNatRule As SubResource" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.OutboundNatRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9893-118">Ruft die ausgehende Regeln, die diesen Back-End-Adresspool verwenden.</span><span class="sxs-lookup"><span data-stu-id="f9893-118">Gets outbound rules that use this backend address pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BackendAddressPool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BackendAddressPool.ProvisioningState" />
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
            <span data-ttu-id="f9893-119">Abrufen oder Festlegen der Bereitstellungsstatus der öffentlichen IP-Adressressource Get.</span><span class="sxs-lookup"><span data-stu-id="f9893-119">Gets or sets get provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="f9893-120">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="f9893-120">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>