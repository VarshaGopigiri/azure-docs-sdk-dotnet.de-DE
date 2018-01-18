<Type Name="DomainInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner">
  <TypeSignature Language="C#" Value="public class DomainInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DomainInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DomainInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DomainInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="875b6-101">Informationen zu einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="875b6-101">Information about a domain.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="875b6-102">Initialisiert eine neue Instanz der DomainInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="875b6-102">Initializes a new instance of the DomainInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DomainInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactAdmin = null, Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactBilling = null, Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactRegistrant = null, Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactTech = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt; registrationStatus = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null, Nullable&lt;bool&gt; privacy = null, Nullable&lt;DateTime&gt; createdTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;DateTime&gt; lastRenewedTime = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;bool&gt; readyForDnsRecordManagement = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; managedHostNames = null, Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent consent = null, System.Collections.Generic.IList&lt;string&gt; domainNotRenewableReasons = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; dnsType = null, string dnsZoneId = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; targetDnsType = null, string authCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactAdmin, class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactBilling, class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactRegistrant, class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contactTech, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt; registrationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState, class System.Collections.Generic.IList`1&lt;string&gt; nameServers, valuetype System.Nullable`1&lt;bool&gt; privacy, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRenewedTime, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;bool&gt; readyForDnsRecordManagement, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; managedHostNames, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent consent, class System.Collections.Generic.IList`1&lt;string&gt; domainNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; dnsType, string dnsZoneId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; targetDnsType, string authCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.AppService.Fluent.Models.Contact,Microsoft.Azure.Management.AppService.Fluent.Models.Contact,Microsoft.Azure.Management.AppService.Fluent.Models.Contact,Microsoft.Azure.Management.AppService.Fluent.Models.Contact,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HostName},Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.DnsType},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.DnsType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional contactAdmin As Contact = null, Optional contactBilling As Contact = null, Optional contactRegistrant As Contact = null, Optional contactTech As Contact = null, Optional registrationStatus As Nullable(Of DomainStatus) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional nameServers As IList(Of String) = null, Optional privacy As Nullable(Of Boolean) = null, Optional createdTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional lastRenewedTime As Nullable(Of DateTime) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional readyForDnsRecordManagement As Nullable(Of Boolean) = null, Optional managedHostNames As IList(Of HostName) = null, Optional consent As DomainPurchaseConsent = null, Optional domainNotRenewableReasons As IList(Of String) = null, Optional dnsType As Nullable(Of DnsType) = null, Optional dnsZoneId As String = null, Optional targetDnsType As Nullable(Of DnsType) = null, Optional authCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.Contact * Microsoft.Azure.Management.AppService.Fluent.Models.Contact * Microsoft.Azure.Management.AppService.Fluent.Models.Contact * Microsoft.Azure.Management.AppService.Fluent.Models.Contact * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner (location, id, name, type, tags, contactAdmin, contactBilling, contactRegistrant, contactTech, registrationStatus, provisioningState, nameServers, privacy, createdTime, expirationTime, lastRenewedTime, autoRenew, readyForDnsRecordManagement, managedHostNames, consent, domainNotRenewableReasons, dnsType, dnsZoneId, targetDnsType, authCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contactAdmin" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
        <Parameter Name="contactBilling" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
        <Parameter Name="contactRegistrant" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
        <Parameter Name="contactTech" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
        <Parameter Name="registrationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="privacy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="createdTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastRenewedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="readyForDnsRecordManagement" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="managedHostNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;" />
        <Parameter Name="consent" Type="Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent" />
        <Parameter Name="domainNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="dnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt;" />
        <Parameter Name="dnsZoneId" Type="System.String" />
        <Parameter Name="targetDnsType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt;" />
        <Parameter Name="authCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="contactAdmin">To be added.</param>
        <param name="contactBilling">To be added.</param>
        <param name="contactRegistrant">To be added.</param>
        <param name="contactTech">To be added.</param>
        <param name="registrationStatus">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="nameServers">To be added.</param>
        <param name="privacy">To be added.</param>
        <param name="createdTime">To be added.</param>
        <param name="expirationTime">To be added.</param>
        <param name="lastRenewedTime">To be added.</param>
        <param name="autoRenew">To be added.</param>
        <param name="readyForDnsRecordManagement">To be added.</param>
        <param name="managedHostNames">To be added.</param>
        <param name="consent">To be added.</param>
        <param name="domainNotRenewableReasons">To be added.</param>
        <param name="dnsType">To be added.</param>
        <param name="dnsZoneId">To be added.</param>
        <param name="targetDnsType">To be added.</param>
        <param name="authCode">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthCode">
      <MemberSignature Language="C#" Value="public string AuthCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.AuthCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthCode As String" />
      <MemberSignature Language="F#" Value="member this.AuthCode : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.AuthCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authCode")</AttributeName>
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
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-103">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die Domäne, automatisch erneuert, andernfalls werden sollen &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="875b6-103">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the domain should be automatically renewed; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Consent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.Consent" />
      <MemberSignature Language="VB.NET" Value="Public Property Consent As DomainPurchaseConsent" />
      <MemberSignature Language="F#" Value="member this.Consent : Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.Consent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-104">Ruft ab, oder legt ihn fest rechtsgültigen Vertrag Zustimmung.</span><span class="sxs-lookup"><span data-stu-id="875b6-104">Gets or sets legal agreement consent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactAdmin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactAdmin As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactAdmin : Microsoft.Azure.Management.AppService.Fluent.Models.Contact with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-105">Ruft ab, oder legt ihn fest Administratorkontakt.</span><span class="sxs-lookup"><span data-stu-id="875b6-105">Gets or sets administrative contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactBilling">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactBilling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactBilling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactBilling" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactBilling As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactBilling : Microsoft.Azure.Management.AppService.Fluent.Models.Contact with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactBilling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactBilling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-106">Ruft ab, oder legt ihn fest Rechnungskontakt.</span><span class="sxs-lookup"><span data-stu-id="875b6-106">Gets or sets billing contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactRegistrant">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactRegistrant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactRegistrant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactRegistrant" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactRegistrant As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactRegistrant : Microsoft.Azure.Management.AppService.Fluent.Models.Contact with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactRegistrant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactRegistrant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-107">Ruft ab, oder legt ihn fest Registrant wenden Sie sich an.</span><span class="sxs-lookup"><span data-stu-id="875b6-107">Gets or sets registrant contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContactTech">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactTech { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact ContactTech" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactTech" />
      <MemberSignature Language="VB.NET" Value="Public Property ContactTech As Contact" />
      <MemberSignature Language="F#" Value="member this.ContactTech : Microsoft.Azure.Management.AppService.Fluent.Models.Contact with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ContactTech" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.contactTech")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-108">Ruft ab oder legt den technischen Kontakt.</span><span class="sxs-lookup"><span data-stu-id="875b6-108">Gets or sets technical contact.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-109">Ruft die Domäne Erstellungszeitstempel ab.</span><span class="sxs-lookup"><span data-stu-id="875b6-109">Gets domain creation timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; DnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; DnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.DnsType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsZoneId">
      <MemberSignature Language="C#" Value="public string DnsZoneId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsZoneId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DnsZoneId" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsZoneId As String" />
      <MemberSignature Language="F#" Value="member this.DnsZoneId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DnsZoneId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsZoneId")</AttributeName>
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
    <Member MemberName="DomainNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DomainNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DomainNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DomainNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DomainNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.DomainNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-110">Ruft ab, oder legt ihn fest Gründe, warum eine Domäne nicht erneuerbar ist.</span><span class="sxs-lookup"><span data-stu-id="875b6-110">Gets or sets reasons why domain is not renewable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-111">Ruft die Ablaufzeit Zeitstempel Domäne ab.</span><span class="sxs-lookup"><span data-stu-id="875b6-111">Gets domain expiration timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRenewedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRenewedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRenewedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.LastRenewedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRenewedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRenewedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.LastRenewedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastRenewedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-112">Ruft die Zeitstempel ab, wenn die Domäne zuletzt erneuert wurde.</span><span class="sxs-lookup"><span data-stu-id="875b6-112">Gets timestamp when the domain was renewed last time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ManagedHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedHostNames As IList(Of HostName)" />
      <MemberSignature Language="F#" Value="member this.ManagedHostNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ManagedHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managedHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-113">Ruft ab oder legt alle Hostnamen abgeleitet aus der Domäne und Azure-Ressourcen zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="875b6-113">Gets or sets all hostnames derived from the domain and assigned to Azure resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nameServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-114">Ruft ab, oder legt ihn fest Namenservern.</span><span class="sxs-lookup"><span data-stu-id="875b6-114">Gets or sets name servers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Privacy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public Property Privacy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Privacy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.Privacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privacy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-115">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Domäne Datenschutz für diese Domäne aktiviert ist, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="875b6-115">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if domain privacy is enabled for this domain; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-116">Ruft Zustand Domäne bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="875b6-116">Gets domain provisioning state.</span></span> <span data-ttu-id="875b6-117">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="875b6-117">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadyForDnsRecordManagement">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReadyForDnsRecordManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReadyForDnsRecordManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ReadyForDnsRecordManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadyForDnsRecordManagement As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReadyForDnsRecordManagement : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.ReadyForDnsRecordManagement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readyForDnsRecordManagement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-118">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Azure App Service-apps; diese Domäne zuweisen kann, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="875b6-118">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Azure can assign this domain to App Service apps; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="875b6-119">Dieser Wert &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn Domäne Registrierungsstatus aktiv ist und es auf Azure bietet programmgesteuerten Zugriff auf Namenservern gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="875b6-119">This value will be &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if domain registration status is active and it is hosted on name servers Azure has programmatic access to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt; RegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt; RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationStatus As Nullable(Of DomainStatus)" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="875b6-120">Ruft die Domäne Registrierungsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="875b6-120">Gets domain registration status.</span></span> <span data-ttu-id="875b6-121">Folgende Werte sind möglich: "Aktiv", "Anwendung wartet auf", "Abgebrochen", "Confiscated", "Deaktiviert", "Ausgeschlossen", "Abgelaufen", "Fehlgeschlagen", "Frei", "Gesperrt", "Parked", "Ausstehend", "Reserviert", "Wiederhergestellten", "Angehalten", "Übertragen", "Unknown", "Entsperrt", "Unparked", " Aktualisiert ', 'JsonConverterFailed'</span><span class="sxs-lookup"><span data-stu-id="875b6-121">Possible values include: 'Active', 'Awaiting', 'Cancelled', 'Confiscated', 'Disabled', 'Excluded', 'Expired', 'Failed', 'Held', 'Locked', 'Parked', 'Pending', 'Reserved', 'Reverted', 'Suspended', 'Transferred', 'Unknown', 'Unlocked', 'Unparked', 'Updated', 'JsonConverterFailed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDnsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; TargetDnsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; TargetDnsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.TargetDnsType" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDnsType As Nullable(Of DnsType)" />
      <MemberSignature Language="F#" Value="member this.TargetDnsType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.TargetDnsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetDnsType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DnsType&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="domainInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="875b6-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="875b6-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="875b6-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="875b6-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>