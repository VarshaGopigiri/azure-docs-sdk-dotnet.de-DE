<Type Name="VaultSecretGroup" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup">
  <TypeSignature Language="C#" Value="public class VaultSecretGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultSecretGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultSecretGroup" />
  <TypeSignature Language="F#" Value="type VaultSecretGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6570a-101">Beschreibt einen Satz von Zertifikaten, die alle im selben Schlüsseltresor befinden.</span><span class="sxs-lookup"><span data-stu-id="6570a-101">Describes a set of certificates which are all in the same Key Vault.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultSecretGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6570a-102">Initialisiert eine neue Instanz der VaultSecretGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6570a-102">Initializes a new instance of the VaultSecretGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultSecretGroup (Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVault = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; vaultCertificates = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource sourceVault, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; vaultCertificates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sourceVault As SubResource = null, Optional vaultCertificates As IList(Of VaultCertificate) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup (sourceVault, vaultCertificates)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceVault" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="vaultCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt;" />
      </Parameters>
      <Docs>
        <param name="sourceVault"><span data-ttu-id="6570a-103">Die Relative URL des Tresors Schlüssel, die alle Zertifikate in VaultCertificates enthält.</span><span class="sxs-lookup"><span data-stu-id="6570a-103">The Relative URL of the Key Vault containing all of the certificates in VaultCertificates.</span></span></param>
        <param name="vaultCertificates"><span data-ttu-id="6570a-104">Die Liste der schlüsseltresor-Verweise in SourceVault die Zertifikate enthalten.</span><span class="sxs-lookup"><span data-stu-id="6570a-104">The list of key vault references in SourceVault which contain certificates.</span></span></param>
        <summary>
            <span data-ttu-id="6570a-105">Initialisiert eine neue Instanz der VaultSecretGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6570a-105">Initializes a new instance of the VaultSecretGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource SourceVault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.SourceVault" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceVault As SubResource" />
      <MemberSignature Language="F#" Value="member this.SourceVault : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.SourceVault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceVault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6570a-106">Ruft ab oder legt die Relative URL des Schlüsseltresor, die alle Zertifikate in VaultCertificates enthält.</span><span class="sxs-lookup"><span data-stu-id="6570a-106">Gets or sets the Relative URL of the Key Vault containing all of the certificates in VaultCertificates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; VaultCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; VaultCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.VaultCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultCertificates As IList(Of VaultCertificate)" />
      <MemberSignature Language="F#" Value="member this.VaultCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VaultSecretGroup.VaultCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vaultCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VaultCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6570a-107">Ruft ab oder legt die Liste der schlüsseltresor Verweise in SourceVault die Zertifikate enthalten.</span><span class="sxs-lookup"><span data-stu-id="6570a-107">Gets or sets the list of key vault references in SourceVault which contain certificates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>