<Type Name="DeploymentOperation" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation">
  <TypeSignature Language="C#" Value="public class DeploymentOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentOperation" />
  <TypeSignature Language="F#" Value="type DeploymentOperation = class" />
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
            <span data-ttu-id="3925b-101">Bereitstellungsvorgangsinformationen.</span><span class="sxs-lookup"><span data-stu-id="3925b-101">Deployment operation information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3925b-102">Initialisiert eine neue Instanz der "deploymentoperation"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3925b-102">Initializes a new instance of the DeploymentOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperation (string id = null, string operationId = null, Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string operationId, class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional operationId As String = null, Optional properties As DeploymentOperationProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation : string * string * Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation (id, operationId, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3925b-103">Vollständige Bereitstellung Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="3925b-103">Full deployment operation ID.</span></span></param>
        <param name="operationId"><span data-ttu-id="3925b-104">Bereitstellung Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="3925b-104">Deployment operation ID.</span></span></param>
        <param name="properties"><span data-ttu-id="3925b-105">Bereitstellungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="3925b-105">Deployment properties.</span></span></param>
        <summary>
            <span data-ttu-id="3925b-106">Initialisiert eine neue Instanz der "deploymentoperation"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3925b-106">Initializes a new instance of the DeploymentOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3925b-107">Ruft vollständige Bereitstellung Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="3925b-107">Gets full deployment operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3925b-108">Ruft die Bereitstellung Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="3925b-108">Gets deployment operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeploymentOperationProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperationProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3925b-109">Ruft ab, oder legt Sie Bereitstellungseigenschaften fest.</span><span class="sxs-lookup"><span data-stu-id="3925b-109">Gets or sets deployment properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>