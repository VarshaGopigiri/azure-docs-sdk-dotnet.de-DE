<Type Name="ApplicationGatewayBackendHttpSettingsInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHttpSettingsInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHttpSettingsInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHttpSettingsInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHttpSettingsInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3a3c0-101">Back-End-Pool adresseinstellungen eines Gateways für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-101">Backend address pool settings of an application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHttpSettingsInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-102">Initialisiert eine neue Instanz der ApplicationGatewayBackendHttpSettingsInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-102">Initializes a new instance of the ApplicationGatewayBackendHttpSettingsInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHttpSettingsInner (string id = null, Nullable&lt;int&gt; port = null, string protocol = null, string cookieBasedAffinity = null, Nullable&lt;int&gt; requestTimeout = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource probe = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; authenticationCertificates = null, Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining connectionDraining = null, string hostName = null, Nullable&lt;bool&gt; pickHostNameFromBackendAddress = null, string affinityCookieName = null, Nullable&lt;bool&gt; probeEnabled = null, string path = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;int32&gt; port, string protocol, string cookieBasedAffinity, valuetype System.Nullable`1&lt;int32&gt; requestTimeout, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource probe, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; authenticationCertificates, class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining connectionDraining, string hostName, valuetype System.Nullable`1&lt;bool&gt; pickHostNameFromBackendAddress, string affinityCookieName, valuetype System.Nullable`1&lt;bool&gt; probeEnabled, string path, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.#ctor(System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional port As Nullable(Of Integer) = null, Optional protocol As String = null, Optional cookieBasedAffinity As String = null, Optional requestTimeout As Nullable(Of Integer) = null, Optional probe As SubResource = null, Optional authenticationCertificates As IList(Of SubResource) = null, Optional connectionDraining As ApplicationGatewayConnectionDraining = null, Optional hostName As String = null, Optional pickHostNameFromBackendAddress As Nullable(Of Boolean) = null, Optional affinityCookieName As String = null, Optional probeEnabled As Nullable(Of Boolean) = null, Optional path As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner : string * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining * string * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner (id, port, protocol, cookieBasedAffinity, requestTimeout, probe, authenticationCertificates, connectionDraining, hostName, pickHostNameFromBackendAddress, affinityCookieName, probeEnabled, path, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="cookieBasedAffinity" Type="System.String" />
        <Parameter Name="requestTimeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="probe" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="authenticationCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="connectionDraining" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="pickHostNameFromBackendAddress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="affinityCookieName" Type="System.String" />
        <Parameter Name="probeEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="port">To be added.</param>
        <param name="protocol">To be added.</param>
        <param name="cookieBasedAffinity">To be added.</param>
        <param name="requestTimeout">To be added.</param>
        <param name="probe">To be added.</param>
        <param name="authenticationCertificates">To be added.</param>
        <param name="connectionDraining">To be added.</param>
        <param name="hostName">To be added.</param>
        <param name="pickHostNameFromBackendAddress">To be added.</param>
        <param name="affinityCookieName">To be added.</param>
        <param name="probeEnabled">To be added.</param>
        <param name="path">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="name">To be added.</param>
        <param name="etag">To be added.</param>
        <param name="type">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityCookieName">
      <MemberSignature Language="C#" Value="public string AffinityCookieName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityCookieName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.AffinityCookieName" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityCookieName As String" />
      <MemberSignature Language="F#" Value="member this.AffinityCookieName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.AffinityCookieName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.affinityCookieName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; AuthenticationCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; AuthenticationCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.AuthenticationCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationCertificates As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.AuthenticationCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.AuthenticationCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authenticationCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-103">Ruft ab, oder legt ihn fest Array von Verweisen auf Zertifikate für die Clientauthentifizierung von Application Gateway.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-103">Gets or sets array of references to application gateway authentication certificates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionDraining">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining ConnectionDraining { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining ConnectionDraining" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ConnectionDraining" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionDraining As ApplicationGatewayConnectionDraining" />
      <MemberSignature Language="F#" Value="member this.ConnectionDraining : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ConnectionDraining" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionDraining")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-104">Ruft ab, oder legt sie fest, Verbindung durch die Back-End-HTTP-Einstellungen-Ressource ein.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-104">Gets or sets connection draining of the backend http settings resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CookieBasedAffinity">
      <MemberSignature Language="C#" Value="public string CookieBasedAffinity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CookieBasedAffinity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.CookieBasedAffinity" />
      <MemberSignature Language="VB.NET" Value="Public Property CookieBasedAffinity As String" />
      <MemberSignature Language="F#" Value="member this.CookieBasedAffinity : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.CookieBasedAffinity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cookieBasedAffinity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-105">Abrufen oder Festlegen der Affinität Cookie-basiert.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-105">Gets or sets cookie based affinity.</span></span> <span data-ttu-id="3a3c0-106">Mögliche Werte sind: "Enabled" und "Disabled".</span><span class="sxs-lookup"><span data-stu-id="3a3c0-106">Possible values are: 'Enabled' and 'Disabled'.</span></span> <span data-ttu-id="3a3c0-107">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="3a3c0-107">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Etag" />
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
            <span data-ttu-id="3a3c0-108">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-108">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="3a3c0-109">Ruft ab oder legt die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-109">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="3a3c0-110">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-110">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PickHostNameFromBackendAddress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PickHostNameFromBackendAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PickHostNameFromBackendAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.PickHostNameFromBackendAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PickHostNameFromBackendAddress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PickHostNameFromBackendAddress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.PickHostNameFromBackendAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pickHostNameFromBackendAddress")</AttributeName>
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
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-111">Ruft ab oder legt ihn fest</span><span class="sxs-lookup"><span data-stu-id="3a3c0-111">Gets or sets port</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Probe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Probe" />
      <MemberSignature Language="VB.NET" Value="Public Property Probe As SubResource" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-112">Ermittelt oder Test-Ressourcen eines Gateways für die Anwendung definiert.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-112">Gets or sets probe resource of an application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProbeEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProbeEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProbeEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ProbeEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ProbeEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProbeEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ProbeEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probeEnabled")</AttributeName>
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
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-113">Ruft ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-113">Gets or sets protocol.</span></span> <span data-ttu-id="3a3c0-114">Mögliche Werte sind: "Http" und "Https".</span><span class="sxs-lookup"><span data-stu-id="3a3c0-114">Possible values are: 'Http' and 'Https'.</span></span>
            <span data-ttu-id="3a3c0-115">Folgende Werte sind möglich: "Http", "Https"</span><span class="sxs-lookup"><span data-stu-id="3a3c0-115">Possible values include: 'Http', 'Https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.ProvisioningState" />
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
            <span data-ttu-id="3a3c0-116">Ruft ab, oder legt sie fest, der Bereitstellungsstatus des Back-End-HTTP-Einstellungsressource.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-116">Gets or sets provisioning state of the backend http settings resource.</span></span> <span data-ttu-id="3a3c0-117">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="3a3c0-117">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.RequestTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3c0-118">Ruft ab oder legt das Anforderungstimeout in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-118">Gets or sets request timeout in seconds.</span></span> <span data-ttu-id="3a3c0-119">Application Gateway wird die Anforderung fehl, wenn keine Antwort innerhalb der RequestTimeout empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-119">Application Gateway will fail the request if response is not received within RequestTimeout.</span></span>
            <span data-ttu-id="3a3c0-120">Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-120">Acceptable values are from 1 second to 86400 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendHttpSettingsInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayBackendHttpSettingsInner.Validate " />
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
            <span data-ttu-id="3a3c0-121">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3a3c0-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3a3c0-122">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3a3c0-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>