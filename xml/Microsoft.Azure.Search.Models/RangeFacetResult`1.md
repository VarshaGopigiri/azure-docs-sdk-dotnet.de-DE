<Type Name="RangeFacetResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.RangeFacetResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangeFacetResult&lt;T&gt; where T : struct" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangeFacetResult`1&lt;struct .ctor (class System.ValueType) T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.RangeFacetResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangeFacetResult(Of T)" />
  <TypeSignature Language="F#" Value="type RangeFacetResult&lt;'T (requires 'T : struct)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <ParameterAttribute>NotNullableValueTypeConstraint</ParameterAttribute>
        <BaseTypeName>System.ValueType</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="738f2-101">Ein Typ, der den Typ des Felds entspricht, der das Facet angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="738f2-101">A type that matches the type of the field to which the facet was applied.</span></span> <span data-ttu-id="738f2-102">Gültige Typen sind <c cref="T:System.DateTimeOffset">"DateTimeOffset"</c>, <c cref="T:System.Double">doppelte</c>, und <c cref="T:System.Int64">Int64</c> (lang in c#).</span><span class="sxs-lookup"><span data-stu-id="738f2-102">Valid types include <c cref="T:System.DateTimeOffset">DateTimeOffset</c>, <c cref="T:System.Double">Double</c>, and <c cref="T:System.Int64">Int64</c> (long in C#).</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="738f2-103">Ein einzelner Bucket des Bereichs Abfrageergebnisses eines Facets, das die Anzahl von Dokumenten mit einem Feldwert meldet, das in einem bestimmten Bereich angibt.</span><span class="sxs-lookup"><span data-stu-id="738f2-103">A single bucket of a range facet query result that reports the number of documents with a field value falling within a particular range.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.Count" />
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
            <span data-ttu-id="738f2-104">Ruft die ungefähre Anzahl der Dokumente, die in der durch dieses Facet beschrieben Bucket fallen.</span><span class="sxs-lookup"><span data-stu-id="738f2-104">Gets the approximate count of documents falling within the bucket described by this facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="From">
      <MemberSignature Language="C#" Value="public Nullable&lt;T&gt; From { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;!T&gt; From" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.From" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property From As Nullable(Of T)" />
      <MemberSignature Language="F#" Value="member this.From : Nullable&lt;'T (requires 'T : struct)&gt;" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.From" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="738f2-105">Ruft einen Wert, der angibt, die inklusive untere Grenze des Facets Bereichs, oder Null, um anzugeben, dass es keine untere Grenze (z. B. für den ersten Bucket).</span><span class="sxs-lookup"><span data-stu-id="738f2-105">Gets a value indicating the inclusive lower bound of the facet's range, or null to indicate that there is no lower bound (i.e. -- for the first bucket).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public Nullable&lt;T&gt; To { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;!T&gt; To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.RangeFacetResult`1.To" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property To As Nullable(Of T)" />
      <MemberSignature Language="F#" Value="member this.To : Nullable&lt;'T (requires 'T : struct)&gt;" Usage="Microsoft.Azure.Search.Models.RangeFacetResult&lt;'T (requires 'T : struct)&gt;.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="738f2-106">Ruft einen Wert, der angibt, die exklusive obere Grenze für des Facets Bereich oder Null, um anzugeben, dass es keine obere Grenze (z. B. für den letzten Bucket).</span><span class="sxs-lookup"><span data-stu-id="738f2-106">Gets a value indicating the exclusive upper bound of the facet's range, or null to indicate that there is no upper bound (i.e. -- for the last bucket).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>