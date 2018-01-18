<Type Name="CertificateIssuerItem" FullName="Microsoft.Azure.KeyVault.Models.CertificateIssuerItem">
  <TypeSignature Language="C#" Value="public class CertificateIssuerItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateIssuerItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateIssuerItem" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateIssuerItem" />
  <TypeSignature Language="F#" Value="type CertificateIssuerItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94dad-101">Das Zertifikat Aussteller-Element, enthält das Zertifikat Aussteller Metadaten.</span><span class="sxs-lookup"><span data-stu-id="94dad-101">The certificate issuer item containing certificate issuer metadata.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94dad-102">Initialisiert eine neue Instanz der CertificateIssuerItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94dad-102">Initializes a new instance of the CertificateIssuerItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerItem (string id = null, string provider = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional provider As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateIssuerItem : string * string -&gt; Microsoft.Azure.KeyVault.Models.CertificateIssuerItem" Usage="new Microsoft.Azure.KeyVault.Models.CertificateIssuerItem (id, provider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="94dad-103">Zertifikatsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="94dad-103">Certificate Identifier.</span></span></param>
        <param name="provider"><span data-ttu-id="94dad-104">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="94dad-104">The issuer provider.</span></span></param>
        <summary>
            <span data-ttu-id="94dad-105">Initialisiert eine neue Instanz der CertificateIssuerItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94dad-105">Initializes a new instance of the CertificateIssuerItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94dad-106">Ruft ab oder legt Zertifikat Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="94dad-106">Gets or sets certificate Identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateIssuerItem.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94dad-107">Abrufen oder Festlegen des Ausstellers-Anbieters.</span><span class="sxs-lookup"><span data-stu-id="94dad-107">Gets or sets the issuer provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>