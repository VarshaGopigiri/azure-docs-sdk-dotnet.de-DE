<Type Name="VirtualNetworkGatewayConnectionInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGatewayConnectionInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGatewayConnectionInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGatewayConnectionInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnectionInner = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="998b6-101">Eine allgemeine Klasse für allgemeine Ressourceninformationen</span><span class="sxs-lookup"><span data-stu-id="998b6-101">A common class for general resource information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewayConnectionInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="998b6-102">Initialisiert eine neue Instanz der VirtualNetworkGatewayConnectionInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="998b6-102">Initializes a new instance of the VirtualNetworkGatewayConnectionInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewayConnectionInner (Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualNetworkGateway1, string connectionType, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string authorizationKey = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualNetworkGateway2 = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource localNetworkGateway2 = null, Nullable&lt;int&gt; routingWeight = null, string sharedKey = null, string connectionStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt; tunnelConnectionStatus = null, Nullable&lt;long&gt; egressBytesTransferred = null, Nullable&lt;long&gt; ingressBytesTransferred = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource peer = null, Nullable&lt;bool&gt; enableBgp = null, Nullable&lt;bool&gt; usePolicyBasedTrafficSelectors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; ipsecPolicies = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualNetworkGateway1, string connectionType, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string authorizationKey, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualNetworkGateway2, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource localNetworkGateway2, valuetype System.Nullable`1&lt;int32&gt; routingWeight, string sharedKey, string connectionStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt; tunnelConnectionStatus, valuetype System.Nullable`1&lt;int64&gt; egressBytesTransferred, valuetype System.Nullable`1&lt;int64&gt; ingressBytesTransferred, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource peer, valuetype System.Nullable`1&lt;bool&gt; enableBgp, valuetype System.Nullable`1&lt;bool&gt; usePolicyBasedTrafficSelectors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; ipsecPolicies, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (virtualNetworkGateway1 As SubResource, connectionType As String, Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional authorizationKey As String = null, Optional virtualNetworkGateway2 As SubResource = null, Optional localNetworkGateway2 As SubResource = null, Optional routingWeight As Nullable(Of Integer) = null, Optional sharedKey As String = null, Optional connectionStatus As String = null, Optional tunnelConnectionStatus As IList(Of TunnelConnectionHealth) = null, Optional egressBytesTransferred As Nullable(Of Long) = null, Optional ingressBytesTransferred As Nullable(Of Long) = null, Optional peer As SubResource = null, Optional enableBgp As Nullable(Of Boolean) = null, Optional usePolicyBasedTrafficSelectors As Nullable(Of Boolean) = null, Optional ipsecPolicies As IList(Of IpsecPolicy) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Nullable&lt;int&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner (virtualNetworkGateway1, connectionType, location, id, name, type, tags, authorizationKey, virtualNetworkGateway2, localNetworkGateway2, routingWeight, sharedKey, connectionStatus, tunnelConnectionStatus, egressBytesTransferred, ingressBytesTransferred, peer, enableBgp, usePolicyBasedTrafficSelectors, ipsecPolicies, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="virtualNetworkGateway1" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="connectionType" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="authorizationKey" Type="System.String" />
        <Parameter Name="virtualNetworkGateway2" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="localNetworkGateway2" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="routingWeight" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sharedKey" Type="System.String" />
        <Parameter Name="connectionStatus" Type="System.String" />
        <Parameter Name="tunnelConnectionStatus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt;" />
        <Parameter Name="egressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="ingressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="peer" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="enableBgp" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="usePolicyBasedTrafficSelectors" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ipsecPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualNetworkGateway1">To be added.</param>
        <param name="connectionType">To be added.</param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="authorizationKey">To be added.</param>
        <param name="virtualNetworkGateway2">To be added.</param>
        <param name="localNetworkGateway2">To be added.</param>
        <param name="routingWeight">To be added.</param>
        <param name="sharedKey">To be added.</param>
        <param name="connectionStatus">To be added.</param>
        <param name="tunnelConnectionStatus">To be added.</param>
        <param name="egressBytesTransferred">To be added.</param>
        <param name="ingressBytesTransferred">To be added.</param>
        <param name="peer">To be added.</param>
        <param name="enableBgp">To be added.</param>
        <param name="usePolicyBasedTrafficSelectors">To be added.</param>
        <param name="ipsecPolicies">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationKey">
      <MemberSignature Language="C#" Value="public string AuthorizationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.AuthorizationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationKey As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.AuthorizationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-103">Ruft ab oder legt die AuthorizationKey.</span><span class="sxs-lookup"><span data-stu-id="998b6-103">Gets or sets the authorizationKey.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStatus">
      <MemberSignature Language="C#" Value="public string ConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStatus : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-104">Ruft virtuelle Netzwerk-Gateway-Verbindungsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="998b6-104">Gets virtual network Gateway connection status.</span></span> <span data-ttu-id="998b6-105">Mögliche Werte sind "Unknown", "Verbinden", "Verbunden" und "NotConnected".</span><span class="sxs-lookup"><span data-stu-id="998b6-105">Possible values are 'Unknown', 'Connecting', 'Connected' and 'NotConnected'.</span></span> <span data-ttu-id="998b6-106">Folgende Werte sind möglich: "Unknown", "Verbinden", "Verbunden", "NotConnected"</span><span class="sxs-lookup"><span data-stu-id="998b6-106">Possible values include: 'Unknown', 'Connecting', 'Connected', 'NotConnected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionType">
      <MemberSignature Language="C#" Value="public string ConnectionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ConnectionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionType As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ConnectionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-107">Ruft ab oder legt ihn fest Gateway Verbindung.</span><span class="sxs-lookup"><span data-stu-id="998b6-107">Gets or sets gateway connection type.</span></span> <span data-ttu-id="998b6-108">Mögliche Werte sind: "Ipsec", "Vnet2Vnet", "ExpressRoute" und "VPNClient.</span><span class="sxs-lookup"><span data-stu-id="998b6-108">Possible values are: 'Ipsec','Vnet2Vnet','ExpressRoute', and 'VPNClient.</span></span> <span data-ttu-id="998b6-109">Folgende Werte sind möglich: "IPsec", "Vnet2Vnet", "ExpressRoute", "VPNClient"</span><span class="sxs-lookup"><span data-stu-id="998b6-109">Possible values include: 'IPsec', 'Vnet2Vnet', 'ExpressRoute', 'VPNClient'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EgressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; EgressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; EgressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.EgressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EgressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.EgressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.EgressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.egressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-110">Ruft die ausgehenden Bytes, die bei dieser Verbindung übertragen.</span><span class="sxs-lookup"><span data-stu-id="998b6-110">Gets the egress bytes transferred in this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBgp">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBgp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBgp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.EnableBgp" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBgp As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBgp : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.EnableBgp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBgp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-111">Ruft ab bzw. legt EnableBgp-Flag fest</span><span class="sxs-lookup"><span data-stu-id="998b6-111">Gets or sets enableBgp flag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.Etag" />
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
            <span data-ttu-id="998b6-112">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="998b6-112">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IngressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IngressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IngressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.IngressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IngressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IngressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.IngressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ingressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-113">Ruft die in dieser Verbindung übertragen eingehend Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="998b6-113">Gets the ingress bytes transferred in this connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; IpsecPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; IpsecPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.IpsecPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecPolicies As IList(Of IpsecPolicy)" />
      <MemberSignature Language="F#" Value="member this.IpsecPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.IpsecPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipsecPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IpsecPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateway2">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource LocalNetworkGateway2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource LocalNetworkGateway2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.LocalNetworkGateway2" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalNetworkGateway2 As SubResource" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateway2 : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.LocalNetworkGateway2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localNetworkGateway2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Peer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Peer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.Peer" />
      <MemberSignature Language="VB.NET" Value="Public Property Peer As SubResource" />
      <MemberSignature Language="F#" Value="member this.Peer : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.Peer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-114">Ruft ab oder legt den Verweis auf die Ressource kann.</span><span class="sxs-lookup"><span data-stu-id="998b6-114">Gets or sets the reference to peerings resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ProvisioningState" />
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
            <span data-ttu-id="998b6-115">Ruft den Bereitstellungsstatus der VirtualNetworkGatewayConnection Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="998b6-115">Gets the provisioning state of the VirtualNetworkGatewayConnection resource.</span></span> <span data-ttu-id="998b6-116">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="998b6-116">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.ResourceGuid" />
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
            <span data-ttu-id="998b6-117">Abrufen oder Festlegen der Ressourcen-GUID-Eigenschaft der Ressource VirtualNetworkGatewayConnection.</span><span class="sxs-lookup"><span data-stu-id="998b6-117">Gets or sets the resource GUID property of the VirtualNetworkGatewayConnection resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutingWeight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RoutingWeight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RoutingWeight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.RoutingWeight" />
      <MemberSignature Language="VB.NET" Value="Public Property RoutingWeight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RoutingWeight : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.RoutingWeight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routingWeight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-118">Abrufen oder Festlegen der routing-Gewichtung.</span><span class="sxs-lookup"><span data-stu-id="998b6-118">Gets or sets the routing weight.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedKey">
      <MemberSignature Language="C#" Value="public string SharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.SharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.SharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-119">Ruft ab oder legt den gemeinsam verwendeten Schlüssel für IPSec.</span><span class="sxs-lookup"><span data-stu-id="998b6-119">Gets or sets the IPSec shared key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TunnelConnectionStatus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt; TunnelConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt; TunnelConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.TunnelConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TunnelConnectionStatus As IList(Of TunnelConnectionHealth)" />
      <MemberSignature Language="F#" Value="member this.TunnelConnectionStatus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.TunnelConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tunnelConnectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="998b6-120">Ruft die Auflistung der Integritätsstatus für alle Tunnel-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="998b6-120">Gets collection of all tunnels' connection health status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsePolicyBasedTrafficSelectors">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsePolicyBasedTrafficSelectors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsePolicyBasedTrafficSelectors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.UsePolicyBasedTrafficSelectors" />
      <MemberSignature Language="VB.NET" Value="Public Property UsePolicyBasedTrafficSelectors As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsePolicyBasedTrafficSelectors : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.UsePolicyBasedTrafficSelectors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usePolicyBasedTrafficSelectors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualNetworkGatewayConnectionInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="998b6-121">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="998b6-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="998b6-122">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="998b6-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateway1">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualNetworkGateway1 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualNetworkGateway1" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.VirtualNetworkGateway1" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkGateway1 As SubResource" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateway1 : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.VirtualNetworkGateway1" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkGateway1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateway2">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualNetworkGateway2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualNetworkGateway2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.VirtualNetworkGateway2" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkGateway2 As SubResource" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateway2 : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner.VirtualNetworkGateway2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkGateway2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>