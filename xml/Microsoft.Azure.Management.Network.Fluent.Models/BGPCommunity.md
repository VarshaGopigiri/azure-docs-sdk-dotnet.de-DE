<Type Name="BGPCommunity" FullName="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity">
  <TypeSignature Language="C#" Value="public class BGPCommunity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BGPCommunity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity" />
  <TypeSignature Language="VB.NET" Value="Public Class BGPCommunity" />
  <TypeSignature Language="F#" Value="type BGPCommunity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a5ca-101">Enthält Informationen zu Communities Bgp in Service-Community-Ressourcen angeboten.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-101">Contains bgp community information offered in Service Community resources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BGPCommunity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a5ca-102">Initialisiert eine neue Instanz der BGPCommunity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-102">Initializes a new instance of the BGPCommunity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BGPCommunity (string serviceSupportedRegion = null, string communityName = null, string communityValue = null, System.Collections.Generic.IList&lt;string&gt; communityPrefixes = null, Nullable&lt;bool&gt; isAuthorizedToUse = null, string serviceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceSupportedRegion, string communityName, string communityValue, class System.Collections.Generic.IList`1&lt;string&gt; communityPrefixes, valuetype System.Nullable`1&lt;bool&gt; isAuthorizedToUse, string serviceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceSupportedRegion As String = null, Optional communityName As String = null, Optional communityValue As String = null, Optional communityPrefixes As IList(Of String) = null, Optional isAuthorizedToUse As Nullable(Of Boolean) = null, Optional serviceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity (serviceSupportedRegion, communityName, communityValue, communityPrefixes, isAuthorizedToUse, serviceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceSupportedRegion" Type="System.String" />
        <Parameter Name="communityName" Type="System.String" />
        <Parameter Name="communityValue" Type="System.String" />
        <Parameter Name="communityPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isAuthorizedToUse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="serviceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceSupportedRegion">To be added.</param>
        <param name="communityName">To be added.</param>
        <param name="communityValue">To be added.</param>
        <param name="communityPrefixes">To be added.</param>
        <param name="isAuthorizedToUse">To be added.</param>
        <param name="serviceGroup">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityName">
      <MemberSignature Language="C#" Value="public string CommunityName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommunityName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityName" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityName As String" />
      <MemberSignature Language="F#" Value="member this.CommunityName : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a5ca-103">Ruft ab oder legt den Namen der Bgp-Community.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-103">Gets or sets the name of the bgp community.</span></span> <span data-ttu-id="8a5ca-104">z. B. Skype.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-104">e.g. Skype.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CommunityPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CommunityPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CommunityPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a5ca-105">Ruft ab oder legt die Präfixe, die die Bgp-Community enthält.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-105">Gets or sets the prefixes that the bgp community contains.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommunityValue">
      <MemberSignature Language="C#" Value="public string CommunityValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommunityValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CommunityValue As String" />
      <MemberSignature Language="F#" Value="member this.CommunityValue : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.CommunityValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="communityValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a5ca-106">Ruft ab oder legt den Wert der Bgp-Community.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-106">Gets or sets the value of the bgp community.</span></span> <span data-ttu-id="8a5ca-107">Weitere Informationen: https://docs.microsoft.com/en-us/azure/expressroute/expressroute-routing.</span><span class="sxs-lookup"><span data-stu-id="8a5ca-107">For more information: https://docs.microsoft.com/en-us/azure/expressroute/expressroute-routing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAuthorizedToUse">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAuthorizedToUse { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAuthorizedToUse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.IsAuthorizedToUse" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAuthorizedToUse As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAuthorizedToUse : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.IsAuthorizedToUse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAuthorizedToUse")</AttributeName>
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
    <Member MemberName="ServiceGroup">
      <MemberSignature Language="C#" Value="public string ServiceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.ServiceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ServiceGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.ServiceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceGroup")</AttributeName>
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
    <Member MemberName="ServiceSupportedRegion">
      <MemberSignature Language="C#" Value="public string ServiceSupportedRegion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceSupportedRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.ServiceSupportedRegion" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceSupportedRegion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceSupportedRegion : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BGPCommunity.ServiceSupportedRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceSupportedRegion")</AttributeName>
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
  </Members>
</Type>