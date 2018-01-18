<Type Name="OperationMetricSpecification" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification">
  <TypeSignature Language="C#" Value="public class OperationMetricSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationMetricSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationMetricSpecification" />
  <TypeSignature Language="F#" Value="type OperationMetricSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8970b-101">Details zu einem Vorgang im Zusammenhang mit Metriken.</span><span class="sxs-lookup"><span data-stu-id="8970b-101">Details about an operation related to metrics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.#ctor" />
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
            <span data-ttu-id="8970b-102">Initialisiert eine neue Instanz der OperationMetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8970b-102">Initializes a new instance of the OperationMetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricSpecification (string name = null, string displayName = null, string displayDescription = null, string unit = null, string aggregationType = null, string enableRegionalMdmAccount = null, string sourceMdmAccount = null, string sourceMdmNamespace = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; availabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string displayDescription, string unit, string aggregationType, string enableRegionalMdmAccount, string sourceMdmAccount, string sourceMdmNamespace, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; availabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional displayDescription As String = null, Optional unit As String = null, Optional aggregationType As String = null, Optional enableRegionalMdmAccount As String = null, Optional sourceMdmAccount As String = null, Optional sourceMdmNamespace As String = null, Optional availabilities As IList(Of OperationMetricAvailability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification (name, displayName, displayDescription, unit, aggregationType, enableRegionalMdmAccount, sourceMdmAccount, sourceMdmNamespace, availabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="displayDescription" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="aggregationType" Type="System.String" />
        <Parameter Name="enableRegionalMdmAccount" Type="System.String" />
        <Parameter Name="sourceMdmAccount" Type="System.String" />
        <Parameter Name="sourceMdmNamespace" Type="System.String" />
        <Parameter Name="availabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="8970b-103">Der Name der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-103">The name of the metric.</span></span></param>
        <param name="displayName"><span data-ttu-id="8970b-104">Lokalisierten Anzeigenamen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-104">Localized display name of the metric.</span></span></param>
        <param name="displayDescription"><span data-ttu-id="8970b-105">Die Beschreibung der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-105">The description of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="8970b-106">Die Einheit, der die Metrik in gemessen wird.</span><span class="sxs-lookup"><span data-stu-id="8970b-106">The unit that the metric is measured in.</span></span></param>
        <param name="aggregationType"><span data-ttu-id="8970b-107">Der Typ der Metrik Aggregation.</span><span class="sxs-lookup"><span data-stu-id="8970b-107">The type of metric aggregation.</span></span></param>
        <param name="enableRegionalMdmAccount"><span data-ttu-id="8970b-108">Und zwar unabhängig davon, ob der Dienst regionale MDM-Konten verwendet.</span><span class="sxs-lookup"><span data-stu-id="8970b-108">Whether or not the service is using regional MDM accounts.</span></span></param>
        <param name="sourceMdmAccount"><span data-ttu-id="8970b-109">Der Name des Kontos MDM.</span><span class="sxs-lookup"><span data-stu-id="8970b-109">The name of the MDM account.</span></span></param>
        <param name="sourceMdmNamespace"><span data-ttu-id="8970b-110">Der Name des MDM-Namespace.</span><span class="sxs-lookup"><span data-stu-id="8970b-110">The name of the MDM namespace.</span></span></param>
        <param name="availabilities"><span data-ttu-id="8970b-111">Definiert, wie oft die Daten für Metriken sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8970b-111">Defines how often data for metrics becomes available.</span></span></param>
        <summary>
            <span data-ttu-id="8970b-112">Initialisiert eine neue Instanz der OperationMetricSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8970b-112">Initializes a new instance of the OperationMetricSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregationType">
      <MemberSignature Language="C#" Value="public string AggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.AggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregationType As String" />
      <MemberSignature Language="F#" Value="member this.AggregationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.AggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-113">Ruft ab oder legt den Typ der Metrik Aggregation.</span><span class="sxs-lookup"><span data-stu-id="8970b-113">Gets or sets the type of metric aggregation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Availabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; Availabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; Availabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Availabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Availabilities As IList(Of OperationMetricAvailability)" />
      <MemberSignature Language="F#" Value="member this.Availabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Availabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-114">Ruft ab oder legt ihn fest definiert, wie oft die Daten für Metriken sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8970b-114">Gets or sets defines how often data for metrics becomes available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayDescription">
      <MemberSignature Language="C#" Value="public string DisplayDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayDescription As String" />
      <MemberSignature Language="F#" Value="member this.DisplayDescription : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-115">Ruft ab oder legt die Beschreibung der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-115">Gets or sets the description of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-116">Ruft ab, oder legt ihn fest lokalisierten Anzeigenamen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-116">Gets or sets localized display name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRegionalMdmAccount">
      <MemberSignature Language="C#" Value="public string EnableRegionalMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnableRegionalMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.EnableRegionalMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRegionalMdmAccount As String" />
      <MemberSignature Language="F#" Value="member this.EnableRegionalMdmAccount : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.EnableRegionalMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableRegionalMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-117">Ruft ab oder legt sie fest, und zwar unabhängig davon, ob der Dienst regionale MDM-Konten verwendet.</span><span class="sxs-lookup"><span data-stu-id="8970b-117">Gets or sets whether or not the service is using regional MDM accounts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-118">Ruft ab oder legt den Namen der Metrik.</span><span class="sxs-lookup"><span data-stu-id="8970b-118">Gets or sets the name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmAccount">
      <MemberSignature Language="C#" Value="public string SourceMdmAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmAccount As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmAccount : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-119">Ruft ab oder legt den Namen des Kontos MDM fest.</span><span class="sxs-lookup"><span data-stu-id="8970b-119">Gets or sets the name of the MDM account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceMdmNamespace">
      <MemberSignature Language="C#" Value="public string SourceMdmNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceMdmNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceMdmNamespace As String" />
      <MemberSignature Language="F#" Value="member this.SourceMdmNamespace : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.SourceMdmNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceMdmNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-120">Ruft ab oder legt den Namen des MDM-Namespace.</span><span class="sxs-lookup"><span data-stu-id="8970b-120">Gets or sets the name of the MDM namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8970b-121">Ruft ab oder legt die Einheit, der die Metrik in gemessen wird.</span><span class="sxs-lookup"><span data-stu-id="8970b-121">Gets or sets the unit that the metric is measured in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>