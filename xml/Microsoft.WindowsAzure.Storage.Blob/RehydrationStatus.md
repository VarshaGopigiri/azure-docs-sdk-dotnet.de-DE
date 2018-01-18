<Type Name="RehydrationStatus" FullName="Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus">
  <TypeSignature Language="C#" Value="public enum RehydrationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RehydrationStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum RehydrationStatus" />
  <TypeSignature Language="F#" Value="type RehydrationStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="d7bf4-101">Der Status der Aktivierung für ein Blob, das derzeit archiviert wird.</span><span class="sxs-lookup"><span data-stu-id="d7bf4-101">The rehydration status for a blob that is currently archived.</span></span>
            </summary>
    <remarks><span data-ttu-id="d7bf4-102">Gilt nur für blockblobs für diese Version.</span><span class="sxs-lookup"><span data-stu-id="d7bf4-102">Only applicable to block blobs for this version.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="PendingToCool">
      <MemberSignature Language="C#" Value="PendingToCool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus PendingToCool = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.PendingToCool" />
      <MemberSignature Language="VB.NET" Value="PendingToCool" />
      <MemberSignature Language="F#" Value="PendingToCool = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.PendingToCool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7bf4-103">Das Blob ist aktiviert wird, um Speicher zu kühlen.</span><span class="sxs-lookup"><span data-stu-id="d7bf4-103">The blob is being rehydrated to cool storage.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PendingToHot">
      <MemberSignature Language="C#" Value="PendingToHot" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus PendingToHot = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.PendingToHot" />
      <MemberSignature Language="VB.NET" Value="PendingToHot" />
      <MemberSignature Language="F#" Value="PendingToHot = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.PendingToHot" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7bf4-104">Das Blob ist aktiviert wird, um Speicher im laufenden.</span><span class="sxs-lookup"><span data-stu-id="d7bf4-104">The blob is being rehydrated to hot storage.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus Unknown = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7bf4-105">Der Status für die Aktivierung ist unbekannt.</span><span class="sxs-lookup"><span data-stu-id="d7bf4-105">The rehydration status is unknown.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>