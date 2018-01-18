<Type Name="AliasPathType" FullName="Microsoft.Azure.Management.ResourceManager.Models.AliasPathType">
  <TypeSignature Language="C#" Value="public class AliasPathType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AliasPathType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.AliasPathType" />
  <TypeSignature Language="VB.NET" Value="Public Class AliasPathType" />
  <TypeSignature Language="F#" Value="type AliasPathType = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf545-101">Der Typ der Pfade für Alias.</span><span class="sxs-lookup"><span data-stu-id="bf545-101">The type of the paths for alias.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AliasPathType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf545-102">Initialisiert eine neue Instanz der AliasPathType-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf545-102">Initializes a new instance of the AliasPathType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AliasPathType (string path = null, System.Collections.Generic.IList&lt;string&gt; apiVersions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path, class System.Collections.Generic.IList`1&lt;string&gt; apiVersions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional path As String = null, Optional apiVersions As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.AliasPathType : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.AliasPathType" Usage="new Microsoft.Azure.Management.ResourceManager.Models.AliasPathType (path, apiVersions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="apiVersions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="bf545-103">Der Pfad eines Alias.</span><span class="sxs-lookup"><span data-stu-id="bf545-103">The path of an alias.</span></span></param>
        <param name="apiVersions"><span data-ttu-id="bf545-104">Die API-Versionen.</span><span class="sxs-lookup"><span data-stu-id="bf545-104">The API versions.</span></span></param>
        <summary>
            <span data-ttu-id="bf545-105">Initialisiert eine neue Instanz der AliasPathType-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf545-105">Initializes a new instance of the AliasPathType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApiVersions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApiVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.ApiVersions" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiVersions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApiVersions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.ApiVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="apiVersions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf545-106">Ruft ab oder legt die API-Versionen.</span><span class="sxs-lookup"><span data-stu-id="bf545-106">Gets or sets the API versions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.AliasPathType.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf545-107">Ruft ab oder legt den Pfad eines Alias fest.</span><span class="sxs-lookup"><span data-stu-id="bf545-107">Gets or sets the path of an alias.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>