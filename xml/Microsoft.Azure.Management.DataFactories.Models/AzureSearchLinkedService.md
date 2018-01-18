<Type Name="AzureSearchLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService">
  <TypeSignature Language="C#" Value="public class AzureSearchLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSearchLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSearchLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureSearchLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureSearch")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a6098-101">Verknüpften Dienst für einen Azure Search-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a6098-101">Linked service for an Azure Search service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSearchLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6098-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6098-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSearchLinkedService (string url, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, key As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService (url, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">To be added.</param>
        <param name="key">To be added.</param>
        <summary>
            <span data-ttu-id="a6098-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="a6098-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6098-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6098-104">Required.</span></span> <span data-ttu-id="a6098-105">Der Administratorschlüssel des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="a6098-105">The admin key of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6098-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="a6098-106">Required.</span></span> <span data-ttu-id="a6098-107">Die URL des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="a6098-107">The URL of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>