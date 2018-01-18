<Type Name="ConvertNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode">
  <TypeSignature Language="C#" Value="public sealed class ConvertNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConvertNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConvertNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type ConvertNode = class&#xA;    inherit QueryNode" />
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
            <span data-ttu-id="841a1-101">Knoten, die eine Konvertierung des primitiven Typs in einen anderen Typ darstellt.</span><span class="sxs-lookup"><span data-stu-id="841a1-101">Node representing a conversion of primitive type to another type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConvertNode (Microsoft.WindowsAzure.MobileServices.Query.QueryNode source, Type targetType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.Query.QueryNode source, class System.Type targetType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.QueryNode,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As QueryNode, targetType As Type)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.ConvertNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode * Type -&gt; Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.ConvertNode (source, targetType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
        <Parameter Name="targetType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="841a1-102">Der zu konvertierende Knoten.</span><span class="sxs-lookup"><span data-stu-id="841a1-102">The node to convert.</span></span></param>
        <param name="targetType"><span data-ttu-id="841a1-103">Der Typ, in den der Knoten konvertiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="841a1-103">The type to convert the node to</span></span></param>
        <summary>
            <span data-ttu-id="841a1-104">Initialisiert eine Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" /></span><span class="sxs-lookup"><span data-stu-id="841a1-104">Initializes an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="convertNode.Accept visitor" />
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
        <typeparam name="T"><span data-ttu-id="841a1-105">Der Typ, den der Besucher zurückgibt, nachdem er dieses Token besucht hat.</span><span class="sxs-lookup"><span data-stu-id="841a1-105">Type that the visitor will return after visiting this token.</span></span></typeparam>
        <param name="visitor"><span data-ttu-id="841a1-106">Eine Implementierung der Besucherschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="841a1-106">An implementation of the visitor interface.</span></span></param>
        <summary>
            <span data-ttu-id="841a1-107">Akzeptiert das Durchlaufen der Struktur von <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />s durch einen <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />.</span><span class="sxs-lookup"><span data-stu-id="841a1-107">Accept a <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> to walk a tree of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />s.</span></span>
            </summary>
        <returns><span data-ttu-id="841a1-108">Ein Objekt, dessen Typ durch den Typparameter des Besuchers bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="841a1-108">An object whose type is determined by the type parameter of the visitor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.Kind" />
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
            <span data-ttu-id="841a1-109">Ruft die Art des Abfrageknotens ab.</span><span class="sxs-lookup"><span data-stu-id="841a1-109">Gets the kind of the query node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As QueryNode" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.Source" />
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
            <span data-ttu-id="841a1-110">Rufen Sie den Datenquelle, die zu konvertierende Wert ab.</span><span class="sxs-lookup"><span data-stu-id="841a1-110">Get the source value to convert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetType">
      <MemberSignature Language="C#" Value="public Type TargetType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type TargetType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.TargetType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetType As Type" />
      <MemberSignature Language="F#" Value="member this.TargetType : Type" Usage="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode.TargetType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="841a1-111">Ruft den Typ, dem wir konvertieren.</span><span class="sxs-lookup"><span data-stu-id="841a1-111">Get the type we're converting to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>