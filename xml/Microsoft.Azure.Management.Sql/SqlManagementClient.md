<Type Name="SqlManagementClient" FullName="Microsoft.Azure.Management.Sql.SqlManagementClient">
  <TypeSignature Language="C#" Value="public class SqlManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Sql.SqlManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Sql.ISqlManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.Sql.SqlManagementClient&gt; implements class Microsoft.Azure.Management.Sql.ISqlManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.SqlManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlManagementClient&#xA;Inherits ServiceClient(Of SqlManagementClient)&#xA;Implements IAzureClient, IDisposable, ISqlManagementClient" />
  <TypeSignature Language="F#" Value="type SqlManagementClient = class&#xA;    inherit ServiceClient&lt;SqlManagementClient&gt;&#xA;    interface ISqlManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.Sql.SqlManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Sql.SqlManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Sql.ISqlManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="70dc4-101">Azure SQL-datenbankverwaltungs-API bietet eine Reihe von Webdiensten, die Interaktion mit Azure SQL-Datenbank-Dienste für die Verwaltung Ihrer Rest.</span><span class="sxs-lookup"><span data-stu-id="70dc4-101">The Azure SQL Database management API provides a RESTful set of web services that interact with Azure SQL Database services to manage your databases.</span></span> <span data-ttu-id="70dc4-102">Der API können Sie zum Erstellen, abrufen, aktualisieren und Löschen von Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="70dc4-102">The API enables you to create, retrieve, update, and delete databases.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SqlManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            <span data-ttu-id="70dc4-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-103">Optional.</span></span> <span data-ttu-id="70dc4-104">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-104">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-105">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-105">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="70dc4-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-106">Required.</span></span> <span data-ttu-id="70dc4-107">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-107">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-108">Optional.</span></span> <span data-ttu-id="70dc4-109">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-109">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-110">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-110">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SqlManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            <span data-ttu-id="70dc4-112">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-112">Optional.</span></span> <span data-ttu-id="70dc4-113">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="70dc4-113">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-114">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-114">Optional.</span></span> <span data-ttu-id="70dc4-115">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-115">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-116">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-116">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SqlManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="70dc4-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-117">Optional.</span></span> <span data-ttu-id="70dc4-118">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="70dc4-118">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-119">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-119">Optional.</span></span> <span data-ttu-id="70dc4-120">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-120">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-121">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-121">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-122">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            <span data-ttu-id="70dc4-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-123">Required.</span></span> <span data-ttu-id="70dc4-124">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-124">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="70dc4-125">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-125">Optional.</span></span> <span data-ttu-id="70dc4-126">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="70dc4-126">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-127">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-127">Optional.</span></span> <span data-ttu-id="70dc4-128">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-128">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-129">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-129">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-130">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="70dc4-131">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-131">Optional.</span></span> <span data-ttu-id="70dc4-132">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="70dc4-132">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="70dc4-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-133">Required.</span></span> <span data-ttu-id="70dc4-134">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-134">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-135">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-135">Optional.</span></span> <span data-ttu-id="70dc4-136">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-136">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-137">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-137">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-138">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SqlManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="70dc4-139">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-139">Optional.</span></span> <span data-ttu-id="70dc4-140">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="70dc4-140">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="70dc4-141">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-141">Optional.</span></span> <span data-ttu-id="70dc4-142">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="70dc4-142">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-143">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-143">Optional.</span></span> <span data-ttu-id="70dc4-144">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-144">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-145">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-145">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-146">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.SqlManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.SqlManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.Sql.SqlManagementClient" Usage="new Microsoft.Azure.Management.Sql.SqlManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            <span data-ttu-id="70dc4-147">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-147">Optional.</span></span> <span data-ttu-id="70dc4-148">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="70dc4-148">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="70dc4-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-149">Required.</span></span> <span data-ttu-id="70dc4-150">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-150">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="70dc4-151">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-151">Optional.</span></span> <span data-ttu-id="70dc4-152">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="70dc4-152">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="70dc4-153">Optional.</span><span class="sxs-lookup"><span data-stu-id="70dc4-153">Optional.</span></span> <span data-ttu-id="70dc4-154">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="70dc4-154">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="70dc4-155">Initialisiert eine neue Instanz der SqlManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70dc4-155">Initializes a new instance of the SqlManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="70dc4-156">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="70dc4-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.ISqlManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-157">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="70dc4-157">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupLongTermRetentionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations BackupLongTermRetentionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations BackupLongTermRetentionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.BackupLongTermRetentionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupLongTermRetentionPolicies As IBackupLongTermRetentionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.BackupLongTermRetentionPolicies : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.BackupLongTermRetentionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-158">Ruft die IBackupLongTermRetentionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-158">Gets the IBackupLongTermRetentionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupLongTermRetentionVaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations BackupLongTermRetentionVaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations BackupLongTermRetentionVaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.BackupLongTermRetentionVaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupLongTermRetentionVaults As IBackupLongTermRetentionVaultsOperations" />
      <MemberSignature Language="F#" Value="member this.BackupLongTermRetentionVaults : Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.BackupLongTermRetentionVaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-159">Ruft die IBackupLongTermRetentionVaultsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-159">Gets the IBackupLongTermRetentionVaultsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.ISqlManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-160">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="70dc4-160">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ICapabilitiesOperations Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ICapabilitiesOperations Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As ICapabilitiesOperations" />
      <MemberSignature Language="F#" Value="member this.Capabilities : Microsoft.Azure.Management.Sql.ICapabilitiesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ICapabilitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-161">Ruft die ICapabilitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-161">Gets the ICapabilitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-162">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="70dc4-162">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseBlobAuditingPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations DatabaseBlobAuditingPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations DatabaseBlobAuditingPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseBlobAuditingPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseBlobAuditingPolicies As IDatabaseBlobAuditingPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseBlobAuditingPolicies : Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseBlobAuditingPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseBlobAuditingPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-163">Ruft die IDatabaseBlobAuditingPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-163">Gets the IDatabaseBlobAuditingPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseOperations DatabaseOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseOperations DatabaseOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseOperations As IDatabaseOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseOperations : Microsoft.Azure.Management.Sql.IDatabaseOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-164">Ruft die IDatabaseOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-164">Gets the IDatabaseOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabasesOperations Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabasesOperations Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.Databases : Microsoft.Azure.Management.Sql.IDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-165">Ruft die IDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-165">Gets the IDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseThreatDetectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations DatabaseThreatDetectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations DatabaseThreatDetectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseThreatDetectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseThreatDetectionPolicies As IDatabaseThreatDetectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseThreatDetectionPolicies : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseThreatDetectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-166">Ruft die IDatabaseThreatDetectionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-166">Gets the IDatabaseThreatDetectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations DatabaseUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations DatabaseUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseUsages As IDatabaseUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.DatabaseUsages : Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DatabaseUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDatabaseUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-167">Ruft die IDatabaseUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-167">Gets the IDatabaseUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations DataMaskingPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations DataMaskingPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DataMaskingPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingPolicies As IDataMaskingPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.DataMaskingPolicies : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DataMaskingPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-168">Ruft die IDataMaskingPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-168">Gets the IDataMaskingPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations DataMaskingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations DataMaskingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DataMaskingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingRules As IDataMaskingRulesOperations" />
      <MemberSignature Language="F#" Value="member this.DataMaskingRules : Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DataMaskingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IDataMaskingRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-169">Ruft die IDataMaskingRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-169">Gets the IDataMaskingRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-170">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="70dc4-170">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations ElasticPoolActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations ElasticPoolActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPoolActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolActivities As IElasticPoolActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolActivities : Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPoolActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-171">Ruft die IElasticPoolActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-171">Gets the IElasticPoolActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolDatabaseActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations ElasticPoolDatabaseActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations ElasticPoolDatabaseActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPoolDatabaseActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolDatabaseActivities As IElasticPoolDatabaseActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolDatabaseActivities : Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPoolDatabaseActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolDatabaseActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-172">Ruft die IElasticPoolDatabaseActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-172">Gets the IElasticPoolDatabaseActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IElasticPoolsOperations ElasticPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IElasticPoolsOperations ElasticPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPools As IElasticPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.ElasticPools : Microsoft.Azure.Management.Sql.IElasticPoolsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ElasticPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IElasticPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-173">Ruft die IElasticPoolsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-173">Gets the IElasticPoolsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionProtectors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations EncryptionProtectors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations EncryptionProtectors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.EncryptionProtectors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionProtectors As IEncryptionProtectorsOperations" />
      <MemberSignature Language="F#" Value="member this.EncryptionProtectors : Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.EncryptionProtectors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IEncryptionProtectorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-174">Ruft die IEncryptionProtectorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-174">Gets the IEncryptionProtectorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IFailoverGroupsOperations FailoverGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IFailoverGroupsOperations FailoverGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.FailoverGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroups As IFailoverGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.FailoverGroups : Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.FailoverGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IFailoverGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-175">Ruft die IFailoverGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-175">Gets the IFailoverGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IFirewallRulesOperations FirewallRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IFirewallRulesOperations FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirewallRules As IFirewallRulesOperations" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : Microsoft.Azure.Management.Sql.IFirewallRulesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IFirewallRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-176">Ruft die IFirewallRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-176">Gets the IFirewallRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.ISqlManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-177">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="70dc4-177">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="70dc4-178">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="70dc4-178">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoBackupPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations GeoBackupPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations GeoBackupPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.GeoBackupPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoBackupPolicies As IGeoBackupPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.GeoBackupPolicies : Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.GeoBackupPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IGeoBackupPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-179">Ruft die IGeoBackupPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-179">Gets the IGeoBackupPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.ISqlManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-180">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="70dc4-180">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="70dc4-181">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="70dc4-181">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.Sql.IOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-182">Ruft die IOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-182">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedElasticPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations RecommendedElasticPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations RecommendedElasticPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.RecommendedElasticPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedElasticPools As IRecommendedElasticPoolsOperations" />
      <MemberSignature Language="F#" Value="member this.RecommendedElasticPools : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.RecommendedElasticPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-183">Ruft die IRecommendedElasticPoolsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-183">Gets the IRecommendedElasticPoolsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverableDatabases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations RecoverableDatabases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations RecoverableDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.RecoverableDatabases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoverableDatabases As IRecoverableDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.RecoverableDatabases : Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.RecoverableDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRecoverableDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-184">Ruft die IRecoverableDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-184">Gets the IRecoverableDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationLinks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IReplicationLinksOperations ReplicationLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IReplicationLinksOperations ReplicationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ReplicationLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationLinks As IReplicationLinksOperations" />
      <MemberSignature Language="F#" Value="member this.ReplicationLinks : Microsoft.Azure.Management.Sql.IReplicationLinksOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ReplicationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IReplicationLinksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-185">Ruft die IReplicationLinksOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-185">Gets the IReplicationLinksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorableDroppedDatabases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations RestorableDroppedDatabases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations RestorableDroppedDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.RestorableDroppedDatabases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorableDroppedDatabases As IRestorableDroppedDatabasesOperations" />
      <MemberSignature Language="F#" Value="member this.RestorableDroppedDatabases : Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.RestorableDroppedDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRestorableDroppedDatabasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-186">Ruft die IRestorableDroppedDatabasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-186">Gets the IRestorableDroppedDatabasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IRestorePointsOperations RestorePoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IRestorePointsOperations RestorePoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.RestorePoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestorePoints As IRestorePointsOperations" />
      <MemberSignature Language="F#" Value="member this.RestorePoints : Microsoft.Azure.Management.Sql.IRestorePointsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.RestorePoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IRestorePointsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-187">Ruft die IRestorePointsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-187">Gets the IRestorePointsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-188">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="70dc4-188">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerAzureADAdministrators">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations ServerAzureADAdministrators { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations ServerAzureADAdministrators" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerAzureADAdministrators" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerAzureADAdministrators As IServerAzureADAdministratorsOperations" />
      <MemberSignature Language="F#" Value="member this.ServerAzureADAdministrators : Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerAzureADAdministrators" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerAzureADAdministratorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-189">Ruft die IServerAzureADAdministratorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-189">Gets the IServerAzureADAdministratorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCommunicationLinks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations ServerCommunicationLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations ServerCommunicationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerCommunicationLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerCommunicationLinks As IServerCommunicationLinksOperations" />
      <MemberSignature Language="F#" Value="member this.ServerCommunicationLinks : Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerCommunicationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-190">Ruft die IServerCommunicationLinksOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-190">Gets the IServerCommunicationLinksOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerConnectionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations ServerConnectionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations ServerConnectionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerConnectionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerConnectionPolicies As IServerConnectionPoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerConnectionPolicies : Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerConnectionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerConnectionPoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-191">Ruft die IServerConnectionPoliciesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-191">Gets the IServerConnectionPoliciesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerDnsAliases">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations ServerDnsAliases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations ServerDnsAliases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerDnsAliases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerDnsAliases As IServerDnsAliasesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerDnsAliases : Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerDnsAliases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerDnsAliasesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-192">Ruft die IServerDnsAliasesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-192">Gets the IServerDnsAliasesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerKeysOperations ServerKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerKeysOperations ServerKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerKeys As IServerKeysOperations" />
      <MemberSignature Language="F#" Value="member this.ServerKeys : Microsoft.Azure.Management.Sql.IServerKeysOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerKeysOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-193">Ruft die IServerKeysOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-193">Gets the IServerKeysOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Servers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServersOperations Servers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServersOperations Servers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.Servers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Servers As IServersOperations" />
      <MemberSignature Language="F#" Value="member this.Servers : Microsoft.Azure.Management.Sql.IServersOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.Servers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-194">Ruft die IServersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-194">Gets the IServersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServerUsagesOperations ServerUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServerUsagesOperations ServerUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServerUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerUsages As IServerUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.ServerUsages : Microsoft.Azure.Management.Sql.IServerUsagesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServerUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServerUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-195">Ruft die IServerUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-195">Gets the IServerUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceObjectives">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServiceObjectivesOperations ServiceObjectives { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServiceObjectivesOperations ServiceObjectives" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServiceObjectives" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceObjectives As IServiceObjectivesOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceObjectives : Microsoft.Azure.Management.Sql.IServiceObjectivesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServiceObjectives" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServiceObjectivesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-196">Ruft die IServiceObjectivesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-196">Gets the IServiceObjectivesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IServiceTierAdvisorsOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IServiceTierAdvisorsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-197">Ruft die IServiceTierAdvisorsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-197">Gets the IServiceTierAdvisorsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.ISqlManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-198">Die Abonnement-ID, die ein Azure-Abonnement identifiziert.</span><span class="sxs-lookup"><span data-stu-id="70dc4-198">The subscription ID that identifies an Azure subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionUsages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations SubscriptionUsages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations SubscriptionUsages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SubscriptionUsages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionUsages As ISubscriptionUsagesOperations" />
      <MemberSignature Language="F#" Value="member this.SubscriptionUsages : Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SubscriptionUsages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISubscriptionUsagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-199">Ruft die ISubscriptionUsagesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-199">Gets the ISubscriptionUsagesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncAgents">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncAgentsOperations SyncAgents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncAgentsOperations SyncAgents" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SyncAgents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncAgents As ISyncAgentsOperations" />
      <MemberSignature Language="F#" Value="member this.SyncAgents : Microsoft.Azure.Management.Sql.ISyncAgentsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SyncAgents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncAgentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-200">Ruft die ISyncAgentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-200">Gets the ISyncAgentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncGroupsOperations SyncGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncGroupsOperations SyncGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SyncGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncGroups As ISyncGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.SyncGroups : Microsoft.Azure.Management.Sql.ISyncGroupsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SyncGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-201">Ruft die ISyncGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-201">Gets the ISyncGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncMembers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ISyncMembersOperations SyncMembers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ISyncMembersOperations SyncMembers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.SyncMembers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncMembers As ISyncMembersOperations" />
      <MemberSignature Language="F#" Value="member this.SyncMembers : Microsoft.Azure.Management.Sql.ISyncMembersOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.SyncMembers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ISyncMembersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-202">Ruft die ISyncMembersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-202">Gets the ISyncMembersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryptionActivities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations TransparentDataEncryptionActivities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations TransparentDataEncryptionActivities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.TransparentDataEncryptionActivities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryptionActivities As ITransparentDataEncryptionActivitiesOperations" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryptionActivities : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.TransparentDataEncryptionActivities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-203">Ruft die ITransparentDataEncryptionActivitiesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-203">Gets the ITransparentDataEncryptionActivitiesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations TransparentDataEncryptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations TransparentDataEncryptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.TransparentDataEncryptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryptions As ITransparentDataEncryptionsOperations" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryptions : Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.TransparentDataEncryptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.ITransparentDataEncryptionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-204">Ruft die ITransparentDataEncryptionsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-204">Gets the ITransparentDataEncryptionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations VirtualNetworkRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations VirtualNetworkRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.SqlManagementClient.VirtualNetworkRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkRules As IVirtualNetworkRulesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkRules : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" Usage="Microsoft.Azure.Management.Sql.SqlManagementClient.VirtualNetworkRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dc4-205">Ruft die IVirtualNetworkRulesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="70dc4-205">Gets the IVirtualNetworkRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>