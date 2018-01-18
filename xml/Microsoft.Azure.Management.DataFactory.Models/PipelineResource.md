<Type Name="PipelineResource" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineResource">
  <TypeSignature Language="C#" Value="public class PipelineResource : Microsoft.Azure.Management.DataFactory.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineResource extends Microsoft.Azure.Management.DataFactory.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineResource&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type PipelineResource = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bdb0b-101">Pipeline-Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-101">Pipeline resource type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.#ctor" />
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
            <span data-ttu-id="bdb0b-102">Initialisiert eine neue Instanz der PipelineResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-102">Initializes a new instance of the PipelineResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineResource (string id = null, string name = null, string type = null, string etag = null, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; activities = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, Nullable&lt;int&gt; concurrency = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; activities, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, valuetype System.Nullable`1&lt;int32&gt; concurrency) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.Activity},System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional etag As String = null, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional activities As IList(Of Activity) = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional concurrency As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineResource" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineResource (id, name, type, etag, additionalProperties, description, activities, parameters, concurrency)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="activities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="concurrency" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bdb0b-103">Der Ressourcenbezeichner.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-103">The resource identifier.</span></span></param>
        <param name="name"><span data-ttu-id="bdb0b-104">Der Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-104">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="bdb0b-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-105">The resource type.</span></span></param>
        <param name="etag"><span data-ttu-id="bdb0b-106">ETag identifiziert die Änderung in der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-106">Etag identifies change in the resource.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="bdb0b-107">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="bdb0b-107">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="bdb0b-108">Die Beschreibung der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-108">The description of the pipeline.</span></span></param>
        <param name="activities"><span data-ttu-id="bdb0b-109">Liste der Aktivitäten in der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-109">List of activities in pipeline.</span></span></param>
        <param name="parameters"><span data-ttu-id="bdb0b-110">Liste der Parameter für die Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-110">List of parameters for pipeline.</span></span></param>
        <param name="concurrency"><span data-ttu-id="bdb0b-111">Die maximale Anzahl von gleichzeitigen Ausführungen für die Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-111">The max number of concurrent runs for the pipeline.</span></span></param>
        <summary>
            <span data-ttu-id="bdb0b-112">Initialisiert eine neue Instanz der PipelineResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-112">Initializes a new instance of the PipelineResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; Activities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.Activity&gt; Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Property Activities As IList(Of Activity)" />
      <MemberSignature Language="F#" Value="member this.Activities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Activities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.Activity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdb0b-113">Ruft ab oder legt die Liste der Aktivitäten in Pipeline fest.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-113">Gets or sets list of activities in pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineResource.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdb0b-114">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="bdb0b-114">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Concurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Concurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Concurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Concurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property Concurrency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Concurrency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Concurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.concurrency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdb0b-115">Ruft ab oder legt die maximale Anzahl von gleichzeitigen Ausführungen für die Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-115">Gets or sets the max number of concurrent runs for the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdb0b-116">Ruft ab oder legt die Beschreibung der Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-116">Gets or sets the description of the pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, ParameterSpecification)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdb0b-117">Ruft ab oder legt die Liste der Parameter für die Pipeline.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-117">Gets or sets list of parameters for pipeline.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineResource.Validate " />
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
            <span data-ttu-id="bdb0b-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bdb0b-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bdb0b-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bdb0b-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>