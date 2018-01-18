<Type Name="SessionHandlerOptions" FullName="Microsoft.Azure.ServiceBus.SessionHandlerOptions">
  <TypeSignature Language="C#" Value="public sealed class SessionHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionHandlerOptions" />
  <TypeSignature Language="F#" Value="type SessionHandlerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="e34ca-101">Bietet Optionen, die zugeordnete Sitzung Datapump Verarbeitung mit <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> und <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />.</span><span class="sxs-lookup"><span data-stu-id="e34ca-101">Provides options associated with session pump processing using <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> and <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionHandlerOptions (Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionHandlerOptions.#ctor(System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionHandlerOptions : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; Microsoft.Azure.ServiceBus.SessionHandlerOptions" Usage="new Microsoft.Azure.ServiceBus.SessionHandlerOptions exceptionReceivedHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionReceivedHandler"><span data-ttu-id="e34ca-102">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="e34ca-102">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="e34ca-103"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="e34ca-103"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary><span data-ttu-id="e34ca-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e34ca-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" /> class.</span></span>
            <span data-ttu-id="e34ca-105">Standardwerte: <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" /> = 2000 <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" /> = "true" <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" /> = 1 Minute <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" /> = 5 Minuten</span><span class="sxs-lookup"><span data-stu-id="e34ca-105">Default Values: <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" /> = 2000 <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" /> = true <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" /> = 1 minute <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" /> = 5 minutes</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e34ca-106">Ruft ab oder legt fest, ob die Option AutoVervollständigen-Funktion den Handler für die Sitzung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e34ca-106">Gets or sets whether the autocomplete option of the session handler is enabled.</span></span></summary>
        <value><span data-ttu-id="e34ca-107">"true", wenn die Option AutoVervollständigen-Funktion den Handler für die Sitzung aktiviert ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="e34ca-107">true if the autocomplete option of the session handler is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; ExceptionReceivedHandler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; ExceptionReceivedHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task)" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedHandler : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt;" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e34ca-108">Tritt auf, wenn eine Ausnahme empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="e34ca-108">Occurs when an exception is received.</span></span> <span data-ttu-id="e34ca-109">Können Sie alle aufgetretenen durch die Sitzung Datapump benachrichtigt zu werden.</span><span class="sxs-lookup"><span data-stu-id="e34ca-109">Enables you to be notified of any errors encountered by the session pump.</span></span>
            <span data-ttu-id="e34ca-110">Beim Empfang von Fehlern werden Anrufe automatisch wiederholt werden also nur zu Informationszwecken.</span><span class="sxs-lookup"><span data-stu-id="e34ca-110">When errors are received calls will automatically be retried, so this is informational.</span></span> </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAutoRenewDuration">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAutoRenewDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAutoRenewDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAutoRenewDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAutoRenewDuration : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e34ca-111">Ruft ab oder legt die Dauer, für die die Sperre für die Sitzung automatisch erneuert wird.</span><span class="sxs-lookup"><span data-stu-id="e34ca-111">Gets or sets the duration for which the session lock will be renewed automatically.</span></span></summary>
        <value><span data-ttu-id="e34ca-112">Die Dauer, für die der Sitzung zu erneuern Datenbankzustands.</span><span class="sxs-lookup"><span data-stu-id="e34ca-112">The duration for which the session renew its state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentSessions">
      <MemberSignature Language="C#" Value="public int MaxConcurrentSessions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentSessions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentSessions As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentSessions : int with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e34ca-113">Ruft ab oder legt die maximale Anzahl der vorhandenen Sitzungen, die der Benutzer möchte gleichzeitig zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="e34ca-113">Gets or sets the maximum number of existing sessions that the User wants to handle concurrently.</span></span></summary>
        <value><span data-ttu-id="e34ca-114">Die maximale Anzahl von Sitzungen, die der Benutzer möchte gleichzeitig zu verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="e34ca-114">The maximum number of sessions that the User wants to handle concurrently.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageWaitTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MessageWaitTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MessageWaitTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageWaitTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MessageWaitTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e34ca-115">Ruft ab oder legt die Verzögerung bis zum Empfangen einer Nachricht.</span><span class="sxs-lookup"><span data-stu-id="e34ca-115">Gets or sets the time to wait for receiving a message.</span></span></summary>
        <value><span data-ttu-id="e34ca-116">Der Zeitpunkt, zum Empfangen der Nachricht gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="e34ca-116">The time to wait for receiving the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>