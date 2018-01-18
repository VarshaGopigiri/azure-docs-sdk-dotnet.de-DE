<Type Name="WorkspaceCollectionsOperationsExtensions" FullName="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WorkspaceCollectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WorkspaceCollectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WorkspaceCollectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WorkspaceCollectionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.BeginDelete (operations, resourceGroupName, workspaceCollectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, workspaceCollectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse CheckNameAvailability (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string location, Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse CheckNameAvailability(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string location, class Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IWorkspaceCollectionsOperations, location As String, body As CheckNameRequest) As CheckNameResponse" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CheckNameAvailability (operations, location, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="location">To be added.</param>
        <param name="body">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string location, Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string location, class Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CheckNameAvailabilityAsync (operations, location, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.CheckNameRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="location">To be added.</param>
        <param name="body">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection Create (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection Create(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Create(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String, body As CreateWorkspaceCollectionRequest) As WorkspaceCollection" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Create (operations, resourceGroupName, workspaceCollectionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; CreateAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; CreateAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.CreateAsync (operations, resourceGroupName, workspaceCollectionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.CreateWorkspaceCollectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Delete(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Delete (operations, resourceGroupName, workspaceCollectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceCollectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAccessKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys GetAccessKeys (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys GetAccessKeys(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetAccessKeys(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAccessKeys (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String) As WorkspaceCollectionAccessKeys" />
      <MemberSignature Language="F#" Value="static member GetAccessKeys : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetAccessKeys (operations, resourceGroupName, workspaceCollectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAccessKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt; GetAccessKeysAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt; GetAccessKeysAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetAccessKeysAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAccessKeysAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetAccessKeysAsync (operations, resourceGroupName, workspaceCollectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;GetAccessKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection GetByName (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection GetByName(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetByName(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByName (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String) As WorkspaceCollection" />
      <MemberSignature Language="F#" Value="static member GetByName : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetByName (operations, resourceGroupName, workspaceCollectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; GetByNameAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; GetByNameAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetByNameAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByNameAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.GetByNameAsync (operations, resourceGroupName, workspaceCollectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;GetByNameAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; ListByResourceGroup (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; ListByResourceGroup(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IWorkspaceCollectionsOperations, resourceGroupName As String) As IEnumerable(Of WorkspaceCollection)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; ListBySubscription (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; ListBySubscription(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListBySubscription(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscription (operations As IWorkspaceCollectionsOperations) As IEnumerable(Of WorkspaceCollection)" />
      <MemberSignature Language="F#" Value="static member ListBySubscription : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations -&gt; seq&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Migrate">
      <MemberSignature Language="C#" Value="public static void Migrate (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Migrate(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Migrate(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Migrate (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, body As MigrateWorkspaceCollectionRequest)" />
      <MemberSignature Language="F#" Value="static member Migrate : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest -&gt; unit" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Migrate (operations, resourceGroupName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="body">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MigrateAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MigrateAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.MigrateAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MigrateAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.MigrateAsync (operations, resourceGroupName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;MigrateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.MigrateWorkspaceCollectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="body">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys RegenerateKey (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys RegenerateKey(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String, body As WorkspaceCollectionAccessKey) As WorkspaceCollectionAccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.RegenerateKey (operations, resourceGroupName, workspaceCollectionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, workspaceCollectionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollectionAccessKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection Update (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest body);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection Update(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest body) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Update(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IWorkspaceCollectionsOperations, resourceGroupName As String, workspaceCollectionName As String, body As UpdateWorkspaceCollectionRequest) As WorkspaceCollection" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest -&gt; Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.Update (operations, resourceGroupName, workspaceCollectionName, body)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; UpdateAsync (this Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt; UpdateAsync(class Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations operations, string resourceGroupName, string workspaceCollectionName, class Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations,System.String,System.String,Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations * string * string * Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;" Usage="Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions.UpdateAsync (operations, resourceGroupName, workspaceCollectionName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.PowerBIEmbedded</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.PowerBIEmbedded.WorkspaceCollectionsOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.PowerBIEmbedded.Models.WorkspaceCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.PowerBIEmbedded.IWorkspaceCollectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceCollectionName" Type="System.String" />
        <Parameter Name="body" Type="Microsoft.Azure.Management.PowerBIEmbedded.Models.UpdateWorkspaceCollectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="workspaceCollectionName">To be added.</param>
        <param name="body">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>