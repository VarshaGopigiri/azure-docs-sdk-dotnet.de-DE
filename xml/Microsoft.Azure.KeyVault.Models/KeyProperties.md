<Type Name="KeyProperties" FullName="Microsoft.Azure.KeyVault.Models.KeyProperties">
  <TypeSignature Language="C#" Value="public class KeyProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyProperties" />
  <TypeSignature Language="F#" Value="type KeyProperties = class" />
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
            <span data-ttu-id="afd99-101">Eigenschaften des Schlüsselpaars ein Zertifikat zu sichern.</span><span class="sxs-lookup"><span data-stu-id="afd99-101">Properties of the key pair backing a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="afd99-102">Initialisiert eine neue Instanz der KeyProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="afd99-102">Initializes a new instance of the KeyProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyProperties (Nullable&lt;bool&gt; exportable = null, string keyType = null, Nullable&lt;int&gt; keySize = null, Nullable&lt;bool&gt; reuseKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; exportable, string keyType, valuetype System.Nullable`1&lt;int32&gt; keySize, valuetype System.Nullable`1&lt;bool&gt; reuseKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyProperties.#ctor(System.Nullable{System.Boolean},System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional exportable As Nullable(Of Boolean) = null, Optional keyType As String = null, Optional keySize As Nullable(Of Integer) = null, Optional reuseKey As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyProperties : Nullable&lt;bool&gt; * string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.KeyVault.Models.KeyProperties" Usage="new Microsoft.Azure.KeyVault.Models.KeyProperties (exportable, keyType, keySize, reuseKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exportable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyType" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="reuseKey" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="exportable"><span data-ttu-id="afd99-103">Gibt an, ob der private Schlüssel exportiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="afd99-103">Indicates if the private key can be exported.</span></span></param>
        <param name="keyType"><span data-ttu-id="afd99-104">Der Schlüsseltyp.</span><span class="sxs-lookup"><span data-stu-id="afd99-104">The key type.</span></span></param>
        <param name="keySize"><span data-ttu-id="afd99-105">Die Schlüsselgröße in Bytes.</span><span class="sxs-lookup"><span data-stu-id="afd99-105">The key size in bytes.</span></span> <span data-ttu-id="afd99-106">Beispiel:  1024 oder</span><span class="sxs-lookup"><span data-stu-id="afd99-106">For example;  1024 or</span></span>
            2048.</param>
        <param name="reuseKey"><span data-ttu-id="afd99-107">Gibt an, ob das gleiche Schlüsselpaar auf zertifikaterneuerung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="afd99-107">Indicates if the same key pair will be used on certificate renewal.</span></span></param>
        <summary>
            <span data-ttu-id="afd99-108">Initialisiert eine neue Instanz der KeyProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="afd99-108">Initializes a new instance of the KeyProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exportable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Exportable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Exportable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyProperties.Exportable" />
      <MemberSignature Language="VB.NET" Value="Public Property Exportable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Exportable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyProperties.Exportable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exportable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afd99-109">Ruft ab oder legt gibt an, ob der private Schlüssel exportiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="afd99-109">Gets or sets indicates if the private key can be exported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyProperties.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyProperties.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key_size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afd99-110">Ruft ab oder legt die Größe des Schlüssels in Bytes fest.</span><span class="sxs-lookup"><span data-stu-id="afd99-110">Gets or sets the key size in bytes.</span></span> <span data-ttu-id="afd99-111">Beispiel:  1024 oder 2048.</span><span class="sxs-lookup"><span data-stu-id="afd99-111">For example;  1024 or 2048.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public string KeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyProperties.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyType As String" />
      <MemberSignature Language="F#" Value="member this.KeyType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyProperties.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kty")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afd99-112">Ruft ab oder legt den Typ des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="afd99-112">Gets or sets the key type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReuseKey">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReuseKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReuseKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyProperties.ReuseKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ReuseKey As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReuseKey : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyProperties.ReuseKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reuse_key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afd99-113">Ruft ab oder legt gibt an, ob das gleiche Schlüsselpaar auf zertifikaterneuerung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="afd99-113">Gets or sets indicates if the same key pair will be used on certificate renewal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>