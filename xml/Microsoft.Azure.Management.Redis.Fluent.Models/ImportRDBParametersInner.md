<Type Name="ImportRDBParametersInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner">
  <TypeSignature Language="C#" Value="public class ImportRDBParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImportRDBParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ImportRDBParametersInner" />
  <TypeSignature Language="F#" Value="type ImportRDBParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14847-101">Parameter für Redis Datenimportvorgang an.</span><span class="sxs-lookup"><span data-stu-id="14847-101">Parameters for Redis import operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRDBParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14847-102">Initialisiert eine neue Instanz der ImportRDBParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14847-102">Initializes a new instance of the ImportRDBParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRDBParametersInner (System.Collections.Generic.IList&lt;string&gt; files, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; files, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (files As IList(Of String), Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner (files, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="files" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="files"><span data-ttu-id="14847-103">zu importierende Dateien.</span><span class="sxs-lookup"><span data-stu-id="14847-103">files to import.</span></span></param>
        <param name="format"><span data-ttu-id="14847-104">Dateiformat.</span><span class="sxs-lookup"><span data-stu-id="14847-104">File format.</span></span></param>
        <summary>
            <span data-ttu-id="14847-105">Initialisiert eine neue Instanz der ImportRDBParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14847-105">Initializes a new instance of the ImportRDBParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Files : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14847-106">Ruft ab, oder legt die zu importierende Dateien fest.</span><span class="sxs-lookup"><span data-stu-id="14847-106">Gets or sets files to import.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14847-107">Ruft ab, oder legt ihn fest-Dateiformat.</span><span class="sxs-lookup"><span data-stu-id="14847-107">Gets or sets file format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ImportRDBParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="importRDBParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14847-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="14847-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="14847-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="14847-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>