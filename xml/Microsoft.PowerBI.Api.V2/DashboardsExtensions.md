<Type Name="DashboardsExtensions" FullName="Microsoft.PowerBI.Api.V2.DashboardsExtensions">
  <TypeSignature Language="C#" Value="public static class DashboardsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DashboardsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.DashboardsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DashboardsExtensions" />
  <TypeSignature Language="F#" Value="type DashboardsExtensions = class" />
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
    <Member MemberName="AddDashboard">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dashboard AddDashboard (this Microsoft.PowerBI.Api.V2.IDashboards operations, Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dashboard AddDashboard(class Microsoft.PowerBI.Api.V2.IDashboards operations, class Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboard(Microsoft.PowerBI.Api.V2.IDashboards,Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddDashboard (operations As IDashboards, requestParameters As AddDashboardRequest) As Dashboard" />
      <MemberSignature Language="F#" Value="static member AddDashboard : Microsoft.PowerBI.Api.V2.IDashboards * Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Dashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboard (operations, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDashboardAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; AddDashboardAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; AddDashboardAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, class Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardAsync(Microsoft.PowerBI.Api.V2.IDashboards,Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddDashboardAsync : Microsoft.PowerBI.Api.V2.IDashboards * Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardAsync (operations, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;AddDashboardAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest" />
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
    <Member MemberName="AddDashboardInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dashboard AddDashboardInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dashboard AddDashboardInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddDashboardInGroup (operations As IDashboards, groupId As String, requestParameters As AddDashboardRequest) As Dashboard" />
      <MemberSignature Language="F#" Value="static member AddDashboardInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Dashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardInGroup (operations, groupId, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest" />
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
    <Member MemberName="AddDashboardInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; AddDashboardInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; AddDashboardInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, class Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddDashboardInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.AddDashboardInGroupAsync (operations, groupId, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;AddDashboardInGroupAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.AddDashboardRequest" />
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
    <Member MemberName="CloneTile">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Tile CloneTile (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Tile CloneTile(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, class Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTile(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneTileRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CloneTile (operations As IDashboards, dashboardKey As String, tileKey As String, requestParameters As CloneTileRequest) As Tile" />
      <MemberSignature Language="F#" Value="static member CloneTile : Microsoft.PowerBI.Api.V2.IDashboards * string * string * Microsoft.PowerBI.Api.V2.Models.CloneTileRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Tile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTile (operations, dashboardKey, tileKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Tile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneTileRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneTileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt; CloneTileAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Tile&gt; CloneTileAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, class Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneTileRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneTileAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * Microsoft.PowerBI.Api.V2.Models.CloneTileRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileAsync (operations, dashboardKey, tileKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;CloneTileAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneTileRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneTileInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Tile CloneTileInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Tile CloneTileInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, class Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneTileRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CloneTileInGroup (operations As IDashboards, groupId As String, dashboardKey As String, tileKey As String, requestParameters As CloneTileRequest) As Tile" />
      <MemberSignature Language="F#" Value="static member CloneTileInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * string * string * Microsoft.PowerBI.Api.V2.Models.CloneTileRequest -&gt; Microsoft.PowerBI.Api.V2.Models.Tile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileInGroup (operations, groupId, dashboardKey, tileKey, requestParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Tile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneTileRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneTileInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt; CloneTileInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Tile&gt; CloneTileInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, class Microsoft.PowerBI.Api.V2.Models.CloneTileRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneTileRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneTileInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * string * Microsoft.PowerBI.Api.V2.Models.CloneTileRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.CloneTileInGroupAsync (operations, groupId, dashboardKey, tileKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;CloneTileInGroupAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneTileRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateToken">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateToken (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateToken(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateToken(Microsoft.PowerBI.Api.V2.IDashboards,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateToken (operations As IDashboards, dashboardKey As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateToken : Microsoft.PowerBI.Api.V2.IDashboards * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateToken (operations, dashboardKey, requestParameters)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenAsync (operations, dashboardKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GenerateTokenAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.EmbedToken GenerateTokenInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateTokenInGroup (operations As IDashboards, groupId As String, dashboardKey As String, requestParameters As GenerateTokenRequest) As EmbedToken" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest -&gt; Microsoft.PowerBI.Api.V2.Models.EmbedToken" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenInGroup (operations, groupId, dashboardKey, requestParameters)" />
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
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt; GenerateTokenInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateTokenInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GenerateTokenInGroupAsync (operations, groupId, dashboardKey, requestParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GenerateTokenInGroupAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboard">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dashboard GetDashboard (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dashboard GetDashboard(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboard(Microsoft.PowerBI.Api.V2.IDashboards,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDashboard (operations As IDashboards, dashboardKey As String) As Dashboard" />
      <MemberSignature Language="F#" Value="static member GetDashboard : Microsoft.PowerBI.Api.V2.IDashboards * string -&gt; Microsoft.PowerBI.Api.V2.Models.Dashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboard (operations, dashboardKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboardAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; GetDashboardAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; GetDashboardAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDashboardAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardAsync (operations, dashboardKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetDashboardAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboardInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Dashboard GetDashboardInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Dashboard GetDashboardInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDashboardInGroup (operations As IDashboards, groupId As String, dashboardKey As String) As Dashboard" />
      <MemberSignature Language="F#" Value="static member GetDashboardInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Dashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardInGroup (operations, groupId, dashboardKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Dashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboardInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; GetDashboardInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dashboard&gt; GetDashboardInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDashboardInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardInGroupAsync (operations, groupId, dashboardKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetDashboardInGroupAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Dashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboards">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard GetDashboards (this Microsoft.PowerBI.Api.V2.IDashboards operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard GetDashboards(class Microsoft.PowerBI.Api.V2.IDashboards operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboards(Microsoft.PowerBI.Api.V2.IDashboards)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDashboards (operations As IDashboards) As ODataResponseListDashboard" />
      <MemberSignature Language="F#" Value="static member GetDashboards : Microsoft.PowerBI.Api.V2.IDashboards -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboards operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDashboardsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt; GetDashboardsAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt; GetDashboardsAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDashboardsAsync : Microsoft.PowerBI.Api.V2.IDashboards * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetDashboardsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
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
    <Member MemberName="GetDashboardsInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard GetDashboardsInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard GetDashboardsInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDashboardsInGroup (operations As IDashboards, groupId As String) As ODataResponseListDashboard" />
      <MemberSignature Language="F#" Value="static member GetDashboardsInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsInGroup (operations, groupId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
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
    <Member MemberName="GetDashboardsInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt; GetDashboardsInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt; GetDashboardsInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDashboardsInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetDashboardsInGroupAsync (operations, groupId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetDashboardsInGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDashboard&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
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
    <Member MemberName="GetTile">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Tile GetTile (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Tile GetTile(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTile(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTile (operations As IDashboards, dashboardKey As String, tileKey As String) As Tile" />
      <MemberSignature Language="F#" Value="static member GetTile : Microsoft.PowerBI.Api.V2.IDashboards * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Tile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTile (operations, dashboardKey, tileKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Tile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt; GetTileAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Tile&gt; GetTileAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, string tileKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTileAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileAsync (operations, dashboardKey, tileKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetTileAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTileInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.Tile GetTileInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.Tile GetTileInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTileInGroup (operations As IDashboards, groupId As String, dashboardKey As String, tileKey As String) As Tile" />
      <MemberSignature Language="F#" Value="static member GetTileInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.Tile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileInGroup (operations, groupId, dashboardKey, tileKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.Tile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTileInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt; GetTileInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.Tile&gt; GetTileInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, string tileKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTileInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTileInGroupAsync (operations, groupId, dashboardKey, tileKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetTileInGroupAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.Tile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="tileKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="tileKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTiles">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile GetTiles (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile GetTiles(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTiles(Microsoft.PowerBI.Api.V2.IDashboards,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTiles (operations As IDashboards, dashboardKey As String) As ODataResponseListTile" />
      <MemberSignature Language="F#" Value="static member GetTiles : Microsoft.PowerBI.Api.V2.IDashboards * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTiles (operations, dashboardKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTilesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt; GetTilesAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt; GetTilesAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string dashboardKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTilesAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesAsync (operations, dashboardKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetTilesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTilesInGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile GetTilesInGroup (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile GetTilesInGroup(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesInGroup(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTilesInGroup (operations As IDashboards, groupId As String, dashboardKey As String) As ODataResponseListTile" />
      <MemberSignature Language="F#" Value="static member GetTilesInGroup : Microsoft.PowerBI.Api.V2.IDashboards * string * string -&gt; Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesInGroup (operations, groupId, dashboardKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTilesInGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt; GetTilesInGroupAsync (this Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt; GetTilesInGroupAsync(class Microsoft.PowerBI.Api.V2.IDashboards operations, string groupId, string dashboardKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesInGroupAsync(Microsoft.PowerBI.Api.V2.IDashboards,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTilesInGroupAsync : Microsoft.PowerBI.Api.V2.IDashboards * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt;" Usage="Microsoft.PowerBI.Api.V2.DashboardsExtensions.GetTilesInGroupAsync (operations, groupId, dashboardKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.DashboardsExtensions/&lt;GetTilesInGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.PowerBI.Api.V2.IDashboards" RefType="this" />
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dashboardKey" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="groupId">To be added.</param>
        <param name="dashboardKey">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>