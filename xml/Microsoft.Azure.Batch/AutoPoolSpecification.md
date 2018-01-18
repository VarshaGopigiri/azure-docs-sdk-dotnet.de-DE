<Type Name="AutoPoolSpecification" FullName="Microsoft.Azure.Batch.AutoPoolSpecification">
  <TypeSignature Language="C#" Value="public class AutoPoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoPoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AutoPoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoPoolSpecification" />
  <TypeSignature Language="F#" Value="type AutoPoolSpecification = class&#xA;    interface ITransportObjectProvider&lt;AutoPoolSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="9a4c2-101">Gibt die Eigenschaften für eine temporäre "Pools".</span><span class="sxs-lookup"><span data-stu-id="9a4c2-101">Specifies characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="9a4c2-102">Der Batch-Dienst wird diese Pools erstellen, führen Sie alle Aufgaben für den Auftrag auf sie und standardmäßig löscht den Pool, nachdem der Auftrag abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-102">The Batch service will create this auto pool, run all the tasks for the job on it, and by default delete the pool once the job has completed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoPoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AutoPoolSpecification.#ctor" />
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
            <span data-ttu-id="9a4c2-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.AutoPoolSpecification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.AutoPoolSpecification" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolIdPrefix">
      <MemberSignature Language="C#" Value="public string AutoPoolIdPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoPoolIdPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.AutoPoolIdPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolIdPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AutoPoolIdPrefix : string with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.AutoPoolIdPrefix" />
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
            <span data-ttu-id="9a4c2-104">Ruft ab oder legt ein Präfix für den eindeutigen Bezeichner hinzugefügt, wenn ein Pool automatisch erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-104">Gets or sets a prefix to be added to the unique identifier when a pool is automatically created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9a4c2-105">Das Präfix ist optional.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-105">The prefix is optional.</span></span> <span data-ttu-id="9a4c2-106">Falls vorhanden, kann bis zu 20 Zeichen lang sein und muss den üblichen Regeln für Ids (alphanumerische Zeichen, Bindestriche und Unterstriche enthalten nur) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-106">If present, it can be up to 20 characters long and must adhere to the usual rules for ids (alphanumeric characters, hyphens and underscores only).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAlive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KeepAlive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KeepAlive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAlive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KeepAlive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" />
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
            <span data-ttu-id="9a4c2-107">Ruft ab oder legt fest, ob um den automatischen Pool nach aufrechtzuerhalten seine <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" /> läuft ab.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-107">Gets or sets whether to keep the auto pool alive after its <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" /> expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9a4c2-108">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-108">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolLifetimeOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.PoolLifetimeOption PoolLifetimeOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.PoolLifetimeOption PoolLifetimeOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolLifetimeOption As PoolLifetimeOption" />
      <MemberSignature Language="F#" Value="member this.PoolLifetimeOption : Microsoft.Azure.Batch.Common.PoolLifetimeOption with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.PoolLifetimeOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolLifetimeOption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a4c2-109">Ruft ab oder legt die minimale Lebensdauer der erstellten automatisch Pools und wie mehrere Aufträge nach einem Zeitplan, die den Pools zugewiesen werden.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-109">Gets or sets the minimum lifetime of created auto pools, and how multiple jobs on a schedule are assigned to pools.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9a4c2-110">Ein automatischer Pool möglicherweise länger als dessen PoolLifetimeOption live, wenn <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" /> festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-110">An auto pool may live longer than its PoolLifetimeOption if <see cref="P:Microsoft.Azure.Batch.AutoPoolSpecification.KeepAlive" /> is set.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolSpecification PoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolSpecification PoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AutoPoolSpecification.PoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolSpecification As PoolSpecification" />
      <MemberSignature Language="F#" Value="member this.PoolSpecification : Microsoft.Azure.Batch.PoolSpecification with get, set" Usage="Microsoft.Azure.Batch.AutoPoolSpecification.PoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a4c2-111">Ruft ab oder legt die poolspezifikation für den automatischen Pool.</span><span class="sxs-lookup"><span data-stu-id="9a4c2-111">Gets or sets the pool specification for the auto pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>