<Type Name="NicIPv6" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6">
  <TypeSignature Language="C#" Value="public class NicIPv6" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NicIPv6 extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6" />
  <TypeSignature Language="VB.NET" Value="Public Class NicIPv6" />
  <TypeSignature Language="F#" Value="type NicIPv6 = class" />
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
            <span data-ttu-id="118d5-101">Die Details im Zusammenhang mit der Konfiguration der IPv6-Adresse.</span><span class="sxs-lookup"><span data-stu-id="118d5-101">Details related to the IPv6 address configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NicIPv6 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="118d5-102">Initialisiert eine neue Instanz der NicIPv6-Klasse.</span><span class="sxs-lookup"><span data-stu-id="118d5-102">Initializes a new instance of the NicIPv6 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NicIPv6 (string ipv6Address = null, string ipv6Prefix = null, string ipv6Gateway = null, string controller0Ipv6Address = null, string controller1Ipv6Address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ipv6Address, string ipv6Prefix, string ipv6Gateway, string controller0Ipv6Address, string controller1Ipv6Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional ipv6Address As String = null, Optional ipv6Prefix As String = null, Optional ipv6Gateway As String = null, Optional controller0Ipv6Address As String = null, Optional controller1Ipv6Address As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 : string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6 (ipv6Address, ipv6Prefix, ipv6Gateway, controller0Ipv6Address, controller1Ipv6Address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ipv6Address" Type="System.String" />
        <Parameter Name="ipv6Prefix" Type="System.String" />
        <Parameter Name="ipv6Gateway" Type="System.String" />
        <Parameter Name="controller0Ipv6Address" Type="System.String" />
        <Parameter Name="controller1Ipv6Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv6Address"><span data-ttu-id="118d5-103">Die IPv6-Adresse des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-103">The IPv6 address of the network adapter.</span></span></param>
        <param name="ipv6Prefix"><span data-ttu-id="118d5-104">Das IPv6-Präfix des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-104">The IPv6 prefix of the network adapter.</span></span></param>
        <param name="ipv6Gateway"><span data-ttu-id="118d5-105">Das IPv6-Gateway des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-105">The IPv6 gateway of the network adapter.</span></span></param>
        <param name="controller0Ipv6Address"><span data-ttu-id="118d5-106">IPv6-Adresse der Controller0.</span><span class="sxs-lookup"><span data-stu-id="118d5-106">The IPv6 address of Controller0.</span></span></param>
        <param name="controller1Ipv6Address"><span data-ttu-id="118d5-107">IPv6-Adresse der Controller1.</span><span class="sxs-lookup"><span data-stu-id="118d5-107">The IPv6 address of Controller1.</span></span></param>
        <summary>
            <span data-ttu-id="118d5-108">Initialisiert eine neue Instanz der NicIPv6-Klasse.</span><span class="sxs-lookup"><span data-stu-id="118d5-108">Initializes a new instance of the NicIPv6 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Controller0Ipv6Address">
      <MemberSignature Language="C#" Value="public string Controller0Ipv6Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Controller0Ipv6Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Controller0Ipv6Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Controller0Ipv6Address As String" />
      <MemberSignature Language="F#" Value="member this.Controller0Ipv6Address : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Controller0Ipv6Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="controller0Ipv6Address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="118d5-109">Ruft ab oder legt die IPv6-Adresse des Controller0.</span><span class="sxs-lookup"><span data-stu-id="118d5-109">Gets or sets the IPv6 address of Controller0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Controller1Ipv6Address">
      <MemberSignature Language="C#" Value="public string Controller1Ipv6Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Controller1Ipv6Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Controller1Ipv6Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Controller1Ipv6Address As String" />
      <MemberSignature Language="F#" Value="member this.Controller1Ipv6Address : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Controller1Ipv6Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="controller1Ipv6Address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="118d5-110">Ruft ab oder legt die IPv6-Adresse des Controller1.</span><span class="sxs-lookup"><span data-stu-id="118d5-110">Gets or sets the IPv6 address of Controller1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6Address">
      <MemberSignature Language="C#" Value="public string Ipv6Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Ipv6Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6Address As String" />
      <MemberSignature Language="F#" Value="member this.Ipv6Address : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipv6Address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="118d5-111">Ruft ab oder legt die IPv6-Adresse des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-111">Gets or sets the IPv6 address of the network adapter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6Gateway">
      <MemberSignature Language="C#" Value="public string Ipv6Gateway { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Ipv6Gateway" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Gateway" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6Gateway As String" />
      <MemberSignature Language="F#" Value="member this.Ipv6Gateway : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Gateway" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipv6Gateway")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="118d5-112">Ruft ab oder legt die IPv6-Gateway des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-112">Gets or sets the IPv6 gateway of the network adapter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6Prefix">
      <MemberSignature Language="C#" Value="public string Ipv6Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Ipv6Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Ipv6Prefix : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NicIPv6.Ipv6Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipv6Prefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="118d5-113">Ruft ab oder legt die IPv6-Präfix des Netzwerkadapters.</span><span class="sxs-lookup"><span data-stu-id="118d5-113">Gets or sets the IPv6 prefix of the network adapter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>