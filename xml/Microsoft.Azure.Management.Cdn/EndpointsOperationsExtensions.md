<Type Name="EndpointsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EndpointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EndpointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EndpointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EndpointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint BeginCreate (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint BeginCreate(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.Endpoint)" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.Endpoint -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginCreate (operations, resourceGroupName, profileName, endpointName, endpoint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpoint">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginCreateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpoint">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginDelete (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginLoadContent">
      <MemberSignature Language="C#" Value="public static void BeginLoadContent (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginLoadContent(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginLoadContent(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginLoadContent (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member BeginLoadContent : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginLoadContent (operations, resourceGroupName, profileName, endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginLoadContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginLoadContentAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginLoadContentAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginLoadContentAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginLoadContentAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginLoadContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginLoadContentAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeContent">
      <MemberSignature Language="C#" Value="public static void BeginPurgeContent (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginPurgeContent(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginPurgeContent(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginPurgeContent (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member BeginPurgeContent : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginPurgeContent (operations, resourceGroupName, profileName, endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPurgeContentAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPurgeContentAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginPurgeContentAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeContentAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginPurgeContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginPurgeContentAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint BeginStart (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint BeginStart(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStart(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStart (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginStartAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginStartAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginStartAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint BeginStop (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint BeginStop(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStop(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStop (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStop (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginStopAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginStopAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginStopAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint BeginUpdate (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint BeginUpdate(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, endpointUpdateProperties As EndpointUpdateParameters) As Endpoint" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginUpdate (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpointUpdateProperties">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpointUpdateProperties">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint Create (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint Create(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Create(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.Endpoint)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.Endpoint -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Create (operations, resourceGroupName, profileName, endpointName, endpoint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Models.Endpoint" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpoint">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.Endpoint endpoint, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.Endpoint,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.Endpoint * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, endpoint, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;CreateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpoint" Type="Microsoft.Azure.Management.Cdn.Models.Endpoint" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpoint">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Delete(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Delete (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint Get (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint Get(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Get(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Get (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; GetAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; GetAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfile">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; ListByProfile (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; ListByProfile(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfile(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByProfile (operations As IEndpointsOperations, resourceGroupName As String, profileName As String) As IPage(Of Endpoint)" />
      <MemberSignature Language="F#" Value="static member ListByProfile : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfile (operations, resourceGroupName, profileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt; ListByProfileAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt; ListByProfileAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByProfileAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;ListByProfileAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; ListByProfileNext (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; ListByProfileNext(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileNext(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByProfileNext (operations As IEndpointsOperations, nextPageLink As String) As IPage(Of Endpoint)" />
      <MemberSignature Language="F#" Value="static member ListByProfileNext : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByProfileNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt; ListByProfileNextAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt; ListByProfileNextAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileNextAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByProfileNextAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListByProfileNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;ListByProfileNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsage">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt; ListResourceUsage (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt; ListResourceUsage(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsage(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListResourceUsage (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As IPage(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsage : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsage (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt; ListResourceUsageAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt; ListResourceUsageAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;ListResourceUsageAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt; ListResourceUsageNext (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt; ListResourceUsageNext(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageNext(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListResourceUsageNext (operations As IEndpointsOperations, nextPageLink As String) As IPage(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageNext : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt; ListResourceUsageNextAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt; ListResourceUsageNextAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageNextAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageNextAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ListResourceUsageNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;ListResourceUsageNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Models.ResourceUsage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadContent">
      <MemberSignature Language="C#" Value="public static void LoadContent (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void LoadContent(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.LoadContent(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub LoadContent (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member LoadContent : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.LoadContent (operations, resourceGroupName, profileName, endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task LoadContentAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task LoadContentAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.LoadContentAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member LoadContentAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.LoadContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;LoadContentAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContent">
      <MemberSignature Language="C#" Value="public static void PurgeContent (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void PurgeContent(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.PurgeContent(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub PurgeContent (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, contentPaths As IList(Of String))" />
      <MemberSignature Language="F#" Value="static member PurgeContent : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.PurgeContent (operations, resourceGroupName, profileName, endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeContentAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.IList&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeContentAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.IList`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.PurgeContentAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeContentAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.PurgeContentAsync (operations, resourceGroupName, profileName, endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;PurgeContentAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint Start (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint Start(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Start(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Start (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; StartAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; StartAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.StartAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;StartAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint Stop (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint Stop(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Stop(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Stop (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Stop (operations, resourceGroupName, profileName, endpointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; StopAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; StopAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.StopAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.StopAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;StopAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.Endpoint Update (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.Endpoint Update(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Update(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, endpointUpdateProperties As EndpointUpdateParameters) As Endpoint" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters -&gt; Microsoft.Azure.Management.Cdn.Models.Endpoint" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.Update (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.Endpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpointUpdateProperties">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; UpdateAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.Endpoint&gt; UpdateAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, class Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters endpointUpdateProperties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, endpointName, endpointUpdateProperties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="endpointUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Models.EndpointUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="endpointUpdateProperties">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomain">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput ValidateCustomDomain (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput ValidateCustomDomain(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ValidateCustomDomain(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ValidateCustomDomain (operations As IEndpointsOperations, resourceGroupName As String, profileName As String, endpointName As String, hostName As String) As ValidateCustomDomainOutput" />
      <MemberSignature Language="F#" Value="static member ValidateCustomDomain : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ValidateCustomDomain (operations, resourceGroupName, profileName, endpointName, hostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="hostName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomainAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput&gt; ValidateCustomDomainAsync (this Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput&gt; ValidateCustomDomainAsync(class Microsoft.Azure.Management.Cdn.IEndpointsOperations operations, string resourceGroupName, string profileName, string endpointName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ValidateCustomDomainAsync(Microsoft.Azure.Management.Cdn.IEndpointsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateCustomDomainAsync : Microsoft.Azure.Management.Cdn.IEndpointsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput&gt;" Usage="Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions.ValidateCustomDomainAsync (operations, resourceGroupName, profileName, endpointName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.EndpointsOperationsExtensions/&lt;ValidateCustomDomainAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Models.ValidateCustomDomainOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.IEndpointsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="hostName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>