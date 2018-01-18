<Type Name="LoadParameters" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters">
  <TypeSignature Language="C#" Value="public class LoadParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadParameters" />
  <TypeSignature Language="F#" Value="type LoadParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="079d3-101">Parameter für das Laden von Inhalt erforderlich.</span><span class="sxs-lookup"><span data-stu-id="079d3-101">Parameters required for content load.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="079d3-102">Initialisiert eine neue Instanz der LoadParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="079d3-102">Initializes a new instance of the LoadParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadParameters (System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters contentPaths" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths"><span data-ttu-id="079d3-103">Der Pfad zum Inhalt geladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="079d3-103">The path to the content to be loaded.</span></span>
            <span data-ttu-id="079d3-104">Pfad muss sich auf eine relative Datei-URL des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="079d3-104">Path should be a relative file URL of the origin.</span></span></param>
        <summary>
            <span data-ttu-id="079d3-105">Initialisiert eine neue Instanz der LoadParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="079d3-105">Initializes a new instance of the LoadParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentPaths">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContentPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContentPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters.ContentPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentPaths As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentPaths : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters.ContentPaths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentPaths")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="079d3-106">Ruft ab oder legt den Pfad fest, auf die Inhalte geladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="079d3-106">Gets or sets the path to the content to be loaded.</span></span> <span data-ttu-id="079d3-107">Pfad muss sich auf eine relative Datei-URL des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="079d3-107">Path should be a relative file URL of the origin.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.LoadParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="loadParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="079d3-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="079d3-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="079d3-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="079d3-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>