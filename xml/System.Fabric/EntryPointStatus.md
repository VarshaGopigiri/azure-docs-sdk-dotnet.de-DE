<Type Name="EntryPointStatus" FullName="System.Fabric.EntryPointStatus">
  <TypeSignature Language="C#" Value="public enum EntryPointStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntryPointStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.EntryPointStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum EntryPointStatus" />
  <TypeSignature Language="F#" Value="type EntryPointStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="aebf8-101">Gibt an, dass der Status der CodePackage EntryPoint auf einem Knoten bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="aebf8-101">Specifies the status of the CodePackage EntryPoint deployed on a node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.EntryPointStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-102">Der Status des Einstiegspunkts ist unbekannt oder ungültig.</span><span class="sxs-lookup"><span data-stu-id="aebf8-102">The status of the entry point is unknown or invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pending">
      <MemberSignature Language="C#" Value="Pending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Pending = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Pending" />
      <MemberSignature Language="VB.NET" Value="Pending" />
      <MemberSignature Language="F#" Value="Pending = 1" Usage="System.Fabric.EntryPointStatus.Pending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-103">Der Einstiegspunkt ist geplant, gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="aebf8-103">The entry point is scheduled to be started.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Started">
      <MemberSignature Language="C#" Value="Started" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Started = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Started" />
      <MemberSignature Language="VB.NET" Value="Started" />
      <MemberSignature Language="F#" Value="Started = 3" Usage="System.Fabric.EntryPointStatus.Started" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-104">Der Einstiegspunkt wurde erfolgreich gestartet und ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="aebf8-104">The entry point was started successfully and is running.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Starting">
      <MemberSignature Language="C#" Value="Starting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Starting = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Starting" />
      <MemberSignature Language="VB.NET" Value="Starting" />
      <MemberSignature Language="F#" Value="Starting = 2" Usage="System.Fabric.EntryPointStatus.Starting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-105">Der Einstiegspunkt wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="aebf8-105">The entry point is being started.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopped">
      <MemberSignature Language="C#" Value="Stopped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Stopped = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Stopped" />
      <MemberSignature Language="VB.NET" Value="Stopped" />
      <MemberSignature Language="F#" Value="Stopped = 5" Usage="System.Fabric.EntryPointStatus.Stopped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-106">Der Einstiegspunkt wird nicht ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="aebf8-106">The entry point is not running.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopping">
      <MemberSignature Language="C#" Value="Stopping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.EntryPointStatus Stopping = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.EntryPointStatus.Stopping" />
      <MemberSignature Language="VB.NET" Value="Stopping" />
      <MemberSignature Language="F#" Value="Stopping = 4" Usage="System.Fabric.EntryPointStatus.Stopping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.EntryPointStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="aebf8-107">Der Einstiegspunkt wird beendet.</span><span class="sxs-lookup"><span data-stu-id="aebf8-107">The entry point is being stopped.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>