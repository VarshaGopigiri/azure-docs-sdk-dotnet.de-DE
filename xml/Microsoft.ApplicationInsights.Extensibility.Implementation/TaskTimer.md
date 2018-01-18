<Type Name="TaskTimer" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer">
  <TypeSignature Language="C#" Value="public class TaskTimer : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskTimer extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskTimer&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TaskTimer = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("This class will be removed in the next major version. Application Insights base library wouldn't provide this functionality any longer.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6e5e4-101">Führt eine Aufgabe aus, nachdem eine bestimmte verzögert, und melden Sie alle Fehler.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-101">Runs a task after a certain delay and log any error.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskTimer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public void Cancel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Cancel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Cancel" />
      <MemberSignature Language="VB.NET" Value="Public Sub Cancel ()" />
      <MemberSignature Language="F#" Value="member this.Cancel : unit -&gt; unit" Usage="taskTimer.Cancel " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e5e4-102">Bricht den aktuellen Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-102">Cancels the current task.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public TimeSpan Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Delay : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e5e4-103">Ruft ab oder legt die Verzögerung, bevor der Task beginnt.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-103">Gets or sets the delay before the task starts.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="taskTimer.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e5e4-104">Nicht verwaltete und optional verwaltete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-104">Releases unmanaged and - optionally - managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfiniteTimeSpan">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan InfiniteTimeSpan;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan InfiniteTimeSpan" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.InfiniteTimeSpan" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InfiniteTimeSpan As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable InfiniteTimeSpan : TimeSpan" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.InfiniteTimeSpan" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e5e4-105">Stellt eine unendliche Zeitspanne dar.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-105">Represents an infinite time span.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStarted">
      <MemberSignature Language="C#" Value="public bool IsStarted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.IsStarted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsStarted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStarted : bool" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.IsStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e5e4-106">Ruft einen Wert, der angibt, ob der Wert, der angibt, ob eine Aufgabe bereits begonnen wurde.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-106">Gets a value indicating whether value that indicates if a task has already started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start (Func&lt;System.Threading.Tasks.Task&gt; elapsed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Start(class System.Func`1&lt;class System.Threading.Tasks.Task&gt; elapsed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TaskTimer.Start(System.Func{System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start (elapsed As Func(Of Task))" />
      <MemberSignature Language="F#" Value="member this.Start : Func&lt;System.Threading.Tasks.Task&gt; -&gt; unit" Usage="taskTimer.Start elapsed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elapsed" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="elapsed"><span data-ttu-id="6e5e4-107">Der Task ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-107">The task to run.</span></span></param>
        <summary>
            <span data-ttu-id="6e5e4-108">Starten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6e5e4-108">Start the task.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>