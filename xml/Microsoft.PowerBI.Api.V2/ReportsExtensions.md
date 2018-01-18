<Type Name="ReportsExtensions" FullName="Microsoft.PowerBI.Api.V2.ReportsExtensions">
  <TypeSignature Language="C#" Value="public static class ReportsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ReportsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.ReportsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ReportsExtensions" />
  <TypeSignature Language="F#" Value="type ReportsExtensions = class" />
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
    <Member MemberName="CloneReport">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report CloneReport (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report CloneReport(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReport(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CloneReport (operations As IReports, reportKey As String, requestParameters As CloneReportRequest) As Report" />
      <MemberSignature Language="F#" Value="static member CloneReport : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReport (operations, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; CloneReportAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; CloneReportAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneReportAsync : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportAsync (operations, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;CloneReportAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneReportInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report CloneReportInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report CloneReportInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CloneReportInGroup (operations As IReports, groupId As String, reportKey As String, requestParameters As CloneReportRequest) As Report" />
      <MemberSignature Language="F#" Value="static member CloneReportInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportInGroup (operations, groupId, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneReportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; CloneReportInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; CloneReportInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneReportInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.CloneReportInGroupAsync (operations, groupId, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;CloneReportInGroupAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReport">
      <MemberSignature Language="C#" Value="public static object DeleteReport (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteReport(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReport(Microsoft.PowerBI.Api.V2.IReports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteReport (operations As IReports, reportKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteReport : Microsoft.PowerBI.Api.V2.IReports * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReport (operations, reportKey)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteReportAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteReportAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteReportAsync : Microsoft.PowerBI.Api.V2.IReports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportAsync (operations, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;DeleteReportAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReportInGroup">
      <MemberSignature Language="C#" Value="public static object DeleteReportInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object DeleteReportInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteReportInGroup (operations As IReports, groupId As String, reportKey As String) As Object" />
      <MemberSignature Language="F#" Value="static member DeleteReportInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportInGroup (operations, groupId, reportKey)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; DeleteReportInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; DeleteReportInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteReportInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.DeleteReportInGroupAsync (operations, groupId, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;DeleteReportInGroupAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReport">
      <MemberSignature Language="C#" Value="public static System.IO.Stream ExportReport (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream ExportReport(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReport(Microsoft.PowerBI.Api.V2.IReports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportReport (operations As IReports, reportKey As String) As Stream" />
      <MemberSignature Language="F#" Value="static member ExportReport : Microsoft.PowerBI.Api.V2.IReports * string -&gt; System.IO.Stream" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReport (operations, reportKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; ExportReportAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; ExportReportAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportReportAsync : Microsoft.PowerBI.Api.V2.IReports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportAsync (operations, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;ExportReportAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReportInGroup">
      <MemberSignature Language="C#" Value="public static System.IO.Stream ExportReportInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream ExportReportInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportReportInGroup (operations As IReports, groupId As String, reportKey As String) As Stream" />
      <MemberSignature Language="F#" Value="static member ExportReportInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string -&gt; System.IO.Stream" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportInGroup (operations, groupId, reportKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; ExportReportInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; ExportReportInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportReportInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.ExportReportInGroupAsync (operations, groupId, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;ExportReportInGroupAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateToken">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateToken (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateToken(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateToken(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateToken (operations As IReports, reportKey As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateToken : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateToken (operations, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.EmbedToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenAsync : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenAsync (operations, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GenerateTokenAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenForCreate (this Microsoft.PowerBI.Api.V2.IReports operations, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenForCreate(class Microsoft.PowerBI.Api.V2.IReports operations, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreate(Microsoft.PowerBI.Api.V2.IReports,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateTokenForCreate (operations As IReports, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateTokenForCreate : Microsoft.PowerBI.Api.V2.IReports * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreate (operations, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.EmbedToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenForCreateAsync (this Microsoft.PowerBI.Api.V2.IReports operations, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenForCreateAsync(class Microsoft.PowerBI.Api.V2.IReports operations, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateAsync(Microsoft.PowerBI.Api.V2.IReports,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenForCreateAsync : Microsoft.PowerBI.Api.V2.IReports * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateAsync (operations, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GenerateTokenForCreateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreateInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenForCreateInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenForCreateInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateTokenForCreateInGroup (operations As IReports, groupId As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateTokenForCreateInGroup : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateInGroup (operations, groupId, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.EmbedToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreateInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenForCreateInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenForCreateInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenForCreateInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenForCreateInGroupAsync (operations, groupId, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GenerateTokenForCreateInGroupAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateTokenInGroup (operations As IReports, groupId As String, reportKey As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenInGroup (operations, groupId, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.EmbedToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GenerateTokenInGroupAsync (operations, groupId, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GenerateTokenInGroupAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReport">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report GetReport (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report GetReport(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReport(Microsoft.PowerBI.Api.V2.IReports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetReport (operations As IReports, reportKey As String) As Report" />
      <MemberSignature Language="F#" Value="static member GetReport : Microsoft.PowerBI.Api.V2.IReports * string -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReport (operations, reportKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; GetReportAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; GetReportAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReportAsync : Microsoft.PowerBI.Api.V2.IReports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportAsync (operations, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GetReportAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report GetReportInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report GetReportInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetReportInGroup (operations As IReports, groupId As String, reportKey As String) As Report" />
      <MemberSignature Language="F#" Value="static member GetReportInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportInGroup (operations, groupId, reportKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; GetReportInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; GetReportInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReportInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportInGroupAsync (operations, groupId, reportKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GetReportInGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReports">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport GetReports (this Microsoft.PowerBI.Api.V2.IReports operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport GetReports(class Microsoft.PowerBI.Api.V2.IReports operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReports(Microsoft.PowerBI.Api.V2.IReports)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetReports (operations As IReports) As ODataResponseListReport" />
      <MemberSignature Language="F#" Value="static member GetReports : Microsoft.PowerBI.Api.V2.IReports -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReports operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt; GetReportsAsync (this Microsoft.PowerBI.Api.V2.IReports operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt; GetReportsAsync(class Microsoft.PowerBI.Api.V2.IReports operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsAsync(Microsoft.PowerBI.Api.V2.IReports,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReportsAsync : Microsoft.PowerBI.Api.V2.IReports * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GetReportsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
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
    <Member MemberName="GetReportsInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport GetReportsInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport GetReportsInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetReportsInGroup (operations As IReports, groupId As String) As ODataResponseListReport" />
      <MemberSignature Language="F#" Value="static member GetReportsInGroup : Microsoft.PowerBI.Api.V2.IReports * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsInGroup (operations, groupId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
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
    <Member MemberName="GetReportsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt; GetReportsInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt; GetReportsInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetReportsInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.GetReportsInGroupAsync (operations, groupId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;GetReportsInGroupAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
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
    <Member MemberName="RebindReport">
      <MemberSignature Language="C#" Value="public static object RebindReport (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object RebindReport(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReport(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RebindReport (operations As IReports, reportKey As String, requestParameters As RebindReportRequest) As Object" />
      <MemberSignature Language="F#" Value="static member RebindReport : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReport (operations, reportKey, requestParameters)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebindReportAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; RebindReportAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; RebindReportAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebindReportAsync : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportAsync (operations, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;RebindReportAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebindReportInGroup">
      <MemberSignature Language="C#" Value="public static object RebindReportInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object RebindReportInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RebindReportInGroup (operations As IReports, groupId As String, reportKey As String, requestParameters As RebindReportRequest) As Object" />
      <MemberSignature Language="F#" Value="static member RebindReportInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest -&gt; obj" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportInGroup (operations, groupId, reportKey, requestParameters)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebindReportInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; RebindReportInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; RebindReportInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebindReportInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.RebindReportInGroupAsync (operations, groupId, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;RebindReportInGroupAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContent">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report UpdateReportContent (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report UpdateReportContent(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContent(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateReportContent (operations As IReports, reportKey As String, requestParameters As UpdateReportContentRequest) As Report" />
      <MemberSignature Language="F#" Value="static member UpdateReportContent : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContent (operations, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; UpdateReportContentAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; UpdateReportContentAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateReportContentAsync : Microsoft.PowerBI.Api.V2.IReports * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentAsync (operations, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;UpdateReportContentAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContentInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Report UpdateReportContentInGroup (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Report UpdateReportContentInGroup(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentInGroup(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateReportContentInGroup (operations As IReports, groupId As String, reportKey As String, requestParameters As UpdateReportContentRequest) As Report" />
      <MemberSignature Language="F#" Value="static member UpdateReportContentInGroup : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Report" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentInGroup (operations, groupId, reportKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Report</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContentInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt; UpdateReportContentInGroupAsync (this Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt; UpdateReportContentInGroupAsync(class Microsoft.PowerBI.Api.V2.IReports operations, string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentInGroupAsync(Microsoft.PowerBI.Api.V2.IReports,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateReportContentInGroupAsync : Microsoft.PowerBI.Api.V2.IReports * string * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;" Usage="Microsoft.PowerBI.Api.V2.ReportsExtensions.UpdateReportContentInGroupAsync (operations, groupId, reportKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.ReportsExtensions/&lt;UpdateReportContentInGroupAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IReports" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>