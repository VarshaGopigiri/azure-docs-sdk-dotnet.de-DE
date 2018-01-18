<Type Name="MagnitudeScoringFunction" FullName="Microsoft.Azure.Search.Models.MagnitudeScoringFunction">
  <TypeSignature Language="C#" Value="public class MagnitudeScoringFunction : Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MagnitudeScoringFunction extends Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MagnitudeScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class MagnitudeScoringFunction&#xA;Inherits ScoringFunction" />
  <TypeSignature Language="F#" Value="type MagnitudeScoringFunction = class&#xA;    inherit ScoringFunction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ScoringFunction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("magnitude")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="02764-101">Definiert eine Funktion, die Ergebnisse basierend auf der Größe eines numerischen Feldes steigert.</span><span class="sxs-lookup"><span data-stu-id="02764-101">Defines a function that boosts scores based on the magnitude of a numeric field.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MagnitudeScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringFunction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02764-102">Initialisiert eine neue Instanz der MagnitudeScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="02764-102">Initializes a new instance of the MagnitudeScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MagnitudeScoringFunction (string fieldName, double boost, Microsoft.Azure.Search.Models.MagnitudeScoringParameters parameters, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, class Microsoft.Azure.Search.Models.MagnitudeScoringParameters parameters, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringFunction.#ctor(System.String,System.Double,Microsoft.Azure.Search.Models.MagnitudeScoringParameters,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, parameters As MagnitudeScoringParameters, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MagnitudeScoringFunction : string * double * Microsoft.Azure.Search.Models.MagnitudeScoringParameters * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.MagnitudeScoringFunction" Usage="new Microsoft.Azure.Search.Models.MagnitudeScoringFunction (fieldName, boost, parameters, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.MagnitudeScoringParameters" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName"><span data-ttu-id="02764-103">Der Name des Felds als Eingabe für die Bewertungsfunktion verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="02764-103">The name of the field used as input to the scoring function.</span></span></param>
        <param name="boost"><span data-ttu-id="02764-104">Ein Multiplikator für die rohbewertung.</span><span class="sxs-lookup"><span data-stu-id="02764-104">A multiplier for the raw score.</span></span> <span data-ttu-id="02764-105">Muss eine positive Zahl sein nicht gleich 1.0.</span><span class="sxs-lookup"><span data-stu-id="02764-105">Must be a positive number not equal to 1.0.</span></span></param>
        <param name="parameters"><span data-ttu-id="02764-106">Parameterwerte für die Größenordnung Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="02764-106">Parameter values for the magnitude scoring function.</span></span></param>
        <param name="interpolation"><span data-ttu-id="02764-107">Ein Wert, der angibt, wie das Verstärkung über Dokument Bewertungen interpoliert werden wird. Der Standardwert ist "Linear".</span><span class="sxs-lookup"><span data-stu-id="02764-107">A value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="02764-108">Folgende Werte sind möglich: "linear", "konstant", "quadratische", "logarithmisch"</span><span class="sxs-lookup"><span data-stu-id="02764-108">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span></param>
        <summary>
            <span data-ttu-id="02764-109">Initialisiert eine neue Instanz der MagnitudeScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="02764-109">Initializes a new instance of the MagnitudeScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MagnitudeScoringFunction (string fieldName, double boost, double boostingRangeStart, double boostingRangeEnd, Nullable&lt;bool&gt; shouldBoostBeyondRangeByConstant = null, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, float64 boostingRangeStart, float64 boostingRangeEnd, valuetype System.Nullable`1&lt;bool&gt; shouldBoostBeyondRangeByConstant, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringFunction.#ctor(System.String,System.Double,System.Double,System.Double,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, boostingRangeStart As Double, boostingRangeEnd As Double, Optional shouldBoostBeyondRangeByConstant As Nullable(Of Boolean) = null, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MagnitudeScoringFunction : string * double * double * double * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.MagnitudeScoringFunction" Usage="new Microsoft.Azure.Search.Models.MagnitudeScoringFunction (fieldName, boost, boostingRangeStart, boostingRangeEnd, shouldBoostBeyondRangeByConstant, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="boostingRangeStart" Type="System.Double" />
        <Parameter Name="boostingRangeEnd" Type="System.Double" />
        <Parameter Name="shouldBoostBeyondRangeByConstant" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">To be added.</param>
        <param name="boost">To be added.</param>
        <param name="boostingRangeStart">To be added.</param>
        <param name="boostingRangeEnd">To be added.</param>
        <param name="shouldBoostBeyondRangeByConstant">To be added.</param>
        <param name="interpolation">To be added.</param>
        <summary>
            <span data-ttu-id="02764-110">Initialisiert eine neue Instanz der MagnitudeScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="02764-110">Initializes a new instance of the MagnitudeScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.MagnitudeScoringParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.MagnitudeScoringParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MagnitudeScoringFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As MagnitudeScoringParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.MagnitudeScoringParameters with get, set" Usage="Microsoft.Azure.Search.Models.MagnitudeScoringFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="magnitude")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.MagnitudeScoringParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02764-111">Abrufen oder Festlegen der Parameterwerte für die Größenordnung Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="02764-111">Gets or sets parameter values for the magnitude scoring function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MagnitudeScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="magnitudeScoringFunction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02764-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="02764-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="02764-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="02764-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>