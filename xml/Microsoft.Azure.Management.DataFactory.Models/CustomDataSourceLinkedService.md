<Type Name="CustomDataSourceLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService">
  <TypeSignature Language="C#" Value="public class CustomDataSourceLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomDataSourceLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomDataSourceLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type CustomDataSourceLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("CustomDataSource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8ebd7-101">Benutzerdefinierte verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-101">Custom linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDataSourceLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService.#ctor" />
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
            <span data-ttu-id="8ebd7-102">Initialisiert eine neue Instanz der CustomDataSourceLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-102">Initializes a new instance of the CustomDataSourceLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomDataSourceLinkedService (object typeProperties, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object typeProperties, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (typeProperties As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string -&gt; Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService (typeProperties, additionalProperties, connectVia, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="typeProperties" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="typeProperties"><span data-ttu-id="8ebd7-103">Eigenschaften des benutzerdefinierten verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-103">Custom linked service properties.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="8ebd7-104">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="8ebd7-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="8ebd7-105">Der Integration Common Language Runtime-Verweis.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-105">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="8ebd7-106">Beschreibung des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-106">Linked service description.</span></span></param>
        <summary>
            <span data-ttu-id="8ebd7-107">Initialisiert eine neue Instanz der CustomDataSourceLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-107">Initializes a new instance of the CustomDataSourceLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeProperties">
      <MemberSignature Language="C#" Value="public object TypeProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TypeProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService.TypeProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeProperties As Object" />
      <MemberSignature Language="F#" Value="member this.TypeProperties : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService.TypeProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ebd7-108">Ruft ab, oder legt ihn fest benutzerdefinierten verknüpften Diensteigenschaften.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-108">Gets or sets custom linked service properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomDataSourceLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customDataSourceLinkedService.Validate " />
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
            <span data-ttu-id="8ebd7-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8ebd7-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8ebd7-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8ebd7-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>