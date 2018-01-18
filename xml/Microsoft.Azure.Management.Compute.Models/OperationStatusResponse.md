<Type Name="OperationStatusResponse" FullName="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse">
  <TypeSignature Language="C#" Value="public class OperationStatusResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationStatusResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationStatusResponse" />
  <TypeSignature Language="F#" Value="type OperationStatusResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68d7c-101">Vorgangsantwort-status</span><span class="sxs-lookup"><span data-stu-id="68d7c-101">Operation status response</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="68d7c-102">Initialisiert eine neue Instanz der OperationStatusResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68d7c-102">Initializes a new instance of the OperationStatusResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusResponse (string name = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Management.Compute.Models.ApiError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Management.Compute.Models.ApiError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.Compute.Models.ApiError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional error As ApiError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.OperationStatusResponse : string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Compute.Models.ApiError -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="new Microsoft.Azure.Management.Compute.Models.OperationStatusResponse (name, status, startTime, endTime, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Compute.Models.ApiError" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="68d7c-103">Vorgangs-ID</span><span class="sxs-lookup"><span data-stu-id="68d7c-103">Operation ID</span></span></param>
        <param name="status"><span data-ttu-id="68d7c-104">Vorgangsstatus</span><span class="sxs-lookup"><span data-stu-id="68d7c-104">Operation status</span></span></param>
        <param name="startTime"><span data-ttu-id="68d7c-105">Startzeit des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="68d7c-105">Start time of the operation</span></span></param>
        <param name="endTime"><span data-ttu-id="68d7c-106">Die Endzeit des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="68d7c-106">End time of the operation</span></span></param>
        <param name="error"><span data-ttu-id="68d7c-107">API-Fehler</span><span class="sxs-lookup"><span data-stu-id="68d7c-107">Api error</span></span></param>
        <summary>
            <span data-ttu-id="68d7c-108">Initialisiert eine neue Instanz der OperationStatusResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="68d7c-108">Initializes a new instance of the OperationStatusResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68d7c-109">Ruft die Endzeit des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="68d7c-109">Gets end time of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ApiError Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ApiError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As ApiError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Compute.Models.ApiError" Usage="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ApiError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68d7c-110">Ruft die API-Fehler</span><span class="sxs-lookup"><span data-stu-id="68d7c-110">Gets api error</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="68d7c-111">Ruft die Vorgangs-ID ab</span><span class="sxs-lookup"><span data-stu-id="68d7c-111">Gets operation ID</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68d7c-112">Ruft die Startzeit des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="68d7c-112">Gets start time of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Compute.Models.OperationStatusResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68d7c-113">Ruft die Vorgangsstatus ab</span><span class="sxs-lookup"><span data-stu-id="68d7c-113">Gets operation status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>