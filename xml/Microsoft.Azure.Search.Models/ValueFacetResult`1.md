<Type Name="ValueFacetResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class ValueFacetResult&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValueFacetResult`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ValueFacetResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ValueFacetResult(Of T)" />
  <TypeSignature Language="F#" Value="type ValueFacetResult&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="eb2e7-101">Ein Typ, der den Typ des Felds entspricht, der das Facet angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="eb2e7-101">A type that matches the type of the field to which the facet was applied.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="eb2e7-102">Ein einzelner Bucket des einfachen oder Abfrageergebnisses eines Facets, das meldet die Anzahl der Dokumente mit einem Feld meldet, das in einem bestimmten Intervall liegt oder einen bestimmten Wert aufweist.</span><span class="sxs-lookup"><span data-stu-id="eb2e7-102">A single bucket of a simple or interval facet query result that reports the number of documents with a field falling within a particular interval or having a specific value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ValueFacetResult`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb2e7-103">Ruft die ungefähre Anzahl der Dokumente, die in der durch dieses Facet beschrieben Bucket fallen.</span><span class="sxs-lookup"><span data-stu-id="eb2e7-103">Gets the approximate count of documents falling within the bucket described by this facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public T Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ValueFacetResult`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As T" />
      <MemberSignature Language="F#" Value="member this.Value : 'T" Usage="Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb2e7-104">Ruft den Wert des Facets oder die inklusive untere Grenze ab, wenn es sich um ein intervallfacet handelt.</span><span class="sxs-lookup"><span data-stu-id="eb2e7-104">Gets the value of the facet, or the inclusive lower bound if it's an interval facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>