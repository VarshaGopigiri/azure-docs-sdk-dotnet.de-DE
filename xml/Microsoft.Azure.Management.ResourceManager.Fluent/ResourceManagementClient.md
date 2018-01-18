<Type Name="ResourceManagementClient" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient">
  <TypeSignature Language="C#" Value="public class ResourceManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient&gt;, IDisposable, Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceManagementClient&#xA;Inherits ServiceClient(Of ResourceManagementClient)&#xA;Implements IAzureClient, IDisposable, IResourceManagementClient" />
  <TypeSignature Language="F#" Value="type ResourceManagementClient = class&#xA;    inherit ServiceClient&lt;ResourceManagementClient&gt;&#xA;    interface IResourceManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResourceManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-101">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-101">Optional.</span></span> <span data-ttu-id="5b753-102">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-102">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-103">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-103">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-104">Required.</span></span> <span data-ttu-id="5b753-105">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-105">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-106">Optional.</span></span> <span data-ttu-id="5b753-107">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-107">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-108">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-108">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-109">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResourceManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-110">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-110">Optional.</span></span> <span data-ttu-id="5b753-111">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="5b753-111">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-112">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-112">Optional.</span></span> <span data-ttu-id="5b753-113">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-113">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-114">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-114">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResourceManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-115">Optional.</span></span> <span data-ttu-id="5b753-116">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5b753-116">The base URI of the service.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-117">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-117">Optional.</span></span> <span data-ttu-id="5b753-118">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-118">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-119">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-119">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-120">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-121">Required.</span></span> <span data-ttu-id="5b753-122">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-122">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="5b753-123">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-123">Optional.</span></span> <span data-ttu-id="5b753-124">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="5b753-124">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-125">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-125">Optional.</span></span> <span data-ttu-id="5b753-126">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-126">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-127">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-127">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-128">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-129">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-129">Optional.</span></span> <span data-ttu-id="5b753-130">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5b753-130">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="5b753-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-131">Required.</span></span> <span data-ttu-id="5b753-132">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-132">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-133">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-133">Optional.</span></span> <span data-ttu-id="5b753-134">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-134">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-135">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-135">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-136">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResourceManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-137">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-137">Optional.</span></span> <span data-ttu-id="5b753-138">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5b753-138">The base URI of the service.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="5b753-139">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-139">Optional.</span></span> <span data-ttu-id="5b753-140">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="5b753-140">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-141">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-141">Optional.</span></span> <span data-ttu-id="5b753-142">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-142">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-143">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-143">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-144">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5b753-145">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-145">Optional.</span></span> <span data-ttu-id="5b753-146">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5b753-146">The base URI of the service.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="5b753-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-147">Required.</span></span> <span data-ttu-id="5b753-148">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-148">Credentials needed for the client to connect to Azure.</span></span>
            </param>
        <param name="rootHandler">
            <span data-ttu-id="5b753-149">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-149">Optional.</span></span> <span data-ttu-id="5b753-150">Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.</span><span class="sxs-lookup"><span data-stu-id="5b753-150">The http client handler used to handle http transport.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="5b753-151">Optional.</span><span class="sxs-lookup"><span data-stu-id="5b753-151">Optional.</span></span> <span data-ttu-id="5b753-152">Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</span><span class="sxs-lookup"><span data-stu-id="5b753-152">The delegating handlers to add to the http client pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b753-153">Initialisiert eine neue Instanz der ResourceManagementClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5b753-153">Initializes a new instance of the ResourceManagementClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="5b753-154">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="5b753-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-155">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="5b753-155">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-156">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="5b753-156">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-157">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="5b753-157">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-158">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5b753-158">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations DeploymentOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations DeploymentOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.DeploymentOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentOperations As IDeploymentOperations" />
      <MemberSignature Language="F#" Value="member this.DeploymentOperations : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.DeploymentOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-159">Ruft die IDeploymentOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-159">Gets the IDeploymentOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deployments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations Deployments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations Deployments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Deployments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Deployments As IDeploymentsOperations" />
      <MemberSignature Language="F#" Value="member this.Deployments : Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Deployments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-160">Ruft die IDeploymentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-160">Gets the IDeploymentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-161">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="5b753-161">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-162">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="5b753-162">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="5b753-163">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="5b753-163">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-164">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5b753-164">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span>
            <span data-ttu-id="5b753-165">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="5b753-165">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations Providers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Providers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Providers As IProvidersOperations" />
      <MemberSignature Language="F#" Value="member this.Providers : Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Providers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IProvidersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-166">Ruft die IProvidersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-166">Gets the IProvidersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations ResourceGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations ResourceGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.ResourceGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroups As IResourceGroupsOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceGroups : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.ResourceGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-167">Ruft die IResourceGroupsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-167">Gets the IResourceGroupsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IResourcesOperations" />
      <MemberSignature Language="F#" Value="member this.Resources : Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IResourcesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-168">Ruft die IResourcesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-168">Gets the IResourcesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-169">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="5b753-169">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-170">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5b753-170">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="5b753-171">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="5b753-171">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ITagsOperations Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.ITagsOperations Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As ITagsOperations" />
      <MemberSignature Language="F#" Value="member this.Tags : Microsoft.Azure.Management.ResourceManager.Fluent.ITagsOperations" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManagementClient.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ITagsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b753-172">Ruft die ITagsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="5b753-172">Gets the ITagsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>