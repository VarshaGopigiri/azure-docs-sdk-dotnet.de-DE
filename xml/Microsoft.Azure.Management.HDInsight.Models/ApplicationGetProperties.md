<Type Name="ApplicationGetProperties" FullName="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties">
  <TypeSignature Language="C#" Value="public class ApplicationGetProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGetProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGetProperties" />
  <TypeSignature Language="F#" Value="type ApplicationGetProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public ApplicationGetProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGetProperties (Microsoft.Azure.Management.HDInsight.Models.ComputeProfile computeProfile = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; installScriptActions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; uninstallScriptActions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; httpsEndpoints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; sshEndpoints = null, string provisioningState = null, string applicationType = null, string applicationState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt; errors = null, string createdDate = null, string marketplaceIdentifier = null, string additionalProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.HDInsight.Models.ComputeProfile computeProfile, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; installScriptActions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; uninstallScriptActions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; httpsEndpoints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; sshEndpoints, string provisioningState, string applicationType, string applicationState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Errors&gt; errors, string createdDate, string marketplaceIdentifier, string additionalProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.#ctor(Microsoft.Azure.Management.HDInsight.Models.ComputeProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction},System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint},System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint},System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.Errors},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties : Microsoft.Azure.Management.HDInsight.Models.ComputeProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt; * string * string * string -&gt; Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties" Usage="new Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties (computeProfile, installScriptActions, uninstallScriptActions, httpsEndpoints, sshEndpoints, provisioningState, applicationType, applicationState, errors, createdDate, marketplaceIdentifier, additionalProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeProfile" Type="Microsoft.Azure.Management.HDInsight.Models.ComputeProfile" />
        <Parameter Name="installScriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="uninstallScriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;" />
        <Parameter Name="httpsEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt;" />
        <Parameter Name="sshEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="applicationType" Type="System.String" />
        <Parameter Name="applicationState" Type="System.String" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt;" />
        <Parameter Name="createdDate" Type="System.String" />
        <Parameter Name="marketplaceIdentifier" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeProfile">To be added.</param>
        <param name="installScriptActions">To be added.</param>
        <param name="uninstallScriptActions">To be added.</param>
        <param name="httpsEndpoints">To be added.</param>
        <param name="sshEndpoints">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="applicationType">To be added.</param>
        <param name="applicationState">To be added.</param>
        <param name="errors">To be added.</param>
        <param name="createdDate">To be added.</param>
        <param name="marketplaceIdentifier">To be added.</param>
        <param name="additionalProperties">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public string AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As String" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="additionalProperties")</AttributeName>
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
    <Member MemberName="ApplicationState">
      <MemberSignature Language="C#" Value="public string ApplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ApplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationState : string" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ApplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationState")</AttributeName>
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
    <Member MemberName="ApplicationType">
      <MemberSignature Language="C#" Value="public string ApplicationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ApplicationType" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationType As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationType : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ApplicationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationType")</AttributeName>
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
    <Member MemberName="ComputeProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Models.ComputeProfile ComputeProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Models.ComputeProfile ComputeProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ComputeProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeProfile As ComputeProfile" />
      <MemberSignature Language="F#" Value="member this.ComputeProfile : Microsoft.Azure.Management.HDInsight.Models.ComputeProfile with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ComputeProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computeProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.ComputeProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedDate">
      <MemberSignature Language="C#" Value="public string CreatedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreatedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.CreatedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedDate As String" />
      <MemberSignature Language="F#" Value="member this.CreatedDate : string" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.CreatedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createdDate")</AttributeName>
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
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.Errors&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of Errors)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.Errors&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; HttpsEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; HttpsEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.HttpsEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsEndpoints As IList(Of ApplicationGetHttpsEndpoint)" />
      <MemberSignature Language="F#" Value="member this.HttpsEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.HttpsEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpsEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetHttpsEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallScriptActions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; InstallScriptActions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; InstallScriptActions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.InstallScriptActions" />
      <MemberSignature Language="VB.NET" Value="Public Property InstallScriptActions As IList(Of RuntimeScriptAction)" />
      <MemberSignature Language="F#" Value="member this.InstallScriptActions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.InstallScriptActions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="installScriptActions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarketplaceIdentifier">
      <MemberSignature Language="C#" Value="public string MarketplaceIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MarketplaceIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.MarketplaceIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MarketplaceIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.MarketplaceIdentifier : string" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.MarketplaceIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="marketplaceIdentifier")</AttributeName>
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
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
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
    <Member MemberName="SshEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; SshEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; SshEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.SshEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property SshEndpoints As IList(Of ApplicationGetEndpoint)" />
      <MemberSignature Language="F#" Value="member this.SshEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.SshEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sshEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ApplicationGetEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UninstallScriptActions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; UninstallScriptActions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; UninstallScriptActions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.UninstallScriptActions" />
      <MemberSignature Language="VB.NET" Value="Public Property UninstallScriptActions As IList(Of RuntimeScriptAction)" />
      <MemberSignature Language="F#" Value="member this.UninstallScriptActions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.ApplicationGetProperties.UninstallScriptActions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uninstallScriptActions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.RuntimeScriptAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>