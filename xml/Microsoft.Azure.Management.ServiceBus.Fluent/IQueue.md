<Type Name="IQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue">
  <TypeSignature Language="C#" Value="public interface IQueue : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IQueue&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueue implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IQueue&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueue&#xA;Implements IGroupableResource(Of IServiceBusManager, QueueInner), IHasInner(Of QueueInner), IHasManager(Of IServiceBusManager), IIndependentChild(Of IServiceBusManager), IIndependentChildResource(Of IServiceBusManager, QueueInner), IRefreshable(Of IQueue), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IQueue = interface&#xA;    interface IIndependentChildResource&lt;IServiceBusManager, QueueInner&gt;&#xA;    interface IGroupableResource&lt;IServiceBusManager, QueueInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;QueueInner&gt;&#xA;    interface IIndependentChild&lt;IServiceBusManager&gt;&#xA;    interface IRefreshable&lt;IQueue&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IQueue&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="dea6c-101">Geben Sie für Service Bus-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="dea6c-101">Type representing Service Bus queue.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="dea6c-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="dea6c-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-103">Ruft die zuletzt eine Nachricht gesendet wurde, oder der letzten Ausführung, es wurde eine Receive-Anforderung an diese Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="dea6c-103">Gets last time a message was sent, or the last time there was a receive request to this queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveMessageCount">
      <MemberSignature Language="C#" Value="public long ActiveMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ActiveMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.ActiveMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ActiveMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.ActiveMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-104">Ruft die Anzahl der aktiven Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="dea6c-104">Gets number of active messages in the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IQueueAuthorizationRules AuthorizationRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.IQueueAuthorizationRules AuthorizationRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.AuthorizationRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationRules As IQueueAuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.AuthorizationRules : Microsoft.Azure.Management.ServiceBus.Fluent.IQueueAuthorizationRules" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.AuthorizationRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IQueueAuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-105">Ruft Einstiegspunkt zum Verwalten von Autorisierungsregeln für den Service Bus-Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="dea6c-105">Gets entry point to manage authorization rules for the Service Bus queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-106">Ruft die genaue Uhrzeit, die Erstellung die Warteschlange, ab.</span><span class="sxs-lookup"><span data-stu-id="dea6c-106">Gets the exact time the queue was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentSizeInBytes">
      <MemberSignature Language="C#" Value="public long CurrentSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CurrentSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.CurrentSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentSizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.CurrentSizeInBytes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.CurrentSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-107">Ruft die aktuelle Größe der Warteschlange, in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="dea6c-107">Gets current size of the queue, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long DeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.DeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-108">Ruft die Anzahl der in der Warteschlange für unzustellbare Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="dea6c-108">Gets number of messages in the dead-letter queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTtlDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTtlDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTtlDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DefaultMessageTtlDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMessageTtlDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTtlDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DefaultMessageTtlDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-109">Ruft die Dauer, die nach der die Nachricht abläuft, beginnend ab dem Zeitpunkt der Nachricht an die Warteschlange gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="dea6c-109">Gets the duration after which the message expires, starting from when the message is sent to queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public long DeleteOnIdleDurationInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DeleteOnIdleDurationInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteOnIdleDurationInMinutes As Long" />
      <MemberSignature Language="F#" Value="member this.DeleteOnIdleDurationInMinutes : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DeleteOnIdleDurationInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-110">Ruft die Leerlaufdauer nach der die Warteschlange automatisch gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="dea6c-110">Gets the idle duration after which the queue is automatically deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateMessageDetectionHistoryDuration">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateMessageDetectionHistoryDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateMessageDetectionHistoryDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DuplicateMessageDetectionHistoryDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DuplicateMessageDetectionHistoryDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateMessageDetectionHistoryDuration : TimeSpan" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.DuplicateMessageDetectionHistoryDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-111">Ruft ab, die die Zeitspanne des duplikaterkennungsverlaufs.</span><span class="sxs-lookup"><span data-stu-id="dea6c-111">Gets the duration of the duplicate detection history.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBatchedOperationsEnabled">
      <MemberSignature Language="C#" Value="public bool IsBatchedOperationsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBatchedOperationsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsBatchedOperationsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBatchedOperationsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBatchedOperationsEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsBatchedOperationsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-112">Ruft gibt an, ob serverseitige Batchvorgänge aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="dea6c-112">Gets indicates whether server-side batched operations are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeadLetteringEnabledForExpiredMessages">
      <MemberSignature Language="C#" Value="public bool IsDeadLetteringEnabledForExpiredMessages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDeadLetteringEnabledForExpiredMessages As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDeadLetteringEnabledForExpiredMessages : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsDeadLetteringEnabledForExpiredMessages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-113">Ruft gibt an, ob dieser Warteschlange für unzustellbare Unterstützung verfügt, wenn eine Nachricht abläuft.</span><span class="sxs-lookup"><span data-stu-id="dea6c-113">Gets indicates whether this queue has dead letter support when a message expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDuplicateDetectionEnabled">
      <MemberSignature Language="C#" Value="public bool IsDuplicateDetectionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDuplicateDetectionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsDuplicateDetectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDuplicateDetectionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDuplicateDetectionEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsDuplicateDetectionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-114">Ruft gibt an, ob diese Warteschlange Erkennung von Duplikaten erfordert.</span><span class="sxs-lookup"><span data-stu-id="dea6c-114">Gets indicates if this queue requires duplicate detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpressEnabled">
      <MemberSignature Language="C#" Value="public bool IsExpressEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpressEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsExpressEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpressEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpressEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsExpressEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-115">Ruft gibt an, ob expressentitäten aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="dea6c-115">Gets indicates whether express entities are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPartitioningEnabled">
      <MemberSignature Language="C#" Value="public bool IsPartitioningEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPartitioningEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsPartitioningEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPartitioningEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPartitioningEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsPartitioningEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-116">Ruft gibt an, ob die Warteschlange über mehrere nachrichtenbroker partitioniert werden.</span><span class="sxs-lookup"><span data-stu-id="dea6c-116">Gets indicates whether the queue is to be partitioned across multiple message brokers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSessionEnabled">
      <MemberSignature Language="C#" Value="public bool IsSessionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSessionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsSessionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSessionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSessionEnabled : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.IsSessionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-117">Ruft angibt, ob die Warteschlange für Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="dea6c-117">Gets indicates whether the queue supports sessions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDurationInSeconds">
      <MemberSignature Language="C#" Value="public long LockDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LockDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.LockDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LockDurationInSeconds : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.LockDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-118">Ruft die Dauer eines Peek / Lock also den Zeitspanne, die die Nachricht für andere Empfänger gesperrt ist.</span><span class="sxs-lookup"><span data-stu-id="dea6c-118">Gets the duration of peek-lock which is the amount of time that the message is locked for other receivers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCountBeforeDeadLetteringMessage">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCountBeforeDeadLetteringMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDeliveryCountBeforeDeadLetteringMessage As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCountBeforeDeadLetteringMessage : int" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MaxDeliveryCountBeforeDeadLetteringMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-119">Ruft die maximale Anzahl von einem Nachrichtenübermittlung bevor es als Warteschlange für unzustellbare Nachrichten Zustellungsversuche kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="dea6c-119">Gets the maximum number of a message delivery before marking it as dead-lettered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMB">
      <MemberSignature Language="C#" Value="public long MaxSizeInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MaxSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSizeInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMB : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MaxSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-120">Ruft die maximale Größe des Arbeitsspeichers für die Warteschlange in Megabyte an.</span><span class="sxs-lookup"><span data-stu-id="dea6c-120">Gets the maximum size of memory allocated for the queue in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-121">Ruft die Anzahl der Nachrichten in der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="dea6c-121">Gets the number of messages in the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledMessageCount">
      <MemberSignature Language="C#" Value="public long ScheduledMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ScheduledMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.ScheduledMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.ScheduledMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.ScheduledMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-122">Ruft die Anzahl der Nachrichten an die Warteschlange gesendet, die noch für Verbrauch veröffentlicht werden soll.</span><span class="sxs-lookup"><span data-stu-id="dea6c-122">Gets number of messages sent to the queue that are yet to be released for consumption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-123">Ruft den aktuellen Status der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="dea6c-123">Gets the current status of the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferDeadLetterMessageCount">
      <MemberSignature Language="C#" Value="public long TransferDeadLetterMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferDeadLetterMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.TransferDeadLetterMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferDeadLetterMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferDeadLetterMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.TransferDeadLetterMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-124">Ruft die Anzahl der Nachrichten, die in der unzustellbare Nachrichten übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="dea6c-124">Gets number of messages transferred into dead letters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMessageCount">
      <MemberSignature Language="C#" Value="public long TransferMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransferMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.TransferMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransferMessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.TransferMessageCount : int64" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.TransferMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-125">Ruft die Anzahl der Nachrichten, die in einer anderen Warteschlange, Thema oder Abonnement übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="dea6c-125">Gets number of messages transferred to another queue, topic, or subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IQueue.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea6c-126">Ruft die genaue Uhrzeit, an die Warteschlange aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="dea6c-126">Gets the exact time the queue was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>