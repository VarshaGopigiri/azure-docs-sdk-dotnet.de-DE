<Type Name="MSITokenProvider" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider">
  <TypeSignature Language="C#" Value="public class MSITokenProvider : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Rest.ITokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSITokenProvider extends System.Object implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Rest.ITokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class MSITokenProvider&#xA;Implements IBeta, ITokenProvider" />
  <TypeSignature Language="F#" Value="type MSITokenProvider = class&#xA;    interface ITokenProvider&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.ITokenProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSITokenProvider (string resource, Nullable&lt;int&gt; port = 50342);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resource, valuetype System.Nullable`1&lt;int32&gt; port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resource As String, Optional port As Nullable(Of Integer) = 50342)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider (resource, port)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="resource">To be added.</param>
        <param name="port">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationHeaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.Headers.AuthenticationHeaderValue&gt; GetAuthenticationHeaderAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.Headers.AuthenticationHeaderValue&gt; GetAuthenticationHeaderAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider.GetAuthenticationHeaderAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationHeaderAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.Headers.AuthenticationHeaderValue&gt;&#xA;override this.GetAuthenticationHeaderAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.Headers.AuthenticationHeaderValue&gt;" Usage="mSITokenProvider.GetAuthenticationHeaderAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Rest.ITokenProvider.GetAuthenticationHeaderAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.MSITokenProvider/&lt;GetAuthenticationHeaderAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.Headers.AuthenticationHeaderValue&gt;</ReturnType>
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
  </Members>
</Type>