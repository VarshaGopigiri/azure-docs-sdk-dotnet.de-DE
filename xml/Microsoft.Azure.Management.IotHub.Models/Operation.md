<Type Name="Operation" FullName="Microsoft.Azure.Management.IotHub.Models.Operation">
  <TypeSignature Language="C#" Value="public class Operation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Operation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.Operation" />
  <TypeSignature Language="VB.NET" Value="Public Class Operation" />
  <TypeSignature Language="F#" Value="type Operation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fbede-101">IoT Hub-REST-API-Vorgang</span><span class="sxs-lookup"><span data-stu-id="fbede-101">IoT Hub REST API operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.Operation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fbede-102">Initialisiert eine neue Instanz der Klasse Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="fbede-102">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Operation (string name = null, Microsoft.Azure.Management.IotHub.Models.OperationDisplay display = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.IotHub.Models.OperationDisplay display) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.Operation.#ctor(System.String,Microsoft.Azure.Management.IotHub.Models.OperationDisplay)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplay = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.Operation : string * Microsoft.Azure.Management.IotHub.Models.OperationDisplay -&gt; Microsoft.Azure.Management.IotHub.Models.Operation" Usage="new Microsoft.Azure.Management.IotHub.Models.Operation (name, display)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.IotHub.Models.OperationDisplay" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fbede-103">Vorgangsname: {Anbieter} / {Resource} / {Lesen | Schreiben | Aktion | löschen}</span><span class="sxs-lookup"><span data-stu-id="fbede-103">Operation name: {provider}/{resource}/{read | write | action | delete}</span></span></param>
        <param name="display"><span data-ttu-id="fbede-104">Das Objekt, das den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fbede-104">The object that represents the operation.</span></span></param>
        <summary>
            <span data-ttu-id="fbede-105">Initialisiert eine neue Instanz der Klasse Vorgang an.</span><span class="sxs-lookup"><span data-stu-id="fbede-105">Initializes a new instance of the Operation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.OperationDisplay Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.OperationDisplay Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.Operation.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplay" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.IotHub.Models.OperationDisplay with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.Operation.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.OperationDisplay</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fbede-106">Ruft ab oder legt das Objekt, das den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="fbede-106">Gets or sets the object that represents the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.Operation.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.IotHub.Models.Operation.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="fbede-107">Ruft die Vorgangsname: {Anbieter} / {Resource} / {Lesen | Schreiben | Aktion | löschen}</span><span class="sxs-lookup"><span data-stu-id="fbede-107">Gets operation name: {provider}/{resource}/{read | write | action | delete}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>