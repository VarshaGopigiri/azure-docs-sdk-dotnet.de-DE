<Type Name="SkuInfo" FullName="Microsoft.Azure.Management.WebSites.Models.SkuInfo">
  <TypeSignature Language="C#" Value="public class SkuInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SkuInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SkuInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class SkuInfo" />
  <TypeSignature Language="F#" Value="type SkuInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c104f-101">Ermittlungsinformationen für SKU.</span><span class="sxs-lookup"><span data-stu-id="c104f-101">SKU discovery information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c104f-102">Initialisiert eine neue Instanz der SkuInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c104f-102">Initializes a new instance of the SkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuInfo (string resourceType = null, Microsoft.Azure.Management.WebSites.Models.SkuDescription sku = null, Microsoft.Azure.Management.WebSites.Models.SkuCapacity capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class Microsoft.Azure.Management.WebSites.Models.SkuDescription sku, class Microsoft.Azure.Management.WebSites.Models.SkuCapacity capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuInfo.#ctor(System.String,Microsoft.Azure.Management.WebSites.Models.SkuDescription,Microsoft.Azure.Management.WebSites.Models.SkuCapacity)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional sku As SkuDescription = null, Optional capacity As SkuCapacity = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SkuInfo : string * Microsoft.Azure.Management.WebSites.Models.SkuDescription * Microsoft.Azure.Management.WebSites.Models.SkuCapacity -&gt; Microsoft.Azure.Management.WebSites.Models.SkuInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.SkuInfo (resourceType, sku, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.WebSites.Models.SkuCapacity" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="c104f-103">Der Ressourcentyp, die dieser SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="c104f-103">Resource type that this SKU applies to.</span></span></param>
        <param name="sku"><span data-ttu-id="c104f-104">Der Name und die Ebene der SKU.</span><span class="sxs-lookup"><span data-stu-id="c104f-104">Name and tier of the SKU.</span></span></param>
        <param name="capacity"><span data-ttu-id="c104f-105">Min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c104f-105">Min, max, and default scale values of the SKU.</span></span></param>
        <summary>
            <span data-ttu-id="c104f-106">Initialisiert eine neue Instanz der SkuInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c104f-106">Initializes a new instance of the SkuInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As SkuCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.WebSites.Models.SkuCapacity with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c104f-107">Ruft ab, oder legt sie fest, min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c104f-107">Gets or sets min, max, and default scale values of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c104f-108">Ruft ab, oder legt ihn fest Ressourcentyp, der dieser SKU gilt.</span><span class="sxs-lookup"><span data-stu-id="c104f-108">Gets or sets resource type that this SKU applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuInfo.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.WebSites.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuInfo.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c104f-109">Ruft ab, oder legt sie fest, Name und der SKU-Ebene.</span><span class="sxs-lookup"><span data-stu-id="c104f-109">Gets or sets name and tier of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>