<Type Name="SiteConfigurationSnapshotInfo" FullName="Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo">
  <TypeSignature Language="C#" Value="public class SiteConfigurationSnapshotInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteConfigurationSnapshotInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteConfigurationSnapshotInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteConfigurationSnapshotInfo = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3091d-101">Eine Momentaufnahme einer Web-app-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="3091d-101">A snapshot of a web app configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigurationSnapshotInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3091d-102">Initialisiert eine neue Instanz der SiteConfigurationSnapshotInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3091d-102">Initializes a new instance of the SiteConfigurationSnapshotInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigurationSnapshotInfo (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;DateTime&gt; time = null, Nullable&lt;int&gt; siteConfigurationSnapshotInfoId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time, valuetype System.Nullable`1&lt;int32&gt; siteConfigurationSnapshotInfoId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional time As Nullable(Of DateTime) = null, Optional siteConfigurationSnapshotInfoId As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo (id, name, kind, type, time, siteConfigurationSnapshotInfoId)" />
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
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfigurationSnapshotInfoId" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3091d-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="3091d-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="3091d-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="3091d-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="3091d-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="3091d-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="3091d-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="3091d-106">Resource type.</span></span></param>
        <param name="time"><span data-ttu-id="3091d-107">Die Uhrzeit, die Erstellung der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="3091d-107">The time the snapshot was taken.</span></span></param>
        <param name="siteConfigurationSnapshotInfoId"><span data-ttu-id="3091d-108">Die Id der Momentaufnahme</span><span class="sxs-lookup"><span data-stu-id="3091d-108">The id of the snapshot</span></span></param>
        <summary>
            <span data-ttu-id="3091d-109">Initialisiert eine neue Instanz der SiteConfigurationSnapshotInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3091d-109">Initializes a new instance of the SiteConfigurationSnapshotInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfigurationSnapshotInfoId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SiteConfigurationSnapshotInfoId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SiteConfigurationSnapshotInfoId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.SiteConfigurationSnapshotInfoId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SiteConfigurationSnapshotInfoId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SiteConfigurationSnapshotInfoId : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.SiteConfigurationSnapshotInfoId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3091d-110">Ruft die Id der Momentaufnahme ab</span><span class="sxs-lookup"><span data-stu-id="3091d-110">Gets the id of the snapshot</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.SiteConfigurationSnapshotInfo.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3091d-111">Ruft die Uhrzeit, die Erstellung der Momentaufnahme, ab.</span><span class="sxs-lookup"><span data-stu-id="3091d-111">Gets the time the snapshot was taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>