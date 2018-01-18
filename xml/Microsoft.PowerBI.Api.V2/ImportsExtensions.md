<Type Name="ImportsExtensions" FullName="Microsoft.PowerBI.Api.V2.ImportsExtensions">
  <TypeSignature Language="C#" Value="public static class ImportsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ImportsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.ImportsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ImportsExtensions" />
  <TypeSignature Language="F#" Value="type ImportsExtensions = class" />
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
    <Member MemberName="GetImportById">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import GetImportById (this Microsoft.PowerBI.Api.V2.IImports operations, string importId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import GetImportById(class Microsoft.PowerBI.Api.V2.IImports operations, string importId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportById(Microsoft.PowerBI.Api.V2.IImports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetImportById (operations As IImports, importId As String) As Import" />
      <MemberSignature Language="F#" Value="static member GetImportById : Microsoft.PowerBI.Api.V2.IImports * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportById (operations, importId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="importId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="importId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetImportByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; GetImportByIdAsync (this Microsoft.PowerBI.Api.V2.IImports operations, string importId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; GetImportByIdAsync(class Microsoft.PowerBI.Api.V2.IImports operations, string importId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdAsync(Microsoft.PowerBI.Api.V2.IImports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetImportByIdAsync : Microsoft.PowerBI.Api.V2.IImports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdAsync (operations, importId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;GetImportByIdAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="importId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="importId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetImportByIdInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import GetImportByIdInGroup (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string importId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import GetImportByIdInGroup(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string importId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdInGroup(Microsoft.PowerBI.Api.V2.IImports,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetImportByIdInGroup (operations As IImports, groupId As String, importId As String) As Import" />
      <MemberSignature Language="F#" Value="static member GetImportByIdInGroup : Microsoft.PowerBI.Api.V2.IImports * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdInGroup (operations, groupId, importId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="importId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="importId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetImportByIdInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; GetImportByIdInGroupAsync (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string importId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; GetImportByIdInGroupAsync(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string importId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdInGroupAsync(Microsoft.PowerBI.Api.V2.IImports,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetImportByIdInGroupAsync : Microsoft.PowerBI.Api.V2.IImports * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportByIdInGroupAsync (operations, groupId, importId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;GetImportByIdInGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="importId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="importId">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetImports">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport GetImports (this Microsoft.PowerBI.Api.V2.IImports operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport GetImports(class Microsoft.PowerBI.Api.V2.IImports operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImports(Microsoft.PowerBI.Api.V2.IImports)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetImports (operations As IImports) As ODataResponseListImport" />
      <MemberSignature Language="F#" Value="static member GetImports : Microsoft.PowerBI.Api.V2.IImports -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImports operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetImportsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt; GetImportsAsync (this Microsoft.PowerBI.Api.V2.IImports operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt; GetImportsAsync(class Microsoft.PowerBI.Api.V2.IImports operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsAsync(Microsoft.PowerBI.Api.V2.IImports,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetImportsAsync : Microsoft.PowerBI.Api.V2.IImports * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;GetImportsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
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
    <Member MemberName="GetImportsInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport GetImportsInGroup (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport GetImportsInGroup(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsInGroup(Microsoft.PowerBI.Api.V2.IImports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetImportsInGroup (operations As IImports, groupId As String) As ODataResponseListImport" />
      <MemberSignature Language="F#" Value="static member GetImportsInGroup : Microsoft.PowerBI.Api.V2.IImports * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsInGroup (operations, groupId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
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
    <Member MemberName="GetImportsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt; GetImportsInGroupAsync (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt; GetImportsInGroupAsync(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsInGroupAsync(Microsoft.PowerBI.Api.V2.IImports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetImportsInGroupAsync : Microsoft.PowerBI.Api.V2.IImports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.GetImportsInGroupAsync (operations, groupId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;GetImportsInGroupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListImport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
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
    <Member MemberName="PostImport">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import PostImport (this Microsoft.PowerBI.Api.V2.IImports operations, string datasetDisplayName, Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import PostImport(class Microsoft.PowerBI.Api.V2.IImports operations, string datasetDisplayName, class Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImport(Microsoft.PowerBI.Api.V2.IImports,System.String,Microsoft.PowerBI.Api.V2.Models.ImportInfo,System.String)" />
      <MemberSignature Language="F#" Value="static member PostImport : Microsoft.PowerBI.Api.V2.IImports * string * Microsoft.PowerBI.Api.V2.Models.ImportInfo * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImport (operations, datasetDisplayName, importInfo, nameConflict)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="importInfo" Type="Microsoft.PowerBI.Api.V2.Models.ImportInfo" />
        <Parameter Name="nameConflict" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="importInfo">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportAsync (this Microsoft.PowerBI.Api.V2.IImports operations, string datasetDisplayName, Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportAsync(class Microsoft.PowerBI.Api.V2.IImports operations, string datasetDisplayName, class Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportAsync(Microsoft.PowerBI.Api.V2.IImports,System.String,Microsoft.PowerBI.Api.V2.Models.ImportInfo,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostImportAsync : Microsoft.PowerBI.Api.V2.IImports * string * Microsoft.PowerBI.Api.V2.Models.ImportInfo * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportAsync (operations, datasetDisplayName, importInfo, nameConflict, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;PostImportAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="importInfo" Type="Microsoft.PowerBI.Api.V2.Models.ImportInfo" />
        <Parameter Name="nameConflict" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="importInfo">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import PostImportInGroup (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string datasetDisplayName, Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import PostImportInGroup(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string datasetDisplayName, class Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportInGroup(Microsoft.PowerBI.Api.V2.IImports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ImportInfo,System.String)" />
      <MemberSignature Language="F#" Value="static member PostImportInGroup : Microsoft.PowerBI.Api.V2.IImports * string * string * Microsoft.PowerBI.Api.V2.Models.ImportInfo * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportInGroup (operations, groupId, datasetDisplayName, importInfo, nameConflict)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="importInfo" Type="Microsoft.PowerBI.Api.V2.Models.ImportInfo" />
        <Parameter Name="nameConflict" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="importInfo">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportInGroupAsync (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string datasetDisplayName, Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportInGroupAsync(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, string datasetDisplayName, class Microsoft.PowerBI.Api.V2.Models.ImportInfo importInfo, string nameConflict, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportInGroupAsync(Microsoft.PowerBI.Api.V2.IImports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ImportInfo,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostImportInGroupAsync : Microsoft.PowerBI.Api.V2.IImports * string * string * Microsoft.PowerBI.Api.V2.Models.ImportInfo * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportInGroupAsync (operations, groupId, datasetDisplayName, importInfo, nameConflict, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;PostImportInGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="importInfo" Type="Microsoft.PowerBI.Api.V2.Models.ImportInfo" />
        <Parameter Name="nameConflict" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="importInfo">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportWithFile">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import PostImportWithFile (this Microsoft.PowerBI.Api.V2.IImports operations, System.IO.Stream fileStream, string datasetDisplayName = null, string nameConflict = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import PostImportWithFile(class Microsoft.PowerBI.Api.V2.IImports operations, class System.IO.Stream fileStream, string datasetDisplayName, string nameConflict) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFile(Microsoft.PowerBI.Api.V2.IImports,System.IO.Stream,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PostImportWithFile (operations As IImports, fileStream As Stream, Optional datasetDisplayName As String = null, Optional nameConflict As String = null) As Import" />
      <MemberSignature Language="F#" Value="static member PostImportWithFile : Microsoft.PowerBI.Api.V2.IImports * System.IO.Stream * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFile (operations, fileStream, datasetDisplayName, nameConflict)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="fileStream" Type="System.IO.Stream" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="nameConflict" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="fileStream">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportWithFileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportWithFileAsync (this Microsoft.PowerBI.Api.V2.IImports operations, System.IO.Stream fileStream, string datasetDisplayName = null, string nameConflict = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportWithFileAsync(class Microsoft.PowerBI.Api.V2.IImports operations, class System.IO.Stream fileStream, string datasetDisplayName, string nameConflict, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileAsync(Microsoft.PowerBI.Api.V2.IImports,System.IO.Stream,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostImportWithFileAsync : Microsoft.PowerBI.Api.V2.IImports * System.IO.Stream * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileAsync (operations, fileStream, datasetDisplayName, nameConflict, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;PostImportWithFileAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="fileStream" Type="System.IO.Stream" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="nameConflict" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="fileStream">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportWithFileAsyncInGroup">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportWithFileAsyncInGroup (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, System.IO.Stream fileStream, string datasetDisplayName = null, string nameConflict = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Import&gt; PostImportWithFileAsyncInGroup(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, class System.IO.Stream fileStream, string datasetDisplayName, string nameConflict, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileAsyncInGroup(Microsoft.PowerBI.Api.V2.IImports,System.String,System.IO.Stream,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PostImportWithFileAsyncInGroup : Microsoft.PowerBI.Api.V2.IImports * string * System.IO.Stream * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileAsyncInGroup (operations, groupId, fileStream, datasetDisplayName, nameConflict, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ImportsExtensions/&lt;PostImportWithFileAsyncInGroup&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Import&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="fileStream" Type="System.IO.Stream" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="nameConflict" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="fileStream">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostImportWithFileInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Import PostImportWithFileInGroup (this Microsoft.PowerBI.Api.V2.IImports operations, string groupId, System.IO.Stream fileStream, string datasetDisplayName = null, string nameConflict = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Import PostImportWithFileInGroup(class Microsoft.PowerBI.Api.V2.IImports operations, string groupId, class System.IO.Stream fileStream, string datasetDisplayName, string nameConflict) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileInGroup(Microsoft.PowerBI.Api.V2.IImports,System.String,System.IO.Stream,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PostImportWithFileInGroup (operations As IImports, groupId As String, fileStream As Stream, Optional datasetDisplayName As String = null, Optional nameConflict As String = null) As Import" />
      <MemberSignature Language="F#" Value="static member PostImportWithFileInGroup : Microsoft.PowerBI.Api.V2.IImports * string * System.IO.Stream * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Import" Usage="Microsoft.PowerBI.Api.V2.ImportsExtensions.PostImportWithFileInGroup (operations, groupId, fileStream, datasetDisplayName, nameConflict)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Import</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IImports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="fileStream" Type="System.IO.Stream" />
        <Parameter Name="datasetDisplayName" Type="System.String" />
        <Parameter Name="nameConflict" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="fileStream">To be added.</param>
        <param name="datasetDisplayName">To be added.</param>
        <param name="nameConflict">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>