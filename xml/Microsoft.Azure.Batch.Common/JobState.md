<Type Name="JobState" FullName="Microsoft.Azure.Batch.Common.JobState">
  <TypeSignature Language="C#" Value="public enum JobState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobState" />
  <TypeSignature Language="F#" Value="type JobState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="4aa68-101">Den Status des Auftrags</span><span class="sxs-lookup"><span data-stu-id="4aa68-101">The state of job</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.JobState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-102">Der Auftrag wird für geplante Aufgaben sind verfügbar.</span><span class="sxs-lookup"><span data-stu-id="4aa68-102">The job is available to have tasks scheduled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Completed = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 5" Usage="Microsoft.Azure.Batch.Common.JobState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-103">Alle Aufgaben beendet haben, und das System nimmt alle Weitere Aufgaben oder weiteren Änderungen an den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="4aa68-103">All tasks have terminated, and the system will not accept any more tasks or any further changes to the job.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Deleting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 6" Usage="Microsoft.Azure.Batch.Common.JobState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-104">Ein Benutzer hat angefordert, dass der Auftrag gelöscht werden, aber der Löschvorgang ist noch in Bearbeitung (z. B. weil das System dennoch Ausführen von Aufgaben beendet wird).</span><span class="sxs-lookup"><span data-stu-id="4aa68-104">A user has requested that the job be deleted, but the delete operation is still in progress (for example, because the system is still terminating running tasks).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Common.JobState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-105">Ein Benutzer hat den Auftrag deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="4aa68-105">A user has disabled the job.</span></span> <span data-ttu-id="4aa68-106">Keine Aufgaben ausgeführt werden, und werden keine neue Tasks geplant werden.</span><span class="sxs-lookup"><span data-stu-id="4aa68-106">No tasks are running, and no new tasks will be scheduled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabling">
      <MemberSignature Language="C#" Value="Disabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Disabling = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Disabling" />
      <MemberSignature Language="VB.NET" Value="Disabling" />
      <MemberSignature Language="F#" Value="Disabling = 1" Usage="Microsoft.Azure.Batch.Common.JobState.Disabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-107">Ein Benutzer hat angefordert, dass der Auftrag deaktiviert werden, aber der Deaktivierungsvorgang ist noch in Bearbeitung (z. B. beim Warten auf die Aufgaben beendet).</span><span class="sxs-lookup"><span data-stu-id="4aa68-107">A user has requested that the job be disabled, but the disable operation is still in progress (for example, waiting for tasks to terminate).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enabling">
      <MemberSignature Language="C#" Value="Enabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Enabling = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Enabling" />
      <MemberSignature Language="VB.NET" Value="Enabling" />
      <MemberSignature Language="F#" Value="Enabling = 3" Usage="Microsoft.Azure.Batch.Common.JobState.Enabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-108">Ein Benutzer hat angefordert, dass der Auftrag aktiviert werden, aber der Aktivierungsvorgang ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="4aa68-108">A user has requested that the job be enabled, but the enable operation is still in progress.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Terminating = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 4" Usage="Microsoft.Azure.Batch.Common.JobState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aa68-109">Der Auftrag ist zum Abschließen, weil eine Auftrags-Manager-Aufgabe abgeschlossen wurde oder der Benutzer, den Auftrag beendet wurde, aber der Vorgang "Beenden" noch in Bearbeitung wird (z. B. weil der Auftrag Version Aufgaben ausgeführt werden).</span><span class="sxs-lookup"><span data-stu-id="4aa68-109">The job is about to complete, either because a Job Manager task has completed or because the user has terminated the job, but the terminate operation is still in progress (for example, because Job Release tasks are running).</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>