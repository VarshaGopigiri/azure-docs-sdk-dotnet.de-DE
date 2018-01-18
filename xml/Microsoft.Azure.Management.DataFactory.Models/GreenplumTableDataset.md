<Type Name="GreenplumTableDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset">
  <TypeSignature Language="C#" Value="public class GreenplumTableDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GreenplumTableDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class GreenplumTableDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type GreenplumTableDataset = class&#xA;    inherit Dataset" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Dataset</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("GreenplumTable")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7fa76-101">Greenplum Datenbank Dataset.</span><span class="sxs-lookup"><span data-stu-id="7fa76-101">Greenplum Database dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GreenplumTableDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fa76-102">Initialisiert eine neue Instanz der GreenplumTableDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7fa76-102">Initializes a new instance of the GreenplumTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GreenplumTableDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset (linkedServiceName, additionalProperties, description, structure, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="7fa76-103">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="7fa76-103">Linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="7fa76-104">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="7fa76-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="7fa76-105">Beschreibung des Datasets.</span><span class="sxs-lookup"><span data-stu-id="7fa76-105">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="7fa76-106">Spalten, die die Struktur des Datasets zu definieren.</span><span class="sxs-lookup"><span data-stu-id="7fa76-106">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="7fa76-107">Typ: Array (oder Ausdruck mit ResultType-Array), ItemType: DatasetDataElement.</span><span class="sxs-lookup"><span data-stu-id="7fa76-107">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="7fa76-108">Parameter für das Dataset.</span><span class="sxs-lookup"><span data-stu-id="7fa76-108">Parameters for dataset.</span></span></param>
        <summary>
            <span data-ttu-id="7fa76-109">Initialisiert eine neue Instanz der GreenplumTableDataset-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7fa76-109">Initializes a new instance of the GreenplumTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.GreenplumTableDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="greenplumTableDataset.Validate " />
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
            <span data-ttu-id="7fa76-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7fa76-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7fa76-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7fa76-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>