<Type Name="ResourceBase&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IDefinitionAfterRegion,DefTypeWithTags,UTypeWithTags&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IDefinitionAfterRegion,DefTypeWithTags,UTypeWithTags&gt;">
  <TypeSignature Language="C#" Value="public abstract class ResourceBase&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IDefinitionAfterRegion,DefTypeWithTags,UTypeWithTags&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.CreatableUpdatable&lt;IFluentResourceT,InnerResourceT,FluentResourceT,Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,UTypeWithTags&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt; where IFluentResourceT : class, IResource where InnerResourceT : Resource where FluentResourceT : ResourceBase&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IDefinitionAfterRegion,DefTypeWithTags,UTypeWithTags&gt;, IFluentResourceT where IDefinitionAfterRegion : class where DefTypeWithTags : class where UTypeWithTags : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ResourceBase`6&lt;class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource) IFluentResourceT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Resource) InnerResourceT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6&lt;!IFluentResourceT, !InnerResourceT, !FluentResourceT, !IDefinitionAfterRegion, !DefTypeWithTags, !UTypeWithTags&gt;, !IFluentResourceT) FluentResourceT, class IDefinitionAfterRegion, class DefTypeWithTags, class UTypeWithTags&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.CreatableUpdatable`5&lt;!IFluentResourceT, !InnerResourceT, !FluentResourceT, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, !UTypeWithTags&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;!DefTypeWithTags&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;!UTypeWithTags&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ResourceBase(Of IFluentResourceT, InnerResourceT, FluentResourceT, IDefinitionAfterRegion, DefTypeWithTags, UTypeWithTags)&#xA;Inherits CreatableUpdatable(Of IFluentResourceT, InnerResourceT, FluentResourceT, IHasId, UTypeWithTags)&#xA;Implements IDefinitionWithTags(Of DefTypeWithTags), IResource, IUpdateWithTags(Of UTypeWithTags)" />
  <TypeSignature Language="F#" Value="type ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; IResource and 'InnerResourceT :&gt; Resource and 'FluentResourceT :&gt; ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt; = class&#xA;    inherit CreatableUpdatable&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, IHasId, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; IResource and 'InnerResourceT :&gt; Resource and 'FluentResourceT :&gt; ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'UTypeWithTags : null)&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IDefinitionWithTags&lt;'DefTypeWithTags (requires 'DefTypeWithTags : null)&gt;&#xA;    interface IUpdateWithTags&lt;'UTypeWithTags (requires 'UTypeWithTags : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="IFluentResourceT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerResourceT">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="FluentResourceT">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;IFluentResourceT,InnerResourceT,FluentResourceT,IDefinitionAfterRegion,DefTypeWithTags,UTypeWithTags&gt;</BaseTypeName>
        <BaseTypeName>IFluentResourceT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IDefinitionAfterRegion">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="DefTypeWithTags">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="UTypeWithTags">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.CreatableUpdatable&lt;IFluentResourceT,InnerResourceT,FluentResourceT,Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,UTypeWithTags&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="IFluentResourceT">IFluentResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="InnerResourceT">InnerResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="FluentResourceT">FluentResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IResourceT">Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IUpdatableT">UTypeWithTags</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="IFluentResourceT"><span data-ttu-id="e8639-101">Die fluent wrapperschnittstelle für die Ressource</span><span class="sxs-lookup"><span data-stu-id="e8639-101">The fluent wrapper interface for the resource</span></span></typeparam>
    <typeparam name="InnerResourceT"><span data-ttu-id="e8639-102">Die Ressource Autorest generiert</span><span class="sxs-lookup"><span data-stu-id="e8639-102">The autorest generated resource</span></span></typeparam>
    <typeparam name="FluentResourceT"><span data-ttu-id="e8639-103">Die Implementierung für fluent wrapperschnittstelle</span><span class="sxs-lookup"><span data-stu-id="e8639-103">The implementation for fluent wrapper interface</span></span></typeparam>
    <typeparam name="IDefinitionAfterRegion">To be added.</typeparam>
    <typeparam name="DefTypeWithTags">To be added.</typeparam>
    <typeparam name="UTypeWithTags">To be added.</typeparam>
    <summary>
            <span data-ttu-id="e8639-104">Diese Klasse verwendet Reflektion, sobald wir haben eine alle Ressource erbt "Ressource" entfernt</span><span class="sxs-lookup"><span data-stu-id="e8639-104">This class uses Reflection, it will be removed once we have a "Resource" from which all resource inherits</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResourceBase (string key, InnerResourceT innerObject);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string key, !InnerResourceT innerObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.#ctor(System.String,`1)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (key As String, innerObject As InnerResourceT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt; : string * 'InnerResourceT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt; (key, innerObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="innerObject" Type="InnerResourceT" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="innerObject">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Id" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id</InterfaceMember>
      </Implements>
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
    <Member MemberName="InnersFromWrappers&lt;InnerT,IWrapperT&gt;">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IList&lt;InnerT&gt; InnersFromWrappers&lt;InnerT,IWrapperT&gt; (System.Collections.Generic.ICollection&lt;IWrapperT&gt; wrappers) where IWrapperT : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerT&gt;;" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IList`1&lt;!!InnerT&gt; InnersFromWrappers&lt;InnerT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;!!InnerT&gt;) IWrapperT&gt;(class System.Collections.Generic.ICollection`1&lt;!!IWrapperT&gt; wrappers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.InnersFromWrappers``2(System.Collections.Generic.ICollection{``1})" />
      <MemberSignature Language="VB.NET" Value="Protected Function InnersFromWrappers(Of InnerT, IWrapperT) (wrappers As ICollection(Of IWrapperT)) As IList(Of InnerT)" />
      <MemberSignature Language="F#" Value="member this.InnersFromWrappers : System.Collections.Generic.ICollection&lt;'IWrapperT (requires 'IWrapperT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;'InnerT&gt;)&gt; -&gt; System.Collections.Generic.IList&lt;'InnerT&gt; (requires 'IWrapperT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;'InnerT&gt;)" Usage="resourceBase.InnersFromWrappers wrappers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;InnerT&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="InnerT" />
        <TypeParameter Name="IWrapperT">
          <Constraints>
            <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerT&gt;</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="wrappers" Type="System.Collections.Generic.ICollection&lt;IWrapperT&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="InnerT">To be added.</typeparam>
        <typeparam name="IWrapperT">To be added.</typeparam>
        <param name="wrappers">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnersFromWrappers&lt;InnerT,IWrapperT&gt;">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IList&lt;InnerT&gt; InnersFromWrappers&lt;InnerT,IWrapperT&gt; (System.Collections.Generic.ICollection&lt;IWrapperT&gt; wrappers, System.Collections.Generic.IList&lt;InnerT&gt; inners) where IWrapperT : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerT&gt;;" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IList`1&lt;!!InnerT&gt; InnersFromWrappers&lt;InnerT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;!!InnerT&gt;) IWrapperT&gt;(class System.Collections.Generic.ICollection`1&lt;!!IWrapperT&gt; wrappers, class System.Collections.Generic.IList`1&lt;!!InnerT&gt; inners) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.InnersFromWrappers``2(System.Collections.Generic.ICollection{``1},System.Collections.Generic.IList{``0})" />
      <MemberSignature Language="VB.NET" Value="Protected Function InnersFromWrappers(Of InnerT, IWrapperT) (wrappers As ICollection(Of IWrapperT), inners As IList(Of InnerT)) As IList(Of InnerT)" />
      <MemberSignature Language="F#" Value="member this.InnersFromWrappers : System.Collections.Generic.ICollection&lt;'IWrapperT (requires 'IWrapperT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;'InnerT&gt;)&gt; * System.Collections.Generic.IList&lt;'InnerT&gt; -&gt; System.Collections.Generic.IList&lt;'InnerT&gt; (requires 'IWrapperT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;'InnerT&gt;)" Usage="resourceBase.InnersFromWrappers (wrappers, inners)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;InnerT&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="InnerT" />
        <TypeParameter Name="IWrapperT">
          <Constraints>
            <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerT&gt;</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="wrappers" Type="System.Collections.Generic.ICollection&lt;IWrapperT&gt;" />
        <Parameter Name="inners" Type="System.Collections.Generic.IList&lt;InnerT&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="InnerT">To be added.</typeparam>
        <typeparam name="IWrapperT">To be added.</typeparam>
        <param name="wrappers">To be added.</param>
        <param name="inners">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInCreateMode">
      <MemberSignature Language="C#" Value="protected bool IsInCreateMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInCreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.IsInCreateMode" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property IsInCreateMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInCreateMode : bool" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.IsInCreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags">
      <MemberSignature Language="C#" Value="System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IResource#Tags" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Tags As IReadOnlyDictionary(Of String, String) Implements IResource.Tags" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTag">
      <MemberSignature Language="C#" Value="DefTypeWithTags IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !DefTypeWithTags Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#Resource#Definition#IDefinitionWithTags&lt;DefTypeWithTags&gt;#WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithTag (key As String, value As String) As DefTypeWithTags Implements IDefinitionWithTags(Of DefTypeWithTags).WithTag" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1.WithTag(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>DefTypeWithTags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTags">
      <MemberSignature Language="C#" Value="DefTypeWithTags IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !DefTypeWithTags Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;DefTypeWithTags&gt;.WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#Resource#Definition#IDefinitionWithTags&lt;DefTypeWithTags&gt;#WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Function WithTags (tags As IDictionary(Of String, String)) As DefTypeWithTags Implements IDefinitionWithTags(Of DefTypeWithTags).WithTags" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>DefTypeWithTags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithoutTag">
      <MemberSignature Language="C#" Value="UTypeWithTags IUpdateWithTags&lt;UTypeWithTags&gt;.WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !UTypeWithTags Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#Resource#Update#IUpdateWithTags&lt;UTypeWithTags&gt;#WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithoutTag (key As String) As UTypeWithTags Implements IUpdateWithTags(Of UTypeWithTags).WithoutTag" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithoutTag(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>UTypeWithTags</ReturnType>
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
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithTag">
      <MemberSignature Language="C#" Value="UTypeWithTags IUpdateWithTags&lt;UTypeWithTags&gt;.WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !UTypeWithTags Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#Resource#Update#IUpdateWithTags&lt;UTypeWithTags&gt;#WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function WithTag (key As String, value As String) As UTypeWithTags Implements IUpdateWithTags(Of UTypeWithTags).WithTag" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithTag(System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>UTypeWithTags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithTags">
      <MemberSignature Language="C#" Value="UTypeWithTags IUpdateWithTags&lt;UTypeWithTags&gt;.WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance !UTypeWithTags Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;UTypeWithTags&gt;.WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Microsoft#Azure#Management#ResourceManager#Fluent#Core#Resource#Update#IUpdateWithTags&lt;UTypeWithTags&gt;#WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Function WithTags (tags As IDictionary(Of String, String)) As UTypeWithTags Implements IUpdateWithTags(Of UTypeWithTags).WithTags" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>UTypeWithTags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Name" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name</InterfaceMember>
      </Implements>
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
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Region" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Region As Region" />
      <MemberSignature Language="F#" Value="member this.Region : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Region" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Region</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.RegionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.RegionName</InterfaceMember>
      </Implements>
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
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Tags" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags (requires 'IFluentResourceT : null and 'IFluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'InnerResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase&lt;'IFluentResourceT, 'InnerResourceT, 'FluentResourceT, 'IDefinitionAfterRegion, 'DefTypeWithTags, 'UTypeWithTags&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionAfterRegion : null and 'DefTypeWithTags : null and 'UTypeWithTags : null)&gt;.Type" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Type</InterfaceMember>
      </Implements>
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
    <Member MemberName="WithoutTag">
      <MemberSignature Language="C#" Value="public FluentResourceT WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTag (key As String) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithoutTag : string -&gt; 'FluentResourceT" Usage="resourceBase.WithoutTag key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
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
    <Member MemberName="WithRegion">
      <MemberSignature Language="C#" Value="public IDefinitionAfterRegion WithRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !IDefinitionAfterRegion WithRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.WithRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'IDefinitionAfterRegion&#xA;override this.WithRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'IDefinitionAfterRegion" Usage="resourceBase.WithRegion region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IDefinitionAfterRegion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithRegion">
      <MemberSignature Language="C#" Value="public IDefinitionAfterRegion WithRegion (string regionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !IDefinitionAfterRegion WithRegion(string regionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.WithRegion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRegion (regionName As String) As IDefinitionAfterRegion" />
      <MemberSignature Language="F#" Value="abstract member WithRegion : string -&gt; 'IDefinitionAfterRegion&#xA;override this.WithRegion : string -&gt; 'IDefinitionAfterRegion" Usage="resourceBase.WithRegion regionName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IDefinitionAfterRegion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="regionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="regionName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public FluentResourceT WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithTag : string * string -&gt; 'FluentResourceT" Usage="resourceBase.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public FluentResourceT WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceBase`6.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; 'FluentResourceT" Usage="resourceBase.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>