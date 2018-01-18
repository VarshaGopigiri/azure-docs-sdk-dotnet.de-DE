<Type Name="GeoFilter" FullName="Microsoft.Azure.Management.Cdn.Models.GeoFilter">
  <TypeSignature Language="C#" Value="public class GeoFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Models.GeoFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoFilter" />
  <TypeSignature Language="F#" Value="type GeoFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
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
      <MemberSignature Language="C#" Value="public GeoFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Models.GeoFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;string&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;string&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Models.GeoFilter.#ctor(System.String,Microsoft.Azure.Management.Cdn.Models.GeoFilterActions,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Models.GeoFilter : string * Microsoft.Azure.Management.Cdn.Models.GeoFilterActions * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Models.GeoFilter" Usage="new Microsoft.Azure.Management.Cdn.Models.GeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Models.GeoFilterActions" />
        <Parameter Name="countryCodes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="relativePath">To be added.</param>
        <param name="action">To be added.</param>
        <param name="countryCodes">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Models.GeoFilterActions Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Cdn.Models.GeoFilterActions Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Models.GeoFilter.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As GeoFilterActions" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.Cdn.Models.GeoFilterActions with get, set" Usage="Microsoft.Azure.Management.Cdn.Models.GeoFilter.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Models.GeoFilterActions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountryCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CountryCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CountryCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Models.GeoFilter.CountryCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property CountryCodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CountryCodes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Models.GeoFilter.CountryCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="countryCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativePath">
      <MemberSignature Language="C#" Value="public string RelativePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Models.GeoFilter.RelativePath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativePath As String" />
      <MemberSignature Language="F#" Value="member this.RelativePath : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Models.GeoFilter.RelativePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativePath")</AttributeName>
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Models.GeoFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="geoFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
  </Members>
</Type>