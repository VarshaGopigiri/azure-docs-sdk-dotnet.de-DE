<Type Name="TransformationsUpdateHeaders" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders">
  <TypeSignature Language="C#" Value="public class TransformationsUpdateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransformationsUpdateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class TransformationsUpdateHeaders" />
  <TypeSignature Language="F#" Value="type TransformationsUpdateHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8995c-101">Definiert die Header für Update-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8995c-101">Defines headers for Update operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransformationsUpdateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8995c-102">Initialisiert eine neue Instanz der TransformationsUpdateHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8995c-102">Initializes a new instance of the TransformationsUpdateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransformationsUpdateHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="8995c-103">Das aktuelle Entitätstag für die Transformation.</span><span class="sxs-lookup"><span data-stu-id="8995c-103">The current entity tag for the transformation.</span></span>
            <span data-ttu-id="8995c-104">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8995c-104">This is an opaque string.</span></span> <span data-ttu-id="8995c-105">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="8995c-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="8995c-106">Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</span><span class="sxs-lookup"><span data-stu-id="8995c-106">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="8995c-107">Initialisiert eine neue Instanz der TransformationsUpdateHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8995c-107">Initializes a new instance of the TransformationsUpdateHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8995c-108">Ruft ab oder legt das aktuelle Entitätstag für die Transformation.</span><span class="sxs-lookup"><span data-stu-id="8995c-108">Gets or sets the current entity tag for the transformation.</span></span> <span data-ttu-id="8995c-109">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8995c-109">This is an opaque string.</span></span> <span data-ttu-id="8995c-110">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="8995c-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="8995c-111">Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</span><span class="sxs-lookup"><span data-stu-id="8995c-111">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>