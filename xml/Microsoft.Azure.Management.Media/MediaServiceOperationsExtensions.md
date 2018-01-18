<Type Name="MediaServiceOperationsExtensions" FullName="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MediaServiceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MediaServiceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MediaServiceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MediaServiceOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
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
    <Member MemberName="CheckNameAvailabilty">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput CheckNameAvailabilty (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput checkNameAvailabilityInput);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput CheckNameAvailabilty(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, class Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput checkNameAvailabilityInput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CheckNameAvailabilty(Microsoft.Azure.Management.Media.IMediaServiceOperations,Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilty : Microsoft.Azure.Management.Media.IMediaServiceOperations * Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput -&gt; Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CheckNameAvailabilty (operations, checkNameAvailabilityInput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="checkNameAvailabilityInput" Type="Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="checkNameAvailabilityInput">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabiltyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabiltyAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput checkNameAvailabilityInput, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabiltyAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, class Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput checkNameAvailabilityInput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CheckNameAvailabiltyAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabiltyAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CheckNameAvailabiltyAsync (operations, checkNameAvailabilityInput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;CheckNameAvailabiltyAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="checkNameAvailabilityInput" Type="Microsoft.Azure.Management.Media.Models.CheckNameAvailabilityInput" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="checkNameAvailabilityInput">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.MediaService Create (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.MediaService mediaService);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.MediaService Create(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.MediaService mediaService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Create(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.MediaService)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.MediaService -&gt; Microsoft.Azure.Management.Media.Models.MediaService" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Create (operations, resourceGroupName, mediaServiceName, mediaService)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.MediaService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="mediaService" Type="Microsoft.Azure.Management.Media.Models.MediaService" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="mediaService">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt; CreateAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.MediaService mediaService, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt; CreateAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.MediaService mediaService, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.MediaService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.MediaService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.CreateAsync (operations, resourceGroupName, mediaServiceName, mediaService, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;CreateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="mediaService" Type="Microsoft.Azure.Management.Media.Models.MediaService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="mediaService">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Delete(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IMediaServiceOperations, resourceGroupName As String, mediaServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Delete (operations, resourceGroupName, mediaServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.DeleteAsync (operations, resourceGroupName, mediaServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.MediaService Get (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.MediaService Get(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Get(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IMediaServiceOperations, resourceGroupName As String, mediaServiceName As String) As MediaService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string -&gt; Microsoft.Azure.Management.Media.Models.MediaService" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Get (operations, resourceGroupName, mediaServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.MediaService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt; GetAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt; GetAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.GetAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.GetAsync (operations, resourceGroupName, mediaServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IMediaServiceOperations, resourceGroupName As String) As IEnumerable(Of MediaService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Media.IMediaServiceOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
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
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.ServiceKeys ListKeys (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.ServiceKeys ListKeys(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListKeys(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IMediaServiceOperations, resourceGroupName As String, mediaServiceName As String) As ServiceKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string -&gt; Microsoft.Azure.Management.Media.Models.ServiceKeys" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListKeys (operations, resourceGroupName, mediaServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.ServiceKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.ServiceKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.ServiceKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.ServiceKeys&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.ListKeysAsync (operations, resourceGroupName, mediaServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;ListKeysAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.ServiceKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput RegenerateKey (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.RegenerateKeyInput regenerateKeyInput);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput RegenerateKey(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.RegenerateKeyInput regenerateKeyInput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.RegenerateKeyInput)" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.RegenerateKeyInput -&gt; Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.RegenerateKey (operations, resourceGroupName, mediaServiceName, regenerateKeyInput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="regenerateKeyInput" Type="Microsoft.Azure.Management.Media.Models.RegenerateKeyInput" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="regenerateKeyInput">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.RegenerateKeyInput regenerateKeyInput, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.RegenerateKeyInput regenerateKeyInput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.RegenerateKeyInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.RegenerateKeyInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, mediaServiceName, regenerateKeyInput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.RegenerateKeyOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="regenerateKeyInput" Type="Microsoft.Azure.Management.Media.Models.RegenerateKeyInput" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="regenerateKeyInput">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncStorageKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.MediaService SyncStorageKeys (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput syncStorageKeysInput);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.MediaService SyncStorageKeys(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput syncStorageKeysInput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.SyncStorageKeys(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput)" />
      <MemberSignature Language="F#" Value="static member SyncStorageKeys : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput -&gt; Microsoft.Azure.Management.Media.Models.MediaService" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.SyncStorageKeys (operations, resourceGroupName, mediaServiceName, syncStorageKeysInput)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.MediaService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="syncStorageKeysInput" Type="Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="syncStorageKeysInput">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncStorageKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt; SyncStorageKeysAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput syncStorageKeysInput, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt; SyncStorageKeysAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput syncStorageKeysInput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.SyncStorageKeysAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SyncStorageKeysAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.SyncStorageKeysAsync (operations, resourceGroupName, mediaServiceName, syncStorageKeysInput, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;SyncStorageKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="syncStorageKeysInput" Type="Microsoft.Azure.Management.Media.Models.SyncStorageKeysInput" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="syncStorageKeysInput">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Media.Models.MediaService Update (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.MediaService mediaService);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Media.Models.MediaService Update(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.MediaService mediaService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Update(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.MediaService)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.MediaService -&gt; Microsoft.Azure.Management.Media.Models.MediaService" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.Update (operations, resourceGroupName, mediaServiceName, mediaService)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Media.Models.MediaService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="mediaService" Type="Microsoft.Azure.Management.Media.Models.MediaService" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="mediaService">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt; UpdateAsync (this Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, Microsoft.Azure.Management.Media.Models.MediaService mediaService, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Media.Models.MediaService&gt; UpdateAsync(class Microsoft.Azure.Management.Media.IMediaServiceOperations operations, string resourceGroupName, string mediaServiceName, class Microsoft.Azure.Management.Media.Models.MediaService mediaService, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Media.IMediaServiceOperations,System.String,System.String,Microsoft.Azure.Management.Media.Models.MediaService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Media.IMediaServiceOperations * string * string * Microsoft.Azure.Management.Media.Models.MediaService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;" Usage="Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions.UpdateAsync (operations, resourceGroupName, mediaServiceName, mediaService, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Media</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Media.MediaServiceOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Media.Models.MediaService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Media.IMediaServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="mediaServiceName" Type="System.String" />
        <Parameter Name="mediaService" Type="Microsoft.Azure.Management.Media.Models.MediaService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="mediaServiceName">To be added.</param>
        <param name="mediaService">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>