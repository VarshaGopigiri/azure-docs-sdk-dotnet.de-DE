<Type Name="ConnectivityHop" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityHop">
  <TypeSignature Language="C#" Value="public class ConnectivityHop" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityHop extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityHop" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityHop" />
  <TypeSignature Language="F#" Value="type ConnectivityHop = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f057-101">Informationen zu einem Hop zwischen der Quelle und Ziel.</span><span class="sxs-lookup"><span data-stu-id="8f057-101">Information about a hop between the source and the destination.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityHop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityHop.#ctor" />
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
            <span data-ttu-id="8f057-102">Initialisiert eine neue Instanz der ConnectivityHop-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f057-102">Initializes a new instance of the ConnectivityHop class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityHop (string type = null, string id = null, string address = null, string resourceId = null, System.Collections.Generic.IList&lt;string&gt; nextHopIds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; issues = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string id, string address, string resourceId, class System.Collections.Generic.IList`1&lt;string&gt; nextHopIds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; issues) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityHop.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ConnectivityIssue})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional id As String = null, Optional address As String = null, Optional resourceId As String = null, Optional nextHopIds As IList(Of String) = null, Optional issues As IList(Of ConnectivityIssue) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityHop : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityHop" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityHop (type, id, address, resourceId, nextHopIds, issues)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="nextHopIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="issues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="8f057-103">Der Typ des Hops.</span><span class="sxs-lookup"><span data-stu-id="8f057-103">The type of the hop.</span></span></param>
        <param name="id"><span data-ttu-id="8f057-104">Die ID des Hops.</span><span class="sxs-lookup"><span data-stu-id="8f057-104">The ID of the hop.</span></span></param>
        <param name="address"><span data-ttu-id="8f057-105">Die IP-Adresse des Hops.</span><span class="sxs-lookup"><span data-stu-id="8f057-105">The IP address of the hop.</span></span></param>
        <param name="resourceId"><span data-ttu-id="8f057-106">Die ID der Ressource an diesem Hop entspricht.</span><span class="sxs-lookup"><span data-stu-id="8f057-106">The ID of the resource corresponding to this hop.</span></span></param>
        <param name="nextHopIds"><span data-ttu-id="8f057-107">Liste der nächste Hop-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="8f057-107">List of next hop identifiers.</span></span></param>
        <param name="issues"><span data-ttu-id="8f057-108">Liste der Probleme.</span><span class="sxs-lookup"><span data-stu-id="8f057-108">List of issues.</span></span></param>
        <summary>
            <span data-ttu-id="8f057-109">Initialisiert eine neue Instanz der ConnectivityHop-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f057-109">Initializes a new instance of the ConnectivityHop class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f057-110">Ruft die IP-Adresse des Hop ab.</span><span class="sxs-lookup"><span data-stu-id="8f057-110">Gets the IP address of the hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f057-111">Ruft die ID des Hops.</span><span class="sxs-lookup"><span data-stu-id="8f057-111">Gets the ID of the hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; Issues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt; Issues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Issues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issues As IList(Of ConnectivityIssue)" />
      <MemberSignature Language="F#" Value="member this.Issues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Issues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ConnectivityIssue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f057-112">Ruft die Liste der Probleme.</span><span class="sxs-lookup"><span data-stu-id="8f057-112">Gets list of issues.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NextHopIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NextHopIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.NextHopIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHopIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NextHopIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.NextHopIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f057-113">Ruft die Liste der nächste Hop-Bezeichner ab.</span><span class="sxs-lookup"><span data-stu-id="8f057-113">Gets list of next hop identifiers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f057-114">Ruft die ID der Ressource entspricht diesem Hop ab.</span><span class="sxs-lookup"><span data-stu-id="8f057-114">Gets the ID of the resource corresponding to this hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityHop.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityHop.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="8f057-115">Ruft den Typ des Hop ab.</span><span class="sxs-lookup"><span data-stu-id="8f057-115">Gets the type of the hop.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>