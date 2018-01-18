<Type Name="Schedule" FullName="Microsoft.Azure.Batch.Schedule">
  <TypeSignature Language="C#" Value="public class Schedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Schedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Schedule" />
  <TypeSignature Language="VB.NET" Value="Public Class Schedule" />
  <TypeSignature Language="F#" Value="type Schedule = class&#xA;    interface ITransportObjectProvider&lt;Schedule&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="cbf72-101">Einen Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbf72-101">A schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Schedule.#ctor" />
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
            <span data-ttu-id="cbf72-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Schedule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cbf72-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Schedule" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Schedule.DoNotRunAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunAfter As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunAfter : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Schedule.DoNotRunAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbf72-103">Ermittelt oder definiert die gesamtbetrachtungszeit nach der kein Auftrag unter diesem Zeitplan für Aufträge geplant wird.</span><span class="sxs-lookup"><span data-stu-id="cbf72-103">Gets or sets the wall clock time after which no job will be scheduled under this job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunUntil">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunUntil { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunUntil" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Schedule.DoNotRunUntil" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunUntil As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunUntil : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Schedule.DoNotRunUntil" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbf72-104">Ruft ab oder legt die früheste Uhrzeit an, den erste Auftrag unter diesem Auftragszeitplan planen</span><span class="sxs-lookup"><span data-stu-id="cbf72-104">Gets or sets the earliest wall clock time at which to schedule the first job under this job schedule</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RecurrenceInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RecurrenceInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Schedule.RecurrenceInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Schedule.RecurrenceInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbf72-105">Ruft ab oder legt das Zeitintervall zwischen den Startzeiten von zwei aufeinander folgenden Aufträgen unter der Auftragszeitplan fest.</span><span class="sxs-lookup"><span data-stu-id="cbf72-105">Gets or sets the time interval between the start times of two successive jobs under the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StartWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StartWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Schedule.StartWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property StartWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Schedule.StartWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbf72-106">Ruft ab oder legt die Zeitfenster, in dem ein Auftrag ab dem Zeitpunkt gestartet werden muss, die der Auftragszeitplan zum Planen bereit ist.</span><span class="sxs-lookup"><span data-stu-id="cbf72-106">Gets or sets the window of time within which a job must be started from the time the job schedule is ready to be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>