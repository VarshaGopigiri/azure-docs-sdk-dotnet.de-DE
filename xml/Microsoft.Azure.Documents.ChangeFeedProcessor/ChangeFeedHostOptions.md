<Type Name="ChangeFeedHostOptions" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions">
  <TypeSignature Language="C#" Value="public class ChangeFeedHostOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedHostOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedHostOptions" />
  <TypeSignature Language="F#" Value="type ChangeFeedHostOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6f87-101">Optionen zum Steuern der verschiedene Aspekte der Partition Verteilung im <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="d6f87-101">Options to control various aspects of partition distribution happening within <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedHostOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d6f87-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d6f87-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointFrequency">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberSignature Language="VB.NET" Value="Public Property CheckpointFrequency As CheckpointFrequency" />
      <MemberSignature Language="F#" Value="member this.CheckpointFrequency : Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-103">Ruft ab oder legt die die Häufigkeit, wie oft die Prüfpunkt-Leases.</span><span class="sxs-lookup"><span data-stu-id="d6f87-103">Gets or sets the the frequency how often to checkpoint leases.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FeedPollDelay">
      <MemberSignature Language="C#" Value="public TimeSpan FeedPollDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FeedPollDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property FeedPollDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FeedPollDelay : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-104">Ruft ab oder legt die Verzögerung zwischen den Abruf eine Partition neue Änderungen auf den feed, nachdem alle aktuellen Änderungen entladen werden.</span><span class="sxs-lookup"><span data-stu-id="d6f87-104">Gets or sets the delay in between polling a partition for new changes on the feed, after all current changes are drained.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseAcquireInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseAcquireInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseAcquireInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseAcquireInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseAcquireInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-105">Ruft ab oder legt das Zeitintervall fest, starten Sie eine Aufgabe berechnet wird, wenn Sie Partitionen auf bekannte Hostinstanzen gleichmäßig verteilt sind.</span><span class="sxs-lookup"><span data-stu-id="d6f87-105">Gets or sets the interval to kick off a task to compute if partitions are distributed evenly among known host instances.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseExpirationInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseExpirationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseExpirationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseExpirationInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseExpirationInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-106">Ruft ab oder legt das Intervall für das die Lease für eine Lease, eine Partition darstellt, ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="d6f87-106">Gets or sets the interval for which the lease is taken on a lease representing a partition.</span></span> <span data-ttu-id="d6f87-107">Wenn die Lease innerhalb dieses Zeitraums nicht erneuert wird, bewirkt ablaufen und den Besitz der Partition wird in einen anderen verschieben <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="d6f87-107">If the lease is not renewed within this interval, it will cause it to expire and ownership of the partition will move to another <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeasePrefix">
      <MemberSignature Language="C#" Value="public string LeasePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeasePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LeasePrefix As String" />
      <MemberSignature Language="F#" Value="member this.LeasePrefix : string with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-108">Ermittelt oder definiert ein Präfix, das als Teil der Lease-Id verwendet werden. Dies kann verwendet werden, um mehrere unterstützen <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanzen desselben Feeds im bei der Verwendung von zusätzlichen derselben Sammlung auf.</span><span class="sxs-lookup"><span data-stu-id="d6f87-108">Gets or sets a prefix to be used as part of the lease id. This can be used to support multiple <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instances pointing at the same feed while using the same auxiliary collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d6f87-109">Ruft ab oder legt Erneuerungsintervall für alle Leases für Partitionen, die derzeit von reservierten <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="d6f87-109">Gets or sets renew interval for all leases for partitions currently held by <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>