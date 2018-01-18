<Type Name="RecurrenceSchedule" FullName="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule">
  <TypeSignature Language="C#" Value="public class RecurrenceSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecurrenceSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecurrenceSchedule" />
  <TypeSignature Language="F#" Value="type RecurrenceSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a39e-101">Die Wiederholung des Zeitplans.</span><span class="sxs-lookup"><span data-stu-id="0a39e-101">The recurrence schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrenceSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-102">Initialisiert eine neue Instanz der RecurrenceSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0a39e-102">Initializes a new instance of the RecurrenceSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrenceSchedule (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; minutes = null, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; hours = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; weekDays = null, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; monthDays = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; monthlyOccurrences = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; minutes, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; hours, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; weekDays, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; monthDays, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; monthlyOccurrences) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Collections.Generic.IList{System.Nullable{System.Int32}},System.Collections.Generic.IList{System.Nullable{System.Int32}},System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek}},System.Collections.Generic.IList{System.Nullable{System.Int32}},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional minutes As IList(Of Nullable(Of Integer)) = null, Optional hours As IList(Of Nullable(Of Integer)) = null, Optional weekDays As IList(Of Nullable(Of DaysOfWeek)) = null, Optional monthDays As IList(Of Nullable(Of Integer)) = null, Optional monthlyOccurrences As IList(Of RecurrenceScheduleOccurrence) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule : System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule" Usage="new Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule (additionalProperties, minutes, hours, weekDays, monthDays, monthlyOccurrences)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="minutes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
        <Parameter Name="hours" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
        <Parameter Name="weekDays" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt;" />
        <Parameter Name="monthDays" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
        <Parameter Name="monthlyOccurrences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="0a39e-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="0a39e-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="minutes"><span data-ttu-id="0a39e-104">Die Minuten.</span><span class="sxs-lookup"><span data-stu-id="0a39e-104">The minutes.</span></span></param>
        <param name="hours"><span data-ttu-id="0a39e-105">Die Stunden.</span><span class="sxs-lookup"><span data-stu-id="0a39e-105">The hours.</span></span></param>
        <param name="weekDays"><span data-ttu-id="0a39e-106">Die Tage der Woche.</span><span class="sxs-lookup"><span data-stu-id="0a39e-106">The days of the week.</span></span></param>
        <param name="monthDays"><span data-ttu-id="0a39e-107">Die Tage des Monats.</span><span class="sxs-lookup"><span data-stu-id="0a39e-107">The month days.</span></span></param>
        <param name="monthlyOccurrences"><span data-ttu-id="0a39e-108">Das monatlichen vorkommen.</span><span class="sxs-lookup"><span data-stu-id="0a39e-108">The monthly occurrences.</span></span></param>
        <summary>
            <span data-ttu-id="0a39e-109">Initialisiert eine neue Instanz der RecurrenceSchedule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0a39e-109">Initializes a new instance of the RecurrenceSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-110">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="0a39e-110">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hours">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Hours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Hours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.Hours" />
      <MemberSignature Language="VB.NET" Value="Public Property Hours As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Hours : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.Hours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-111">Ruft ab oder legt die Stunden.</span><span class="sxs-lookup"><span data-stu-id="0a39e-111">Gets or sets the hours.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minutes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Minutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Minutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.Minutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Minutes As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Minutes : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.Minutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-112">Ruft ab oder legt die Minuten.</span><span class="sxs-lookup"><span data-stu-id="0a39e-112">Gets or sets the minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; MonthDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; MonthDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.MonthDays" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthDays As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.MonthDays : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.MonthDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="monthDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-113">Ruft ab oder legt die Tage des Monats.</span><span class="sxs-lookup"><span data-stu-id="0a39e-113">Gets or sets the month days.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonthlyOccurrences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; MonthlyOccurrences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; MonthlyOccurrences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.MonthlyOccurrences" />
      <MemberSignature Language="VB.NET" Value="Public Property MonthlyOccurrences As IList(Of RecurrenceScheduleOccurrence)" />
      <MemberSignature Language="F#" Value="member this.MonthlyOccurrences : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.MonthlyOccurrences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="monthlyOccurrences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-114">Ruft ab oder legt das monatlichen vorkommen.</span><span class="sxs-lookup"><span data-stu-id="0a39e-114">Gets or sets the monthly occurrences.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WeekDays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; WeekDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; WeekDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.WeekDays" />
      <MemberSignature Language="VB.NET" Value="Public Property WeekDays As IList(Of Nullable(Of DaysOfWeek))" />
      <MemberSignature Language="F#" Value="member this.WeekDays : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceSchedule.WeekDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weekDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DaysOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a39e-115">Ruft ab, oder die Tage der Woche festgelegt.</span><span class="sxs-lookup"><span data-stu-id="0a39e-115">Gets or sets the days of the week.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>