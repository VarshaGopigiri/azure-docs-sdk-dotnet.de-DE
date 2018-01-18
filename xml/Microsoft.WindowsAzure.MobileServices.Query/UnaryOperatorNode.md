<Type Name="UnaryOperatorNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode">
  <TypeSignature Language="C#" Value="public sealed class UnaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UnaryOperatorNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UnaryOperatorNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type UnaryOperatorNode = class&#xA;    inherit QueryNode" />
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
            <span data-ttu-id="5984a-101">Knoten, die einen unäroperator darstellt.</span><span class="sxs-lookup"><span data-stu-id="5984a-101">Node representing a unary operator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnaryOperatorNode (Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind kind, Microsoft.WindowsAzure.MobileServices.Query.QueryNode operand);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind kind, class Microsoft.WindowsAzure.MobileServices.Query.QueryNode operand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind,Microsoft.WindowsAzure.MobileServices.Query.QueryNode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kind As UnaryOperatorKind, operand As QueryNode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind * Microsoft.WindowsAzure.MobileServices.Query.QueryNode -&gt; Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode (kind, operand)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind" />
        <Parameter Name="operand" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
      </Parameters>
      <Docs>
        <param name="kind"></param>
        <param name="operand"></param>
        <summary>
            <span data-ttu-id="5984a-102">Initialisiert eine Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" /></span><span class="sxs-lookup"><span data-stu-id="5984a-102">Initializes an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="unaryOperatorNode.Accept visitor" />
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
        <typeparam name="T"><span data-ttu-id="5984a-103">Der Typ, den der Besucher zurückgibt, nachdem er dieses Token besucht hat.</span><span class="sxs-lookup"><span data-stu-id="5984a-103">Type that the visitor will return after visiting this token.</span></span></typeparam>
        <param name="visitor"><span data-ttu-id="5984a-104">Eine Implementierung der Besucherschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="5984a-104">An implementation of the visitor interface.</span></span></param>
        <summary>
            <span data-ttu-id="5984a-105">Akzeptiert das Durchlaufen der Struktur von <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />s durch einen <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />.</span><span class="sxs-lookup"><span data-stu-id="5984a-105">Accept a <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> to walk a tree of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />s.</span></span>
            </summary>
        <returns><span data-ttu-id="5984a-106">Ein Objekt, dessen Typ durch den Typparameter des Besuchers bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="5984a-106">An object whose type is determined by the type parameter of the visitor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.Kind" />
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
            <span data-ttu-id="5984a-107">Ruft den Operator ab, der von diesem Knoten dargestellt wird.</span><span class="sxs-lookup"><span data-stu-id="5984a-107">Gets the operator represented by this node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode Operand { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode Operand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.Operand" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operand As QueryNode" />
      <MemberSignature Language="F#" Value="member this.Operand : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.Operand" />
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
            <span data-ttu-id="5984a-108">Der Operand des unären Operators.</span><span class="sxs-lookup"><span data-stu-id="5984a-108">The operand of the unary operator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorKind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind OperatorKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind OperatorKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.OperatorKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatorKind As UnaryOperatorKind" />
      <MemberSignature Language="F#" Value="member this.OperatorKind : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode.OperatorKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5984a-109">Der Operator, der von diesem Knoten dargestellt wird.</span><span class="sxs-lookup"><span data-stu-id="5984a-109">The operator represented by this node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>