<Type Name="UpgradeUpdateDescriptionBase" FullName="System.Fabric.Description.UpgradeUpdateDescriptionBase">
  <TypeSignature Language="C#" Value="public abstract class UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit UpgradeUpdateDescriptionBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type UpgradeUpdateDescriptionBase = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="529c4-101">Stellt die abstrakte Basisklasse für <see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" /> und <see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-101">Represents the abstract base class for <see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" /> and <see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />.</span></span>
            <span data-ttu-id="529c4-102">Diese Klasse kann verwendet werden, so ändern Sie die Upgrade-Parameter, die das Verhalten der Anwendung oder -Cluster-Upgrades beschreibt.</span><span class="sxs-lookup"><span data-stu-id="529c4-102">This class can be used to modify the upgrade parameters describing the behavior of the application or cluster upgrades.</span></span> <span data-ttu-id="529c4-103">Besuchen Sie <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" /> und <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" /> , als das Nutzungsrecht sehen.</span><span class="sxs-lookup"><span data-stu-id="529c4-103">Visit <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" /> and <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" /> to see the usage.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected UpgradeUpdateDescriptionBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UpgradeUpdateDescriptionBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.UpgradeUpdateDescriptionBase" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="529c4-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.UpgradeUpdateDescriptionBase" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureAction&gt; FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureAction&gt; FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As Nullable(Of UpgradeFailureAction)" />
      <MemberSignature Language="F#" Value="member this.FailureAction : Nullable&lt;System.Fabric.UpgradeFailureAction&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-105">Ruft ab oder legt den neuen Wert des <see cref="T:System.Fabric.UpgradeFailureAction" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-105">Gets or sets the new value of <see cref="T:System.Fabric.UpgradeFailureAction" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-106">Der neue Wert von <see cref="T:System.Fabric.UpgradeFailureAction" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-106">The new value of <see cref="T:System.Fabric.UpgradeFailureAction" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRestart">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ForceRestart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ForceRestart" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRestart As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ForceRestart : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.ForceRestart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-107">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-107">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-108">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-108">The new value of <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-109">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-109">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-110">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-110">The new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckStableDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-111">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-111">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-112">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-112">The new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.HealthCheckWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-113">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-113">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-114">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-114">The new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeDomainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-115">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-115">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-116">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-116">The new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.RollingUpgradeMode&gt; UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.RollingUpgradeMode&gt; UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As Nullable(Of RollingUpgradeMode)" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : Nullable&lt;System.Fabric.RollingUpgradeMode&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.RollingUpgradeMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-117">Ruft ab oder legt den neuen Wert des <see cref="T:System.Fabric.RollingUpgradeMode" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-117">Gets or sets the new value of <see cref="T:System.Fabric.RollingUpgradeMode" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-118">Der neue Wert von <see cref="T:System.Fabric.RollingUpgradeMode" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-118">The new value of <see cref="T:System.Fabric.RollingUpgradeMode" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeReplicaSetCheckTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeReplicaSetCheckTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeReplicaSetCheckTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeReplicaSetCheckTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeReplicaSetCheckTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-119">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-119">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-120">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-120">The new value of <see cref="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.UpgradeUpdateDescriptionBase.UpgradeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="529c4-121">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-121">Gets or sets the new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="529c4-122">Der neue Wert von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />.</span><span class="sxs-lookup"><span data-stu-id="529c4-122">The new value of <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>