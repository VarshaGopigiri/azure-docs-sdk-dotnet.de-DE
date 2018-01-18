<Type Name="Datasets" FullName="Microsoft.PowerBI.Api.V2.Datasets">
  <TypeSignature Language="C#" Value="public class Datasets : Microsoft.PowerBI.Api.V2.IDatasets, Microsoft.Rest.IServiceOperations&lt;Microsoft.PowerBI.Api.V2.PowerBIClient&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Datasets extends System.Object implements class Microsoft.PowerBI.Api.V2.IDatasets, class Microsoft.Rest.IServiceOperations`1&lt;class Microsoft.PowerBI.Api.V2.PowerBIClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.Datasets" />
  <TypeSignature Language="VB.NET" Value="Public Class Datasets&#xA;Implements IDatasets, IServiceOperations(Of PowerBIClient)" />
  <TypeSignature Language="F#" Value="type Datasets = class&#xA;    interface IServiceOperations&lt;PowerBIClient&gt;&#xA;    interface IDatasets" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.PowerBI.Api.V2.IDatasets</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.IServiceOperations&lt;Microsoft.PowerBI.Api.V2.PowerBIClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Datasets (Microsoft.PowerBI.Api.V2.PowerBIClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.PowerBI.Api.V2.PowerBIClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.#ctor(Microsoft.PowerBI.Api.V2.PowerBIClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (client As PowerBIClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.PowerBI.Api.V2.Datasets : Microsoft.PowerBI.Api.V2.PowerBIClient -&gt; Microsoft.PowerBI.Api.V2.Datasets" Usage="new Microsoft.PowerBI.Api.V2.Datasets client" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.PowerBI.Api.V2.PowerBIClient" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindToGatewayInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; BindToGatewayInGroupWithHttpMessagesAsync (string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; BindToGatewayInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.BindToGatewayInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BindToGatewayInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.BindToGatewayInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.BindToGatewayInGroupWithHttpMessagesAsync (groupId, datasetKey, bindToGatewayRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.BindToGatewayInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;BindToGatewayInGroupWithHttpMessagesAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindToGatewayWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; BindToGatewayWithHttpMessagesAsync (string datasetKey, Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; BindToGatewayWithHttpMessagesAsync(string datasetKey, class Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest bindToGatewayRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.BindToGatewayWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BindToGatewayWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.BindToGatewayWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.BindToGatewayWithHttpMessagesAsync (datasetKey, bindToGatewayRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.BindToGatewayWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;BindToGatewayWithHttpMessagesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="bindToGatewayRequest" Type="Microsoft.PowerBI.Api.V2.Models.BindToGatewayRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="bindToGatewayRequest">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public Microsoft.PowerBI.Api.V2.PowerBIClient Client { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.PowerBI.Api.V2.PowerBIClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.PowerBI.Api.V2.Datasets.Client" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Client As PowerBIClient" />
      <MemberSignature Language="F#" Value="member this.Client : Microsoft.PowerBI.Api.V2.PowerBIClient" Usage="Microsoft.PowerBI.Api.V2.Datasets.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.PowerBIClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteDatasetByIdInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteDatasetByIdInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.DeleteDatasetByIdInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatasetByIdInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteDatasetByIdInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.DeleteDatasetByIdInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.DeleteDatasetByIdInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;DeleteDatasetByIdInGroupWithHttpMessagesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatasetByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteDatasetByIdWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteDatasetByIdWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.DeleteDatasetByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatasetByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteDatasetByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.DeleteDatasetByIdWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.DeleteDatasetByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;DeleteDatasetByIdWithHttpMessagesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteRowsInGroupWithHttpMessagesAsync (string groupId, string datasetKey, string tableName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteRowsInGroupWithHttpMessagesAsync(string groupId, string datasetKey, string tableName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.DeleteRowsInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRowsInGroupWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteRowsInGroupWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.DeleteRowsInGroupWithHttpMessagesAsync (groupId, datasetKey, tableName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.DeleteRowsInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;DeleteRowsInGroupWithHttpMessagesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRowsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteRowsWithHttpMessagesAsync (string datasetKey, string tableName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteRowsWithHttpMessagesAsync(string datasetKey, string tableName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.DeleteRowsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRowsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteRowsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.DeleteRowsWithHttpMessagesAsync (datasetKey, tableName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.DeleteRowsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;DeleteRowsWithHttpMessagesAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenInGroupWithHttpMessagesAsync (string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GenerateTokenInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;&#xA;override this.GenerateTokenInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="datasets.GenerateTokenInGroupWithHttpMessagesAsync (groupId, datasetKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GenerateTokenInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GenerateTokenInGroupWithHttpMessagesAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt; GetDatasetByIdInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt; GetDatasetByIdInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasetByIdInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasetByIdInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;&#xA;override this.GetDatasetByIdInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;" Usage="datasets.GetDatasetByIdInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasetByIdInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasetByIdInGroupWithHttpMessagesAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt; GetDatasetByIdWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt; GetDatasetByIdWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasetByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasetByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;&#xA;override this.GetDatasetByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;" Usage="datasets.GetDatasetByIdWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasetByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasetByIdWithHttpMessagesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Dataset&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetsInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt; GetDatasetsInGroupWithHttpMessagesAsync (string groupId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt; GetDatasetsInGroupWithHttpMessagesAsync(string groupId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasetsInGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasetsInGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;&#xA;override this.GetDatasetsInGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;" Usage="datasets.GetDatasetsInGroupWithHttpMessagesAsync (groupId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasetsInGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasetsInGroupWithHttpMessagesAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasetsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt; GetDatasetsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt; GetDatasetsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasetsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasetsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;&#xA;override this.GetDatasetsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;" Usage="datasets.GetDatasetsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasetsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasetsWithHttpMessagesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDataset&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesAsAdminWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesAsAdminWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesAsAdminWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasourcesAsAdminWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasourcesAsAdminWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;&#xA;override this.GetDatasourcesAsAdminWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;" Usage="datasets.GetDatasourcesAsAdminWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasourcesAsAdminWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasourcesAsAdminWithHttpMessagesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasourcesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;&#xA;override this.GetDatasourcesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;" Usage="datasets.GetDatasourcesInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasourcesInGroupWithHttpMessagesAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatasourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt; GetDatasourcesWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetDatasourcesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatasourcesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;&#xA;override this.GetDatasourcesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;" Usage="datasets.GetDatasourcesWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetDatasourcesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetDatasourcesWithHttpMessagesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListDatasource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt; GetGatewayDatasourcesInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt; GetGatewayDatasourcesInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetGatewayDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetGatewayDatasourcesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;&#xA;override this.GetGatewayDatasourcesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;" Usage="datasets.GetGatewayDatasourcesInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetGatewayDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetGatewayDatasourcesInGroupWithHttpMessagesAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayDatasourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt; GetGatewayDatasourcesWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt; GetGatewayDatasourcesWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetGatewayDatasourcesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetGatewayDatasourcesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;&#xA;override this.GetGatewayDatasourcesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;" Usage="datasets.GetGatewayDatasourcesWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetGatewayDatasourcesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetGatewayDatasourcesWithHttpMessagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListGatewayDatasource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistoryInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt; GetRefreshHistoryInGroupWithHttpMessagesAsync (string groupId, string datasetKey, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt; GetRefreshHistoryInGroupWithHttpMessagesAsync(string groupId, string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetRefreshHistoryInGroupWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRefreshHistoryInGroupWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;&#xA;override this.GetRefreshHistoryInGroupWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;" Usage="datasets.GetRefreshHistoryInGroupWithHttpMessagesAsync (groupId, datasetKey, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetRefreshHistoryInGroupWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetRefreshHistoryInGroupWithHttpMessagesAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRefreshHistoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt; GetRefreshHistoryWithHttpMessagesAsync (string datasetKey, Nullable&lt;int&gt; top = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt; GetRefreshHistoryWithHttpMessagesAsync(string datasetKey, valuetype System.Nullable`1&lt;int32&gt; top, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetRefreshHistoryWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRefreshHistoryWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;&#xA;override this.GetRefreshHistoryWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;" Usage="datasets.GetRefreshHistoryWithHttpMessagesAsync (datasetKey, top, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetRefreshHistoryWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetRefreshHistoryWithHttpMessagesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListRefresh&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="top">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt; GetTablesInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt; GetTablesInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetTablesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTablesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;&#xA;override this.GetTablesInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;" Usage="datasets.GetTablesInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetTablesInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetTablesInGroupWithHttpMessagesAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt; GetTablesWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt; GetTablesWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.GetTablesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTablesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;&#xA;override this.GetTablesWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;" Usage="datasets.GetTablesWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.GetTablesWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;GetTablesWithHttpMessagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PostDatasetInGroupWithHttpMessagesAsync (string groupId, Microsoft.PowerBI.Api.V2.Models.Dataset dataset, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PostDatasetInGroupWithHttpMessagesAsync(string groupId, class Microsoft.PowerBI.Api.V2.Models.Dataset dataset, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PostDatasetInGroupWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.Dataset,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PostDatasetInGroupWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.Dataset * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PostDatasetInGroupWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.Dataset * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PostDatasetInGroupWithHttpMessagesAsync (groupId, dataset, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PostDatasetInGroupWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.Dataset,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PostDatasetInGroupWithHttpMessagesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="dataset">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostDatasetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PostDatasetWithHttpMessagesAsync (Microsoft.PowerBI.Api.V2.Models.Dataset dataset, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PostDatasetWithHttpMessagesAsync(class Microsoft.PowerBI.Api.V2.Models.Dataset dataset, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PostDatasetWithHttpMessagesAsync(Microsoft.PowerBI.Api.V2.Models.Dataset,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PostDatasetWithHttpMessagesAsync : Microsoft.PowerBI.Api.V2.Models.Dataset * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PostDatasetWithHttpMessagesAsync : Microsoft.PowerBI.Api.V2.Models.Dataset * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PostDatasetWithHttpMessagesAsync (dataset, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PostDatasetWithHttpMessagesAsync(Microsoft.PowerBI.Api.V2.Models.Dataset,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PostDatasetWithHttpMessagesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataset" Type="Microsoft.PowerBI.Api.V2.Models.Dataset" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="dataset">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PostRowsInGroupWithHttpMessagesAsync (string groupId, string datasetKey, string tableName, object requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PostRowsInGroupWithHttpMessagesAsync(string groupId, string datasetKey, string tableName, object requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PostRowsInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PostRowsInGroupWithHttpMessagesAsync : string * string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PostRowsInGroupWithHttpMessagesAsync : string * string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PostRowsInGroupWithHttpMessagesAsync (groupId, datasetKey, tableName, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PostRowsInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PostRowsInGroupWithHttpMessagesAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PostRowsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PostRowsWithHttpMessagesAsync (string datasetKey, string tableName, object requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PostRowsWithHttpMessagesAsync(string datasetKey, string tableName, object requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PostRowsWithHttpMessagesAsync(System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PostRowsWithHttpMessagesAsync : string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PostRowsWithHttpMessagesAsync : string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PostRowsWithHttpMessagesAsync (datasetKey, tableName, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PostRowsWithHttpMessagesAsync(System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PostRowsWithHttpMessagesAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PutTableInGroupWithHttpMessagesAsync (string groupId, string datasetKey, string tableName, object requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PutTableInGroupWithHttpMessagesAsync(string groupId, string datasetKey, string tableName, object requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PutTableInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutTableInGroupWithHttpMessagesAsync : string * string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PutTableInGroupWithHttpMessagesAsync : string * string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PutTableInGroupWithHttpMessagesAsync (groupId, datasetKey, tableName, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PutTableInGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PutTableInGroupWithHttpMessagesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; PutTableWithHttpMessagesAsync (string datasetKey, string tableName, object requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; PutTableWithHttpMessagesAsync(string datasetKey, string tableName, object requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.PutTableWithHttpMessagesAsync(System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PutTableWithHttpMessagesAsync : string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.PutTableWithHttpMessagesAsync : string * string * obj * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.PutTableWithHttpMessagesAsync (datasetKey, tableName, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.PutTableWithHttpMessagesAsync(System.String,System.String,System.Object,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;PutTableWithHttpMessagesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="requestMessage" Type="System.Object" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="tableName">To be added.</param>
        <param name="requestMessage">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDatasetInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; RefreshDatasetInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; RefreshDatasetInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.RefreshDatasetInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshDatasetInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.RefreshDatasetInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.RefreshDatasetInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.RefreshDatasetInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;RefreshDatasetInGroupWithHttpMessagesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshDatasetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; RefreshDatasetWithHttpMessagesAsync (string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; RefreshDatasetWithHttpMessagesAsync(string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.RefreshDatasetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshDatasetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.RefreshDatasetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.RefreshDatasetWithHttpMessagesAsync (datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.RefreshDatasetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;RefreshDatasetWithHttpMessagesAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnectionsInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; SetAllDatasetConnectionsInGroupWithHttpMessagesAsync (string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; SetAllDatasetConnectionsInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.SetAllDatasetConnectionsInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAllDatasetConnectionsInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.SetAllDatasetConnectionsInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.SetAllDatasetConnectionsInGroupWithHttpMessagesAsync (groupId, datasetKey, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.SetAllDatasetConnectionsInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;SetAllDatasetConnectionsInGroupWithHttpMessagesAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAllDatasetConnectionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; SetAllDatasetConnectionsWithHttpMessagesAsync (string datasetKey, Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; SetAllDatasetConnectionsWithHttpMessagesAsync(string datasetKey, class Microsoft.PowerBI.Api.V2.Models.ConnectionDetails parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.SetAllDatasetConnectionsWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAllDatasetConnectionsWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.SetAllDatasetConnectionsWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.ConnectionDetails * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.SetAllDatasetConnectionsWithHttpMessagesAsync (datasetKey, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.SetAllDatasetConnectionsWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.ConnectionDetails,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;SetAllDatasetConnectionsWithHttpMessagesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.PowerBI.Api.V2.Models.ConnectionDetails" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeOverInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; TakeOverInGroupWithHttpMessagesAsync (string groupId, string datasetKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; TakeOverInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.TakeOverInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TakeOverInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.TakeOverInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.TakeOverInGroupWithHttpMessagesAsync (groupId, datasetKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.TakeOverInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;TakeOverInGroupWithHttpMessagesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourcesInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; UpdateDatasourcesInGroupWithHttpMessagesAsync (string groupId, string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; UpdateDatasourcesInGroupWithHttpMessagesAsync(string groupId, string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.UpdateDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDatasourcesInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.UpdateDatasourcesInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.UpdateDatasourcesInGroupWithHttpMessagesAsync (groupId, datasetKey, updateDatasourcesRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.UpdateDatasourcesInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;UpdateDatasourcesInGroupWithHttpMessagesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDatasourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; UpdateDatasourcesWithHttpMessagesAsync (string datasetKey, Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; UpdateDatasourcesWithHttpMessagesAsync(string datasetKey, class Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest updateDatasourcesRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Datasets.UpdateDatasourcesWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDatasourcesWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.UpdateDatasourcesWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="datasets.UpdateDatasourcesWithHttpMessagesAsync (datasetKey, updateDatasourcesRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IDatasets.UpdateDatasourcesWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Datasets/&lt;UpdateDatasourcesWithHttpMessagesAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="datasetKey" Type="System.String" />
        <Parameter Name="updateDatasourcesRequest" Type="Microsoft.PowerBI.Api.V2.Models.UpdateDatasourcesRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="datasetKey">To be added.</param>
        <param name="updateDatasourcesRequest">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>