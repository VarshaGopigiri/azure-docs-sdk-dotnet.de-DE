<Type Name="ExtensionOperationsExtensions" FullName="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExtensionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExtensionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExtensionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExtensionOperationsExtensions = class" />
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
    <Member MemberName="BeginDisableMonitoring">
      <MemberSignature Language="C#" Value="public static void BeginDisableMonitoring (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDisableMonitoring(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginDisableMonitoring(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDisableMonitoring (operations As IExtensionOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDisableMonitoring : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginDisableMonitoring (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="BeginDisableMonitoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDisableMonitoringAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDisableMonitoringAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginDisableMonitoringAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDisableMonitoringAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginDisableMonitoringAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;BeginDisableMonitoringAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="BeginEnableMonitoring">
      <MemberSignature Language="C#" Value="public static void BeginEnableMonitoring (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginEnableMonitoring(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginEnableMonitoring(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginEnableMonitoring (operations As IExtensionOperations, resourceGroupName As String, clusterName As String, parameters As ClusterMonitoringRequest)" />
      <MemberSignature Language="F#" Value="static member BeginEnableMonitoring : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginEnableMonitoring (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest" />
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
    <Member MemberName="BeginEnableMonitoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginEnableMonitoringAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginEnableMonitoringAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginEnableMonitoringAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginEnableMonitoringAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.BeginEnableMonitoringAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;BeginEnableMonitoringAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest" />
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static void Create (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.Extension parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Create(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.Extension parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Create(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.Extension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Create (operations As IExtensionOperations, resourceGroupName As String, clusterName As String, parameters As Extension)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.Extension -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Create (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.Extension" />
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
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.Extension parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.Extension parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.CreateAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.Extension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.Extension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.CreateAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;CreateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.Extension" />
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
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Delete(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IExtensionOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Delete (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DeleteAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="DisableMonitoring">
      <MemberSignature Language="C#" Value="public static void DisableMonitoring (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableMonitoring(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DisableMonitoring(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableMonitoring (operations As IExtensionOperations, resourceGroupName As String, clusterName As String)" />
      <MemberSignature Language="F#" Value="static member DisableMonitoring : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DisableMonitoring (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="DisableMonitoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableMonitoringAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableMonitoringAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DisableMonitoringAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableMonitoringAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.DisableMonitoringAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;DisableMonitoringAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="EnableMonitoring">
      <MemberSignature Language="C#" Value="public static void EnableMonitoring (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableMonitoring(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.EnableMonitoring(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableMonitoring (operations As IExtensionOperations, resourceGroupName As String, clusterName As String, parameters As ClusterMonitoringRequest)" />
      <MemberSignature Language="F#" Value="static member EnableMonitoring : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest -&gt; unit" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.EnableMonitoring (operations, resourceGroupName, clusterName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest" />
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
    <Member MemberName="EnableMonitoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableMonitoringAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableMonitoringAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.EnableMonitoringAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableMonitoringAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.EnableMonitoringAsync (operations, resourceGroupName, clusterName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;EnableMonitoringAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringRequest" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.Extension Get (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.Extension Get(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Get(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExtensionOperations, resourceGroupName As String, clusterName As String) As Extension" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string -&gt; Microsoft.Azure.Management.HDInsight.Models.Extension" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.Get (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Extension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Extension&gt; GetAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Extension&gt; GetAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Extension&gt;" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.Extension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="GetMonitoringStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse GetMonitoringStatus (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse GetMonitoringStatus(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetMonitoringStatus(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetMonitoringStatus (operations As IExtensionOperations, resourceGroupName As String, clusterName As String) As ClusterMonitoringResponse" />
      <MemberSignature Language="F#" Value="static member GetMonitoringStatus : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string -&gt; Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetMonitoringStatus (operations, resourceGroupName, clusterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
    <Member MemberName="GetMonitoringStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse&gt; GetMonitoringStatusAsync (this Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse&gt; GetMonitoringStatusAsync(class Microsoft.Azure.Management.HDInsight.IExtensionOperations operations, string resourceGroupName, string clusterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetMonitoringStatusAsync(Microsoft.Azure.Management.HDInsight.IExtensionOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMonitoringStatusAsync : Microsoft.Azure.Management.HDInsight.IExtensionOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse&gt;" Usage="Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions.GetMonitoringStatusAsync (operations, resourceGroupName, clusterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.HDInsight.ExtensionOperationsExtensions/&lt;GetMonitoringStatusAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.HDInsight.Models.ClusterMonitoringResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.HDInsight.IExtensionOperations" RefType="this" />
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
  </Members>
</Type>