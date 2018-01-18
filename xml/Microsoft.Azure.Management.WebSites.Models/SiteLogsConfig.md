<Type Name="SiteLogsConfig" FullName="Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig">
  <TypeSignature Language="C#" Value="public class SiteLogsConfig : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteLogsConfig extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteLogsConfig&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteLogsConfig = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="f32a6-101">Die Konfiguration der App Service-Site-Protokolle.</span><span class="sxs-lookup"><span data-stu-id="f32a6-101">Configuration of App Service site logs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-102">Initialisiert eine neue Instanz der SiteLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f32a6-102">Initializes a new instance of the SiteLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLogsConfig (string id = null, string name = null, string kind = null, string type = null, Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig applicationLogs = null, Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig httpLogs = null, Microsoft.Azure.Management.WebSites.Models.EnabledConfig failedRequestsTracing = null, Microsoft.Azure.Management.WebSites.Models.EnabledConfig detailedErrorMessages = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig applicationLogs, class Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig httpLogs, class Microsoft.Azure.Management.WebSites.Models.EnabledConfig failedRequestsTracing, class Microsoft.Azure.Management.WebSites.Models.EnabledConfig detailedErrorMessages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig,Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig,Microsoft.Azure.Management.WebSites.Models.EnabledConfig,Microsoft.Azure.Management.WebSites.Models.EnabledConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional applicationLogs As ApplicationLogsConfig = null, Optional httpLogs As HttpLogsConfig = null, Optional failedRequestsTracing As EnabledConfig = null, Optional detailedErrorMessages As EnabledConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig : string * string * string * string * Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig * Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig * Microsoft.Azure.Management.WebSites.Models.EnabledConfig * Microsoft.Azure.Management.WebSites.Models.EnabledConfig -&gt; Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig (id, name, kind, type, applicationLogs, httpLogs, failedRequestsTracing, detailedErrorMessages)" />
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
        <Parameter Name="applicationLogs" Type="Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig" />
        <Parameter Name="httpLogs" Type="Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig" />
        <Parameter Name="failedRequestsTracing" Type="Microsoft.Azure.Management.WebSites.Models.EnabledConfig" />
        <Parameter Name="detailedErrorMessages" Type="Microsoft.Azure.Management.WebSites.Models.EnabledConfig" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f32a6-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="f32a6-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="f32a6-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="f32a6-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="f32a6-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f32a6-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="f32a6-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="f32a6-106">Resource type.</span></span></param>
        <param name="applicationLogs"><span data-ttu-id="f32a6-107">Anwendungsprotokolle Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-107">Application logs configuration.</span></span></param>
        <param name="httpLogs"><span data-ttu-id="f32a6-108">Konfiguration des HTTP-Protokolle.</span><span class="sxs-lookup"><span data-stu-id="f32a6-108">HTTP logs configuration.</span></span></param>
        <param name="failedRequestsTracing"><span data-ttu-id="f32a6-109">Anforderungsfehler Ablaufverfolgungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-109">Failed requests tracing configuration.</span></span></param>
        <param name="detailedErrorMessages"><span data-ttu-id="f32a6-110">Ausführliche Meldungen Fehlerkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-110">Detailed error messages configuration.</span></span></param>
        <summary>
            <span data-ttu-id="f32a6-111">Initialisiert eine neue Instanz der SiteLogsConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f32a6-111">Initializes a new instance of the SiteLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLogs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig ApplicationLogs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig ApplicationLogs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.ApplicationLogs" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLogs As ApplicationLogsConfig" />
      <MemberSignature Language="F#" Value="member this.ApplicationLogs : Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.ApplicationLogs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLogs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ApplicationLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-112">Ruft ab, oder legt ihn fest-Protokolle Anwendungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-112">Gets or sets application logs configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedErrorMessages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.EnabledConfig DetailedErrorMessages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.EnabledConfig DetailedErrorMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.DetailedErrorMessages" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedErrorMessages As EnabledConfig" />
      <MemberSignature Language="F#" Value="member this.DetailedErrorMessages : Microsoft.Azure.Management.WebSites.Models.EnabledConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.DetailedErrorMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedErrorMessages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.EnabledConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-113">Ruft ab, oder legt ihn fest ausführliche Meldungen Fehlerkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-113">Gets or sets detailed error messages configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedRequestsTracing">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.EnabledConfig FailedRequestsTracing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.EnabledConfig FailedRequestsTracing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.FailedRequestsTracing" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedRequestsTracing As EnabledConfig" />
      <MemberSignature Language="F#" Value="member this.FailedRequestsTracing : Microsoft.Azure.Management.WebSites.Models.EnabledConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.FailedRequestsTracing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failedRequestsTracing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.EnabledConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-114">Ruft ab, oder legt ihn fest Anforderungsfehler Ablaufverfolgungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-114">Gets or sets failed requests tracing configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpLogs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig HttpLogs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig HttpLogs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.HttpLogs" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpLogs As HttpLogsConfig" />
      <MemberSignature Language="F#" Value="member this.HttpLogs : Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.HttpLogs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpLogs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HttpLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-115">Ruft ab, oder legt ihn fest-HTTP-Protokolle Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="f32a6-115">Gets or sets HTTP logs configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="siteLogsConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f32a6-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f32a6-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f32a6-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f32a6-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>