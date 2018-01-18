<Type Name="ClustersOperationsExtensions" FullName="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ClustersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ClustersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ClustersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ClustersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Cluster BeginCreate (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Cluster BeginCreate(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParametersExtended) As Cluster" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended -&gt; Microsoft.Azure.Management.HDInsight.Models.Cluster" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreate (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreateAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreateAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginCreateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreating">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreating (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreating(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreating(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreating (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As AzureOperationResponse(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member BeginCreating : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters -&gt; Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreating (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreatingAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; BeginCreatingAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreatingAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginCreatingAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginCreatingAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginDelete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteScriptActions">
      <MemberSignature Language="C#" Value="public static void BeginExecuteScriptActions (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginExecuteScriptActions(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActions(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginExecuteScriptActions (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ExecuteScriptActionParameters)" />
      <MemberSignature Language="F#" Value="static member BeginExecuteScriptActions : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActions (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteScriptActions">
      <MemberSignature Language="C#" Value="public static void BeginExecuteScriptActions (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginExecuteScriptActions(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActions(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginExecuteScriptActions (operations As IClustersOperations, resourceGroupName As String, clusterName As String, scriptActions As IList(Of RuntimeScriptAction), persistOnSuccess As Boolean)" />
      <MemberSignature Language="F#" Value="static member BeginExecuteScriptActions : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * bool -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActions (operations, resourceGroupName, clusterName, scriptActions, persistOnSuccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="persistOnSuccess" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptActions">To be added.</param>
        <param name="persistOnSuccess">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteScriptActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginExecuteScriptActionsAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginExecuteScriptActionsAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActionsAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExecuteScriptActionsAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActionsAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginExecuteScriptActionsAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteScriptActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginExecuteScriptActionsAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginExecuteScriptActionsAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActionsAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginExecuteScriptActionsAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginExecuteScriptActionsAsync (operations, resourceGroupName, clusterName, scriptActions, persistOnSuccess, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginExecuteScriptActionsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="persistOnSuccess" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptActions">To be added.</param>
        <param name="persistOnSuccess">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResize">
      <MemberSignature Language="C#" Value="public static void BeginResize (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginResize(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResize(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginResize (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterResizeParameters)" />
      <MemberSignature Language="F#" Value="static member BeginResize : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResize (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResizeAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResizeAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizeAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResizeAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizeAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginResizeAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResizing">
      <MemberSignature Language="C#" Value="public static void BeginResizing (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int targetInstanceCount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginResizing(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int32 targetInstanceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizing(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginResizing (operations As IClustersOperations, resourceGroupName As String, clusterName As String, targetInstanceCount As Integer)" />
      <MemberSignature Language="F#" Value="static member BeginResizing : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * int -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizing (operations, resourceGroupName, clusterName, targetInstanceCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="targetInstanceCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="targetInstanceCount">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResizingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginResizingAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int targetInstanceCount, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginResizingAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int32 targetInstanceCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizingAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResizingAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.BeginResizingAsync (operations, resourceGroupName, clusterName, targetInstanceCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;BeginResizingAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="targetInstanceCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="targetInstanceCount">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Cluster Create (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Cluster Create(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Create(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters -&gt; Microsoft.Azure.Management.HDInsight.Models.Cluster" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Cluster Create (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Cluster Create(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Create(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterCreateParametersExtended) As Cluster" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended -&gt; Microsoft.Azure.Management.HDInsight.Models.Cluster" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; CreateAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; CreateAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; CreateAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; CreateAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterCreateParametersExtended" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Delete(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IClustersOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Delete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.DeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;DeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScriptActions">
      <MemberSignature Language="C#" Value="public static void ExecuteScriptActions (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ExecuteScriptActions(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActions(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ExecuteScriptActions (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ExecuteScriptActionParameters)" />
      <MemberSignature Language="F#" Value="static member ExecuteScriptActions : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActions (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScriptActions">
      <MemberSignature Language="C#" Value="public static void ExecuteScriptActions (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ExecuteScriptActions(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActions(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ExecuteScriptActions (operations As IClustersOperations, resourceGroupName As String, clusterName As String, scriptActions As IList(Of RuntimeScriptAction), persistOnSuccess As Boolean)" />
      <MemberSignature Language="F#" Value="static member ExecuteScriptActions : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * bool -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActions (operations, resourceGroupName, clusterName, scriptActions, persistOnSuccess)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="persistOnSuccess" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptActions">To be added.</param>
        <param name="persistOnSuccess">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScriptActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExecuteScriptActionsAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExecuteScriptActionsAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActionsAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExecuteScriptActionsAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActionsAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ExecuteScriptActionsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ExecuteScriptActionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScriptActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ExecuteScriptActionsAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ExecuteScriptActionsAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; scriptActions, bool persistOnSuccess, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActionsAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExecuteScriptActionsAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ExecuteScriptActionsAsync (operations, resourceGroupName, clusterName, scriptActions, persistOnSuccess, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ExecuteScriptActionsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="persistOnSuccess" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptActions">To be added.</param>
        <param name="persistOnSuccess">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Cluster Get (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Cluster Get(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Get(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IClustersOperations, resourceGroupName As String, clusterName As String) As Cluster" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string -&gt; Microsoft.Azure.Management.HDInsight.Models.Cluster" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Get (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; GetAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; GetAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.GetAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.GetAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;GetAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; List (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; List(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.List(Microsoft.Azure.Management.HDInsight.IClustersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IClustersOperations) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.HDInsight.IClustersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ListAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListByResourceGroup (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListByResourceGroup(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IClustersOperations, resourceGroupName As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.HDInsight.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.HDInsight.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListNext (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; ListNext(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListNext(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IClustersOperations, nextPageLink As String) As IPage(Of Cluster)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.HDInsight.IClustersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ListNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
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
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static void Resize (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Resize(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Resize(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Resize (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterResizeParameters)" />
      <MemberSignature Language="F#" Value="static member Resize : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Resize (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static void Resize (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int targetInstanceCount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Resize(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int32 targetInstanceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Resize(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Resize (operations As IClustersOperations, resourceGroupName As String, clusterName As String, targetInstanceCount As Integer)" />
      <MemberSignature Language="F#" Value="static member Resize : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * int -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Resize (operations, resourceGroupName, clusterName, targetInstanceCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="targetInstanceCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="targetInstanceCount">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResizeAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResizeAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ResizeAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResizeAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ResizeAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ResizeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterResizeParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResizeAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int targetInstanceCount, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResizeAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, int32 targetInstanceCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ResizeAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResizeAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.ResizeAsync (operations, resourceGroupName, clusterName, targetInstanceCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;ResizeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="targetInstanceCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="targetInstanceCount">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Cluster Update (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Cluster Update(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Update(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IClustersOperations, resourceGroupName As String, clusterName As String, parameters As ClusterPatchParameters) As Cluster" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters -&gt; Microsoft.Azure.Management.HDInsight.Models.Cluster" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.Update (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Cluster</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; UpdateAsync (this Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Cluster&gt; UpdateAsync(class Microsoft.Azure.Management.HDInsight.IClustersOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.HDInsight.IClustersOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.HDInsight.IClustersOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;" Usage="Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions.UpdateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ClustersOperationsExtensions/&lt;UpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Cluster&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IClustersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>