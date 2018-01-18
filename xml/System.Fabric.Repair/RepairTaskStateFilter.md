<Type Name="RepairTaskStateFilter" FullName="System.Fabric.Repair.RepairTaskStateFilter">
  <TypeSignature Language="C#" Value="public enum RepairTaskStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskStateFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskStateFilter" />
  <TypeSignature Language="F#" Value="type RepairTaskStateFilter = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="5756b-101">Gibt Werte, die kombiniert werden können, als eine Bitmaske reparieren Tasks gefiltert nach ihren aktuellen Workflowstatus abzurufen.</span><span class="sxs-lookup"><span data-stu-id="5756b-101">Specifies values that can be combined as a bitmask to retrieve repair tasks filtered by their current workflow state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Active = int32(63)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 63" Usage="System.Fabric.Repair.RepairTaskStateFilter.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>63</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-102">Enthält Aufgaben, reparieren, die nicht abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="5756b-102">Includes repair tasks that are not completed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter All = int32(127)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 127" Usage="System.Fabric.Repair.RepairTaskStateFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>127</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-103">Schließt alle reparieren Aufgaben unabhängig vom Status an.</span><span class="sxs-lookup"><span data-stu-id="5756b-103">Includes all repair tasks, regardless of state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Approved">
      <MemberSignature Language="C#" Value="Approved" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Approved = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Approved" />
      <MemberSignature Language="VB.NET" Value="Approved" />
      <MemberSignature Language="F#" Value="Approved = 8" Usage="System.Fabric.Repair.RepairTaskStateFilter.Approved" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-104">Enthält Tasks reparieren im Status "genehmigt".</span><span class="sxs-lookup"><span data-stu-id="5756b-104">Includes repair tasks in the Approved state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Claimed">
      <MemberSignature Language="C#" Value="Claimed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Claimed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Claimed" />
      <MemberSignature Language="VB.NET" Value="Claimed" />
      <MemberSignature Language="F#" Value="Claimed = 2" Usage="System.Fabric.Repair.RepairTaskStateFilter.Claimed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-105">Enthält Tasks reparieren im Status "Claimed".</span><span class="sxs-lookup"><span data-stu-id="5756b-105">Includes repair tasks in the Claimed state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Completed = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 64" Usage="System.Fabric.Repair.RepairTaskStateFilter.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-106">Enthält Tasks reparieren im Status "abgeschlossen".</span><span class="sxs-lookup"><span data-stu-id="5756b-106">Includes repair tasks in the Completed state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="Created" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Created = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Created" />
      <MemberSignature Language="VB.NET" Value="Created" />
      <MemberSignature Language="F#" Value="Created = 1" Usage="System.Fabric.Repair.RepairTaskStateFilter.Created" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-107">Enthält Tasks reparieren im Created-Zustand.</span><span class="sxs-lookup"><span data-stu-id="5756b-107">Includes repair tasks in the Created state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Repair.RepairTaskStateFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-108">Schließt alle reparieren Aufgaben unabhängig vom Status an.</span><span class="sxs-lookup"><span data-stu-id="5756b-108">Includes all repair tasks, regardless of state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Executing">
      <MemberSignature Language="C#" Value="Executing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Executing = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Executing" />
      <MemberSignature Language="VB.NET" Value="Executing" />
      <MemberSignature Language="F#" Value="Executing = 16" Usage="System.Fabric.Repair.RepairTaskStateFilter.Executing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-109">Enthält Tasks reparieren im ausgeführten Zustand an.</span><span class="sxs-lookup"><span data-stu-id="5756b-109">Includes repair tasks in the Executing state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Preparing">
      <MemberSignature Language="C#" Value="Preparing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Preparing = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Preparing" />
      <MemberSignature Language="VB.NET" Value="Preparing" />
      <MemberSignature Language="F#" Value="Preparing = 4" Usage="System.Fabric.Repair.RepairTaskStateFilter.Preparing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-110">Enthält Tasks reparieren im Status "Vorbereitung" an.</span><span class="sxs-lookup"><span data-stu-id="5756b-110">Includes repair tasks in the Preparing state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReadyToExecute">
      <MemberSignature Language="C#" Value="ReadyToExecute" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter ReadyToExecute = int32(24)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.ReadyToExecute" />
      <MemberSignature Language="VB.NET" Value="ReadyToExecute" />
      <MemberSignature Language="F#" Value="ReadyToExecute = 24" Usage="System.Fabric.Repair.RepairTaskStateFilter.ReadyToExecute" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>24</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-111">Enthält Tasks reparieren im Status "genehmigt" oder ausführen.</span><span class="sxs-lookup"><span data-stu-id="5756b-111">Includes repair tasks in the Approved or Executing state.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Restoring">
      <MemberSignature Language="C#" Value="Restoring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskStateFilter Restoring = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskStateFilter.Restoring" />
      <MemberSignature Language="VB.NET" Value="Restoring" />
      <MemberSignature Language="F#" Value="Restoring = 32" Usage="System.Fabric.Repair.RepairTaskStateFilter.Restoring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5756b-112">Enthält Tasks reparieren im Status Restoring.</span><span class="sxs-lookup"><span data-stu-id="5756b-112">Includes repair tasks in the Restoring state.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>