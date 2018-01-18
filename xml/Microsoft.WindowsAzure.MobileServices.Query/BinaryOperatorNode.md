<Type Name="BinaryOperatorNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode">
  <TypeSignature Language="C#" Value="public sealed class BinaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BinaryOperatorNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BinaryOperatorNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type BinaryOperatorNode = class&#xA;    inherit QueryNode" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c1750-101">Ein Abfrageknoten, die einen binären Operator darstellt.</span><span class="sxs-lookup"><span data-stu-id="c1750-101">Query node representing a binary operator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BinaryOperatorNode (Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind kind, Microsoft.WindowsAzure.MobileServices.Query.QueryNode left, Microsoft.WindowsAzure.MobileServices.Query.QueryNode right);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind kind, class Microsoft.WindowsAzure.MobileServices.Query.QueryNode left, class Microsoft.WindowsAzure.MobileServices.Query.QueryNode right) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind,Microsoft.WindowsAzure.MobileServices.Query.QueryNode,Microsoft.WindowsAzure.MobileServices.Query.QueryNode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kind As BinaryOperatorKind, left As QueryNode, right As QueryNode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind * Microsoft.WindowsAzure.MobileServices.Query.QueryNode * Microsoft.WindowsAzure.MobileServices.Query.QueryNode -&gt; Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode (kind, left, right)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind" />
        <Parameter Name="left" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
        <Parameter Name="right" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="c1750-102">Die Art des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c1750-102">The kind of this node.</span></span></param>
        <param name="left"><span data-ttu-id="c1750-103">Der linke Operand.</span><span class="sxs-lookup"><span data-stu-id="c1750-103">The left operand.</span></span></param>
        <param name="right"><span data-ttu-id="c1750-104">Der rechte Operand.</span><span class="sxs-lookup"><span data-stu-id="c1750-104">The right operand.</span></span></param>
        <summary>
            <span data-ttu-id="c1750-105">Initialisiert die Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" /></span><span class="sxs-lookup"><span data-stu-id="c1750-105">Initializes instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="binaryOperatorNode.Accept visitor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="visitor" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="c1750-106">Der Typ, den der Besucher zurückgibt, nachdem er dieses Token besucht hat.</span><span class="sxs-lookup"><span data-stu-id="c1750-106">Type that the visitor will return after visiting this token.</span></span></typeparam>
        <param name="visitor"><span data-ttu-id="c1750-107">Eine Implementierung der Besucherschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="c1750-107">An implementation of the visitor interface.</span></span></param>
        <summary>
            <span data-ttu-id="c1750-108">Akzeptiert das Durchlaufen der Struktur von <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />s durch einen <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />.</span><span class="sxs-lookup"><span data-stu-id="c1750-108">Accept a <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> to walk a tree of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />s.</span></span>
            </summary>
        <returns><span data-ttu-id="c1750-109">Ein Objekt, dessen Typ durch den Typparameter des Besuchers bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="c1750-109">An object whose type is determined by the type parameter of the visitor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1750-110">Ruft die Art des Abfrageknotens ab.</span><span class="sxs-lookup"><span data-stu-id="c1750-110">Gets the kind of the query node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeftOperand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode LeftOperand { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode LeftOperand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.LeftOperand" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeftOperand As QueryNode" />
      <MemberSignature Language="F#" Value="member this.LeftOperand : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.LeftOperand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1750-111">Ruft den linken Operanden ab.</span><span class="sxs-lookup"><span data-stu-id="c1750-111">Gets the left operand.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorKind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind OperatorKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind OperatorKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.OperatorKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatorKind As BinaryOperatorKind" />
      <MemberSignature Language="F#" Value="member this.OperatorKind : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.OperatorKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1750-112">Der Operator, der von diesem Knoten dargestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c1750-112">The operator represented by this node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RightOperand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode RightOperand { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode RightOperand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.RightOperand" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RightOperand As QueryNode" />
      <MemberSignature Language="F#" Value="member this.RightOperand : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode.RightOperand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1750-113">Ruft den rechten Operanden ab.</span><span class="sxs-lookup"><span data-stu-id="c1750-113">Gets the right operand.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>