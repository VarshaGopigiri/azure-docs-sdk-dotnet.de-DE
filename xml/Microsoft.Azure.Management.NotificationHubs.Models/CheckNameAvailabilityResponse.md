<Type Name="CheckNameAvailabilityResponse" FullName="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse">
  <TypeSignature Language="C#" Value="public class CheckNameAvailabilityResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckNameAvailabilityResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckNameAvailabilityResponse" />
  <TypeSignature Language="F#" Value="type CheckNameAvailabilityResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f465c-101">Initialisiert eine neue Instanz der CheckNameAvailabilityResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f465c-101">Initializes a new instance of the CheckNameAvailabilityResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckNameAvailabilityResponse (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable"><span data-ttu-id="f465c-102">Überprüft, ob der Name des Namespaces verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="f465c-102">Checks if the namespace name is available</span></span></param>
        <param name="reason"><span data-ttu-id="f465c-103">Gibt die Ursache, aufgrund, die Name des Namespaces nicht verfügbar ist</span><span class="sxs-lookup"><span data-stu-id="f465c-103">States the reason due to which the namespace name is not available</span></span></param>
        <param name="message"><span data-ttu-id="f465c-104">Die Nachricht wird zurückgegeben, wenn für die Verfügbarkeit des Namespacenamens überprüfen</span><span class="sxs-lookup"><span data-stu-id="f465c-104">The messsage returned when checking for namespace name availability</span></span></param>
        <summary>
            <span data-ttu-id="f465c-105">Initialisiert eine neue Instanz der CheckNameAvailabilityResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f465c-105">Initializes a new instance of the CheckNameAvailabilityResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f465c-106">Ruft ab oder legt die Nachricht zurückgegeben, wenn für die Verfügbarkeit des Namespacenamens überprüfen</span><span class="sxs-lookup"><span data-stu-id="f465c-106">Gets or sets the messsage returned when checking for namespace name availability</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="NameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f465c-107">Ruft ab oder legt überprüft, wenn der Name des Namespaces verfügbar ist</span><span class="sxs-lookup"><span data-stu-id="f465c-107">Gets or sets checks if the namespace name is available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f465c-108">Ruft ab oder legt Zustände die Ursache, aufgrund, die Name des Namespaces nicht verfügbar ist</span><span class="sxs-lookup"><span data-stu-id="f465c-108">Gets or sets states the reason due to which the namespace name is not available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>