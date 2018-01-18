<Type Name="ScheduleRecurrenceWeekly" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly">
  <TypeSignature Language="C#" Value="public class ScheduleRecurrenceWeekly : Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleRecurrenceWeekly extends Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleRecurrenceWeekly&#xA;Inherits ScheduleRecurrence" />
  <TypeSignature Language="F#" Value="type ScheduleRecurrenceWeekly = class&#xA;    inherit ScheduleRecurrence" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrence</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b2136-101">Wöchentliche Wiederholungszeitplan Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b2136-101">Backup policy weekly recurring schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrenceWeekly ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2136-102">Initialisiert eine neue Instanz der ScheduleRecurrenceWeekly-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b2136-102">Initializes a new instance of the ScheduleRecurrenceWeekly class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrenceWeekly (System.Collections.Generic.List&lt;DayOfWeek&gt; weekDays, Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType recurrenceType, int recurrenceValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;valuetype System.DayOfWeek&gt; weekDays, valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType recurrenceType, int32 recurrenceValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly.#ctor(System.Collections.Generic.List{System.DayOfWeek},Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly : System.Collections.Generic.List&lt;DayOfWeek&gt; * Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType * int -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly (weekDays, recurrenceType, recurrenceValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="weekDays" Type="System.Collections.Generic.List&lt;System.DayOfWeek&gt;" />
        <Parameter Name="recurrenceType" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RecurrenceType" />
        <Parameter Name="recurrenceValue" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="weekDays">To be added.</param>
        <param name="recurrenceType">To be added.</param>
        <param name="recurrenceValue">To be added.</param>
        <summary>
            <span data-ttu-id="b2136-103">Initialisiert eine neue Instanz der ScheduleRecurrenceWeekly-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="b2136-103">Initializes a new instance of the ScheduleRecurrenceWeekly class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WeekDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;DayOfWeek&gt; WeekDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.DayOfWeek&gt; WeekDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly.WeekDays" />
      <MemberSignature Language="VB.NET" Value="Public Property WeekDays As IList(Of DayOfWeek)" />
      <MemberSignature Language="F#" Value="member this.WeekDays : System.Collections.Generic.IList&lt;DayOfWeek&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ScheduleRecurrenceWeekly.WeekDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.DayOfWeek&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2136-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b2136-104">Required.</span></span> <span data-ttu-id="b2136-105">Der Liste Tage die Woche für diese Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="b2136-105">The week days list for this recurrence.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>