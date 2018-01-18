<Type Name="IndependentChildrenImpl&lt;T,ImplT,InnerT,InnerCollectionT,ManagerT,ParentT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;T,ImplT,InnerT,InnerCollectionT,ManagerT,ParentT&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndependentChildrenImpl&lt;T,ImplT,InnerT,InnerCollectionT,ManagerT,ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CreatableResources&lt;T,ImplT,InnerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;T&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent&lt;T,ParentT,ManagerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent&lt;T,ParentT,ManagerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerCollectionT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;ManagerT&gt; where T : class, IHasId where ImplT : T where ParentT : IResource, IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndependentChildrenImpl`6&lt;class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId) T, (!T) ImplT, InnerT, InnerCollectionT, ManagerT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup) ParentT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.CreatableResources`3&lt;!T, !ImplT, !InnerT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1&lt;!T&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3&lt;!T, !ParentT, !ManagerT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3&lt;!T, !ParentT, !ManagerT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;!InnerCollectionT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;!ManagerT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndependentChildrenImpl(Of T, ImplT, InnerT, InnerCollectionT, ManagerT, ParentT)&#xA;Inherits CreatableResources(Of T, ImplT, InnerT)&#xA;Implements IHasInner(Of InnerCollectionT), IHasManager(Of ManagerT), ISupportsDeletingByParent, ISupportsGettingById(Of T), ISupportsGettingByParent(Of T, ParentT, ManagerT), ISupportsListingByParent(Of T, ParentT, ManagerT)" />
  <TypeSignature Language="F#" Value="type IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; IHasId and 'ParentT :&gt; IResource and 'ParentT :&gt; IHasResourceGroup)&gt; = class&#xA;    inherit CreatableResources&lt;'T, #'T, 'InnerT (requires 'T : null and 'T :&gt; IHasId)&gt;&#xA;    interface ISupportsGettingById&lt;'T (requires 'T : null and 'T :&gt; IHasId)&gt;&#xA;    interface ISupportsGettingByParent&lt;'T, 'ParentT, 'ManagerT (requires 'T : null and 'T :&gt; IHasId and 'ParentT :&gt; IResource and 'ParentT :&gt; IHasResourceGroup)&gt;&#xA;    interface ISupportsListingByParent&lt;'T, 'ParentT, 'ManagerT (requires 'T : null and 'T :&gt; IHasId and 'ParentT :&gt; IResource and 'ParentT :&gt; IHasResourceGroup)&gt;&#xA;    interface ISupportsDeletingById&#xA;    interface ISupportsDeletingByParent&#xA;    interface IHasManager&lt;'ManagerT&gt;&#xA;    interface IHasInner&lt;'InnerCollectionT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="ImplT">
      <Constraints>
        <BaseTypeName>T</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerT" />
    <TypeParameter Name="InnerCollectionT" />
    <TypeParameter Name="ManagerT" />
    <TypeParameter Name="ParentT">
      <Constraints>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CreatableResources&lt;T,ImplT,InnerT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="IFluentResourceT">T</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="FluentResourceT">ImplT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="InnerResourceT">InnerT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent&lt;T,ParentT,ManagerT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent&lt;T,ParentT,ManagerT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerCollectionT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;ManagerT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <typeparam name="ImplT">To be added.</typeparam>
    <typeparam name="InnerT">To be added.</typeparam>
    <typeparam name="InnerCollectionT">To be added.</typeparam>
    <typeparam name="ManagerT">To be added.</typeparam>
    <typeparam name="ParentT">To be added.</typeparam>
    <summary>
            <span data-ttu-id="8a085-101">GENTHASH:Y29tLm1pY3Jvc29mdC5henVyZS5tYW5hZ2VtZW50LnJlc291cmNlcy5mbHVlbnRjb3JlLmFybS5jb2xsZWN0aW9uLmltcGxlbWVudGF0aW9uLkluZGVwZW5kZW50Q2hpbGRyZW5JbXBs-Basisklasse für unabhängige untergeordnete Sammlung-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a085-101">GENTHASH:Y29tLm1pY3Jvc29mdC5henVyZS5tYW5hZ2VtZW50LnJlc291cmNlcy5mbHVlbnRjb3JlLmFybS5jb2xsZWN0aW9uLmltcGxlbWVudGF0aW9uLkluZGVwZW5kZW50Q2hpbGRyZW5JbXBs Base class for independent child collection class.</span></span>
             <span data-ttu-id="8a085-102">(Nur interne Verwendung).</span><span class="sxs-lookup"><span data-stu-id="8a085-102">(Internal use only).</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndependentChildrenImpl (InnerCollectionT innerCollection, ManagerT manager);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!InnerCollectionT innerCollection, !ManagerT manager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.#ctor(`3,`4)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerCollection As InnerCollectionT, manager As ManagerT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup)&gt; : 'InnerCollectionT * 'ManagerT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup)&gt; (innerCollection, manager)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerCollection" Type="InnerCollectionT" />
        <Parameter Name="manager" Type="ManagerT" />
      </Parameters>
      <Docs>
        <param name="innerCollection">To be added.</param>
        <param name="manager">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public override void DeleteById (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void DeleteById(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.DeleteById(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub DeleteById (id As String)" />
      <MemberSignature Language="F#" Value="override this.DeleteById : string -&gt; unit" Usage="independentChildrenImpl.DeleteById id" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById.DeleteById(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task DeleteByIdAsync (string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task DeleteByIdAsync(string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.DeleteByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DeleteByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="independentChildrenImpl.DeleteByIdAsync (id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingById.DeleteByIdAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6/&lt;DeleteByIdAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByParent">
      <MemberSignature Language="C#" Value="public void DeleteByParent (string groupName, string parentName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByParent(string groupName, string parentName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.DeleteByParent(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByParent (groupName As String, parentName As String, name As String)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByParent : string * string * string -&gt; unit&#xA;override this.DeleteByParent : string * string * string -&gt; unit" Usage="independentChildrenImpl.DeleteByParent (groupName, parentName, name)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent.DeleteByParent(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName">To be added.</param>
        <param name="parentName">To be added.</param>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByParentAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteByParentAsync (string groupName, string parentName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteByParentAsync(string groupName, string parentName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.DeleteByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByParentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="independentChildrenImpl.DeleteByParentAsync (groupName, parentName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent.DeleteByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupName">To be added.</param>
        <param name="parentName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public T GetById (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetById(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetById(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetById (id As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetById : string -&gt; 'T&#xA;override this.GetById : string -&gt; 'T" Usage="independentChildrenImpl.GetById id" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetById(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByIdAsync (string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByIdAsync(string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;&#xA;override this.GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="independentChildrenImpl.GetByIdAsync (id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetByIdAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6/&lt;GetByIdAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByParent">
      <MemberSignature Language="C#" Value="public T GetByParent (ParentT parentResource, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByParent(!ParentT parentResource, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetByParent(`5,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByParent (parentResource As ParentT, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByParent : 'ParentT * string -&gt; 'T&#xA;override this.GetByParent : 'ParentT * string -&gt; 'T" Usage="independentChildrenImpl.GetByParent (parentResource, name)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParent(`1,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentResource">To be added.</param>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByParent">
      <MemberSignature Language="C#" Value="public T GetByParent (string resourceGroup, string parentName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByParent(string resourceGroup, string parentName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetByParent(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByParent (resourceGroup As String, parentName As String, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByParent : string * string * string -&gt; 'T&#xA;override this.GetByParent : string * string * string -&gt; 'T" Usage="independentChildrenImpl.GetByParent (resourceGroup, parentName, name)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParent(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">To be added.</param>
        <param name="parentName">To be added.</param>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByParentAsync (ParentT parentResource, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByParentAsync(!ParentT parentResource, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetByParentAsync(`5,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByParentAsync : 'ParentT * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;&#xA;override this.GetByParentAsync : 'ParentT * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="independentChildrenImpl.GetByParentAsync (parentResource, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParentAsync(`1,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6/&lt;GetByParentAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentResource">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByParentAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;T&gt; GetByParentAsync (string resourceGroup, string parentName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByParentAsync(string resourceGroup, string parentName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.GetByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByParentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="independentChildrenImpl.GetByParentAsync (resourceGroup, parentName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">To be added.</param>
        <param name="parentName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inner">
      <MemberSignature Language="C#" Value="public InnerCollectionT Inner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !InnerCollectionT Inner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.Inner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Inner As InnerCollectionT" />
      <MemberSignature Language="F#" Value="member this.Inner : 'InnerCollectionT" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup)&gt;.Inner" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1.Inner</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>InnerCollectionT</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByParent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByParent (ParentT parentResource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByParent(!ParentT parentResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.ListByParent(`5)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByParent (parentResource As ParentT) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByParent : 'ParentT -&gt; seq&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;&#xA;override this.ListByParent : 'ParentT -&gt; seq&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="independentChildrenImpl.ListByParent parentResource" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParent(`1)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
      </Parameters>
      <Docs>
        <param name="parentResource">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByParent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByParent (string resourceGroupName, string parentName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByParent(string resourceGroupName, string parentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.ListByParent(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByParent (resourceGroupName As String, parentName As String) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByParent : string * string -&gt; seq&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;&#xA;override this.ListByParent : string * string -&gt; seq&lt;'T (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId)&gt;" Usage="independentChildrenImpl.ListByParent (resourceGroupName, parentName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParent(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="parentName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByParentAsync (ParentT parentResource, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByParentAsync(!ParentT parentResource, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.ListByParentAsync(`5,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByParentAsync : 'ParentT * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;&#xA;override this.ListByParentAsync : 'ParentT * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="independentChildrenImpl.ListByParentAsync (parentResource, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParentAsync(`1,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6/&lt;ListByParentAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentResource">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByParentAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByParentAsync (string resourceGroupName, string parentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByParentAsync(string resourceGroupName, string parentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.ListByParentAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByParentAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="independentChildrenImpl.ListByParentAsync (resourceGroupName, parentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParentAsync(System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="parentName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Manager">
      <MemberSignature Language="C#" Value="public ManagerT Manager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !ManagerT Manager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl`6.Manager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Manager As ManagerT" />
      <MemberSignature Language="F#" Value="member this.Manager : 'ManagerT" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildrenImpl&lt;'T, #'T, 'InnerT, 'InnerCollectionT, 'ManagerT, 'ParentT (requires 'T : null and 'T :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'ParentT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup)&gt;.Manager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ManagerT</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>