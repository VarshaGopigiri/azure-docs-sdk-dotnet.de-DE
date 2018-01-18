<Type Name="OperationResource" FullName="Microsoft.Azure.Management.HDInsight.Models.OperationResource">
  <TypeSignature Language="C#" Value="public class OperationResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationResource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Models.OperationResource" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationResource" />
  <TypeSignature Language="F#" Value="type OperationResource = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.OperationResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResource (Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; status = null, Microsoft.Azure.Management.HDInsight.Models.Errors error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; status, class Microsoft.Azure.Management.HDInsight.Models.Errors error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.OperationResource.#ctor(System.Nullable{Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState},Microsoft.Azure.Management.HDInsight.Models.Errors)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As Nullable(Of AsyncOperationState) = null, Optional error As Errors = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Models.OperationResource : Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; * Microsoft.Azure.Management.HDInsight.Models.Errors -&gt; Microsoft.Azure.Management.HDInsight.Models.OperationResource" Usage="new Microsoft.Azure.Management.HDInsight.Models.OperationResource (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.HDInsight.Models.Errors" />
      </Parameters>
      <Docs>
        <param name="status">To be added.</param>
        <param name="error">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Models.Errors Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Models.Errors Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.OperationResource.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As Errors" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.HDInsight.Models.Errors with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.OperationResource.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.Errors</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.OperationResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of AsyncOperationState)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.OperationResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.HDInsight.Models.AsyncOperationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>