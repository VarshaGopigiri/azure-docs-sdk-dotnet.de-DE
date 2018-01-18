<Type Name="PurgeParameters" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters">
  <TypeSignature Language="C#" Value="public class PurgeParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PurgeParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PurgeParameters" />
  <TypeSignature Language="F#" Value="type PurgeParameters = class" />
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
            <span data-ttu-id="dd921-101">Für inhaltsbereinigung erforderliche Parameter.</span><span class="sxs-lookup"><span data-stu-id="dd921-101">Parameters required for content purge.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PurgeParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd921-102">Initialisiert eine neue Instanz der PurgeParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd921-102">Initializes a new instance of the PurgeParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PurgeParameters (System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters contentPaths" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths"><span data-ttu-id="dd921-103">Der Pfad zum Inhalt gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="dd921-103">The path to the content to be purged.</span></span>
            <span data-ttu-id="dd921-104">Hierbei kann es sich um einen Dateipfad oder ein Platzhalter-Verzeichnis beschreiben.</span><span class="sxs-lookup"><span data-stu-id="dd921-104">Can describe a file path or a wild card directory.</span></span></param>
        <summary>
            <span data-ttu-id="dd921-105">Initialisiert eine neue Instanz der PurgeParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd921-105">Initializes a new instance of the PurgeParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentPaths">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContentPaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContentPaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters.ContentPaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentPaths As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentPaths : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters.ContentPaths" />
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
            <span data-ttu-id="dd921-106">Ruft ab oder legt den Pfad zum Inhalt gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="dd921-106">Gets or sets the path to the content to be purged.</span></span> <span data-ttu-id="dd921-107">Hierbei kann es sich um einen Dateipfad oder ein Platzhalter-Verzeichnis beschreiben.</span><span class="sxs-lookup"><span data-stu-id="dd921-107">Can describe a file path or a wild card directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.PurgeParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="purgeParameters.Validate " />
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
            <span data-ttu-id="dd921-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dd921-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dd921-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dd921-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>