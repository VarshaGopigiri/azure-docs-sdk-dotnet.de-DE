<Type Name="EdgeNode" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode">
  <TypeSignature Language="C#" Value="public class EdgeNode : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EdgeNode extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class EdgeNode&#xA;Inherits Wrapper(Of EdgeNodeInner)" />
  <TypeSignature Language="F#" Value="type EdgeNode = class&#xA;    inherit Wrapper&lt;EdgeNodeInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd0aa-101">Edge-Knoten des CDN-Diensts.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-101">Edge node of CDN service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EdgeNode (Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.#ctor(Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inner As EdgeNodeInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode : Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode inner" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNodeInner" />
      </Parameters>
      <Docs>
        <param name="inner">To be added.</param>
        <summary>
            <span data-ttu-id="dd0aa-102">Initialisiert eine neue Instanz der EdgeNodeInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-102">Initializes a new instance of the EdgeNodeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-103">Ruft ab, oder legt ihn fest Edge Knoten Ressourcen-ID-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-103">Gets or sets Edge node resource ID string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup&gt; IpAddressGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup&gt; IpAddressGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.IpAddressGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpAddressGroups As IList(Of IpAddressGroup)" />
      <MemberSignature Language="F#" Value="member this.IpAddressGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.IpAddressGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.IpAddressGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-104">Ruft ab oder legt die Liste der IP-Adressgruppen.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-104">Gets or sets list of ip address groups.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-105">Ruft ab, oder legt ihn fest Standortzeichenfolge für Edge-Knoten.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-105">Gets or sets Edge node location string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-106">Ruft ab, oder legt ihn fest Edge Knoten Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-106">Gets or sets Edge node resource name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-107">Ruft ab, oder legt ihn fest Standortzeichenfolge für Edge-Knoten.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-107">Gets or sets Edge node location string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.EdgeNode.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd0aa-108">Ruft ab, oder legt ihn fest Typzeichenfolge für Edge-Knoten.</span><span class="sxs-lookup"><span data-stu-id="dd0aa-108">Gets or sets Edge node type string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>