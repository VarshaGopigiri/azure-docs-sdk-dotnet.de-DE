<Type Name="GenericRecoveryPoint" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint">
  <TypeSignature Language="C#" Value="public class GenericRecoveryPoint : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GenericRecoveryPoint extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint" />
  <TypeSignature Language="VB.NET" Value="Public Class GenericRecoveryPoint&#xA;Inherits RecoveryPoint" />
  <TypeSignature Language="F#" Value="type GenericRecoveryPoint = class&#xA;    inherit RecoveryPoint" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPoint</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d194-101">Generische Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="9d194-101">Generic backup copy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericRecoveryPoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d194-102">Initialisiert eine neue Instanz der GenericRecoveryPoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d194-102">Initializes a new instance of the GenericRecoveryPoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GenericRecoveryPoint (string friendlyName = null, string recoveryPointType = null, Nullable&lt;DateTime&gt; recoveryPointTime = null, string recoveryPointAdditionalInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string recoveryPointType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; recoveryPointTime, string recoveryPointAdditionalInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional recoveryPointType As String = null, Optional recoveryPointTime As Nullable(Of DateTime) = null, Optional recoveryPointAdditionalInfo As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint : string * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint (friendlyName, recoveryPointType, recoveryPointTime, recoveryPointAdditionalInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="recoveryPointType" Type="System.String" />
        <Parameter Name="recoveryPointTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryPointAdditionalInfo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="9d194-103">Anzeigename der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="9d194-103">Friendly name of the backup copy.</span></span></param>
        <param name="recoveryPointType"><span data-ttu-id="9d194-104">Der Typ der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="9d194-104">Type of the backup copy.</span></span></param>
        <param name="recoveryPointTime"><span data-ttu-id="9d194-105">Zeitpunkt, zu dem dieser Sicherungskopie erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9d194-105">Time at which this backup copy was created.</span></span></param>
        <param name="recoveryPointAdditionalInfo"><span data-ttu-id="9d194-106">Zusätzliche Informationen, die dieser Sicherungskopie zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="9d194-106">Additional information associated with this backup copy.</span></span></param>
        <summary>
            <span data-ttu-id="9d194-107">Initialisiert eine neue Instanz der GenericRecoveryPoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d194-107">Initializes a new instance of the GenericRecoveryPoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d194-108">Ruft ab, oder legt ihn fest Anzeigenamen der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="9d194-108">Gets or sets friendly name of the backup copy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointAdditionalInfo">
      <MemberSignature Language="C#" Value="public string RecoveryPointAdditionalInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointAdditionalInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointAdditionalInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointAdditionalInfo As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointAdditionalInfo : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointAdditionalInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointAdditionalInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d194-109">Ermittelt oder definiert zusätzlichen Informationen, die mit dieser Sicherungskopie verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="9d194-109">Gets or sets additional information associated with this backup copy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RecoveryPointTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RecoveryPointTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d194-110">Abrufen oder Festlegen der Zeitpunkt, zu dem dieser Sicherungskopie erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9d194-110">Gets or sets time at which this backup copy was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointType">
      <MemberSignature Language="C#" Value="public string RecoveryPointType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointType As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.GenericRecoveryPoint.RecoveryPointType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d194-111">Ruft ab oder legt ihn fest die Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="9d194-111">Gets or sets type of the backup copy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>