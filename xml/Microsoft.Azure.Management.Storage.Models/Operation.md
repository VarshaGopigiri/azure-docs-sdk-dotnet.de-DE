<Type Name="Operation" FullName="Microsoft.Azure.Management.Storage.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0afaf-101">Vorgangsdefinition Speicher-REST-API.</span><span class="sxs-lookup"><span data-stu-id="0afaf-101">Storage REST API operation definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0afaf-102">Initialisiert eine neue Instanz der Klasse Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="0afaf-102">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.Storage.Models.OperationDisplay display = null, string origin = null, Microsoft.Azure.Management.Storage.Models.ServiceSpecification serviceSpecification = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Storage.Models.OperationDisplay display, string origin, class Microsoft.Azure.Management.Storage.Models.ServiceSpecification serviceSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.Storage.Models.OperationDisplay,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Operation : string * Microsoft.Azure.Management.Storage.Models.OperationDisplay * string * Microsoft.Azure.Management.Storage.Models.ServiceSpecification -&gt; Microsoft.Azure.Management.Storage.Models.Operation" Usage="new Microsoft.Azure.Management.Storage.Models.Operation (name, display, origin, serviceSpecification)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.Storage.Models.OperationDisplay" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="serviceSpecification" Type="Microsoft.Azure.Management.Storage.Models.ServiceSpecification" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0afaf-103">Vorgangsname: {Anbieter} / {Resource} / {Operation}</span><span class="sxs-lookup"><span data-stu-id="0afaf-103">Operation name: {provider}/{resource}/{operation}</span></span></param>
        <param name="display"><span data-ttu-id="0afaf-104">Anzeigen von Metadaten, die dem Vorgang zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0afaf-104">Display metadata associated with the operation.</span></span></param>
        <param name="origin"><span data-ttu-id="0afaf-105">Der Ursprung der Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="0afaf-105">The origin of operations.</span></span></param>
        <param name="serviceSpecification"><span data-ttu-id="0afaf-106">Eine Eigenschaft des Vorgangs enthalten metrische Spezifikationen.</span><span class="sxs-lookup"><span data-stu-id="0afaf-106">One property of operation, include metric specifications.</span></span></param>
        <summary>
            <span data-ttu-id="0afaf-107">Initialisiert eine neue Instanz der Klasse Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="0afaf-107">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.OperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.OperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.Storage.Models.OperationDisplay with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.OperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0afaf-108">Ruft ab, oder legt ihn fest Metadaten anzeigen, die dem Vorgang zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0afaf-108">Gets or sets display metadata associated with the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="0afaf-109">Ruft ab oder legt ihn fest Vorgangsname: {Anbieter} / {Resource} / {Operation}</span><span class="sxs-lookup"><span data-stu-id="0afaf-109">Gets or sets operation name: {provider}/{resource}/{operation}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Operation.Origin" />
      <MemberSignature Language="VB.NET" Value="Public Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Operation.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0afaf-110">Ruft ab oder legt den Ursprung der Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="0afaf-110">Gets or sets the origin of operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.ServiceSpecification ServiceSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.ServiceSpecification ServiceSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Operation.ServiceSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceSpecification As ServiceSpecification" />
      <MemberSignature Language="F#" Value="member this.ServiceSpecification : Microsoft.Azure.Management.Storage.Models.ServiceSpecification with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Operation.ServiceSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ServiceSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0afaf-111">Ruft ab oder legt eine Eigenschaft des Vorgangs, enthalten Sie metrische Spezifikationen.</span><span class="sxs-lookup"><span data-stu-id="0afaf-111">Gets or sets one property of operation, include metric specifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>