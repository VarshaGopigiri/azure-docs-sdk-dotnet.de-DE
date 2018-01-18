<Type Name="RelayServiceConnectionEntityInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner">
  <TypeSignature Language="C#" Value="public class RelayServiceConnectionEntityInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayServiceConnectionEntityInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayServiceConnectionEntityInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RelayServiceConnectionEntityInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5148b-101">Hybridverbindung für eine App Service-app.</span><span class="sxs-lookup"><span data-stu-id="5148b-101">Hybrid Connection for an App Service app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayServiceConnectionEntityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5148b-102">Initialisiert eine neue Instanz der RelayServiceConnectionEntityInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5148b-102">Initializes a new instance of the RelayServiceConnectionEntityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayServiceConnectionEntityInner (string id = null, string name = null, string kind = null, string type = null, string entityName = null, string entityConnectionString = null, string resourceType = null, string resourceConnectionString = null, string hostname = null, Nullable&lt;int&gt; port = null, string biztalkUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string entityName, string entityConnectionString, string resourceType, string resourceConnectionString, string hostname, valuetype System.Nullable`1&lt;int32&gt; port, string biztalkUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional entityName As String = null, Optional entityConnectionString As String = null, Optional resourceType As String = null, Optional resourceConnectionString As String = null, Optional hostname As String = null, Optional port As Nullable(Of Integer) = null, Optional biztalkUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner : string * string * string * string * string * string * string * string * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner (id, name, kind, type, entityName, entityConnectionString, resourceType, resourceConnectionString, hostname, port, biztalkUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="entityConnectionString" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceConnectionString" Type="System.String" />
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="biztalkUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="entityName">To be added.</param>
        <param name="entityConnectionString">To be added.</param>
        <param name="resourceType">To be added.</param>
        <param name="resourceConnectionString">To be added.</param>
        <param name="hostname">To be added.</param>
        <param name="port">To be added.</param>
        <param name="biztalkUri">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BiztalkUri">
      <MemberSignature Language="C#" Value="public string BiztalkUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BiztalkUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.BiztalkUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BiztalkUri As String" />
      <MemberSignature Language="F#" Value="member this.BiztalkUri : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.BiztalkUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.biztalkUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConnectionString">
      <MemberSignature Language="C#" Value="public string EntityConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.EntityConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.EntityConnectionString : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.EntityConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.entityConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityName">
      <MemberSignature Language="C#" Value="public string EntityName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.EntityName" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityName As String" />
      <MemberSignature Language="F#" Value="member this.EntityName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.EntityName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.entityName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hostname">
      <MemberSignature Language="C#" Value="public string Hostname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Hostname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.Hostname" />
      <MemberSignature Language="VB.NET" Value="Public Property Hostname As String" />
      <MemberSignature Language="F#" Value="member this.Hostname : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.Hostname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceConnectionString">
      <MemberSignature Language="C#" Value="public string ResourceConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.ResourceConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ResourceConnectionString : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.ResourceConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>