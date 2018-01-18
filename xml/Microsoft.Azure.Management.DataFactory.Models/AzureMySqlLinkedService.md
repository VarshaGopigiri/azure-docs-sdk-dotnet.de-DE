<Type Name="AzureMySqlLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMySqlLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMySqlLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMySqlLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type AzureMySqlLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureMySql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="254c1-101">Azure MySQL-Datenbank verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="254c1-101">Azure MySQL database linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMySqlLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="254c1-102">Initialisiert eine neue Instanz der AzureMySqlLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="254c1-102">Initializes a new instance of the AzureMySqlLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMySqlLinkedService (Microsoft.Azure.Management.DataFactory.Models.SecureString connectionString, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.SecureString connectionString, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.#ctor(Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As SecureString, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService : Microsoft.Azure.Management.DataFactory.Models.SecureString * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService (connectionString, additionalProperties, connectVia, description, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="254c1-103">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="254c1-103">The connection string.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="254c1-104">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="254c1-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="254c1-105">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="254c1-105">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="254c1-106">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="254c1-106">Linked service description.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="254c1-107">Die verschlüsselten Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="254c1-107">The encrypted credential used for authentication.</span></span> <span data-ttu-id="254c1-108">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="254c1-108">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="254c1-109">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="254c1-109">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="254c1-110">Initialisiert eine neue Instanz der AzureMySqlLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="254c1-110">Initializes a new instance of the AzureMySqlLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As SecureString" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="254c1-111">Ruft ab oder legt die Verbindungszeichenfolge fest.</span><span class="sxs-lookup"><span data-stu-id="254c1-111">Gets or sets the connection string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="254c1-112">Ruft ab oder legt die verschlüsselte Anmeldeinformationen für die Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="254c1-112">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="254c1-113">Anmeldeinformationen werden verschlüsselt, mit dem Integration Runtime Anmeldeinformations-Manager.</span><span class="sxs-lookup"><span data-stu-id="254c1-113">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="254c1-114">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="254c1-114">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMySqlLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMySqlLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="254c1-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="254c1-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="254c1-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="254c1-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>