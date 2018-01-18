<Type Name="ApplicationInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner">
  <TypeSignature Language="C#" Value="public class ApplicationInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationInner" />
  <TypeSignature Language="F#" Value="type ApplicationInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="55c2a-101">Active Directory-Anwendungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="55c2a-101">Active Directory application information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-102">Initialisiert eine neue Instanz der ApplicationInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="55c2a-102">Initializes a new instance of the ApplicationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationInner (string objectId = null, string objectType = null, string appId = null, System.Collections.Generic.IList&lt;string&gt; appPermissions = null, Nullable&lt;bool&gt; availableToOtherTenants = null, string displayName = null, System.Collections.Generic.IList&lt;string&gt; identifierUris = null, System.Collections.Generic.IList&lt;string&gt; replyUrls = null, string homepage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string objectId, string objectType, string appId, class System.Collections.Generic.IList`1&lt;string&gt; appPermissions, valuetype System.Nullable`1&lt;bool&gt; availableToOtherTenants, string displayName, class System.Collections.Generic.IList`1&lt;string&gt; identifierUris, class System.Collections.Generic.IList`1&lt;string&gt; replyUrls, string homepage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional objectId As String = null, Optional objectType As String = null, Optional appId As String = null, Optional appPermissions As IList(Of String) = null, Optional availableToOtherTenants As Nullable(Of Boolean) = null, Optional displayName As String = null, Optional identifierUris As IList(Of String) = null, Optional replyUrls As IList(Of String) = null, Optional homepage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner (objectId, objectType, appId, appPermissions, availableToOtherTenants, displayName, identifierUris, replyUrls, homepage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="appId" Type="System.String" />
        <Parameter Name="appPermissions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availableToOtherTenants" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="identifierUris" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="replyUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="homepage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="55c2a-103">Die Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="55c2a-103">The object ID.</span></span></param>
        <param name="objectType"><span data-ttu-id="55c2a-104">Der Objekttyp.</span><span class="sxs-lookup"><span data-stu-id="55c2a-104">The object type.</span></span></param>
        <param name="appId"><span data-ttu-id="55c2a-105">Die Anwendungs-ID.</span><span class="sxs-lookup"><span data-stu-id="55c2a-105">The application ID.</span></span></param>
        <param name="appPermissions"><span data-ttu-id="55c2a-106">Die Berechtigungen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-106">The application permissions.</span></span></param>
        <param name="availableToOtherTenants"><span data-ttu-id="55c2a-107">Gibt an, ob die Anwendung ist, werden andere Mandanten zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-107">Whether the application is be available to other tenants.</span></span></param>
        <param name="displayName"><span data-ttu-id="55c2a-108">Der Anzeigename der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-108">The display name of the application.</span></span></param>
        <param name="identifierUris"><span data-ttu-id="55c2a-109">Eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-109">A collection of URIs for the application.</span></span></param>
        <param name="replyUrls"><span data-ttu-id="55c2a-110">Eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-110">A collection of reply URLs for the application.</span></span></param>
        <param name="homepage"><span data-ttu-id="55c2a-111">Die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-111">The home page of the application.</span></span></param>
        <summary>
            <span data-ttu-id="55c2a-112">Initialisiert eine neue Instanz der ApplicationInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="55c2a-112">Initializes a new instance of the ApplicationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppId">
      <MemberSignature Language="C#" Value="public string AppId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AppId" />
      <MemberSignature Language="VB.NET" Value="Public Property AppId As String" />
      <MemberSignature Language="F#" Value="member this.AppId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AppId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-113">Ruft ab oder legt die Anwendungs-ID.</span><span class="sxs-lookup"><span data-stu-id="55c2a-113">Gets or sets the application ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppPermissions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppPermissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppPermissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AppPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Property AppPermissions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppPermissions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AppPermissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appPermissions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-114">Ruft ab oder legt die Berechtigungen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-114">Gets or sets the application permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableToOtherTenants">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AvailableToOtherTenants { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AvailableToOtherTenants" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AvailableToOtherTenants" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableToOtherTenants As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AvailableToOtherTenants : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.AvailableToOtherTenants" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableToOtherTenants")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-115">Ruft ab oder legt fest, ob die Anwendung ist für andere Mandanten verfügbar sein.</span><span class="sxs-lookup"><span data-stu-id="55c2a-115">Gets or sets whether the application is be available to other tenants.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-116">Ruft ab oder legt den Anzeigenamen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-116">Gets or sets the display name of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Homepage">
      <MemberSignature Language="C#" Value="public string Homepage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Homepage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.Homepage" />
      <MemberSignature Language="VB.NET" Value="Public Property Homepage As String" />
      <MemberSignature Language="F#" Value="member this.Homepage : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.Homepage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="homepage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-117">Ruft ab oder legt die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-117">Gets or sets the home page of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentifierUris">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IdentifierUris { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IdentifierUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.IdentifierUris" />
      <MemberSignature Language="VB.NET" Value="Public Property IdentifierUris As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IdentifierUris : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.IdentifierUris" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identifierUris")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-118">Ruft ab oder legt eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-118">Gets or sets a collection of URIs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-119">Ruft ab oder legt die Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="55c2a-119">Gets or sets the object ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-120">Ruft ab oder legt den Objekttyp fest.</span><span class="sxs-lookup"><span data-stu-id="55c2a-120">Gets or sets the object type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ReplyUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ReplyUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ReplyUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ReplyUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner.ReplyUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replyUrls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="55c2a-121">Ruft ab oder legt eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="55c2a-121">Gets or sets a collection of reply URLs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>