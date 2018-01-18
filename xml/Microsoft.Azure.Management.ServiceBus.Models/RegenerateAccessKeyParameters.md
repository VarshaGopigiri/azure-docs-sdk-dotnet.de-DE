<Type Name="RegenerateAccessKeyParameters" FullName="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters">
  <TypeSignature Language="C#" Value="public class RegenerateAccessKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegenerateAccessKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegenerateAccessKeyParameters" />
  <TypeSignature Language="F#" Value="type RegenerateAccessKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20850-101">Parameter für den Vorgang erneut generieren Autorisierungsregel bereitgestellte gibt an, welche Schlüssel Neeeds zurückgesetzt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="20850-101">Parameters supplied to the Regenerate Authorization Rule operation, specifies which key neeeds to be reset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateAccessKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20850-102">Initialisiert eine neue Instanz der RegenerateAccessKeyParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20850-102">Initializes a new instance of the RegenerateAccessKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateAccessKeyParameters (Microsoft.Azure.Management.ServiceBus.Models.KeyType keyType, string key = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ServiceBus.Models.KeyType keyType, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.#ctor(Microsoft.Azure.Management.ServiceBus.Models.KeyType,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters : Microsoft.Azure.Management.ServiceBus.Models.KeyType * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" Usage="new Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters (keyType, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.ServiceBus.Models.KeyType" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyType"><span data-ttu-id="20850-103">Der Zugriffsschlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="20850-103">The access key to regenerate.</span></span> <span data-ttu-id="20850-104">Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</span><span class="sxs-lookup"><span data-stu-id="20850-104">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span></param>
        <param name="key"><span data-ttu-id="20850-105">Dies ist optional, wenn der Schlüsselwert angegeben, wird zurückgesetzt "KeyType" Wert "oder" Autogenerate Schlüssel-Wert für "KeyType" festgelegt</span><span class="sxs-lookup"><span data-stu-id="20850-105">Optional, if the key value provided, is reset for KeyType value or autogenerate Key value set for keyType</span></span></param>
        <summary>
            <span data-ttu-id="20850-106">Initialisiert eine neue Instanz der RegenerateAccessKeyParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20850-106">Initializes a new instance of the RegenerateAccessKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20850-107">Ruft ab oder legt ihn fest optional, wenn der Schlüsselwert angegeben, wird zurückgesetzt "KeyType" Wert "oder" Autogenerate Schlüssel-Wert für "KeyType" festgelegt</span><span class="sxs-lookup"><span data-stu-id="20850-107">Gets or sets optional, if the key value provided, is reset for KeyType value or autogenerate Key value set for keyType</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.KeyType KeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Models.KeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyType As KeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.Management.ServiceBus.Models.KeyType with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.KeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20850-108">Ruft ab oder legt den Zugriffsschlüssel erneut generieren.</span><span class="sxs-lookup"><span data-stu-id="20850-108">Gets or sets the access key to regenerate.</span></span> <span data-ttu-id="20850-109">Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</span><span class="sxs-lookup"><span data-stu-id="20850-109">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="regenerateAccessKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20850-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="20850-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="20850-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="20850-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>