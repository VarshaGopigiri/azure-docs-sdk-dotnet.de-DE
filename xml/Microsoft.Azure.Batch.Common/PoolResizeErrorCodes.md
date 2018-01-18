<Type Name="PoolResizeErrorCodes" FullName="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes">
  <TypeSignature Language="C#" Value="public static class PoolResizeErrorCodes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolResizeErrorCodes extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolResizeErrorCodes" />
  <TypeSignature Language="F#" Value="type PoolResizeErrorCodes = class" />
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
            <span data-ttu-id="36e8b-101">Enthält die Fehlercodes, die spezifisch für Pool-Größe-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="36e8b-101">Contains error codes specific to pool resize errors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccountCoreQuotaReached">
      <MemberSignature Language="C#" Value="public const string AccountCoreQuotaReached;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AccountCoreQuotaReached" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AccountCoreQuotaReached" />
      <MemberSignature Language="VB.NET" Value="Public Const AccountCoreQuotaReached As String " />
      <MemberSignature Language="F#" Value="val mutable AccountCoreQuotaReached : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AccountCoreQuotaReached" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-102">Das Konto hat sein Kontingent von Compute-Knoten erreicht.</span><span class="sxs-lookup"><span data-stu-id="36e8b-102">The account has reached its quota of compute nodes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationFailed">
      <MemberSignature Language="C#" Value="public const string AllocationFailed;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AllocationFailed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationFailed" />
      <MemberSignature Language="VB.NET" Value="Public Const AllocationFailed As String " />
      <MemberSignature Language="F#" Value="val mutable AllocationFailed : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationFailed" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-103">Fehler beim Versuch, die gewünschte Anzahl von Compute-Knoten zu reservieren.</span><span class="sxs-lookup"><span data-stu-id="36e8b-103">An error occurred while trying to allocate the desired number of compute nodes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTimedOut">
      <MemberSignature Language="C#" Value="public const string AllocationTimedOut;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AllocationTimedOut" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationTimedOut" />
      <MemberSignature Language="VB.NET" Value="Public Const AllocationTimedOut As String " />
      <MemberSignature Language="F#" Value="val mutable AllocationTimedOut : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.AllocationTimedOut" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-104">Der Batch-Dienst konnte die gewünschte Anzahl von Serverknoten innerhalb des Timeouts zum Ändern der Größe zuordnen.</span><span class="sxs-lookup"><span data-stu-id="36e8b-104">The Batch service was unable to allocate the desired number of compute nodes within the resize timeout.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesFailed">
      <MemberSignature Language="C#" Value="public const string RemoveNodesFailed;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RemoveNodesFailed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.RemoveNodesFailed" />
      <MemberSignature Language="VB.NET" Value="Public Const RemoveNodesFailed As String " />
      <MemberSignature Language="F#" Value="val mutable RemoveNodesFailed : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.RemoveNodesFailed" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-105">Fehler beim Entfernen des Compute-Knoten aus dem Pool.</span><span class="sxs-lookup"><span data-stu-id="36e8b-105">An error occurred when removing compute nodes from the pool.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeStopped">
      <MemberSignature Language="C#" Value="public const string ResizeStopped;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ResizeStopped" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.ResizeStopped" />
      <MemberSignature Language="VB.NET" Value="Public Const ResizeStopped As String " />
      <MemberSignature Language="F#" Value="val mutable ResizeStopped : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.ResizeStopped" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-106">Der Benutzer beendet den Vorgang zum Ändern der Größe.</span><span class="sxs-lookup"><span data-stu-id="36e8b-106">The user stopped the resize operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="public const string Unknown;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Unknown" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.Unknown" />
      <MemberSignature Language="VB.NET" Value="Public Const Unknown As String " />
      <MemberSignature Language="F#" Value="val mutable Unknown : string" Usage="Microsoft.Azure.Batch.Common.PoolResizeErrorCodes.Unknown" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="36e8b-107">Die Ursache des Fehlers ist nicht bekannt.</span><span class="sxs-lookup"><span data-stu-id="36e8b-107">The reason for the failure is not known.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>