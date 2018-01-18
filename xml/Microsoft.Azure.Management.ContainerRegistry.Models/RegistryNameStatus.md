<Type Name="RegistryNameStatus" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus">
  <TypeSignature Language="C#" Value="public class RegistryNameStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryNameStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryNameStatus" />
  <TypeSignature Language="F#" Value="type RegistryNameStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e68e6-101">Das Ergebnis einer Anforderung an die Verfügbarkeit des Namens eines Container-Registrierung zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="e68e6-101">The result of a request to check the availability of a container registry name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryNameStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e68e6-102">Initialisiert eine neue Instanz der RegistryNameStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e68e6-102">Initializes a new instance of the RegistryNameStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryNameStatus (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable"><span data-ttu-id="e68e6-103">Der Wert, der angibt, ob der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-103">The value that indicates whether the name is available.</span></span></param>
        <param name="reason"><span data-ttu-id="e68e6-104">Sofern vorhanden, die Ursache, die der Namen nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-104">If any, the reason that the name is not available.</span></span></param>
        <param name="message"><span data-ttu-id="e68e6-105">Sofern vorhanden, enthält die Fehlermeldung, die weitere Details für den Grund an, dem der Namen nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-105">If any, the error message that provides more detail for the reason that the name is not available.</span></span></param>
        <summary>
            <span data-ttu-id="e68e6-106">Initialisiert eine neue Instanz der RegistryNameStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e68e6-106">Initializes a new instance of the RegistryNameStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e68e6-107">Ruft ab oder legt sie fest, sofern vorhanden, die Fehlermeldung, die weitere Details für den Grund bereitstellt, die der Namen nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-107">Gets or sets if any, the error message that provides more detail for the reason that the name is not available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e68e6-108">Ruft ab oder legt den Wert, der angibt, ob der Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-108">Gets or sets the value that indicates whether the name is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryNameStatus.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e68e6-109">Ruft ab oder legt sie fest, sofern vorhanden, die Ursache, die der Namen nicht verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e68e6-109">Gets or sets if any, the reason that the name is not available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>