<Type Name="ServerVersionCapability" FullName="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability">
  <TypeSignature Language="C#" Value="public class ServerVersionCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerVersionCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerVersionCapability" />
  <TypeSignature Language="F#" Value="type ServerVersionCapability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23961-101">Die Serverfunktionen.</span><span class="sxs-lookup"><span data-stu-id="23961-101">The server capabilities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerVersionCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23961-102">Initialisiert eine neue Instanz der ServerVersionCapability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23961-102">Initializes a new instance of the ServerVersionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerVersionCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; supportedEditions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; supportedElasticPoolEditions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; supportedEditions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; supportedElasticPoolEditions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.EditionCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedEditions As IList(Of EditionCapability) = null, Optional supportedElasticPoolEditions As IList(Of ElasticPoolEditionCapability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerVersionCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ServerVersionCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ServerVersionCapability (name, status, supportedEditions, supportedElasticPoolEditions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedEditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;" />
        <Parameter Name="supportedElasticPoolEditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="23961-103">Der Name des Server-Version.</span><span class="sxs-lookup"><span data-stu-id="23961-103">The server version name.</span></span></param>
        <param name="status"><span data-ttu-id="23961-104">Der Status des Server-Version.</span><span class="sxs-lookup"><span data-stu-id="23961-104">The status of the server version.</span></span> <span data-ttu-id="23961-105">Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="23961-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedEditions"><span data-ttu-id="23961-106">Die Liste der unterstützten Datenbankeditionen.</span><span class="sxs-lookup"><span data-stu-id="23961-106">The list of supported database editions.</span></span></param>
        <param name="supportedElasticPoolEditions"><span data-ttu-id="23961-107">Die Liste der unterstützten elastischen Pool-Editionen.</span><span class="sxs-lookup"><span data-stu-id="23961-107">The list of supported elastic pool editions.</span></span></param>
        <summary>
            <span data-ttu-id="23961-108">Initialisiert eine neue Instanz der ServerVersionCapability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23961-108">Initializes a new instance of the ServerVersionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="23961-109">Ruft den Versionsnamen ab.</span><span class="sxs-lookup"><span data-stu-id="23961-109">Gets the server version name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23961-110">Ruft den Status von Server-Version ab.</span><span class="sxs-lookup"><span data-stu-id="23961-110">Gets the status of the server version.</span></span> <span data-ttu-id="23961-111">Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="23961-111">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedEditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; SupportedEditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.EditionCapability&gt; SupportedEditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedEditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedEditions As IList(Of EditionCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedEditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedEditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedEditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.EditionCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23961-112">Ruft die Liste der unterstützten Datenbankeditionen ab.</span><span class="sxs-lookup"><span data-stu-id="23961-112">Gets the list of supported database editions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedElasticPoolEditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; SupportedElasticPoolEditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt; SupportedElasticPoolEditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedElasticPoolEditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedElasticPoolEditions As IList(Of ElasticPoolEditionCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedElasticPoolEditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServerVersionCapability.SupportedElasticPoolEditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedElasticPoolEditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23961-113">Ruft die Liste der unterstützten elastischen Pool Editionen ab.</span><span class="sxs-lookup"><span data-stu-id="23961-113">Gets the list of supported elastic pool editions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>