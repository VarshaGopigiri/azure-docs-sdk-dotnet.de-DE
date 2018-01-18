<Type Name="TableQueryableExtensions" FullName="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions">
  <TypeSignature Language="C#" Value="public static class TableQueryableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed TableQueryableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableQueryableExtensions" />
  <TypeSignature Language="F#" Value="type TableQueryableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1f0a8-101">Stellt einen Satz von Erweiterungsmethoden für Objekte vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-101">Provides a set of extension methods for objects of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AsTableQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; AsTableQuery&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; AsTableQuery&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.AsTableQuery``1(System.Linq.IQueryable{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AsTableQuery(Of TElement) (query As IQueryable(Of TElement)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member AsTableQuery : System.Linq.IQueryable&lt;'Element&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.AsTableQuery query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="1f0a8-102">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-102">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="1f0a8-103">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-103">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <summary>
            <span data-ttu-id="1f0a8-104">Gibt an, dass eine Abfrage zurückgegeben werden, als ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-104">Specifies that a query be returned as a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object.</span></span>
            </summary>
        <returns><span data-ttu-id="1f0a8-105">Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-105">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="Resolve&lt;TElement,TResolved&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TResolved&gt; Resolve&lt;TElement,TResolved&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResolved&gt; resolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TResolved&gt; Resolve&lt;TElement, TResolved&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResolved&gt; resolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.Resolve``2(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resolve(Of TElement, TResolved) (query As IQueryable(Of TElement), resolver As EntityResolver(Of TResolved)) As TableQuery(Of TResolved)" />
      <MemberSignature Language="F#" Value="static member Resolve : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Resolved&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Resolved&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.Resolve (query, resolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TResolved&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
        <TypeParameter Name="TResolved" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResolved&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="1f0a8-106">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-106">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResolved"><span data-ttu-id="1f0a8-107">Der Typ des Konfliktlösers.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-107">The type of the resolver.</span></span></typeparam>
        <param name="query"><span data-ttu-id="1f0a8-108">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-108">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="resolver"><span data-ttu-id="1f0a8-109">Der Typ der Entitäten-Resolver <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-109">The entity resolver, of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />.</span></span></param>
        <summary>
            <span data-ttu-id="1f0a8-110">Gibt eine Entitäten-Resolver für die Abfrage an.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-110">Specifies an entity resolver for the query.</span></span>
            </summary>
        <returns><span data-ttu-id="1f0a8-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> mit den angegebenen Konfliktlöser.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-111">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> with the specified resolver.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithContext&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; WithContext&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; WithContext&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithContext``1(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WithContext : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithContext (query, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="1f0a8-112">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-112">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="1f0a8-113">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-113">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="operationContext"><span data-ttu-id="1f0a8-114">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-114">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="1f0a8-115">Gibt eine <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> für die Abfrage.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-115">Specifies an <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> for the query.</span></span>
            </summary>
        <returns><span data-ttu-id="1f0a8-116">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt mit den angegebenen Vorgangskontext.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object with the specified operation context.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithOptions&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; WithOptions&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; WithOptions&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithOptions``1(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WithOptions(Of TElement) (query As IQueryable(Of TElement), options As TableRequestOptions) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member WithOptions : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithOptions (query, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="1f0a8-117">Der Entitätstyp der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-117">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="1f0a8-118">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-118">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="options"><span data-ttu-id="1f0a8-119">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-119">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <summary>
            <span data-ttu-id="1f0a8-120">Gibt einen Satz von <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> mit dem die Abfrage ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-120">Specifies a set of <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> with which the query will be executed.</span></span>
            </summary>
        <returns><span data-ttu-id="1f0a8-121">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt, für die angegebene Anforderung Optionen festgelegt.</span><span class="sxs-lookup"><span data-stu-id="1f0a8-121">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> object with the specified request options set.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
  </Members>
</Type>