<Type Name="Conflict" FullName="Microsoft.Azure.Documents.Conflict">
  <TypeSignature Language="C#" Value="public class Conflict : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Conflict extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Conflict" />
  <TypeSignature Language="VB.NET" Value="Public Class Conflict&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Conflict = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23359-101">Dies ist die in Konflikt stehenden Ressource durch eine parallele asynchrone entsteht in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="23359-101">This is the conflicting resource resulting from a concurrent async operation in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="23359-102">In seltenen Fällen kann ein Versionskonflikt bei einem asynchronen Vorgang (Insert, Replace und Delete) für eine Ressource auftreten.</span><span class="sxs-lookup"><span data-stu-id="23359-102">On rare occasions, during an async operation (insert, replace and delete), a version conflict may occur on a resource.</span></span>
            <span data-ttu-id="23359-103">Die in Konflikt stehenden Ressource wird als Konflikt Ressource beibehalten.</span><span class="sxs-lookup"><span data-stu-id="23359-103">The conflicting resource is persisted as a Conflict resource.</span></span>  
            <span data-ttu-id="23359-104">Konflikt Ressourcen überprüfen können Sie bestimmen, welche Vorgänge und Ressourcen, die in Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="23359-104">Inspecting Conflict resources will allow you to determine which operations and resources resulted in conflicts.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Conflict ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Conflict.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23359-105">Initialisiert eine neue Instanz der Klasse Konflikt in der Azure-Cosmos-DB-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="23359-105">Initialize a new instance of a Conflict class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResource&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetResource&lt;T&gt; () where T : Microsoft.Azure.Documents.Resourcenew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetResource&lt;.ctor (class Microsoft.Azure.Documents.Resource) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Conflict.GetResource``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResource(Of T As {ResourceNew}) () As T" />
      <MemberSignature Language="F#" Value="member this.GetResource : unit -&gt; 'T (requires 'T :&gt; Microsoft.Azure.Documents.Resource and 'T : (new : unit -&gt; 'T))" Usage="conflict.GetResource " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"><span data-ttu-id="23359-106">Der zurückgegebene Typ der in Konflikt stehenden Ressource.</span><span class="sxs-lookup"><span data-stu-id="23359-106">The returned type of conflicting resource.</span></span></typeparam>
        <summary>
            <span data-ttu-id="23359-107">Ruft die in Konflikt stehenden Ressource im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="23359-107">Gets the conflicting resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="23359-108">Die in Konflikt stehenden Ressource.</span><span class="sxs-lookup"><span data-stu-id="23359-108">The conflicting resource.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationKind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.OperationKind OperationKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.OperationKind OperationKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.OperationKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationKind As OperationKind" />
      <MemberSignature Language="F#" Value="member this.OperationKind : Microsoft.Azure.Documents.OperationKind" Usage="Microsoft.Azure.Documents.Conflict.OperationKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23359-109">Ruft den Vorgang mit der der Konflikt in der Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="23359-109">Gets the operation that resulted in the conflict in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23359-110">Einer der Werte von der <see cref="P:Microsoft.Azure.Documents.Conflict.OperationKind" /> Enumeration.</span><span class="sxs-lookup"><span data-stu-id="23359-110">One of the values of the <see cref="P:Microsoft.Azure.Documents.Conflict.OperationKind" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public Type ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As Type" />
      <MemberSignature Language="F#" Value="member this.ResourceType : Type" Usage="Microsoft.Azure.Documents.Conflict.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23359-111">Ruft den Typ der in Konflikt stehenden Ressource im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="23359-111">Gets the type of the conflicting resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="23359-112">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="23359-112">The type of the resource.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Conflict.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string" Usage="Microsoft.Azure.Documents.Conflict.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23359-113">Ruft die Ressourcen-ID für den Konflikt im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="23359-113">Gets the resource ID for the conflict in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>