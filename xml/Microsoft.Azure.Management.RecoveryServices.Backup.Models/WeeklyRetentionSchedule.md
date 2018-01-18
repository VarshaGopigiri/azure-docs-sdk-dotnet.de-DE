<Type Name="WeeklyRetentionSchedule" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule">
  <TypeSignature Language="C#" Value="public class WeeklyRetentionSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WeeklyRetentionSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class WeeklyRetentionSchedule" />
  <TypeSignature Language="F#" Value="type WeeklyRetentionSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3ba1b-101">Wöchentlicher Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-101">Weekly retention schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WeeklyRetentionSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ba1b-102">Initialisiert eine neue Instanz der WeeklyRetentionSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-102">Initializes a new instance of the WeeklyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WeeklyRetentionSchedule (System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; daysOfTheWeek = null, System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; retentionTimes = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; daysOfTheWeek, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; retentionTimes, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration retentionDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.#ctor(System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek}},System.Collections.Generic.IList{System.Nullable{System.DateTime}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule (daysOfTheWeek, retentionTimes, retentionDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="daysOfTheWeek" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;" />
        <Parameter Name="retentionTimes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;" />
        <Parameter Name="retentionDuration" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration" />
      </Parameters>
      <Docs>
        <param name="daysOfTheWeek"><span data-ttu-id="3ba1b-103">Liste der Wochentage für wöchentliche Aufbewahrungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-103">List of days of week for weekly retention policy.</span></span></param>
        <param name="retentionTimes"><span data-ttu-id="3ba1b-104">Aufbewahrungsdauer der Aufbewahrungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-104">Retention times of retention policy.</span></span></param>
        <param name="retentionDuration"><span data-ttu-id="3ba1b-105">Die Beibehaltungsdauer der Beibehaltungsdauer Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-105">Retention duration of retention Policy.</span></span></param>
        <summary>
            <span data-ttu-id="3ba1b-106">Initialisiert eine neue Instanz der WeeklyRetentionSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-106">Initializes a new instance of the WeeklyRetentionSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DaysOfTheWeek">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; DaysOfTheWeek { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; DaysOfTheWeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.DaysOfTheWeek" />
      <MemberSignature Language="VB.NET" Value="Public Property DaysOfTheWeek As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.DaysOfTheWeek : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.DaysOfTheWeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="daysOfTheWeek")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ba1b-107">Ruft ab oder legt die Liste der Wochentage für die Aufbewahrungsrichtlinie für die wöchentliche.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-107">Gets or sets list of days of week for weekly retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionDuration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration RetentionDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.RetentionDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionDuration As RetentionDuration" />
      <MemberSignature Language="F#" Value="member this.RetentionDuration : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.RetentionDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ba1b-108">Abrufen oder Festlegen der Beibehaltungsdauer für die Aufbewahrung Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-108">Gets or sets retention duration of retention Policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTimes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; RetentionTimes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype System.DateTime&gt;&gt; RetentionTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.RetentionTimes" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTimes As IList(Of Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="member this.RetentionTimes : System.Collections.Generic.IList&lt;Nullable&lt;DateTime&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WeeklyRetentionSchedule.RetentionTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTimes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.DateTime&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ba1b-109">Abrufen oder Festlegen der Aufbewahrungsdauer der Aufbewahrungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3ba1b-109">Gets or sets retention times of retention policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>