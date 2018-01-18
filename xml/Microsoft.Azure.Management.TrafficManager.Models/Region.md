<Type Name="Region" FullName="Microsoft.Azure.Management.TrafficManager.Models.Region">
  <TypeSignature Language="C#" Value="public class Region" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Region extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Region" />
  <TypeSignature Language="VB.NET" Value="Public Class Region" />
  <TypeSignature Language="F#" Value="type Region = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1cf88-101">Klasse, die einen Bereich in der geografischen Hierarchie mit der geografischen verkehrsroutingmethode verwendet darstellt.</span><span class="sxs-lookup"><span data-stu-id="1cf88-101">Class representing a region in the Geographic hierarchy used with the Geographic traffic routing method.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Region ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Region.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1cf88-102">Initialisiert eine neue Instanz der Klasse Region an.</span><span class="sxs-lookup"><span data-stu-id="1cf88-102">Initializes a new instance of the Region class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Region (string code = null, string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; regions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Region&gt; regions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Region.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Models.Region})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional name As String = null, Optional regions As IList(Of Region) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Region : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Region" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Region (code, name, regions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="regions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="1cf88-103">Der Code der region</span><span class="sxs-lookup"><span data-stu-id="1cf88-103">The code of the region</span></span></param>
        <param name="name"><span data-ttu-id="1cf88-104">Der Name der region</span><span class="sxs-lookup"><span data-stu-id="1cf88-104">The name of the region</span></span></param>
        <param name="regions"><span data-ttu-id="1cf88-105">Die Liste der Regionen, die unter dieser Region in der geografischen Hierarchie gruppiert sind.</span><span class="sxs-lookup"><span data-stu-id="1cf88-105">The list of Regions grouped under this Region in the Geographic Hierarchy.</span></span></param>
        <summary>
            <span data-ttu-id="1cf88-106">Initialisiert eine neue Instanz der Klasse Region an.</span><span class="sxs-lookup"><span data-stu-id="1cf88-106">Initializes a new instance of the Region class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cf88-107">Ruft ab oder legt den Code für die region</span><span class="sxs-lookup"><span data-stu-id="1cf88-107">Gets or sets the code of the region</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="1cf88-108">Ruft ab oder legt den Namen der region</span><span class="sxs-lookup"><span data-stu-id="1cf88-108">Gets or sets the name of the region</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Regions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; Regions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Region&gt; Regions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Region.Regions" />
      <MemberSignature Language="VB.NET" Value="Public Property Regions As IList(Of Region)" />
      <MemberSignature Language="F#" Value="member this.Regions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Region.Regions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="regions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Region&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cf88-109">Ruft ab oder legt die Liste der Regionen, die unter dieser Region in der geografischen Hierarchie gruppiert sind.</span><span class="sxs-lookup"><span data-stu-id="1cf88-109">Gets or sets the list of Regions grouped under this Region in the Geographic Hierarchy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>