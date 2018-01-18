<Type Name="JobSpecification" FullName="Microsoft.Azure.Batch.JobSpecification">
  <TypeSignature Language="C#" Value="public class JobSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSpecification" />
  <TypeSignature Language="F#" Value="type JobSpecification = class&#xA;    interface ITransportObjectProvider&lt;JobSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="0276d-101">Die <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" /> von einem <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-101">The <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" /> of a <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification (Microsoft.Azure.Batch.PoolInformation poolInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.PoolInformation poolInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobSpecification.#ctor(Microsoft.Azure.Batch.PoolInformation)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.JobSpecification : Microsoft.Azure.Batch.PoolInformation -&gt; Microsoft.Azure.Batch.JobSpecification" Usage="new Microsoft.Azure.Batch.JobSpecification poolInformation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolInformation" Type="Microsoft.Azure.Batch.PoolInformation" />
      </Parameters>
      <Docs>
        <param name="poolInformation"><span data-ttu-id="0276d-102">Der Pool, auf dem der Batch-Dienst führt die Aufgaben in der erstellten Aufträge über dieses <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-102">The pool on which the Batch service runs the tasks of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span></param>
        <summary>
            <span data-ttu-id="0276d-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.JobSpecification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0276d-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-104">Ruft ab oder legt eine Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="0276d-104">Gets or sets a list of common environment variable settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0276d-105">Diese Umgebungsvariablen festgelegt sind, für alle Aufgaben in den unter diesem erstellten Aufträge <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> (einschließlich der Auftrags-Manager, Auftrag zur Vorbereitung und Auftrag Version).</span><span class="sxs-lookup"><span data-stu-id="0276d-105">These environment variables are set for all tasks in jobs created under this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-106">Ruft ab oder legt die ausführungseinschränkungen für Aufträge, die über diese erstellt <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-106">Gets or sets the execution constraints for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-107">Ruft ab oder legt einen Anzeigenamen für alle Aufträge, die über diese erstellt <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-107">Gets or sets a display name for all jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-108">Ruft ab oder legt Sie die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn ein Auftrag, über dieses erstellt wird <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-108">Gets or sets details of a Job Manager task to be launched when a job is created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-109">Übernimmt oder bestimmt die Aufgabe Auftrag zur Vorbereitung für Aufträge, die über diese erstellt <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-109">Gets or sets the Job Preparation task for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0276d-110">Der Batch-Dienst wird die Auftrag zur Vorbereitung Aufgabe vor dem Starten alle Aufgaben dieses Auftrags auf diesem Computeknoten auf einem Serverknoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="0276d-110">The Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-111">Übernimmt oder bestimmt die Version des Auftrags Aufgabe für Aufträge, die über diese erstellt <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-111">Gets or sets the Job Release task for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0276d-112">Der Batch-Dienst führt den Auftrag Version Task aus, wenn der Auftrag beendet, in dem jede Aufgabe des Auftrags ausgeführt wurde, auf jedem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="0276d-112">The Batch service runs the Job Release task when the job ends, on each compute node where any task of the job has run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-113">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die über dieses erstellten Aufträge zugeordnet <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> als Metadaten.</span><span class="sxs-lookup"><span data-stu-id="0276d-113">Gets or sets a list of name-value pairs associated with jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-114">Ruft ab oder legt fest, die Aktion den Batch, der Dienst abwartet, wenn alle Aufgaben im Auftrag in sind die <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="0276d-114">Gets or sets the action the Batch service should take when all tasks in the job are in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-115">Ruft ab oder legt fest, die Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="0276d-115">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0276d-116">Eine Aufgabe gilt als fehlgeschlagen betrachtet, wenn es mit einem Exitcode ungleich 0 (null) abgeschlossen, und die Wiederholungsanzahl verbraucht hat oder ein Planungsfehler wäre.</span><span class="sxs-lookup"><span data-stu-id="0276d-116">A task is considered to have failed if it completes with a non-zero exit code and has exhausted its retry count, or if it had a scheduling error.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolInformation PoolInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolInformation PoolInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.PoolInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInformation As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInformation : Microsoft.Azure.Batch.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.PoolInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-117">Ruft ab oder legt den Pool, auf dem der Batch-Dienst führt die Aufgaben in der erstellten Aufträge über dieses <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-117">Gets or sets the pool on which the Batch service runs the tasks of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-118">Ruft ab oder legt die Priorität der Aufträge, die über diese erstellt <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span><span class="sxs-lookup"><span data-stu-id="0276d-118">Gets or sets the priority of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="0276d-119">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="0276d-119">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0276d-120">Ruft ab oder legt sie fest, ob die Aufgaben in Aufträgen unter diesem erstellt <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> Definieren der Abhängigkeiten können voneinander abhängig.</span><span class="sxs-lookup"><span data-stu-id="0276d-120">Gets or sets whether tasks in jobs created under this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> can define dependencies on each other.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0276d-121">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="0276d-121">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>