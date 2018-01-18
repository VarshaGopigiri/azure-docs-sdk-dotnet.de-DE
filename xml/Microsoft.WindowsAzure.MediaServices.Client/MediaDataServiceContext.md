<Type Name="MediaDataServiceContext" FullName="Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext">
  <TypeSignature Language="C#" Value="public class MediaDataServiceContext : Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext, Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MediaDataServiceContext extends System.Object implements class Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext, class Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public Class MediaDataServiceContext&#xA;Implements IMediaDataServiceContext, IRetryPolicyAdapter" />
  <TypeSignature Language="F#" Value="type MediaDataServiceContext = class&#xA;    interface IMediaDataServiceContext&#xA;    interface IRetryPolicyAdapter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
    <AssemblyVersion>4.0.0.4</AssemblyVersion>
    <AssemblyVersion>4.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MediaDataServiceContext (System.Data.Services.Client.DataServiceContext dataContext, Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.MediaRetryPolicy queryRetryPolicy, Microsoft.WindowsAzure.MediaServices.Client.RequestAdapters.ClientRequestIdAdapter clientRequestAdapter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Data.Services.Client.DataServiceContext dataContext, class Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.MediaRetryPolicy queryRetryPolicy, class Microsoft.WindowsAzure.MediaServices.Client.RequestAdapters.ClientRequestIdAdapter clientRequestAdapter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.#ctor(System.Data.Services.Client.DataServiceContext,Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.MediaRetryPolicy,Microsoft.WindowsAzure.MediaServices.Client.RequestAdapters.ClientRequestIdAdapter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataContext As DataServiceContext, queryRetryPolicy As MediaRetryPolicy, clientRequestAdapter As ClientRequestIdAdapter)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext : System.Data.Services.Client.DataServiceContext * Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.MediaRetryPolicy * Microsoft.WindowsAzure.MediaServices.Client.RequestAdapters.ClientRequestIdAdapter -&gt; Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext" Usage="new Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext (dataContext, queryRetryPolicy, clientRequestAdapter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataContext" Type="System.Data.Services.Client.DataServiceContext" />
        <Parameter Name="queryRetryPolicy" Type="Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.MediaRetryPolicy" />
        <Parameter Name="clientRequestAdapter" Type="Microsoft.WindowsAzure.MediaServices.Client.RequestAdapters.ClientRequestIdAdapter" />
      </Parameters>
      <Docs>
        <param name="dataContext">To be added.</param>
        <param name="queryRetryPolicy">To be added.</param>
        <param name="clientRequestAdapter">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdaptExecuteAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.Tasks.Task&gt; AdaptExecuteAsync (Func&lt;System.Threading.Tasks.Task&gt; taskFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Func`1&lt;class System.Threading.Tasks.Task&gt; AdaptExecuteAsync(class System.Func`1&lt;class System.Threading.Tasks.Task&gt; taskFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AdaptExecuteAsync(System.Func{System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Function AdaptExecuteAsync (taskFunc As Func(Of Task)) As Func(Of Task)" />
      <MemberSignature Language="F#" Value="abstract member AdaptExecuteAsync : Func&lt;System.Threading.Tasks.Task&gt; -&gt; Func&lt;System.Threading.Tasks.Task&gt;&#xA;override this.AdaptExecuteAsync : Func&lt;System.Threading.Tasks.Task&gt; -&gt; Func&lt;System.Threading.Tasks.Task&gt;" Usage="mediaDataServiceContext.AdaptExecuteAsync taskFunc" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAsync(System.Func{System.Threading.Tasks.Task})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskFunc" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="taskFunc">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddLink">
      <MemberSignature Language="C#" Value="public void AddLink (object source, string sourceProperty, object target);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddLink(object source, string sourceProperty, object target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AddLink(System.Object,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddLink (source As Object, sourceProperty As String, target As Object)" />
      <MemberSignature Language="F#" Value="abstract member AddLink : obj * string * obj -&gt; unit&#xA;override this.AddLink : obj * string * obj -&gt; unit" Usage="mediaDataServiceContext.AddLink (source, sourceProperty, target)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.AddLink(System.Object,System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="sourceProperty" Type="System.String" />
        <Parameter Name="target" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="sourceProperty">To be added.</param>
        <param name="target">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddObject">
      <MemberSignature Language="C#" Value="public void AddObject (string entitySetName, object entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddObject(string entitySetName, object entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AddObject(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddObject (entitySetName As String, entity As Object)" />
      <MemberSignature Language="F#" Value="abstract member AddObject : string * obj -&gt; unit&#xA;override this.AddObject : string * obj -&gt; unit" Usage="mediaDataServiceContext.AddObject (entitySetName, entity)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.AddObject(System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entitySetName" Type="System.String" />
        <Parameter Name="entity" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entitySetName">To be added.</param>
        <param name="entity">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRelatedObject">
      <MemberSignature Language="C#" Value="public void AddRelatedObject (object source, string sourceProperty, object target);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddRelatedObject(object source, string sourceProperty, object target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AddRelatedObject(System.Object,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRelatedObject (source As Object, sourceProperty As String, target As Object)" />
      <MemberSignature Language="F#" Value="abstract member AddRelatedObject : obj * string * obj -&gt; unit&#xA;override this.AddRelatedObject : obj * string * obj -&gt; unit" Usage="mediaDataServiceContext.AddRelatedObject (source, sourceProperty, target)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.AddRelatedObject(System.Object,System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="sourceProperty" Type="System.String" />
        <Parameter Name="target" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="sourceProperty">To be added.</param>
        <param name="target">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachTo">
      <MemberSignature Language="C#" Value="public void AttachTo (string entitySetName, object entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AttachTo(string entitySetName, object entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AttachTo(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachTo (entitySetName As String, entity As Object)" />
      <MemberSignature Language="F#" Value="abstract member AttachTo : string * obj -&gt; unit&#xA;override this.AttachTo : string * obj -&gt; unit" Usage="mediaDataServiceContext.AttachTo (entitySetName, entity)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.AttachTo(System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entitySetName" Type="System.String" />
        <Parameter Name="entity" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entitySetName">To be added.</param>
        <param name="entity">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachTo">
      <MemberSignature Language="C#" Value="public void AttachTo (string entitySetName, object entity, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AttachTo(string entitySetName, object entity, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.AttachTo(System.String,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachTo (entitySetName As String, entity As Object, etag As String)" />
      <MemberSignature Language="F#" Value="abstract member AttachTo : string * obj * string -&gt; unit&#xA;override this.AttachTo : string * obj * string -&gt; unit" Usage="mediaDataServiceContext.AttachTo (entitySetName, entity, etag)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.AttachTo(System.String,System.Object,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entitySetName" Type="System.String" />
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entitySetName">To be added.</param>
        <param name="entity">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery&lt;TIinterface,TData&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;TIinterface&gt; CreateQuery&lt;TIinterface,TData&gt; (string entitySetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!TIinterface&gt; CreateQuery&lt;TIinterface, TData&gt;(string entitySetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.CreateQuery``2(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQuery(Of TIinterface, TData) (entitySetName As String) As IQueryable(Of TIinterface)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string -&gt; System.Linq.IQueryable&lt;'Iinterface&gt;&#xA;override this.CreateQuery : string -&gt; System.Linq.IQueryable&lt;'Iinterface&gt;" Usage="mediaDataServiceContext.CreateQuery entitySetName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.CreateQuery``2(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TIinterface&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TIinterface" />
        <TypeParameter Name="TData" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="entitySetName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TIinterface">To be added.</typeparam>
        <typeparam name="TData">To be added.</typeparam>
        <param name="entitySetName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLink">
      <MemberSignature Language="C#" Value="public void DeleteLink (object source, string sourceProperty, object target);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteLink(object source, string sourceProperty, object target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.DeleteLink(System.Object,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteLink (source As Object, sourceProperty As String, target As Object)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLink : obj * string * obj -&gt; unit&#xA;override this.DeleteLink : obj * string * obj -&gt; unit" Usage="mediaDataServiceContext.DeleteLink (source, sourceProperty, target)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.DeleteLink(System.Object,System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="sourceProperty" Type="System.String" />
        <Parameter Name="target" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="sourceProperty">To be added.</param>
        <param name="target">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteObject">
      <MemberSignature Language="C#" Value="public void DeleteObject (object entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteObject(object entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.DeleteObject(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteObject (entity As Object)" />
      <MemberSignature Language="F#" Value="abstract member DeleteObject : obj -&gt; unit&#xA;override this.DeleteObject : obj -&gt; unit" Usage="mediaDataServiceContext.DeleteObject entity" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.DeleteObject(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.OperationResponse Execute (Uri requestUri, string httpMethod, params System.Data.Services.Client.OperationParameter[] operationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Data.Services.Client.OperationResponse Execute(class System.Uri requestUri, string httpMethod, class System.Data.Services.Client.OperationParameter[] operationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.Execute(System.Uri,System.String,System.Data.Services.Client.OperationParameter[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Execute (requestUri As Uri, httpMethod As String, ParamArray operationParameters As OperationParameter()) As OperationResponse" />
      <MemberSignature Language="F#" Value="abstract member Execute : Uri * string * System.Data.Services.Client.OperationParameter[] -&gt; System.Data.Services.Client.OperationResponse&#xA;override this.Execute : Uri * string * System.Data.Services.Client.OperationParameter[] -&gt; System.Data.Services.Client.OperationResponse" Usage="mediaDataServiceContext.Execute (requestUri, httpMethod, operationParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.Execute(System.Uri,System.String,System.Data.Services.Client.OperationParameter[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="httpMethod" Type="System.String" />
        <Parameter Name="operationParameters" Type="System.Data.Services.Client.OperationParameter[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="requestUri">To be added.</param>
        <param name="httpMethod">To be added.</param>
        <param name="operationParameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;TElement&gt; Execute&lt;TElement&gt; (Uri requestUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TElement&gt; Execute&lt;TElement&gt;(class System.Uri requestUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.Execute``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function Execute(Of TElement) (requestUri As Uri) As IEnumerable(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Uri -&gt; seq&lt;'Element&gt;&#xA;override this.Execute : Uri -&gt; seq&lt;'Element&gt;" Usage="mediaDataServiceContext.Execute requestUri" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.Execute``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">To be added.</typeparam>
        <param name="requestUri">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.OperationResponse&gt; ExecuteAsync (Uri requestUri, object state, string httpMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.OperationResponse&gt; ExecuteAsync(class System.Uri requestUri, object state, string httpMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.ExecuteAsync(System.Uri,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync (requestUri As Uri, state As Object, httpMethod As String) As Task(Of OperationResponse)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Uri * obj * string -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.OperationResponse&gt;&#xA;override this.ExecuteAsync : Uri * obj * string -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.OperationResponse&gt;" Usage="mediaDataServiceContext.ExecuteAsync (requestUri, state, httpMethod)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.ExecuteAsync(System.Uri,System.Object,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="httpMethod" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="requestUri">To be added.</param>
        <param name="state">To be added.</param>
        <param name="httpMethod">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ExecuteAsync&lt;T&gt; (System.Data.Services.Client.DataServiceQueryContinuation&lt;T&gt; continuation, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!T&gt;&gt; ExecuteAsync&lt;T&gt;(class System.Data.Services.Client.DataServiceQueryContinuation`1&lt;!!T&gt; continuation, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.ExecuteAsync``1(System.Data.Services.Client.DataServiceQueryContinuation{``0},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync(Of T) (continuation As DataServiceQueryContinuation(Of T), state As Object) As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : System.Data.Services.Client.DataServiceQueryContinuation&lt;'T&gt; * obj -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;&#xA;override this.ExecuteAsync : System.Data.Services.Client.DataServiceQueryContinuation&lt;'T&gt; * obj -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="mediaDataServiceContext.ExecuteAsync (continuation, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.ExecuteAsync``1(System.Data.Services.Client.DataServiceQueryContinuation{``0},System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="continuation" Type="System.Data.Services.Client.DataServiceQueryContinuation&lt;T&gt;" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="continuation">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ExecuteAsync&lt;T&gt; (Uri requestUri, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!T&gt;&gt; ExecuteAsync&lt;T&gt;(class System.Uri requestUri, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.ExecuteAsync``1(System.Uri,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync(Of T) (requestUri As Uri, state As Object) As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Uri * obj -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;&#xA;override this.ExecuteAsync : Uri * obj -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="mediaDataServiceContext.ExecuteAsync (requestUri, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.ExecuteAsync``1(System.Uri,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="requestUri">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ExecuteAsync&lt;T&gt; (Uri requestUri, string httpMethod, bool singleResult, params System.Data.Services.Client.OperationParameter[] parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!T&gt;&gt; ExecuteAsync&lt;T&gt;(class System.Uri requestUri, string httpMethod, bool singleResult, class System.Data.Services.Client.OperationParameter[] parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.ExecuteAsync``1(System.Uri,System.String,System.Boolean,System.Data.Services.Client.OperationParameter[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync(Of T) (requestUri As Uri, httpMethod As String, singleResult As Boolean, ParamArray parameters As OperationParameter()) As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Uri * string * bool * System.Data.Services.Client.OperationParameter[] -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;&#xA;override this.ExecuteAsync : Uri * string * bool * System.Data.Services.Client.OperationParameter[] -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="mediaDataServiceContext.ExecuteAsync (requestUri, httpMethod, singleResult, parameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.ExecuteAsync``1(System.Uri,System.String,System.Boolean,System.Data.Services.Client.OperationParameter[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="requestUri" Type="System.Uri" />
        <Parameter Name="httpMethod" Type="System.String" />
        <Parameter Name="singleResult" Type="System.Boolean" />
        <Parameter Name="parameters" Type="System.Data.Services.Client.OperationParameter[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="requestUri">To be added.</param>
        <param name="httpMethod">To be added.</param>
        <param name="singleResult">To be added.</param>
        <param name="parameters">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; ExecuteBatchAsync (object state, params System.Data.Services.Client.DataServiceRequest[] queries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; ExecuteBatchAsync(object state, class System.Data.Services.Client.DataServiceRequest[] queries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.ExecuteBatchAsync(System.Object,System.Data.Services.Client.DataServiceRequest[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteBatchAsync (state As Object, ParamArray queries As DataServiceRequest()) As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : obj * System.Data.Services.Client.DataServiceRequest[] -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;&#xA;override this.ExecuteBatchAsync : obj * System.Data.Services.Client.DataServiceRequest[] -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="mediaDataServiceContext.ExecuteBatchAsync (state, queries)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.ExecuteBatchAsync(System.Object,System.Data.Services.Client.DataServiceRequest[])</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="queries" Type="System.Data.Services.Client.DataServiceRequest[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="state">To be added.</param>
        <param name="queries">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReadStreamAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceStreamResponse&gt; GetReadStreamAsync (object entity, System.Data.Services.Client.DataServiceRequestArgs args, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceStreamResponse&gt; GetReadStreamAsync(object entity, class System.Data.Services.Client.DataServiceRequestArgs args, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.GetReadStreamAsync(System.Object,System.Data.Services.Client.DataServiceRequestArgs,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReadStreamAsync (entity As Object, args As DataServiceRequestArgs, state As Object) As Task(Of DataServiceStreamResponse)" />
      <MemberSignature Language="F#" Value="abstract member GetReadStreamAsync : obj * System.Data.Services.Client.DataServiceRequestArgs * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceStreamResponse&gt;&#xA;override this.GetReadStreamAsync : obj * System.Data.Services.Client.DataServiceRequestArgs * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceStreamResponse&gt;" Usage="mediaDataServiceContext.GetReadStreamAsync (entity, args, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.GetReadStreamAsync(System.Object,System.Data.Services.Client.DataServiceRequestArgs,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceStreamResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="args" Type="System.Data.Services.Client.DataServiceRequestArgs" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <param name="args">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreResourceNotFoundException">
      <MemberSignature Language="C#" Value="public bool IgnoreResourceNotFoundException { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IgnoreResourceNotFoundException" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.IgnoreResourceNotFoundException" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreResourceNotFoundException As Boolean" />
      <MemberSignature Language="F#" Value="member this.IgnoreResourceNotFoundException : bool with get, set" Usage="Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.IgnoreResourceNotFoundException" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.IgnoreResourceNotFoundException</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadProperty">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.QueryOperationResponse LoadProperty (object entity, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Data.Services.Client.QueryOperationResponse LoadProperty(object entity, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.LoadProperty(System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadProperty (entity As Object, propertyName As String) As QueryOperationResponse" />
      <MemberSignature Language="F#" Value="abstract member LoadProperty : obj * string -&gt; System.Data.Services.Client.QueryOperationResponse&#xA;override this.LoadProperty : obj * string -&gt; System.Data.Services.Client.QueryOperationResponse" Usage="mediaDataServiceContext.LoadProperty (entity, propertyName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.LoadProperty(System.Object,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.QueryOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <param name="propertyName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync (object entity, string propertyName, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync(object entity, string propertyName, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadPropertyAsync (entity As Object, propertyName As String, state As Object) As Task(Of QueryOperationResponse)" />
      <MemberSignature Language="F#" Value="abstract member LoadPropertyAsync : obj * string * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;&#xA;override this.LoadPropertyAsync : obj * string * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;" Usage="mediaDataServiceContext.LoadPropertyAsync (entity, propertyName, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <param name="propertyName">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync (object entity, string propertyName, System.Data.Services.Client.DataServiceQueryContinuation continuation, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync(object entity, string propertyName, class System.Data.Services.Client.DataServiceQueryContinuation continuation, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Data.Services.Client.DataServiceQueryContinuation,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadPropertyAsync (entity As Object, propertyName As String, continuation As DataServiceQueryContinuation, state As Object) As Task(Of QueryOperationResponse)" />
      <MemberSignature Language="F#" Value="abstract member LoadPropertyAsync : obj * string * System.Data.Services.Client.DataServiceQueryContinuation * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;&#xA;override this.LoadPropertyAsync : obj * string * System.Data.Services.Client.DataServiceQueryContinuation * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;" Usage="mediaDataServiceContext.LoadPropertyAsync (entity, propertyName, continuation, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Data.Services.Client.DataServiceQueryContinuation,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="continuation" Type="System.Data.Services.Client.DataServiceQueryContinuation" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <param name="propertyName">To be added.</param>
        <param name="continuation">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync (object entity, string propertyName, Uri nextLinkUri, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.QueryOperationResponse&gt; LoadPropertyAsync(object entity, string propertyName, class System.Uri nextLinkUri, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Uri,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadPropertyAsync (entity As Object, propertyName As String, nextLinkUri As Uri, state As Object) As Task(Of QueryOperationResponse)" />
      <MemberSignature Language="F#" Value="abstract member LoadPropertyAsync : obj * string * Uri * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;&#xA;override this.LoadPropertyAsync : obj * string * Uri * obj -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;" Usage="mediaDataServiceContext.LoadPropertyAsync (entity, propertyName, nextLinkUri, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.LoadPropertyAsync(System.Object,System.String,System.Uri,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.QueryOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="nextLinkUri" Type="System.Uri" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <param name="propertyName">To be added.</param>
        <param name="nextLinkUri">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAction&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="Func&lt;TResult&gt; IRetryPolicyAdapter.AdaptExecuteAction&lt;TResult&gt; (Func&lt;TResult&gt; func);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Func`1&lt;!!TResult&gt; Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAction&lt;TResult&gt;(class System.Func`1&lt;!!TResult&gt; func) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.Microsoft#WindowsAzure#MediaServices#Client#TransientFaultHandling#IRetryPolicyAdapter#AdaptExecuteAction``1(System.Func{``0})" />
      <MemberSignature Language="VB.NET" Value="Function AdaptExecuteAction(Of TResult) (func As Func(Of TResult)) As Func(Of TResult) Implements IRetryPolicyAdapter.AdaptExecuteAction" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAction``1(System.Func{``0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="func" Type="System.Func&lt;TResult&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="func">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="Func&lt;System.Threading.Tasks.Task&lt;TResult&gt;&gt; IRetryPolicyAdapter.AdaptExecuteAsync&lt;TResult&gt; (Func&lt;System.Threading.Tasks.Task&lt;TResult&gt;&gt; taskFunc);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Func`1&lt;class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAsync&lt;TResult&gt;(class System.Func`1&lt;class System.Threading.Tasks.Task`1&lt;!!TResult&gt;&gt; taskFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.Microsoft#WindowsAzure#MediaServices#Client#TransientFaultHandling#IRetryPolicyAdapter#AdaptExecuteAsync``1(System.Func{System.Threading.Tasks.Task{``0}})" />
      <MemberSignature Language="VB.NET" Value="Function AdaptExecuteAsync(Of TResult) (taskFunc As Func(Of Task(Of TResult))) As Func(Of Task(Of TResult)) Implements IRetryPolicyAdapter.AdaptExecuteAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.TransientFaultHandling.IRetryPolicyAdapter.AdaptExecuteAsync``1(System.Func{System.Threading.Tasks.Task{``0}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.Tasks.Task&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="taskFunc" Type="System.Func&lt;System.Threading.Tasks.Task&lt;TResult&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="taskFunc">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChanges">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse SaveChanges ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse SaveChanges() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.SaveChanges" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChanges () As IMediaDataServiceResponse" />
      <MemberSignature Language="F#" Value="abstract member SaveChanges : unit -&gt; Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&#xA;override this.SaveChanges : unit -&gt; Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse" Usage="mediaDataServiceContext.SaveChanges " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.SaveChanges</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync (object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync(object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.SaveChangesAsync(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesAsync (state As Object) As Task(Of IMediaDataServiceResponse)" />
      <MemberSignature Language="F#" Value="abstract member SaveChangesAsync : obj -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;&#xA;override this.SaveChangesAsync : obj -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;" Usage="mediaDataServiceContext.SaveChangesAsync state" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.SaveChangesAsync(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync (System.Data.Services.Client.SaveChangesOptions options, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.SaveChangesAsync(System.Data.Services.Client.SaveChangesOptions,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesAsync (options As SaveChangesOptions, state As Object) As Task(Of IMediaDataServiceResponse)" />
      <MemberSignature Language="F#" Value="abstract member SaveChangesAsync : System.Data.Services.Client.SaveChangesOptions * obj -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;&#xA;override this.SaveChangesAsync : System.Data.Services.Client.SaveChangesOptions * obj -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;" Usage="mediaDataServiceContext.SaveChangesAsync (options, state)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.SaveChangesAsync(System.Data.Services.Client.SaveChangesOptions,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync (System.Data.Services.Client.SaveChangesOptions options, object state, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt; SaveChangesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, object state, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.SaveChangesAsync(System.Data.Services.Client.SaveChangesOptions,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesAsync (options As SaveChangesOptions, state As Object, token As CancellationToken) As Task(Of IMediaDataServiceResponse)" />
      <MemberSignature Language="F#" Value="abstract member SaveChangesAsync : System.Data.Services.Client.SaveChangesOptions * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;&#xA;override this.SaveChangesAsync : System.Data.Services.Client.SaveChangesOptions * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;" Usage="mediaDataServiceContext.SaveChangesAsync (options, state, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.SaveChangesAsync(System.Data.Services.Client.SaveChangesOptions,System.Object,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="state" Type="System.Object" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">To be added.</param>
        <param name="state">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetLink">
      <MemberSignature Language="C#" Value="public void SetLink (object source, string sourceProperty, object target);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetLink(object source, string sourceProperty, object target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.SetLink(System.Object,System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetLink (source As Object, sourceProperty As String, target As Object)" />
      <MemberSignature Language="F#" Value="abstract member SetLink : obj * string * obj -&gt; unit&#xA;override this.SetLink : obj * string * obj -&gt; unit" Usage="mediaDataServiceContext.SetLink (source, sourceProperty, target)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.SetLink(System.Object,System.String,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="sourceProperty" Type="System.String" />
        <Parameter Name="target" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="sourceProperty">To be added.</param>
        <param name="target">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateObject">
      <MemberSignature Language="C#" Value="public void UpdateObject (object entity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateObject(object entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MediaServices.Client.MediaDataServiceContext.UpdateObject(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateObject (entity As Object)" />
      <MemberSignature Language="F#" Value="abstract member UpdateObject : obj -&gt; unit&#xA;override this.UpdateObject : obj -&gt; unit" Usage="mediaDataServiceContext.UpdateObject entity" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MediaServices.Client.IMediaDataServiceContext.UpdateObject(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.MediaServices.Client</AssemblyName>
        <AssemblyVersion>4.0.0.4</AssemblyVersion>
        <AssemblyVersion>4.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entity">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>