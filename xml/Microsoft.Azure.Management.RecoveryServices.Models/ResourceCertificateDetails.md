<Type Name="ResourceCertificateDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails">
  <TypeSignature Language="C#" Value="public class ResourceCertificateDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceCertificateDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceCertificateDetails" />
  <TypeSignature Language="F#" Value="type ResourceCertificateDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f5f3-101">Details des Zertifikats, das die tresoranmeldeinformationen darstellt.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-101">Certificate details representing the Vault credentials.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-102">Initialisiert eine neue Instanz der ResourceCertificateDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-102">Initializes a new instance of the ResourceCertificateDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceCertificateDetails (byte[] certificate = null, string friendlyName = null, string issuer = null, Nullable&lt;long&gt; resourceId = null, string subject = null, string thumbprint = null, Nullable&lt;DateTime&gt; validFrom = null, Nullable&lt;DateTime&gt; validTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] certificate, string friendlyName, string issuer, valuetype System.Nullable`1&lt;int64&gt; resourceId, string subject, string thumbprint, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validFrom, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; validTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.#ctor(System.Byte[],System.String,System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificate As Byte() = null, Optional friendlyName As String = null, Optional issuer As String = null, Optional resourceId As Nullable(Of Long) = null, Optional subject As String = null, Optional thumbprint As String = null, Optional validFrom As Nullable(Of DateTime) = null, Optional validTo As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails : byte[] * string * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails (certificate, friendlyName, issuer, resourceId, subject, thumbprint, validFrom, validTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificate" Type="System.Byte[]" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
        <Parameter Name="resourceId" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="validFrom" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="validTo" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="certificate"><span data-ttu-id="4f5f3-103">Die base64-codierte Zertifikat Rohdaten Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-103">The base64 encoded certificate raw data string.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="4f5f3-104">Friendlyname-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-104">Certificate friendlyname.</span></span></param>
        <param name="issuer"><span data-ttu-id="4f5f3-105">Aussteller des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-105">Certificate issuer.</span></span></param>
        <param name="resourceId"><span data-ttu-id="4f5f3-106">Ressourcen-ID des Tresors.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-106">Resource ID of the vault.</span></span></param>
        <param name="subject"><span data-ttu-id="4f5f3-107">Zertifikatsantragsteller.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-107">Certificate Subject Name.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="4f5f3-108">Fingerabdruck des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-108">Certificate thumbprint.</span></span></param>
        <param name="validFrom"><span data-ttu-id="4f5f3-109">Startzeit der Gültigkeit des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-109">Certificate Validity start Date time.</span></span></param>
        <param name="validTo"><span data-ttu-id="4f5f3-110">Enddatum für die Gültigkeit des Zertifikatzeit.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-110">Certificate Validity End Date time.</span></span></param>
        <summary>
            <span data-ttu-id="4f5f3-111">Initialisiert eine neue Instanz der ResourceCertificateDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-111">Initializes a new instance of the ResourceCertificateDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public byte[] Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As Byte()" />
      <MemberSignature Language="F#" Value="member this.Certificate : byte[] with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-112">Ruft ab oder legt die base64-codierte Zertifikat Rohdaten-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-112">Gets or sets the base64 encoded certificate raw data string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-113">Ruft ab, oder legt ihn fest Friendlyname Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-113">Gets or sets certificate friendlyname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Issuer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="issuer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-114">Abrufen oder Festlegen der Aussteller des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-114">Gets or sets certificate issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ResourceId : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-115">Abrufen oder Festlegen der Ressourcen-ID des Tresors.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-115">Gets or sets resource ID of the vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subject">
      <MemberSignature Language="C#" Value="public string Subject { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Subject" />
      <MemberSignature Language="VB.NET" Value="Public Property Subject As String" />
      <MemberSignature Language="F#" Value="member this.Subject : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Subject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subject")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-116">Ruft ab oder legt die Namen des Zertifikatantragstellers fest.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-116">Gets or sets certificate Subject Name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-117">Abrufen oder Festlegen der Fingerabdruck des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-117">Gets or sets certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidFrom">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ValidFrom { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ValidFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ValidFrom" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidFrom As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ValidFrom : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ValidFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validFrom")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-118">Ruft ab, oder legt ihn fest Zertifikat Gültigkeit Startzeit.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-118">Gets or sets certificate Validity start Date time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidTo">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ValidTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ValidTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ValidTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidTo As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ValidTo : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ResourceCertificateDetails.ValidTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f5f3-119">Ruft ab, oder legt ihn fest Gültigkeit Enddatum Zertifikatzeit.</span><span class="sxs-lookup"><span data-stu-id="4f5f3-119">Gets or sets certificate Validity End Date time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>