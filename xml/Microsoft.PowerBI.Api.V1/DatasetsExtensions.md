<Type Name="DatasetsExtensions" FullName="Microsoft.PowerBI.Api.V1.DatasetsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V1.DatasetsExtensions" />
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
    <Member MemberName="DeleteDatasetById">
      <MemberSignature Language="C#" Value="public static object DeleteDatasetById (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteDatasetById(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteDatasetById(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteDatasetById (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetById : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteDatasetById (operations, collectionName, workspaceId, datasetKey)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteDatasetByIdAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteDatasetByIdAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteDatasetByIdAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteDatasetByIdAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteDatasetByIdAsync (operations, collectionName, workspaceId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;DeleteDatasetByIdAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRows">
      <MemberSignature Language="C#" Value="public static object DeleteRows (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteRows(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteRows(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteRows (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String, tableName As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteRows : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteRows (operations, collectionName, workspaceId, datasetKey, tableName)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteRowsAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteRowsAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteRowsAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteRowsAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.DeleteRowsAsync (operations, collectionName, workspaceId, datasetKey, tableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;DeleteRowsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetById">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V1.Models.Dataset GetDatasetById (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V1.Models.Dataset GetDatasetById(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetById(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasetById (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String) As Dataset" />
      <MemberSignature Language="F#" Value="static member GetDatasetById : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string -&gt; Microsoft.PowerBI.Api.V1.Models.Dataset" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetById (operations, collectionName, workspaceId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V1.Models.Dataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.Dataset&gt; GetDatasetByIdAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V1.Models.Dataset&gt; GetDatasetByIdAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetByIdAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetByIdAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.Dataset&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetByIdAsync (operations, collectionName, workspaceId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;GetDatasetByIdAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.Dataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasets">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset GetDatasets (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset GetDatasets(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasets(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasets (operations As IDatasets, collectionName As String, workspaceId As String) As ODataResponseListDataset" />
      <MemberSignature Language="F#" Value="static member GetDatasets : Microsoft.PowerBI.Api.V1.IDatasets * string * string -&gt; Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasets (operations, collectionName, workspaceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset&gt; GetDatasetsAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset&gt; GetDatasetsAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetsAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasetsAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasetsAsync (operations, collectionName, workspaceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;GetDatasetsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDataset&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasources">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource GetDatasources (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource GetDatasources(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasources(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatasources (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String) As ODataResponseListDatasource" />
      <MemberSignature Language="F#" Value="static member GetDatasources : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string -&gt; Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasources (operations, collectionName, workspaceId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource&gt; GetDatasourcesAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource&gt; GetDatasourcesAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasourcesAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatasourcesAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetDatasourcesAsync (operations, collectionName, workspaceId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;GetDatasourcesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasources">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource GetGatewayDatasources (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource GetGatewayDatasources(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetGatewayDatasources(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayDatasources (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String) As ODataResponseListGatewayDatasource" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasources : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string -&gt; Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetGatewayDatasources (operations, collectionName, workspaceId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource&gt; GetGatewayDatasourcesAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetGatewayDatasourcesAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayDatasourcesAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetGatewayDatasourcesAsync (operations, collectionName, workspaceId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;GetGatewayDatasourcesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListGatewayDatasource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTables">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable GetTables (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable GetTables(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetTables(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTables (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String) As ODataResponseListTable" />
      <MemberSignature Language="F#" Value="static member GetTables : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string -&gt; Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetTables (operations, collectionName, workspaceId, datasetKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable&gt; GetTablesAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable&gt; GetTablesAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetTablesAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTablesAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.GetTablesAsync (operations, collectionName, workspaceId, datasetKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;GetTablesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V1.Models.ODataResponseListTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDataset">
      <MemberSignature Language="C#" Value="public static object PostDataset (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, Microsoft.PowerBI.Api.V1.Models.Dataset dataset);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostDataset(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, class Microsoft.PowerBI.Api.V1.Models.Dataset dataset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostDataset(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V1.Models.Dataset)" />
      <MemberSignature Language="F#" Value="static member PostDataset : Microsoft.PowerBI.Api.V1.IDatasets * string * string * Microsoft.PowerBI.Api.V1.Models.Dataset -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostDataset (operations, collectionName, workspaceId, dataset)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V1.Models.Dataset" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="dataset">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostDatasetAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, Microsoft.PowerBI.Api.V1.Models.Dataset dataset, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostDatasetAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, class Microsoft.PowerBI.Api.V1.Models.Dataset dataset, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostDatasetAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,Microsoft.PowerBI.Api.V1.Models.Dataset,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostDatasetAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * Microsoft.PowerBI.Api.V1.Models.Dataset * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostDatasetAsync (operations, collectionName, workspaceId, dataset, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;PostDatasetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V1.Models.Dataset" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="dataset">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRows">
      <MemberSignature Language="C#" Value="public static object PostRows (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PostRows(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostRows(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PostRows (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PostRows : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostRows (operations, collectionName, workspaceId, datasetKey, tableName, requestMessage)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PostRowsAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PostRowsAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostRowsAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostRowsAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PostRowsAsync (operations, collectionName, workspaceId, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;PostRowsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
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
      <MemberSignature Language="C#" Value="public static object PutTable (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object PutTable(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PutTable(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PutTable (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String, tableName As String, requestMessage As Object) As Object" />
      <MemberSignature Language="F#" Value="static member PutTable : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PutTable (operations, collectionName, workspaceId, datasetKey, tableName, requestMessage)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; PutTableAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; PutTableAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, string tableName, object requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.PutTableAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PutTableAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.PutTableAsync (operations, collectionName, workspaceId, datasetKey, tableName, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;PutTableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllConnections">
      <MemberSignature Language="C#" Value="public static object SetAllConnections (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, object parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object SetAllConnections(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, object parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.SetAllConnections(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetAllConnections (operations As IDatasets, collectionName As String, workspaceId As String, datasetKey As String, parameters As Object) As Object" />
      <MemberSignature Language="F#" Value="static member SetAllConnections : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * obj -&gt; obj" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.SetAllConnections (operations, collectionName, workspaceId, datasetKey, parameters)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; SetAllConnectionsAsync (this Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, object parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; SetAllConnectionsAsync(class Microsoft.PowerBI.Api.V1.IDatasets operations, string collectionName, string workspaceId, string datasetKey, object parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V1.DatasetsExtensions.SetAllConnectionsAsync(Microsoft.PowerBI.Api.V1.IDatasets,System.String,System.String,System.String,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetAllConnectionsAsync : Microsoft.PowerBI.Api.V1.IDatasets * string * string * string * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V1.DatasetsExtensions.SetAllConnectionsAsync (operations, collectionName, workspaceId, datasetKey, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V1.DatasetsExtensions/&lt;SetAllConnectionsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V1.IDatasets" RefType="this" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="workspaceId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="collectionName">To be added.</param>
        <param name="workspaceId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>