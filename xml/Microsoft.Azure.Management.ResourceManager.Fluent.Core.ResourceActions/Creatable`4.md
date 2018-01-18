<Type Name="Creatable&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IResourceT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IResourceT&gt;">
  <TypeSignature Language="C#" Value="public abstract class Creatable&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IResourceT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper&lt;IFluentResourceT,InnerResourceT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt; where IFluentResourceT : class, IResourceT where FluentResourceT : class where IResourceT : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Creatable`4&lt;class (!IResourceT) IFluentResourceT, InnerResourceT, class FluentResourceT, class IResourceT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper`2&lt;!IFluentResourceT, !InnerResourceT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator`1&lt;!IResourceT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Creatable(Of IFluentResourceT, InnerResourceT, FluentResourceT, IResourceT)&#xA;Inherits IndexableRefreshableWrapper(Of IFluentResourceT, InnerResourceT)&#xA;Implements IResourceCreator(Of IResourceT)" />
  <TypeSignature Language="F#" Value="type Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt; = class&#xA;    inherit IndexableRefreshableWrapper&lt;#'IResourceT, 'InnerResourceT&gt;&#xA;    interface IResourceCreator&lt;'IResourceT (requires 'IResourceT : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="IFluentResourceT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <BaseTypeName>IResourceT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerResourceT" />
    <TypeParameter Name="FluentResourceT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IResourceT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IndexableRefreshableWrapper&lt;IFluentResourceT,InnerResourceT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="IFluentResourceT">IFluentResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="InnerResourceT">InnerResourceT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="IFluentResourceT"><span data-ttu-id="5a2ee-101">Der fluent Modelltyp, erstellbare Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="5a2ee-101">The fluent model type representing the creatable resource</span></span></typeparam>
    <typeparam name="InnerResourceT"><span data-ttu-id="5a2ee-102">Der innere Modelltyp, den die fluent-Modelltyp umschließt</span><span class="sxs-lookup"><span data-stu-id="5a2ee-102">The model inner type that the fluent model type wraps</span></span></typeparam>
    <typeparam name="FluentResourceT"><span data-ttu-id="5a2ee-103">Der Implementierungstyp fluent-Modell</span><span class="sxs-lookup"><span data-stu-id="5a2ee-103">The fluent model implementation type</span></span></typeparam>
    <typeparam name="IResourceT"><span data-ttu-id="5a2ee-104">Die fluent-Ressourcen zugewiesen oder von der Basisschnittstelle, von denen erbt</span><span class="sxs-lookup"><span data-stu-id="5a2ee-104">The fluent resourced or one of the base interface from which inherits</span></span></typeparam>
    <summary>
            <span data-ttu-id="5a2ee-105">Die Basisklasse für alle erstellbar Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="5a2ee-105">The base class for all creatable resources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Creatable (string name, InnerResourceT innerObject);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name, !InnerResourceT innerObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.#ctor(System.String,`1)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String, innerObject As InnerResourceT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt; : string * 'InnerResourceT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt; (name, innerObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="innerObject" Type="InnerResourceT" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="innerObject">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCreatableDependency">
      <MemberSignature Language="C#" Value="protected void AddCreatableDependency (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt; creatableResource);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void AddCreatableDependency(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator`1&lt;!IResourceT&gt; creatableResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.AddCreatableDependency(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator{`3})" />
      <MemberSignature Language="VB.NET" Value="Protected Sub AddCreatableDependency (creatableResource As IResourceCreator(Of IResourceT))" />
      <MemberSignature Language="F#" Value="member this.AddCreatableDependency : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;'IResourceT (requires 'IResourceT : null)&gt; -&gt; unit" Usage="creatable.AddCreatableDependency creatableResource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatableResource" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;" />
      </Parameters>
      <Docs>
        <param name="creatableResource">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public IFluentResourceT Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !IFluentResourceT Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.Create" />
      <MemberSignature Language="VB.NET" Value="Public Function Create () As IFluentResourceT" />
      <MemberSignature Language="F#" Value="abstract member Create : unit -&gt; 'IFluentResourceT&#xA;override this.Create : unit -&gt; 'IFluentResourceT" Usage="creatable.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IFluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;IFluentResourceT&gt; CreateAsync (System.Threading.CancellationToken cancellationToken, bool multiThreaded = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!IFluentResourceT&gt; CreateAsync(valuetype System.Threading.CancellationToken cancellationToken, bool multiThreaded) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.CreateAsync(System.Threading.CancellationToken,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken * bool -&gt; System.Threading.Tasks.Task&lt;#'IResourceT&gt;&#xA;override this.CreateAsync : System.Threading.CancellationToken * bool -&gt; System.Threading.Tasks.Task&lt;#'IResourceT&gt;" Usage="creatable.CreateAsync (cancellationToken, multiThreaded)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;IFluentResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="multiThreaded" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <param name="multiThreaded">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedResource">
      <MemberSignature Language="C#" Value="protected IResourceT CreatedResource (string key);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !IResourceT CreatedResource(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.CreatedResource(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function CreatedResource (key As String) As IResourceT" />
      <MemberSignature Language="F#" Value="member this.CreatedResource : string -&gt; 'IResourceT" Usage="creatable.CreatedResource key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResource">
      <MemberSignature Language="C#" Value="public virtual IFluentResourceT CreateResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !IFluentResourceT CreateResource() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.CreateResource" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateResource () As IFluentResourceT" />
      <MemberSignature Language="F#" Value="abstract member CreateResource : unit -&gt; 'IFluentResourceT&#xA;override this.CreateResource : unit -&gt; 'IFluentResourceT" Usage="creatable.CreateResource " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IFluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResourceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;IFluentResourceT&gt; CreateResourceAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!IFluentResourceT&gt; CreateResourceAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.CreateResourceAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateResourceAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;#'IResourceT&gt;" Usage="creatable.CreateResourceAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;IFluentResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatorTaskGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.DAG.CreatorTaskGroup&lt;IResourceT&gt; CreatorTaskGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.DAG.CreatorTaskGroup`1&lt;!IResourceT&gt; CreatorTaskGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.CreatorTaskGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatorTaskGroup As CreatorTaskGroup(Of IResourceT)" />
      <MemberSignature Language="F#" Value="member this.CreatorTaskGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.DAG.CreatorTaskGroup&lt;'IResourceT (requires 'IResourceT : null)&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt;.CreatorTaskGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.DAG.CreatorTaskGroup&lt;IResourceT&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;.CreateResource">
      <MemberSignature Language="C#" Value="IResourceT IResourceCreator&lt;IResourceT&gt;.CreateResource ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !IResourceT Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;.CreateResource() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.Microsoft#Azure#Management#ResourceManager#Fluent#Core#ResourceActions#IResourceCreator&lt;IResourceT&gt;#CreateResource" />
      <MemberSignature Language="VB.NET" Value="Function CreateResource () As IResourceT Implements IResourceCreator(Of IResourceT).CreateResource" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator`1.CreateResource</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IResourceT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;.CreateResourceAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;IResourceT&gt; IResourceCreator&lt;IResourceT&gt;.CreateResourceAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!IResourceT&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator&lt;IResourceT&gt;.CreateResourceAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.Microsoft#Azure#Management#ResourceManager#Fluent#Core#ResourceActions#IResourceCreator&lt;IResourceT&gt;#CreateResourceAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IResourceCreator`1.CreateResourceAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4/&lt;Microsoft-Azure-Management-ResourceManager-Fluent-Core-ResourceActions-IResourceCreator&lt;IResourceT&gt;-CreateResourceAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;IResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable`4.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Creatable&lt;#'IResourceT, 'InnerResourceT, 'FluentResourceT, 'IResourceT (requires 'FluentResourceT : null and 'IResourceT : null)&gt;.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>