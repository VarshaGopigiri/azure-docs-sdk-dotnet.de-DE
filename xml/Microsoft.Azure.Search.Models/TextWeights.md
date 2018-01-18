<Type Name="TextWeights" FullName="Microsoft.Azure.Search.Models.TextWeights">
  <TypeSignature Language="C#" Value="public class TextWeights" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TextWeights extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TextWeights" />
  <TypeSignature Language="VB.NET" Value="Public Class TextWeights" />
  <TypeSignature Language="F#" Value="type TextWeights = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ed72b-101">Gewichtungen definiert für die Übereinstimmungen erhöhen soll in Suchabfragen Bewertung Indexfelder.</span><span class="sxs-lookup"><span data-stu-id="ed72b-101">Defines weights on index fields for which matches should boost scoring in search queries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TextWeights ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TextWeights.#ctor" />
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
            <span data-ttu-id="ed72b-102">Initialisiert eine neue Instanz der TextWeights-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed72b-102">Initializes a new instance of the TextWeights class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TextWeights (System.Collections.Generic.IDictionary&lt;string,double&gt; weights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; weights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TextWeights.#ctor(System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (weights As IDictionary(Of String, Double))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TextWeights : System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; Microsoft.Azure.Search.Models.TextWeights" Usage="new Microsoft.Azure.Search.Models.TextWeights weights" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="weights" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="weights"><span data-ttu-id="ed72b-103">Das Wörterbuch von Dokument Bewertung zur Verbesserung der pro feldgewichtungen.</span><span class="sxs-lookup"><span data-stu-id="ed72b-103">The dictionary of per-field weights to boost document scoring.</span></span> <span data-ttu-id="ed72b-104">Die Schlüssel sind die Feldnamen, und die Werte sind die Gewichtungen für jedes Feld.</span><span class="sxs-lookup"><span data-stu-id="ed72b-104">The keys are field names and the values are the weights for each field.</span></span></param>
        <summary>
            <span data-ttu-id="ed72b-105">Initialisiert eine neue Instanz der TextWeights-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed72b-105">Initializes a new instance of the TextWeights class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TextWeights.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="textWeights.Validate " />
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
            <span data-ttu-id="ed72b-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ed72b-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ed72b-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ed72b-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Weights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,double&gt; Weights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Weights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TextWeights.Weights" />
      <MemberSignature Language="VB.NET" Value="Public Property Weights As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Weights : System.Collections.Generic.IDictionary&lt;string, double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TextWeights.Weights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed72b-108">Ermittelt oder definiert das Wörterbuch der zur Verbesserung der Bewertung Dokument pro feldgewichtungen.</span><span class="sxs-lookup"><span data-stu-id="ed72b-108">Gets or sets the dictionary of per-field weights to boost document scoring.</span></span> <span data-ttu-id="ed72b-109">Die Schlüssel sind die Feldnamen, und die Werte sind die Gewichtungen für jedes Feld.</span><span class="sxs-lookup"><span data-stu-id="ed72b-109">The keys are field names and the values are the weights for each field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>