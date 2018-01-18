<Type Name="DeviceInner" FullName="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner">
  <TypeSignature Language="C#" Value="public class DeviceInner : Microsoft.Azure.Management.StorSimple.Fluent.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceInner extends Microsoft.Azure.Management.StorSimple.Fluent.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceInner&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type DeviceInner = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple.Fluent.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceInner (string friendlyName, DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus status, string serialNumber, Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType deviceType, Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId activeController, string friendlySoftwareVersion, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.Kind&gt; kind = null, string friendlySoftwareName = null, Nullable&lt;long&gt; availableLocalStorageInBytes = null, Nullable&lt;long&gt; availableTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedLocalStorageInBytes = null, Nullable&lt;long&gt; provisionedVolumeSizeInBytes = null, Nullable&lt;long&gt; usingStorageInBytes = null, Nullable&lt;long&gt; totalTieredStorageInBytes = null, Nullable&lt;int&gt; agentGroupVersion = null, Nullable&lt;int&gt; networkInterfaceCardCount = null, string deviceLocation = null, Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt; virtualMachineApiType = null, Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails details = null, Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails rolloverDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, valuetype System.DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus status, string serialNumber, valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType deviceType, valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId activeController, string friendlySoftwareVersion, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.Kind&gt; kind, string friendlySoftwareName, valuetype System.Nullable`1&lt;int64&gt; availableLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; availableTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedVolumeSizeInBytes, valuetype System.Nullable`1&lt;int64&gt; usingStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; totalTieredStorageInBytes, valuetype System.Nullable`1&lt;int32&gt; agentGroupVersion, valuetype System.Nullable`1&lt;int32&gt; networkInterfaceCardCount, string deviceLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt; virtualMachineApiType, class Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails details, class Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails rolloverDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.#ctor(System.String,System.DateTime,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus,System.String,System.String,Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus,System.String,Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType,Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple.Fluent.Models.Kind},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType},Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails,Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner : string * DateTime * string * string * string * Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus * string * string * Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus * string * Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType * Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.Kind&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt; * Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails * Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails -&gt; Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner" Usage="new Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner (friendlyName, activationTime, culture, deviceDescription, deviceSoftwareVersion, deviceConfigurationStatus, targetIqn, modelDescription, status, serialNumber, deviceType, activeController, friendlySoftwareVersion, id, name, type, kind, friendlySoftwareName, availableLocalStorageInBytes, availableTieredStorageInBytes, provisionedTieredStorageInBytes, provisionedLocalStorageInBytes, provisionedVolumeSizeInBytes, usingStorageInBytes, totalTieredStorageInBytes, agentGroupVersion, networkInterfaceCardCount, deviceLocation, virtualMachineApiType, details, rolloverDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="activationTime" Type="System.DateTime" />
        <Parameter Name="culture" Type="System.String" />
        <Parameter Name="deviceDescription" Type="System.String" />
        <Parameter Name="deviceSoftwareVersion" Type="System.String" />
        <Parameter Name="deviceConfigurationStatus" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus" />
        <Parameter Name="targetIqn" Type="System.String" />
        <Parameter Name="modelDescription" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="deviceType" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType" />
        <Parameter Name="activeController" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId" />
        <Parameter Name="friendlySoftwareVersion" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.Kind&gt;" />
        <Parameter Name="friendlySoftwareName" Type="System.String" />
        <Parameter Name="availableLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="availableTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedVolumeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="usingStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="totalTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="agentGroupVersion" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="networkInterfaceCardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="deviceLocation" Type="System.String" />
        <Parameter Name="virtualMachineApiType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt;" />
        <Parameter Name="details" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails" />
        <Parameter Name="rolloverDetails" Type="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails" />
      </Parameters>
      <Docs>
        <param name="friendlyName">To be added.</param>
        <param name="activationTime">To be added.</param>
        <param name="culture">To be added.</param>
        <param name="deviceDescription">To be added.</param>
        <param name="deviceSoftwareVersion">To be added.</param>
        <param name="deviceConfigurationStatus">To be added.</param>
        <param name="targetIqn">To be added.</param>
        <param name="modelDescription">To be added.</param>
        <param name="status">To be added.</param>
        <param name="serialNumber">To be added.</param>
        <param name="deviceType">To be added.</param>
        <param name="activeController">To be added.</param>
        <param name="friendlySoftwareVersion">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="friendlySoftwareName">To be added.</param>
        <param name="availableLocalStorageInBytes">To be added.</param>
        <param name="availableTieredStorageInBytes">To be added.</param>
        <param name="provisionedTieredStorageInBytes">To be added.</param>
        <param name="provisionedLocalStorageInBytes">To be added.</param>
        <param name="provisionedVolumeSizeInBytes">To be added.</param>
        <param name="usingStorageInBytes">To be added.</param>
        <param name="totalTieredStorageInBytes">To be added.</param>
        <param name="agentGroupVersion">To be added.</param>
        <param name="networkInterfaceCardCount">To be added.</param>
        <param name="deviceLocation">To be added.</param>
        <param name="virtualMachineApiType">To be added.</param>
        <param name="details">To be added.</param>
        <param name="rolloverDetails">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivationTime">
      <MemberSignature Language="C#" Value="public DateTime ActivationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ActivationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ActivationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ActivationTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ActivationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveController">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId ActiveController { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId ActiveController" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ActiveController" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveController As ControllerId" />
      <MemberSignature Language="F#" Value="member this.ActiveController : Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ActiveController" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeController")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.ControllerId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentGroupVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AgentGroupVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AgentGroupVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AgentGroupVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AgentGroupVersion As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AgentGroupVersion : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AgentGroupVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.agentGroupVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AvailableLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AvailableLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableLocalStorageInBytes")</AttributeName>
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
    <Member MemberName="AvailableTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AvailableTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.AvailableTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableTieredStorageInBytes")</AttributeName>
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
    <Member MemberName="Culture">
      <MemberSignature Language="C#" Value="public string Culture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Culture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Culture" />
      <MemberSignature Language="VB.NET" Value="Public Property Culture As String" />
      <MemberSignature Language="F#" Value="member this.Culture : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Culture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.culture")</AttributeName>
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
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As DeviceDetails" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceConfigurationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus DeviceConfigurationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus DeviceConfigurationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceConfigurationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceConfigurationStatus As DeviceConfigurationStatus" />
      <MemberSignature Language="F#" Value="member this.DeviceConfigurationStatus : Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceConfigurationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceConfigurationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceConfigurationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceDescription">
      <MemberSignature Language="C#" Value="public string DeviceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceDescription As String" />
      <MemberSignature Language="F#" Value="member this.DeviceDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceDescription")</AttributeName>
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
    <Member MemberName="DeviceLocation">
      <MemberSignature Language="C#" Value="public string DeviceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceLocation As String" />
      <MemberSignature Language="F#" Value="member this.DeviceLocation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceLocation")</AttributeName>
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
    <Member MemberName="DeviceSoftwareVersion">
      <MemberSignature Language="C#" Value="public string DeviceSoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceSoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceSoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceSoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.DeviceSoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceSoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceSoftwareVersion")</AttributeName>
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
    <Member MemberName="DeviceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType DeviceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType DeviceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceType" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceType As DeviceType" />
      <MemberSignature Language="F#" Value="member this.DeviceType : Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.DeviceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
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
    <Member MemberName="FriendlySoftwareName">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlySoftwareName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlySoftwareName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareName")</AttributeName>
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
    <Member MemberName="FriendlySoftwareVersion">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlySoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.FriendlySoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareVersion")</AttributeName>
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
    <Member MemberName="ModelDescription">
      <MemberSignature Language="C#" Value="public string ModelDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ModelDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelDescription As String" />
      <MemberSignature Language="F#" Value="member this.ModelDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ModelDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.modelDescription")</AttributeName>
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
    <Member MemberName="NetworkInterfaceCardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NetworkInterfaceCardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NetworkInterfaceCardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.NetworkInterfaceCardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceCardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceCardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.NetworkInterfaceCardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaceCardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedLocalStorageInBytes")</AttributeName>
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
    <Member MemberName="ProvisionedTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedTieredStorageInBytes")</AttributeName>
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
    <Member MemberName="ProvisionedVolumeSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedVolumeSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedVolumeSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedVolumeSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.ProvisionedVolumeSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedVolumeSizeInBytes")</AttributeName>
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
    <Member MemberName="RolloverDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails RolloverDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails RolloverDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.RolloverDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property RolloverDetails As DeviceRolloverDetails" />
      <MemberSignature Language="F#" Value="member this.RolloverDetails : Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.RolloverDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rolloverDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceRolloverDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
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
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As DeviceStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetIqn">
      <MemberSignature Language="C#" Value="public string TargetIqn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetIqn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.TargetIqn" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetIqn As String" />
      <MemberSignature Language="F#" Value="member this.TargetIqn : string with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.TargetIqn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetIqn")</AttributeName>
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
    <Member MemberName="TotalTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.TotalTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.TotalTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalTieredStorageInBytes")</AttributeName>
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
    <Member MemberName="UsingStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; UsingStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; UsingStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.UsingStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UsingStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.UsingStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usingStorageInBytes")</AttributeName>
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deviceInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineApiType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt; VirtualMachineApiType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt; VirtualMachineApiType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.VirtualMachineApiType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineApiType As Nullable(Of VirtualMachineApiType)" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineApiType : Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt;" Usage="Microsoft.Azure.Management.StorSimple.Fluent.Models.DeviceInner.VirtualMachineApiType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineApiType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple.Fluent.Models.VirtualMachineApiType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>