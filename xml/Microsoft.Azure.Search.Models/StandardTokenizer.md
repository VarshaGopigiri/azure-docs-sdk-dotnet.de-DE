<Type Name="StandardTokenizer" FullName="Microsoft.Azure.Search.Models.StandardTokenizer">
  <TypeSignature Language="C#" Value="public class StandardTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StandardTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StandardTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class StandardTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type StandardTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StandardTokenizer")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Obsolete("This type is obsolete. Please use StandardTokenizerV2 instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="62dcc-101">Unterbricht Text nach den Regeln für Unicode-Textsegmentierung an.</span><span class="sxs-lookup"><span data-stu-id="62dcc-101">Breaks text following the Unicode Text Segmentation rules.</span></span> <span data-ttu-id="62dcc-102">Diese Tokenizer wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="62dcc-102">This tokenizer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/StandardTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StandardTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StandardTokenizer.#ctor" />
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
            <span data-ttu-id="62dcc-103">Initialisiert eine neue Instanz der StandardTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="62dcc-103">Initializes a new instance of the StandardTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StandardTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StandardTokenizer.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StandardTokenizer : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.StandardTokenizer" Usage="new Microsoft.Azure.Search.Models.StandardTokenizer (name, maxTokenLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="maxTokenLength">To be added.</param>
        <summary>
            <span data-ttu-id="62dcc-104">Initialisiert eine neue Instanz der StandardTokenizer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="62dcc-104">Initializes a new instance of the StandardTokenizer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StandardTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StandardTokenizer.MaxTokenLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="62dcc-105">Ruft ab oder legt die maximale Tokenlänge.</span><span class="sxs-lookup"><span data-stu-id="62dcc-105">Gets or sets the maximum token length.</span></span> <span data-ttu-id="62dcc-106">Standardwert ist 255.</span><span class="sxs-lookup"><span data-stu-id="62dcc-106">Default is 255.</span></span> <span data-ttu-id="62dcc-107">Token, die länger als die maximale Länge werden geteilt.</span><span class="sxs-lookup"><span data-stu-id="62dcc-107">Tokens longer than the maximum length are split</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StandardTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="standardTokenizer.Validate " />
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
            <span data-ttu-id="62dcc-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="62dcc-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="62dcc-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="62dcc-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>