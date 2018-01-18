<Type Name="TroubleshootingResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner">
  <TypeSignature Language="C#" Value="public class TroubleshootingResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TroubleshootingResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TroubleshootingResultInner" />
  <TypeSignature Language="F#" Value="type TroubleshootingResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6920e-101">Informationen zur Problembehandlung gewonnenen Erkenntnisse aus der angegebenen Ressource.</span><span class="sxs-lookup"><span data-stu-id="6920e-101">Troubleshooting information gained from specified resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6920e-102">Initialisiert eine neue Instanz der TroubleshootingResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6920e-102">Initializes a new instance of the TroubleshootingResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingResultInner (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string code = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; results = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string code, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; results) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional code As String = null, Optional results As IList(Of TroubleshootingDetails) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner (startTime, endTime, code, results)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="results" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="6920e-103">Die Startzeit für die Problembehandlung.</span><span class="sxs-lookup"><span data-stu-id="6920e-103">The start time of the troubleshooting.</span></span></param>
        <param name="endTime"><span data-ttu-id="6920e-104">Die Endzeit der Fehlerbehebung.</span><span class="sxs-lookup"><span data-stu-id="6920e-104">The end time of the troubleshooting.</span></span></param>
        <param name="code"><span data-ttu-id="6920e-105">Der Ergebniscode der Fehlerbehebung.</span><span class="sxs-lookup"><span data-stu-id="6920e-105">The result code of the troubleshooting.</span></span></param>
        <param name="results"><span data-ttu-id="6920e-106">Informationen zur Problembehandlung.</span><span class="sxs-lookup"><span data-stu-id="6920e-106">Information from troubleshooting.</span></span></param>
        <summary>
            <span data-ttu-id="6920e-107">Initialisiert eine neue Instanz der TroubleshootingResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6920e-107">Initializes a new instance of the TroubleshootingResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6920e-108">Abrufen oder festlegen den Ergebniscode der Fehlerbehebung.</span><span class="sxs-lookup"><span data-stu-id="6920e-108">Gets or sets the result code of the troubleshooting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6920e-109">Ruft ab oder legt die Endzeit der Fehlerbehebung.</span><span class="sxs-lookup"><span data-stu-id="6920e-109">Gets or sets the end time of the troubleshooting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of TroubleshootingDetails)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="results")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6920e-110">Abrufen oder Festlegen der Informationen zur Problembehandlung.</span><span class="sxs-lookup"><span data-stu-id="6920e-110">Gets or sets information from troubleshooting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TroubleshootingResultInner.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="6920e-111">Ruft ab oder legt die Startzeit für die Problembehandlung.</span><span class="sxs-lookup"><span data-stu-id="6920e-111">Gets or sets the start time of the troubleshooting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>