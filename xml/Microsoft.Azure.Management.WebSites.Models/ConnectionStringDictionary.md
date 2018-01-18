<Type Name="ConnectionStringDictionary" FullName="Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary">
  <TypeSignature Language="C#" Value="public class ConnectionStringDictionary : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectionStringDictionary extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectionStringDictionary&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ConnectionStringDictionary = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2d8b5-101">String-Wörterbuch-Ressource.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-101">String dictionary resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStringDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d8b5-102">Initialisiert eine neue Instanz der ConnectionStringDictionary-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-102">Initializes a new instance of the ConnectionStringDictionary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectionStringDictionary (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional properties As IDictionary(Of String, ConnStringValueTypePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary" Usage="new Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary (id, name, kind, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2d8b5-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="2d8b5-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="2d8b5-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="2d8b5-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-106">Resource type.</span></span></param>
        <param name="properties"><span data-ttu-id="2d8b5-107">Verbindungszeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-107">Connection strings.</span></span></param>
        <summary>
            <span data-ttu-id="2d8b5-108">Initialisiert eine neue Instanz der ConnectionStringDictionary-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-108">Initializes a new instance of the ConnectionStringDictionary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, ConnStringValueTypePair)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnectionStringDictionary.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d8b5-109">Ruft ab, oder legt ihn fest-Verbindungszeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="2d8b5-109">Gets or sets connection strings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>