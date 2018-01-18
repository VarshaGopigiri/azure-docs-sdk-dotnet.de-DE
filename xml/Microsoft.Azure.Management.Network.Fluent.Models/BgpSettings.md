<Type Name="BgpSettings" FullName="Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings">
  <TypeSignature Language="C#" Value="public class BgpSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpSettings" />
  <TypeSignature Language="F#" Value="type BgpSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3cb7-101">Initialisiert eine neue Instanz der Klasse BgpSettings.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-101">Initializes a new instance of the BgpSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpSettings (Nullable&lt;long&gt; asn = null, string bgpPeeringAddress = null, Nullable&lt;int&gt; peerWeight = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; asn, string bgpPeeringAddress, valuetype System.Nullable`1&lt;int32&gt; peerWeight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.#ctor(System.Nullable{System.Int64},System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional asn As Nullable(Of Long) = null, Optional bgpPeeringAddress As String = null, Optional peerWeight As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings : Nullable&lt;int64&gt; * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings (asn, bgpPeeringAddress, peerWeight)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="asn" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="bgpPeeringAddress" Type="System.String" />
        <Parameter Name="peerWeight" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="asn"><span data-ttu-id="a3cb7-102">Der BGP-Lautsprecher ASN.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-102">The BGP speaker's ASN.</span></span></param>
        <param name="bgpPeeringAddress"><span data-ttu-id="a3cb7-103">Der BGP-peering-Adresse und der BGP-Bezeichner, der diese BGP-Lautsprecher.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-103">The BGP peering address and BGP identifier of this BGP speaker.</span></span></param>
        <param name="peerWeight"><span data-ttu-id="a3cb7-104">Die Gewichtung, die Routen, die von diesem BGP sprechender Benutzer hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-104">The weight added to routes learned from this BGP speaker.</span></span></param>
        <summary>
            <span data-ttu-id="a3cb7-105">Initialisiert eine neue Instanz der Klasse BgpSettings.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-105">Initializes a new instance of the BgpSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Asn">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Asn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Asn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.Asn" />
      <MemberSignature Language="VB.NET" Value="Public Property Asn As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Asn : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.Asn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="asn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3cb7-106">Abrufen oder Festlegen der BGP-Lautsprecher ASN.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-106">Gets or sets the BGP speaker's ASN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpPeeringAddress">
      <MemberSignature Language="C#" Value="public string BgpPeeringAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BgpPeeringAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.BgpPeeringAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpPeeringAddress As String" />
      <MemberSignature Language="F#" Value="member this.BgpPeeringAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.BgpPeeringAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bgpPeeringAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3cb7-107">Ruft ab oder legt das BGP-peering-Adresse und den BGP-Bezeichner, der diese BGP-Lautsprecher.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-107">Gets or sets the BGP peering address and BGP identifier of this BGP speaker.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeerWeight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PeerWeight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PeerWeight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.PeerWeight" />
      <MemberSignature Language="VB.NET" Value="Public Property PeerWeight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PeerWeight : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings.PeerWeight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="peerWeight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3cb7-108">Ruft ab oder legt die Gewichtung, die Routen, die von diesem BGP sprechender Benutzer hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a3cb7-108">Gets or sets the weight added to routes learned from this BGP speaker.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>