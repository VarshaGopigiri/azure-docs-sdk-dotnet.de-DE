<Type Name="FunctionsGetHeaders" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders">
  <TypeSignature Language="C#" Value="public class FunctionsGetHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FunctionsGetHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class FunctionsGetHeaders" />
  <TypeSignature Language="F#" Value="type FunctionsGetHeaders = class" />
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
            <span data-ttu-id="21d78-101">Definiert die Header für die Get-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="21d78-101">Defines headers for Get operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionsGetHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="21d78-102">Initialisiert eine neue Instanz der FunctionsGetHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="21d78-102">Initializes a new instance of the FunctionsGetHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FunctionsGetHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders : string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag"><span data-ttu-id="21d78-103">Das aktuelle Entitätstag für die Funktion.</span><span class="sxs-lookup"><span data-stu-id="21d78-103">The current entity tag for the function.</span></span> <span data-ttu-id="21d78-104">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="21d78-104">This is an opaque string.</span></span> <span data-ttu-id="21d78-105">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="21d78-105">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="21d78-106">Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</span><span class="sxs-lookup"><span data-stu-id="21d78-106">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="21d78-107">Initialisiert eine neue Instanz der FunctionsGetHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="21d78-107">Initializes a new instance of the FunctionsGetHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders.ETag" />
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
            <span data-ttu-id="21d78-108">Ruft ab oder legt das aktuelle Entitätstag für die Funktion.</span><span class="sxs-lookup"><span data-stu-id="21d78-108">Gets or sets the current entity tag for the function.</span></span> <span data-ttu-id="21d78-109">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="21d78-109">This is an opaque string.</span></span> <span data-ttu-id="21d78-110">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="21d78-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="21d78-111">Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</span><span class="sxs-lookup"><span data-stu-id="21d78-111">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>