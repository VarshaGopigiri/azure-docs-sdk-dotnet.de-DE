<Type Name="ScriptExecutionHistoryOperationsExtensions" FullName="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ScriptExecutionHistoryOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ScriptExecutionHistoryOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ScriptExecutionHistoryOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ScriptExecutionHistoryOperationsExtensions = class" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt; List (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt; List(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.List(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IScriptExecutionHistoryOperations, resourceGroupName As String, clusterName As String) As IPage(Of RuntimeScriptActionDetail)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.List (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
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
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt; ListAsync (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt; ListAsync(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListAsync(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
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
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt; ListNext (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt; ListNext(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListNext(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IScriptExecutionHistoryOperations, nextPageLink As String) As IPage(Of RuntimeScriptActionDetail)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt;" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptActionDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
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
    <Member MemberName="Promote">
      <MemberSignature Language="C#" Value="public static void Promote (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, long scriptExecutionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Promote(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, int64 scriptExecutionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.Promote(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Promote (operations As IScriptExecutionHistoryOperations, resourceGroupName As String, clusterName As String, scriptExecutionId As Long)" />
      <MemberSignature Language="F#" Value="static member Promote : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string * string * int64 -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.Promote (operations, resourceGroupName, clusterName, scriptExecutionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptExecutionId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptExecutionId">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromoteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PromoteAsync (this Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, long scriptExecutionId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PromoteAsync(class Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations operations, string resourceGroupName, string clusterName, int64 scriptExecutionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.PromoteAsync(Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations,System.String,System.String,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PromoteAsync : Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations * string * string * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions.PromoteAsync (operations, resourceGroupName, clusterName, scriptExecutionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ScriptExecutionHistoryOperationsExtensions/&lt;PromoteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IScriptExecutionHistoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="scriptExecutionId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="clusterName">To be added.</param>
        <param name="scriptExecutionId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>