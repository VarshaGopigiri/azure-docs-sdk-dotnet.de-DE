<Type Name="CaaRecord" FullName="Microsoft.Azure.Management.Dns.Models.CaaRecord">
  <TypeSignature Language="C#" Value="public class CaaRecord" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CaaRecord extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Models.CaaRecord" />
  <TypeSignature Language="VB.NET" Value="Public Class CaaRecord" />
  <TypeSignature Language="F#" Value="type CaaRecord = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c4d09-101">Ein Datensatz CAA.</span><span class="sxs-lookup"><span data-stu-id="c4d09-101">A CAA record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaaRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.CaaRecord.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4d09-102">Initialisiert eine neue Instanz der CaaRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4d09-102">Initializes a new instance of the CaaRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaaRecord (Nullable&lt;int&gt; flags = null, string tag = null, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; flags, string tag, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.CaaRecord.#ctor(System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional flags As Nullable(Of Integer) = null, Optional tag As String = null, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Models.CaaRecord : Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.Dns.Models.CaaRecord" Usage="new Microsoft.Azure.Management.Dns.Models.CaaRecord (flags, tag, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="flags" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="flags"><span data-ttu-id="c4d09-103">Die Flags für diesen Datensatz CAA als ganze Zahl zwischen 0 und 255.</span><span class="sxs-lookup"><span data-stu-id="c4d09-103">The flags for this CAA record as an integer between 0 and 255.</span></span></param>
        <param name="tag"><span data-ttu-id="c4d09-104">Das Tag für diesen Datensatz CAA.</span><span class="sxs-lookup"><span data-stu-id="c4d09-104">The tag for this CAA record.</span></span></param>
        <param name="value"><span data-ttu-id="c4d09-105">Der Wert für diesen Datensatz CAA.</span><span class="sxs-lookup"><span data-stu-id="c4d09-105">The value for this CAA record.</span></span></param>
        <summary>
            <span data-ttu-id="c4d09-106">Initialisiert eine neue Instanz der CaaRecord-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4d09-106">Initializes a new instance of the CaaRecord class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Flags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Flags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.CaaRecord.Flags" />
      <MemberSignature Language="VB.NET" Value="Public Property Flags As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Flags : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Models.CaaRecord.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="flags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d09-107">Ruft ab oder legt die Flags für diesen Datensatz CAA als ganze Zahl zwischen 0 und 255.</span><span class="sxs-lookup"><span data-stu-id="c4d09-107">Gets or sets the flags for this CAA record as an integer between 0 and 255.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tag">
      <MemberSignature Language="C#" Value="public string Tag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.CaaRecord.Tag" />
      <MemberSignature Language="VB.NET" Value="Public Property Tag As String" />
      <MemberSignature Language="F#" Value="member this.Tag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Models.CaaRecord.Tag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d09-108">Ruft ab oder legt das Tag für diesen Datensatz CAA.</span><span class="sxs-lookup"><span data-stu-id="c4d09-108">Gets or sets the tag for this CAA record.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.CaaRecord.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Dns.Models.CaaRecord.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d09-109">Ruft ab oder legt den Wert für diesen Datensatz CAA fest.</span><span class="sxs-lookup"><span data-stu-id="c4d09-109">Gets or sets the value for this CAA record.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>