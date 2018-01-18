<Type Name="ResourceSkuCosts" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts">
  <TypeSignature Language="C#" Value="public class ResourceSkuCosts" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceSkuCosts extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceSkuCosts" />
  <TypeSignature Language="F#" Value="type ResourceSkuCosts = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuCosts ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceSkuCosts (string meterID = null, Nullable&lt;long&gt; quantity = null, string extendedUnit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string meterID, valuetype System.Nullable`1&lt;int64&gt; quantity, string extendedUnit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.#ctor(System.String,System.Nullable{System.Int64},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional meterID As String = null, Optional quantity As Nullable(Of Long) = null, Optional extendedUnit As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts : string * Nullable&lt;int64&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts (meterID, quantity, extendedUnit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="meterID" Type="System.String" />
        <Parameter Name="quantity" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="extendedUnit" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="meterID">To be added.</param>
        <param name="quantity">To be added.</param>
        <param name="extendedUnit">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedUnit">
      <MemberSignature Language="C#" Value="public string ExtendedUnit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtendedUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.ExtendedUnit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExtendedUnit As String" />
      <MemberSignature Language="F#" Value="member this.ExtendedUnit : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.ExtendedUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterID">
      <MemberSignature Language="C#" Value="public string MeterID { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.MeterID" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterID As String" />
      <MemberSignature Language="F#" Value="member this.MeterID : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.MeterID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="meterID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Quantity">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Quantity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Quantity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.Quantity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Quantity As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Quantity : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ResourceSkuCosts.Quantity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quantity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>