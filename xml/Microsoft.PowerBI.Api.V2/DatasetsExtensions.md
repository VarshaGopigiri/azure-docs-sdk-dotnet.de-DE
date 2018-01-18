<Type Name="DatasetsExtensions" FullName="Microsoft.PowerBI.Api.V2.DatasetsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.DatasetsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatasetsExtensions" />
  <TypeSignature Language="F#" Value="type DatasetsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
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
    <Member MemberName="BindToGateway">
      <MemberSignature Language="C#" Value="public static object BindToGateway (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object BindToGateway(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGateway(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest)" />
      <MemberSignature Language="F#" Value="static member BindToGateway : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGateway (operations, datasetKey, bindToGatewayRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindToGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; BindToGatewayAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; BindToGatewayAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BindToGatewayAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayAsync (operations, datasetKey, bindToGatewayRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;BindToGatewayAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindToGatewayInGroup">
      <MemberSignature Language="C#" Value="public static object BindToGatewayInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object BindToGatewayInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest)" />
      <MemberSignature Language="F#" Value="static member BindToGatewayInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayInGroup (operations, groupId, datasetKey, bindToGatewayRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindToGatewayInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; BindToGatewayInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; BindToGatewayInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BindToGatewayInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.BindToGatewayInGroupAsync (operations, groupId, datasetKey, bindToGatewayRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;BindToGatewayInGroupAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetById">
      <MemberSignature Language="C#" Value="public static object DeleteDatasetById (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteDatasetById(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetById(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteDatasetById (operations As IDatasets, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetById : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetById (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteDatasetByIdAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteDatasetByIdAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetByIdAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;DeleteDatasetByIdAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdInGroup">
      <MemberSignature Language="C#" Value="public static object DeleteDatasetByIdInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteDatasetByIdInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteDatasetByIdInGroup (operations As IDatasets, groupId As String, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetByIdInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteDatasetByIdInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteDatasetByIdInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetByIdInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteDatasetByIdInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;DeleteDatasetByIdInGroupAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRows">
      <MemberSignature Language="C#" Value="public static object DeleteRows (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteRows(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRows(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteRows (operations As IDatasets, datasetKey As String, tableName As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteRows : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRows (operations, datasetKey, tableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteRowsAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteRowsAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteRowsAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsAsync (operations, datasetKey, tableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;DeleteRowsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsInGroup">
      <MemberSignature Language="C#" Value="public static object DeleteRowsInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteRowsInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteRowsInGroup (operations As IDatasets, groupId As String, datasetKey As String, tableName As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteRowsInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsInGroup (operations, groupId, datasetKey, tableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteRowsInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteRowsInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteRowsInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.DeleteRowsInGroupAsync (operations, groupId, datasetKey, tableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;DeleteRowsInGroupAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GenerateTokenInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateTokenInGroup (operations As IDatasets, groupId As String, datasetKey As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GenerateTokenInGroup (operations, groupId, datasetKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.EmbedToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GenerateTokenInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GenerateTokenInGroupAsync (operations, groupId, datasetKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GenerateTokenInGroupAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetById">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dataset GetDatasetById (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dataset GetDatasetById(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetById(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasetById (operations As IDatasets, datasetKey As String) As Dataset" />
      <MemberSignature Language="F#" Value="static member GetDatasetById : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.Dataset" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetById (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt; GetDatasetByIdAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dataset&gt; GetDatasetByIdAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetByIdAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasetByIdAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dataset GetDatasetByIdInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dataset GetDatasetByIdInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasetByIdInGroup (operations As IDatasets, groupId As String, datasetKey As String) As Dataset" />
      <MemberSignature Language="F#" Value="static member GetDatasetByIdInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Dataset" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt; GetDatasetByIdInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dataset&gt; GetDatasetByIdInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetByIdInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetByIdInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasetByIdInGroupAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasets">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset GetDatasets (this Microsoft.PowerBI.Api.V2.IDatasets operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset GetDatasets(class Microsoft.PowerBI.Api.V2.IDatasets operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasets(Microsoft.PowerBI.Api.V2.IDatasets)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasets (operations As IDatasets) As ODataResponseListDataset" />
      <MemberSignature Language="F#" Value="static member GetDatasets : Microsoft.PowerBI.Api.V2.IDatasets -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasets operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt; GetDatasetsAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt; GetDatasetsAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetsAsync : Microsoft.PowerBI.Api.V2.IDatasets * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasetsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
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
    <Member MemberName="GetDatasetsInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset GetDatasetsInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset GetDatasetsInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasetsInGroup (operations As IDatasets, groupId As String) As ODataResponseListDataset" />
      <MemberSignature Language="F#" Value="static member GetDatasetsInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsInGroup (operations, groupId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt; GetDatasetsInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt; GetDatasetsInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetsInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasetsInGroupAsync (operations, groupId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasetsInGroupAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasources">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasources (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasources(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasources(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasources (operations As IDatasets, datasetKey As String) As ODataResponseListDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasources : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasources (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsAdmin">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasourcesAsAdmin (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasourcesAsAdmin(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsAdmin(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasourcesAsAdmin (operations As IDatasets, datasetKey As String) As ODataResponseListDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesAsAdmin : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsAdmin (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsAdminAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesAsAdminAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesAsAdminAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsAdminAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesAsAdminAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsAdminAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasourcesAsAdminAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasourcesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasourcesInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource GetDatasourcesInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasourcesInGroup (operations As IDatasets, groupId As String, datasetKey As String) As ODataResponseListDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt; GetDatasourcesInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetDatasourcesInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetDatasourcesInGroupAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasources">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetGatewayDatasources (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetGatewayDatasources(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasources(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayDatasources (operations As IDatasets, datasetKey As String) As ODataResponseListGatewayDatasource" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasources : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasources (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasourcesAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetGatewayDatasourcesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetGatewayDatasourcesInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource GetGatewayDatasourcesInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayDatasourcesInGroup (operations As IDatasets, groupId As String, datasetKey As String) As ODataResponseListGatewayDatasource" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasourcesInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasourcesInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetGatewayDatasourcesInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetGatewayDatasourcesInGroupAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistory">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh GetRefreshHistory (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh GetRefreshHistory(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistory(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRefreshHistory (operations As IDatasets, datasetKey As String, Optional top As Nullable(Of Integer) = null) As ODataResponseListRefresh" />
      <MemberSignature Language="F#" Value="static member GetRefreshHistory : Microsoft.PowerBI.Api.V2.IDatasets * string * Nullable&lt;int&gt; -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistory (operations, datasetKey, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt; GetRefreshHistoryAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt; GetRefreshHistoryAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRefreshHistoryAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryAsync (operations, datasetKey, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetRefreshHistoryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistoryInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh GetRefreshHistoryInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh GetRefreshHistoryInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRefreshHistoryInGroup (operations As IDatasets, groupId As String, datasetKey As String, Optional top As Nullable(Of Integer) = null) As ODataResponseListRefresh" />
      <MemberSignature Language="F#" Value="static member GetRefreshHistoryInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Nullable&lt;int&gt; -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryInGroup (operations, groupId, datasetKey, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistoryInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt; GetRefreshHistoryInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt; GetRefreshHistoryInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRefreshHistoryInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetRefreshHistoryInGroupAsync (operations, groupId, datasetKey, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetRefreshHistoryInGroupAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTables">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable GetTables (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable GetTables(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTables(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTables (operations As IDatasets, datasetKey As String) As ODataResponseListTable" />
      <MemberSignature Language="F#" Value="static member GetTables : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTables (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt; GetTablesAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt; GetTablesAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTablesAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetTablesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable GetTablesInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable GetTablesInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTablesInGroup (operations As IDatasets, groupId As String, datasetKey As String) As ODataResponseListTable" />
      <MemberSignature Language="F#" Value="static member GetTablesInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt; GetTablesInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt; GetTablesInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTablesInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.GetTablesInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;GetTablesInGroupAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDataset">
      <MemberSignature Language="C#" Value="public static object PostDataset (this Microsoft.PowerBI.Api.V2.IDatasets operations, Microsoft.PowerBI.Api.V2.Models.Dataset dataset);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostDataset(class Microsoft.PowerBI.Api.V2.IDatasets operations, class Microsoft.PowerBI.Api.V2.Models.Dataset dataset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDataset(Microsoft.PowerBI.Api.V2.IDatasets,Microsoft.PowerBI.Api.V2.Models.Dataset)" />
      <MemberSignature Language="F#" Value="static member PostDataset : Microsoft.PowerBI.Api.V2.IDatasets * Microsoft.PowerBI.Api.V2.Models.Dataset -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDataset (operations, dataset)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dataset">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostDatasetAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, Microsoft.PowerBI.Api.V2.Models.Dataset dataset, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostDatasetAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, class Microsoft.PowerBI.Api.V2.Models.Dataset dataset, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetAsync(Microsoft.PowerBI.Api.V2.IDatasets,Microsoft.PowerBI.Api.V2.Models.Dataset,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostDatasetAsync : Microsoft.PowerBI.Api.V2.IDatasets * Microsoft.PowerBI.Api.V2.Models.Dataset * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetAsync (operations, dataset, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PostDatasetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dataset">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetInGroup">
      <MemberSignature Language="C#" Value="public static object PostDatasetInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, Microsoft.PowerBI.Api.V2.Models.Dataset dataset);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostDatasetInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.Dataset dataset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.Dataset)" />
      <MemberSignature Language="F#" Value="static member PostDatasetInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.Dataset -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetInGroup (operations, groupId, dataset)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dataset">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostDatasetInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, Microsoft.PowerBI.Api.V2.Models.Dataset dataset, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostDatasetInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.Dataset dataset, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.Dataset,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostDatasetInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.Dataset * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostDatasetInGroupAsync (operations, groupId, dataset, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PostDatasetInGroupAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dataset">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRows">
      <MemberSignature Language="C#" Value="public static object PostRows (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostRows(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRows(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PostRows (operations As IDatasets, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PostRows : Microsoft.PowerBI.Api.V2.IDatasets * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRows (operations, datasetKey, tableName, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostRowsAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostRowsAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostRowsAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsAsync (operations, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PostRowsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsInGroup">
      <MemberSignature Language="C#" Value="public static object PostRowsInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostRowsInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PostRowsInGroup (operations As IDatasets, groupId As String, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PostRowsInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsInGroup (operations, groupId, datasetKey, tableName, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostRowsInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostRowsInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostRowsInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PostRowsInGroupAsync (operations, groupId, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PostRowsInGroupAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTable">
      <MemberSignature Language="C#" Value="public static object PutTable (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PutTable(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTable(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PutTable (operations As IDatasets, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PutTable : Microsoft.PowerBI.Api.V2.IDatasets * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTable (operations, datasetKey, tableName, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PutTableAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PutTableAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PutTableAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableAsync (operations, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PutTableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableInGroup">
      <MemberSignature Language="C#" Value="public static object PutTableInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PutTableInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PutTableInGroup (operations As IDatasets, groupId As String, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PutTableInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableInGroup (operations, groupId, datasetKey, tableName, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PutTableInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PutTableInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PutTableInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.PutTableInGroupAsync (operations, groupId, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;PutTableInGroupAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDataset">
      <MemberSignature Language="C#" Value="public static object RefreshDataset (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object RefreshDataset(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDataset(Microsoft.PowerBI.Api.V2.IDatasets,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RefreshDataset (operations As IDatasets, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member RefreshDataset : Microsoft.PowerBI.Api.V2.IDatasets * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDataset (operations, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDatasetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; RefreshDatasetAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; RefreshDatasetAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshDatasetAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetAsync (operations, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;RefreshDatasetAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDatasetInGroup">
      <MemberSignature Language="C#" Value="public static object RefreshDatasetInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object RefreshDatasetInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RefreshDatasetInGroup (operations As IDatasets, groupId As String, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member RefreshDatasetInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDatasetInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; RefreshDatasetInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; RefreshDatasetInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RefreshDatasetInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.RefreshDatasetInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;RefreshDatasetInGroupAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnections">
      <MemberSignature Language="C#" Value="public static object SetAllDatasetConnections (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object SetAllDatasetConnections(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnections(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetAllDatasetConnections (operations As IDatasets, datasetKey As String, parameters As ConnectionDetails) As Object" />
      <MemberSignature Language="F#" Value="static member SetAllDatasetConnections : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnections (operations, datasetKey, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; SetAllDatasetConnectionsAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; SetAllDatasetConnectionsAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAllDatasetConnectionsAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsAsync (operations, datasetKey, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;SetAllDatasetConnectionsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnectionsInGroup">
      <MemberSignature Language="C#" Value="public static object SetAllDatasetConnectionsInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object SetAllDatasetConnectionsInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetAllDatasetConnectionsInGroup (operations As IDatasets, groupId As String, datasetKey As String, parameters As ConnectionDetails) As Object" />
      <MemberSignature Language="F#" Value="static member SetAllDatasetConnectionsInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsInGroup (operations, groupId, datasetKey, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnectionsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; SetAllDatasetConnectionsInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; SetAllDatasetConnectionsInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAllDatasetConnectionsInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.SetAllDatasetConnectionsInGroupAsync (operations, groupId, datasetKey, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;SetAllDatasetConnectionsInGroupAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeOverInGroup">
      <MemberSignature Language="C#" Value="public static object TakeOverInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object TakeOverInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.TakeOverInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function TakeOverInGroup (operations As IDatasets, groupId As String, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member TakeOverInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.TakeOverInGroup (operations, groupId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeOverInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; TakeOverInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; TakeOverInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.TakeOverInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TakeOverInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.TakeOverInGroupAsync (operations, groupId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;TakeOverInGroupAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasources">
      <MemberSignature Language="C#" Value="public static object UpdateDatasources (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object UpdateDatasources(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasources(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasources : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasources (operations, datasetKey, updateDatasourcesRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; UpdateDatasourcesAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; UpdateDatasourcesAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasourcesAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesAsync (operations, datasetKey, updateDatasourcesRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;UpdateDatasourcesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourcesInGroup">
      <MemberSignature Language="C#" Value="public static object UpdateDatasourcesInGroup (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object UpdateDatasourcesInGroup(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesInGroup(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasourcesInGroup : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesInGroup (operations, groupId, datasetKey, updateDatasourcesRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourcesInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; UpdateDatasourcesInGroupAsync (this Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; UpdateDatasourcesInGroupAsync(class Microsoft.PowerBI.Api.V2.IDatasets operations, string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesInGroupAsync(Microsoft.PowerBI.Api.V2.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateDatasourcesInGroupAsync : Microsoft.PowerBI.Api.V2.IDatasets * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.DatasetsExtensions.UpdateDatasourcesInGroupAsync (operations, groupId, datasetKey, updateDatasourcesRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DatasetsExtensions/&lt;UpdateDatasourcesInGroupAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDatasets" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>