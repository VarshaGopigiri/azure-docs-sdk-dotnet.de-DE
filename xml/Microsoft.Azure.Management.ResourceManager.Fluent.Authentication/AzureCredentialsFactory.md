<Type Name="AzureCredentialsFactory" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory">
  <TypeSignature Language="C#" Value="public class AzureCredentialsFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureCredentialsFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureCredentialsFactory" />
  <TypeSignature Language="F#" Value="type AzureCredentialsFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureCredentialsFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromFile (string authFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromFile(string authFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FromFile (authFile As String) As AzureCredentials" />
      <MemberSignature Language="F#" Value="abstract member FromFile : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials&#xA;override this.FromFile : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromFile authFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authFile" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authFile"><span data-ttu-id="03220-101">der Pfad zur Datei</span><span class="sxs-lookup"><span data-stu-id="03220-101">the path to the file</span></span></param>
        <summary>
             <span data-ttu-id="03220-102">Erstellt ein Anmeldeinformationsobjekt aus einer Datei im folgenden Format an:</span><span class="sxs-lookup"><span data-stu-id="03220-102">Creates a credentials object from a file in the following format:</span></span>
            
                 <span data-ttu-id="03220-103">Abonnement =&lt;Abonnement-Id&gt; Mandanten =&lt;Mandanten-Id&gt; Client =&lt;Client-Id&gt; Schlüssel =&lt;Clientschlüssel&gt; ManagementURI =&lt;Management-URI&gt; BaseURL =&lt;Basis-URL&gt; AuthURL =&lt;-URL für Webauthentifizierung&gt;</span><span class="sxs-lookup"><span data-stu-id="03220-103">subscription=&lt;subscription-id&gt; tenant=&lt;tenant-id&gt; client=&lt;client-id&gt; key=&lt;client-key&gt; managementURI=&lt;management-URI&gt; baseURL=&lt;base-URL&gt; authURL=&lt;authentication-URL&gt;</span></span>
                 </summary>
        <returns><span data-ttu-id="03220-104">ein Objekt authentifizierte Anmeldeinformationen verwenden</span><span class="sxs-lookup"><span data-stu-id="03220-104">an authenticated credentials object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromMSI">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromMSI (Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment, int port = 50342);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromMSI(class Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment, int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromMSI(Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromMSI (environment As AzureEnvironment, Optional port As Integer = 50342) As AzureCredentials" />
      <MemberSignature Language="F#" Value="member this.FromMSI : Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment * int -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromMSI (environment, port)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="environment" Type="Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment" />
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="environment">To be added.</param>
        <param name="port">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromServicePrincipal">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal (string clientId, System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, string tenantId, Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal(string clientId, class System.Security.Cryptography.X509Certificates.X509Certificate2 certificate, string tenantId, class Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromServicePrincipal(System.String,System.Security.Cryptography.X509Certificates.X509Certificate2,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromServicePrincipal (clientId As String, certificate As X509Certificate2, tenantId As String, environment As AzureEnvironment) As AzureCredentials" />
      <MemberSignature Language="F#" Value="member this.FromServicePrincipal : string * System.Security.Cryptography.X509Certificates.X509Certificate2 * string * Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromServicePrincipal (clientId, certificate, tenantId, environment)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="certificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="environment" Type="Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment" />
      </Parameters>
      <Docs>
        <param name="clientId">To be added.</param>
        <param name="certificate">To be added.</param>
        <param name="tenantId">To be added.</param>
        <param name="environment">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromServicePrincipal">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal (string clientId, string clientSecret, string tenantId, Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal(string clientId, string clientSecret, string tenantId, class Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromServicePrincipal(System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromServicePrincipal (clientId As String, clientSecret As String, tenantId As String, environment As AzureEnvironment) As AzureCredentials" />
      <MemberSignature Language="F#" Value="member this.FromServicePrincipal : string * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromServicePrincipal (clientId, clientSecret, tenantId, environment)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="environment" Type="Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="03220-105">die Client-ID der Anwendung dem Dienstprinzipal zugeordnet ist</span><span class="sxs-lookup"><span data-stu-id="03220-105">the client ID of the application the service principal is associated with</span></span></param>
        <param name="clientSecret"><span data-ttu-id="03220-106">Der geheime Schlüssel für die Client-ID</span><span class="sxs-lookup"><span data-stu-id="03220-106">the secret for the client ID</span></span></param>
        <param name="tenantId"><span data-ttu-id="03220-107">die Mandanten-ID oder die Domäne, in die Anwendung enthalten ist</span><span class="sxs-lookup"><span data-stu-id="03220-107">the tenant ID or domain the application is in</span></span></param>
        <param name="environment"><span data-ttu-id="03220-108">die Umgebung zu authentifizieren</span><span class="sxs-lookup"><span data-stu-id="03220-108">the environment to authenticate to</span></span></param>
        <summary>
            <span data-ttu-id="03220-109">Erstellt ein Anmeldeinformationsobjekt aus einem Dienstprinzipal.</span><span class="sxs-lookup"><span data-stu-id="03220-109">Creates a credentials object from a service principal.</span></span>
            </summary>
        <returns><span data-ttu-id="03220-110">ein Objekt authentifizierte Anmeldeinformationen verwenden</span><span class="sxs-lookup"><span data-stu-id="03220-110">an authenticated credentials object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromServicePrincipal">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal (string clientId, string certificatePath, string certificatePassword, string tenantId, Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromServicePrincipal(string clientId, string certificatePath, string certificatePassword, string tenantId, class Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromServicePrincipal(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromServicePrincipal (clientId As String, certificatePath As String, certificatePassword As String, tenantId As String, environment As AzureEnvironment) As AzureCredentials" />
      <MemberSignature Language="F#" Value="member this.FromServicePrincipal : string * string * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromServicePrincipal (clientId, certificatePath, certificatePassword, tenantId, environment)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="certificatePath" Type="System.String" />
        <Parameter Name="certificatePassword" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="environment" Type="Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment" />
      </Parameters>
      <Docs>
        <param name="clientId">To be added.</param>
        <param name="certificatePath">To be added.</param>
        <param name="certificatePassword">To be added.</param>
        <param name="tenantId">To be added.</param>
        <param name="environment">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromUser (string username, string password, string clientId, string tenantId, Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials FromUser(string username, string password, string clientId, string tenantId, class Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment environment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentialsFactory.FromUser(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromUser (username As String, password As String, clientId As String, tenantId As String, environment As AzureEnvironment) As AzureCredentials" />
      <MemberSignature Language="F#" Value="member this.FromUser : string * string * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" Usage="azureCredentialsFactory.FromUser (username, password, clientId, tenantId, environment)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="environment" Type="Microsoft.Azure.Management.ResourceManager.Fluent.AzureEnvironment" />
      </Parameters>
      <Docs>
        <param name="username"><span data-ttu-id="03220-111">Der Benutzername</span><span class="sxs-lookup"><span data-stu-id="03220-111">the user name</span></span></param>
        <param name="password"><span data-ttu-id="03220-112">das zugehörige Kennwort</span><span class="sxs-lookup"><span data-stu-id="03220-112">the associated password</span></span></param>
        <param name="clientId"><span data-ttu-id="03220-113">die Client-ID der Anwendung</span><span class="sxs-lookup"><span data-stu-id="03220-113">the client ID of the application</span></span></param>
        <param name="tenantId"><span data-ttu-id="03220-114">die Mandanten-ID oder die Domäne der Benutzer befindet sich in</span><span class="sxs-lookup"><span data-stu-id="03220-114">the tenant ID or domain the user is in</span></span></param>
        <param name="environment"><span data-ttu-id="03220-115">die Umgebung zu authentifizieren</span><span class="sxs-lookup"><span data-stu-id="03220-115">the environment to authenticate to</span></span></param>
        <summary>
            <span data-ttu-id="03220-116">Erstellt ein Anmeldeinformationsobjekt aus einer Kombination Benutzername/Kennwort.</span><span class="sxs-lookup"><span data-stu-id="03220-116">Creates a credentials object from a username/password combination.</span></span>
            </summary>
        <returns><span data-ttu-id="03220-117">ein Objekt authentifizierte Anmeldeinformationen verwenden</span><span class="sxs-lookup"><span data-stu-id="03220-117">an authenticated credentials object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>