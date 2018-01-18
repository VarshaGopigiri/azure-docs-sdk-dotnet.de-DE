<Type Name="DatasetZipDeflateCompression" FullName="Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression">
  <TypeSignature Language="C#" Value="public class DatasetZipDeflateCompression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatasetZipDeflateCompression extends Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression" />
  <TypeSignature Language="VB.NET" Value="Public Class DatasetZipDeflateCompression&#xA;Inherits DatasetCompression" />
  <TypeSignature Language="F#" Value="type DatasetZipDeflateCompression = class&#xA;    inherit DatasetCompression" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.DatasetCompression</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("ZipDeflate")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="85526-101">Die Komprimierung ZipDeflate Methode für ein Dataset verwendet.</span><span class="sxs-lookup"><span data-stu-id="85526-101">The ZipDeflate compression method used on a dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatasetZipDeflateCompression ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85526-102">Initialisiert eine neue Instanz der DatasetZipDeflateCompression-Klasse.</span><span class="sxs-lookup"><span data-stu-id="85526-102">Initializes a new instance of the DatasetZipDeflateCompression class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatasetZipDeflateCompression (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string level = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string level) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional level As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression" Usage="new Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression (additionalProperties, level)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="level" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="85526-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="85526-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="level"><span data-ttu-id="85526-104">Die Komprimierungsebene ZipDeflate</span><span class="sxs-lookup"><span data-stu-id="85526-104">The ZipDeflate compression level.</span></span> <span data-ttu-id="85526-105">Folgende Werte sind möglich: "Optimal", "Fastest"</span><span class="sxs-lookup"><span data-stu-id="85526-105">Possible values include: 'Optimal', 'Fastest'</span></span></param>
        <summary>
            <span data-ttu-id="85526-106">Initialisiert eine neue Instanz der DatasetZipDeflateCompression-Klasse.</span><span class="sxs-lookup"><span data-stu-id="85526-106">Initializes a new instance of the DatasetZipDeflateCompression class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public string Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As String" />
      <MemberSignature Language="F#" Value="member this.Level : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DatasetZipDeflateCompression.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85526-107">Ermittelt oder definiert die Komprimierungsebene ZipDeflate.</span><span class="sxs-lookup"><span data-stu-id="85526-107">Gets or sets the ZipDeflate compression level.</span></span> <span data-ttu-id="85526-108">Folgende Werte sind möglich: "Optimal", "Fastest"</span><span class="sxs-lookup"><span data-stu-id="85526-108">Possible values include: 'Optimal', 'Fastest'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>