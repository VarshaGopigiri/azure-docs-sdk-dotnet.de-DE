<Type Name="Role" FullName="Microsoft.Azure.Management.HDInsight.Models.Role">
  <TypeSignature Language="C#" Value="public class Role" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Role extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.HDInsight.Models.Role" />
  <TypeSignature Language="VB.NET" Value="Public Class Role" />
  <TypeSignature Language="F#" Value="type Role = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Role ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.Role.#ctor" />
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
      <MemberSignature Language="C#" Value="public Role (string name = null, Nullable&lt;int&gt; minInstanceCount = null, Nullable&lt;int&gt; targetInstanceCount = null, Microsoft.Azure.Management.HDInsight.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.HDInsight.Models.OsProfile osProfile = null, Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile virtualNetworkProfile = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; dataDisksGroups = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; scriptActions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minInstanceCount, valuetype System.Nullable`1&lt;int32&gt; targetInstanceCount, class Microsoft.Azure.Management.HDInsight.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.HDInsight.Models.OsProfile osProfile, class Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile virtualNetworkProfile, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; dataDisksGroups, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; scriptActions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.HDInsight.Models.Role.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.HDInsight.Models.HardwareProfile,Microsoft.Azure.Management.HDInsight.Models.OsProfile,Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups},System.Collections.Generic.IList{Microsoft.Azure.Management.HDInsight.Models.ScriptAction})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.HDInsight.Models.Role : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.HDInsight.Models.HardwareProfile * Microsoft.Azure.Management.HDInsight.Models.OsProfile * Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; -&gt; Microsoft.Azure.Management.HDInsight.Models.Role" Usage="new Microsoft.Azure.Management.HDInsight.Models.Role (name, minInstanceCount, targetInstanceCount, hardwareProfile, osProfile, virtualNetworkProfile, dataDisksGroups, scriptActions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.HDInsight.Models.HardwareProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.HDInsight.Models.OsProfile" />
        <Parameter Name="virtualNetworkProfile" Type="Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile" />
        <Parameter Name="dataDisksGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt;" />
        <Parameter Name="scriptActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="minInstanceCount">To be added.</param>
        <param name="targetInstanceCount">To be added.</param>
        <param name="hardwareProfile">To be added.</param>
        <param name="osProfile">To be added.</param>
        <param name="virtualNetworkProfile">To be added.</param>
        <param name="dataDisksGroups">To be added.</param>
        <param name="scriptActions">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisksGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; DataDisksGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; DataDisksGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.DataDisksGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisksGroups As IList(Of DataDisksGroups)" />
      <MemberSignature Language="F#" Value="member this.DataDisksGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.DataDisksGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisksGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.DataDisksGroups&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.HDInsight.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.HardwareProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hardwareProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.HardwareProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinInstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.MinInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MinInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinInstanceCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.MinInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minInstanceCount")</AttributeName>
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
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
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
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Models.OsProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Models.OsProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OsProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.HDInsight.Models.OsProfile with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.OsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptActions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; ScriptActions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; ScriptActions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.ScriptActions" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptActions As IList(Of ScriptAction)" />
      <MemberSignature Language="F#" Value="member this.ScriptActions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.ScriptActions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptActions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.HDInsight.Models.ScriptAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetInstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.TargetInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetInstanceCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.TargetInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetInstanceCount")</AttributeName>
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
    <Member MemberName="VirtualNetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile VirtualNetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile VirtualNetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.HDInsight.Models.Role.VirtualNetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkProfile As VirtualNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkProfile : Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile with get, set" Usage="Microsoft.Azure.Management.HDInsight.Models.Role.VirtualNetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.HDInsight</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetworkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.HDInsight.Models.VirtualNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>