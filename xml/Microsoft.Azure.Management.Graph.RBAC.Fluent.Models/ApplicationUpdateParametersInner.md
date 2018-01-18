<Type Name="ApplicationUpdateParametersInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class ApplicationUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateParametersInner = class" />
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
            <span data-ttu-id="7077c-101">Anforderungsparameter für die Aktualisierung einer vorhandenen Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-101">Request parameters for updating an existing application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7077c-102">Initialisiert eine neue Instanz der ApplicationUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7077c-102">Initializes a new instance of the ApplicationUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateParametersInner (Nullable&lt;bool&gt; availableToOtherTenants = null, string displayName = null, string homepage = null, System.Collections.Generic.IList&lt;string&gt; identifierUris = null, System.Collections.Generic.IList&lt;string&gt; replyUrls = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; keyCredentials = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; passwordCredentials = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; availableToOtherTenants, string displayName, string homepage, class System.Collections.Generic.IList`1&lt;string&gt; identifierUris, class System.Collections.Generic.IList`1&lt;string&gt; replyUrls, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; keyCredentials, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; passwordCredentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.#ctor(System.Nullable{System.Boolean},System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential},System.Collections.Generic.IList{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional availableToOtherTenants As Nullable(Of Boolean) = null, Optional displayName As String = null, Optional homepage As String = null, Optional identifierUris As IList(Of String) = null, Optional replyUrls As IList(Of String) = null, Optional keyCredentials As IList(Of KeyCredential) = null, Optional passwordCredentials As IList(Of PasswordCredential) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner : Nullable&lt;bool&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner (availableToOtherTenants, displayName, homepage, identifierUris, replyUrls, keyCredentials, passwordCredentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="availableToOtherTenants" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="homepage" Type="System.String" />
        <Parameter Name="identifierUris" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="replyUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;" />
        <Parameter Name="passwordCredentials" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;" />
      </Parameters>
      <Docs>
        <param name="availableToOtherTenants"><span data-ttu-id="7077c-103">Gibt an, ob die Anwendung anderen Mandanten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="7077c-103">Whether the application is available to other tenants</span></span></param>
        <param name="displayName"><span data-ttu-id="7077c-104">Der Anzeigename der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-104">The display name of the application.</span></span></param>
        <param name="homepage"><span data-ttu-id="7077c-105">Die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-105">The home page of the application.</span></span></param>
        <param name="identifierUris"><span data-ttu-id="7077c-106">Eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-106">A collection of URIs for the application.</span></span></param>
        <param name="replyUrls"><span data-ttu-id="7077c-107">Eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-107">A collection of reply URLs for the application.</span></span></param>
        <param name="keyCredentials"><span data-ttu-id="7077c-108">Die Liste der KeyCredential Objekte.</span><span class="sxs-lookup"><span data-stu-id="7077c-108">The list of KeyCredential objects.</span></span></param>
        <param name="passwordCredentials"><span data-ttu-id="7077c-109">Die Liste der PasswordCredential-Objekte.</span><span class="sxs-lookup"><span data-stu-id="7077c-109">The list of PasswordCredential objects.</span></span></param>
        <summary>
            <span data-ttu-id="7077c-110">Initialisiert eine neue Instanz der ApplicationUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7077c-110">Initializes a new instance of the ApplicationUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableToOtherTenants">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AvailableToOtherTenants { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AvailableToOtherTenants" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.AvailableToOtherTenants" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableToOtherTenants As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AvailableToOtherTenants : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.AvailableToOtherTenants" />
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
            <span data-ttu-id="7077c-111">Ruft ab oder legt sie fest, ob die Anwendung anderen Mandanten verfügbar ist</span><span class="sxs-lookup"><span data-stu-id="7077c-111">Gets or sets whether the application is available to other tenants</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.DisplayName" />
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
            <span data-ttu-id="7077c-112">Ruft ab oder legt den Anzeigenamen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-112">Gets or sets the display name of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Homepage">
      <MemberSignature Language="C#" Value="public string Homepage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Homepage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.Homepage" />
      <MemberSignature Language="VB.NET" Value="Public Property Homepage As String" />
      <MemberSignature Language="F#" Value="member this.Homepage : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.Homepage" />
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
            <span data-ttu-id="7077c-113">Ruft ab oder legt die Startseite der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-113">Gets or sets the home page of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentifierUris">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IdentifierUris { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IdentifierUris" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.IdentifierUris" />
      <MemberSignature Language="VB.NET" Value="Public Property IdentifierUris As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IdentifierUris : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.IdentifierUris" />
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
            <span data-ttu-id="7077c-114">Ruft ab oder legt eine Auflistung von URIs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-114">Gets or sets a collection of URIs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; KeyCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; KeyCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.KeyCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyCredentials As IList(Of KeyCredential)" />
      <MemberSignature Language="F#" Value="member this.KeyCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.KeyCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7077c-115">Ruft ab oder legt die Liste der KeyCredential Objekte.</span><span class="sxs-lookup"><span data-stu-id="7077c-115">Gets or sets the list of KeyCredential objects.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordCredentials">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; PasswordCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; PasswordCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.PasswordCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordCredentials As IList(Of PasswordCredential)" />
      <MemberSignature Language="F#" Value="member this.PasswordCredentials : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.PasswordCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordCredentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7077c-116">Ruft ab oder legt die Liste der PasswordCredential-Objekte.</span><span class="sxs-lookup"><span data-stu-id="7077c-116">Gets or sets the list of PasswordCredential objects.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ReplyUrls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ReplyUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.ReplyUrls" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ReplyUrls : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner.ReplyUrls" />
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
            <span data-ttu-id="7077c-117">Ruft ab oder legt eine Auflistung von Antwort-URLs für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="7077c-117">Gets or sets a collection of reply URLs for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>