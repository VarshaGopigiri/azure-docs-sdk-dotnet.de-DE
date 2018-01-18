<Type Name="DeployedServicePackageHealthStateList" FullName="System.Fabric.Health.DeployedServicePackageHealthStateList">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateList : System.Collections.Generic.ICollection&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;, System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateList&#xA;Implements ICollection(Of DeployedServicePackageHealthState), IEnumerable(Of DeployedServicePackageHealthState), IList(Of DeployedServicePackageHealthState)" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateList = class&#xA;    interface IList&lt;DeployedServicePackageHealthState&gt;&#xA;    interface ICollection&lt;DeployedServicePackageHealthState&gt;&#xA;    interface seq&lt;DeployedServicePackageHealthState&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="dbcb7-101">Stellt eine Auflistung von <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> einzeln nach Index zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-101">Represents a collection of <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> that can be individually accessed by index.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Health.DeployedServicePackageHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Health.DeployedServicePackageHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.Add(System.Fabric.Health.DeployedServicePackageHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedServicePackageHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Health.DeployedServicePackageHealthState -&gt; unit&#xA;override this.Add : System.Fabric.Health.DeployedServicePackageHealthState -&gt; unit" Usage="deployedServicePackageHealthStateList.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.DeployedServicePackageHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="dbcb7-102">Das Element, das hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-103">Fügt der Auflistung ein Element hinzu.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-103">Adds an item to the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedServicePackageHealthStateList.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="dbcb7-104">Entfernt alle Elemente aus der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-104">Removes all items from the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Health.DeployedServicePackageHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Health.DeployedServicePackageHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.Contains(System.Fabric.Health.DeployedServicePackageHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedServicePackageHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Health.DeployedServicePackageHealthState -&gt; bool&#xA;override this.Contains : System.Fabric.Health.DeployedServicePackageHealthState -&gt; bool" Usage="deployedServicePackageHealthStateList.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.DeployedServicePackageHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="dbcb7-105">Das Element in der Auflistung gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-105">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-106">Ermittelt, ob die Auflistung einen bestimmten Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-106">Determines whether the collection contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="dbcb7-107"><languageKeyword>"true"</languageKeyword> Wenn das Element gefunden wurde, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-107"><languageKeyword>true</languageKeyword> if the item is found; otherwise, <languageKeyword>false</languageKeyword>.</span></span> </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Health.DeployedServicePackageHealthState[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Health.DeployedServicePackageHealthState[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.CopyTo(System.Fabric.Health.DeployedServicePackageHealthState[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedServicePackageHealthState(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Health.DeployedServicePackageHealthState[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Health.DeployedServicePackageHealthState[] * int -&gt; unit" Usage="deployedServicePackageHealthStateList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Health.DeployedServicePackageHealthState[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="dbcb7-108">Das eindimensionale Array, das das Ziel der aus ICollection kopierten Elemente ist.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-108">The one-dimensional Array that is the destination of the elements copied from ICollection.</span></span> <span data-ttu-id="dbcb7-109">Für das Array muss eine nullbasierte Indizierung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-109">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="dbcb7-110">Der nullbasierte Index im Array, ab dem kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-111">Kopiert die Elemente der ICollection in ein Array, beginnend an einem bestimmten Arrayindex begonnen.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-111">Copies the elements of the ICollection to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.DeployedServicePackageHealthStateList.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dbcb7-112">Ruft die Anzahl der Elemente ab.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-112">Gets the number of elements.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dbcb7-113">Eine <see cref="T:System.Int32" /> , die die Anzahl der Elemente darstellt.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-113">An <see cref="T:System.Int32" /> representing the number of elements.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Health.DeployedServicePackageHealthState&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedServicePackageHealthState)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;" Usage="deployedServicePackageHealthStateList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.DeployedServicePackageHealthState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="dbcb7-114">Gibt einen Enumerator zurück, der eine Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-114">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="dbcb7-115">Ein <see cref="T:System.Collections.Generic.IEnumerator`1" />-Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-115">An <see cref="T:System.Collections.Generic.IEnumerator`1" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Health.DeployedServicePackageHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Health.DeployedServicePackageHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.IndexOf(System.Fabric.Health.DeployedServicePackageHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedServicePackageHealthState) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Health.DeployedServicePackageHealthState -&gt; int&#xA;override this.IndexOf : System.Fabric.Health.DeployedServicePackageHealthState -&gt; int" Usage="deployedServicePackageHealthStateList.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.DeployedServicePackageHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="dbcb7-116">Das Element in der Auflistung gesucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-116">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-117">Bestimmt den Index eines bestimmten Elements in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-117">Determines the index of a specific item in the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="dbcb7-118">Ein <see cref="T:System.Int32" /> der den Index des Elements darstellt, wenn in der Auflistung gefunden wurde, andernfalls -1.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-118">An <see cref="T:System.Int32" /> which represents the index of the item if found in the collection; otherwise, -1.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Health.DeployedServicePackageHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Health.DeployedServicePackageHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.Insert(System.Int32,System.Fabric.Health.DeployedServicePackageHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedServicePackageHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Health.DeployedServicePackageHealthState -&gt; unit&#xA;override this.Insert : int * System.Fabric.Health.DeployedServicePackageHealthState -&gt; unit" Usage="deployedServicePackageHealthStateList.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="System.Fabric.Health.DeployedServicePackageHealthState" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="dbcb7-119">Der nullbasierte Index, an dem der Wert eingefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-119">The zero-based index at which value should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="dbcb7-120">Das Element eingefügt werden.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-120">The item to be inserted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-121">Fügt ein Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-121">Inserts an item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.DeployedServicePackageHealthStateList.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dbcb7-122">Ruft einen Wert ab, der angibt, ob die Liste schreibgeschützt ist.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-122">Gets a value indicating whether the list is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="dbcb7-123"><languageKeyword>"true"</languageKeyword> Wenn die Auflistung schreibgeschützt ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-123"><languageKeyword>true</languageKeyword> if the collection is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthState this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthState Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedServicePackageHealthState" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Health.DeployedServicePackageHealthState with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="dbcb7-124">Der nullbasierte Index des Elements, das abgerufen oder festgelegt werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-124">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-125">Ruft das Element am angegebenen Index ab oder legt dieses fest.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-125">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dbcb7-126">Der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-126">The <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Health.DeployedServicePackageHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Health.DeployedServicePackageHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.Remove(System.Fabric.Health.DeployedServicePackageHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedServicePackageHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Health.DeployedServicePackageHealthState -&gt; bool&#xA;override this.Remove : System.Fabric.Health.DeployedServicePackageHealthState -&gt; bool" Usage="deployedServicePackageHealthStateList.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.DeployedServicePackageHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="dbcb7-127">Das zu entfernende Element.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-127">The item to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-128">Entfernt das erste Vorkommen eines bestimmten Elements aus der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-128">Removes the first occurrence of a specific item from the collection.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="dbcb7-129"><languageKeyword>"true"</languageKeyword> , wenn das Element entfernt; andernfalls wurde, <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-129"><languageKeyword>true</languageKeyword> if the item was removed; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedServicePackageHealthStateList.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="dbcb7-130">Der nullbasierte Index des zu entfernenden Elements.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dbcb7-131">Entfernt das Element am angegebenen Index.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-131">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateList.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="dbcb7-132">Gibt einen Enumerator zurück, der eine Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-132">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="dbcb7-133">Ein <see cref="T:System.Collections.IEnumerator" />-Objekt, das zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="dbcb7-133">An <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>