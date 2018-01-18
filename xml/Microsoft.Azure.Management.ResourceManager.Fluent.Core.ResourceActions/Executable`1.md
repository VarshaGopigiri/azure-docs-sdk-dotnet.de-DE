<Type Name="Executable&lt;IFluentResourceT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Executable&lt;IFluentResourceT&gt;">
  <TypeSignature Language="C#" Value="public abstract class Executable&lt;IFluentResourceT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Indexable, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IExecutable&lt;IFluentResourceT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Executable`1&lt;IFluentResourceT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Indexable implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IExecutable`1&lt;!IFluentResourceT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Executable`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Executable(Of IFluentResourceT)&#xA;Inherits Indexable&#xA;Implements IExecutable(Of IFluentResourceT)" />
  <TypeSignature Language="F#" Value="type Executable&lt;'IFluentResourceT&gt; = class&#xA;    inherit Indexable&#xA;    interface IExecutable&lt;'IFluentResourceT&gt;&#xA;    interface IIndexable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="IFluentResourceT" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Indexable</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IExecutable&lt;IFluentResourceT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="IFluentResourceT">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Executable ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Executable`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public IFluentResourceT Execute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !IFluentResourceT Execute() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Executable`1.Execute" />
      <MemberSignature Language="VB.NET" Value="Public Function Execute () As IFluentResourceT" />
      <MemberSignature Language="F#" Value="abstract member Execute : unit -&gt; 'IFluentResourceT&#xA;override this.Execute : unit -&gt; 'IFluentResourceT" Usage="executable.Execute " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IExecutable`1.Execute</InterfaceMember>
      </Implements>
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
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;IFluentResourceT&gt; ExecuteAsync (System.Threading.CancellationToken cancellationToken = null, bool multiThreaded = true);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!IFluentResourceT&gt; ExecuteAsync(valuetype System.Threading.CancellationToken cancellationToken, bool multiThreaded) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.Executable`1.ExecuteAsync(System.Threading.CancellationToken,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : System.Threading.CancellationToken * bool -&gt; System.Threading.Tasks.Task&lt;'IFluentResourceT&gt;" Usage="executable.ExecuteAsync (cancellationToken, multiThreaded)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IExecutable`1.ExecuteAsync(System.Threading.CancellationToken,System.Boolean)</InterfaceMember>
      </Implements>
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
  </Members>
</Type>