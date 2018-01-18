<Type Name="CatalogItem" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem">
  <TypeSignature Language="C#" Value="public class CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CatalogItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="VB.NET" Value="Public Class CatalogItem" />
  <TypeSignature Language="F#" Value="type CatalogItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2ed6-101">Ein Data Lake Analytics-Katalogelement.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-101">A Data Lake Analytics catalog item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CatalogItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a2ed6-102">Initialisiert eine neue Instanz der CatalogItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-102">Initializes a new instance of the CatalogItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CatalogItem (string computeAccountName = null, Nullable&lt;Guid&gt; version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.#ctor(System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem : string * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem (computeAccountName, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="a2ed6-103">der Name des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="a2ed6-104">die Version des Katalogelements.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-104">the version of the catalog item.</span></span></param>
        <summary>
            <span data-ttu-id="a2ed6-105">Initialisiert eine neue Instanz der CatalogItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-105">Initializes a new instance of the CatalogItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeAccountName">
      <MemberSignature Language="C#" Value="public string ComputeAccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputeAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.ComputeAccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeAccountName As String" />
      <MemberSignature Language="F#" Value="member this.ComputeAccountName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.ComputeAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computeAccountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2ed6-106">Ruft ab oder legt den Namen des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-106">Gets or sets the name of the Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.Version : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2ed6-107">Ruft ab oder legt die Version des Katalogelements.</span><span class="sxs-lookup"><span data-stu-id="a2ed6-107">Gets or sets the version of the catalog item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>