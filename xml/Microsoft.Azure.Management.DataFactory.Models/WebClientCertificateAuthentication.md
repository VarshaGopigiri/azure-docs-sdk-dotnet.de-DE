<Type Name="WebClientCertificateAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication">
  <TypeSignature Language="C#" Value="public class WebClientCertificateAuthentication : Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebClientCertificateAuthentication extends Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebClientCertificateAuthentication&#xA;Inherits WebLinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type WebClientCertificateAuthentication = class&#xA;    inherit WebLinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("ClientCertificate")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="09601-101">Eine WebLinkedService, die Clientzertifikat verwenden-basierte Authentifizierung für die Kommunikation mit einem HTTP-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="09601-101">A WebLinkedService that uses client certificate based authentication to communicate with an HTTP endpoint.</span></span> <span data-ttu-id="09601-102">Dieses Schema folgt gegenseitigen Authentifizierung; die Server muss gültige Anmeldeinformationen auch an den Client bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="09601-102">This scheme follows mutual authentication; the server must also provide valid credentials to the client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09601-103">Initialisiert eine neue Instanz der WebClientCertificateAuthentication-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09601-103">Initializes a new instance of the WebClientCertificateAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication (object url, Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, Microsoft.Azure.Management.DataFactory.Models.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, class Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, pfx As SecureString, password As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication : obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication (url, pfx, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="pfx" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="09601-104">Die URL des des Webdienst-Endpunkts, z. B. http://www.microsoft.com.</span><span class="sxs-lookup"><span data-stu-id="09601-104">The URL of the web service endpoint, e.g. http://www.microsoft.com .</span></span> <span data-ttu-id="09601-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="09601-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="pfx"><span data-ttu-id="09601-106">Base64-codierte Inhalt einer PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="09601-106">Base64-encoded contents of a PFX file.</span></span></param>
        <param name="password"><span data-ttu-id="09601-107">Kennwort für die PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="09601-107">Password for the PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="09601-108">Initialisiert eine neue Instanz der WebClientCertificateAuthentication-Klasse.</span><span class="sxs-lookup"><span data-stu-id="09601-108">Initializes a new instance of the WebClientCertificateAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09601-109">Ruft ab oder legt das Kennwort für die PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="09601-109">Gets or sets password for the PFX file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pfx">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberSignature Language="VB.NET" Value="Public Property Pfx As SecureString" />
      <MemberSignature Language="F#" Value="member this.Pfx : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfx")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="09601-110">Ruft ab oder legt die base64-codierte Inhalt einer PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="09601-110">Gets or sets base64-encoded contents of a PFX file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webClientCertificateAuthentication.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09601-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="09601-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="09601-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="09601-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>