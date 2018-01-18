<Type Name="DNSSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings">
  <TypeSignature Language="C#" Value="public class DNSSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DNSSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class DNSSettings" />
  <TypeSignature Language="F#" Value="type DNSSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="366e2-101">Die DNS (Domain Namenserver)-Einstellungen eines Geräts.</span><span class="sxs-lookup"><span data-stu-id="366e2-101">The DNS(Domain Name Server) settings of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DNSSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="366e2-102">Initialisiert eine neue Instanz der DNSSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="366e2-102">Initializes a new instance of the DNSSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DNSSettings (string primaryDnsServer = null, string primaryIpv6DnsServer = null, System.Collections.Generic.IList&lt;string&gt; secondaryDnsServers = null, System.Collections.Generic.IList&lt;string&gt; secondaryIpv6DnsServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryDnsServer, string primaryIpv6DnsServer, class System.Collections.Generic.IList`1&lt;string&gt; secondaryDnsServers, class System.Collections.Generic.IList`1&lt;string&gt; secondaryIpv6DnsServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryDnsServer As String = null, Optional primaryIpv6DnsServer As String = null, Optional secondaryDnsServers As IList(Of String) = null, Optional secondaryIpv6DnsServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings (primaryDnsServer, primaryIpv6DnsServer, secondaryDnsServers, secondaryIpv6DnsServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryDnsServer" Type="System.String" />
        <Parameter Name="primaryIpv6DnsServer" Type="System.String" />
        <Parameter Name="secondaryDnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="secondaryIpv6DnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="primaryDnsServer"><span data-ttu-id="366e2-103">Die primäre IPv4-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-103">The primary IPv4 DNS server for the device</span></span></param>
        <param name="primaryIpv6DnsServer"><span data-ttu-id="366e2-104">Die primäre IPv6-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-104">The primary IPv6 DNS server for the device</span></span></param>
        <param name="secondaryDnsServers"><span data-ttu-id="366e2-105">Die sekundären IPv4-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-105">The secondary IPv4 DNS server for the device</span></span></param>
        <param name="secondaryIpv6DnsServers"><span data-ttu-id="366e2-106">Die sekundären IPv6-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-106">The secondary IPv6 DNS server for the device</span></span></param>
        <summary>
            <span data-ttu-id="366e2-107">Initialisiert eine neue Instanz der DNSSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="366e2-107">Initializes a new instance of the DNSSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryDnsServer">
      <MemberSignature Language="C#" Value="public string PrimaryDnsServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryDnsServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.PrimaryDnsServer" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryDnsServer As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryDnsServer : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.PrimaryDnsServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryDnsServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="366e2-108">Ruft ab oder legt den primären IPv4-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-108">Gets or sets the primary IPv4 DNS server for the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryIpv6DnsServer">
      <MemberSignature Language="C#" Value="public string PrimaryIpv6DnsServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryIpv6DnsServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.PrimaryIpv6DnsServer" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryIpv6DnsServer As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryIpv6DnsServer : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.PrimaryIpv6DnsServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryIpv6DnsServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="366e2-109">Ruft ab oder legt die primären IPv6-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-109">Gets or sets the primary IPv6 DNS server for the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryDnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SecondaryDnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SecondaryDnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.SecondaryDnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryDnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SecondaryDnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.SecondaryDnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryDnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="366e2-110">Ruft ab oder legt den sekundären IPv4-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-110">Gets or sets the secondary IPv4 DNS server for the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryIpv6DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SecondaryIpv6DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SecondaryIpv6DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.SecondaryIpv6DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryIpv6DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SecondaryIpv6DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings.SecondaryIpv6DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryIpv6DnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="366e2-111">Ruft ab oder legt den sekundären IPv6-DNS-Server für das Gerät</span><span class="sxs-lookup"><span data-stu-id="366e2-111">Gets or sets the secondary IPv6 DNS server for the device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>