<Type Name="ComputeNodeGetRemoteLoginSettingsResult" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult">
  <TypeSignature Language="C#" Value="public class ComputeNodeGetRemoteLoginSettingsResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeGetRemoteLoginSettingsResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeGetRemoteLoginSettingsResult" />
  <TypeSignature Language="F#" Value="type ComputeNodeGetRemoteLoginSettingsResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80649-101">Die remote-Anmelde-Einstellungen für einen Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="80649-101">The remote login settings for a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeGetRemoteLoginSettingsResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80649-102">Initialisiert eine neue Instanz der ComputeNodeGetRemoteLoginSettingsResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="80649-102">Initializes a new instance of the ComputeNodeGetRemoteLoginSettingsResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeGetRemoteLoginSettingsResult (string remoteLoginIPAddress, int remoteLoginPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string remoteLoginIPAddress, int32 remoteLoginPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (remoteLoginIPAddress As String, remoteLoginPort As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult : string * int -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult (remoteLoginIPAddress, remoteLoginPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="remoteLoginIPAddress" Type="System.String" />
        <Parameter Name="remoteLoginPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="remoteLoginIPAddress"><span data-ttu-id="80649-103">Die IP-Adresse für die Remoteanmeldung auf den Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="80649-103">The IP address used for remote login to the compute node.</span></span></param>
        <param name="remoteLoginPort"><span data-ttu-id="80649-104">Der Port für die Remoteanmeldung an den Compute-Knoten verwendet.</span><span class="sxs-lookup"><span data-stu-id="80649-104">The port used for remote login to the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="80649-105">Initialisiert eine neue Instanz der ComputeNodeGetRemoteLoginSettingsResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="80649-105">Initializes a new instance of the ComputeNodeGetRemoteLoginSettingsResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteLoginIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteLoginIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteLoginIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.RemoteLoginIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteLoginIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteLoginIPAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.RemoteLoginIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteLoginIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80649-106">Ruft ab oder legt die IP-Adresse für die Remoteanmeldung auf den Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="80649-106">Gets or sets the IP address used for remote login to the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteLoginPort">
      <MemberSignature Language="C#" Value="public int RemoteLoginPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RemoteLoginPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.RemoteLoginPort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteLoginPort As Integer" />
      <MemberSignature Language="F#" Value="member this.RemoteLoginPort : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.RemoteLoginPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteLoginPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80649-107">Abrufen oder festlegen den Port für die Remoteanmeldung auf den Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="80649-107">Gets or sets the port used for remote login to the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNodeGetRemoteLoginSettingsResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80649-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="80649-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="80649-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="80649-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>