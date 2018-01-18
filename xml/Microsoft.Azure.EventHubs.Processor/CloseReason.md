<Type Name="CloseReason" FullName="Microsoft.Azure.EventHubs.Processor.CloseReason">
  <TypeSignature Language="C#" Value="public enum CloseReason" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CloseReason extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.CloseReason" />
  <TypeSignature Language="VB.NET" Value="Public Enum CloseReason" />
  <TypeSignature Language="F#" Value="type CloseReason = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="993e9-101">Ursache für die Schließung einer <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />.</span><span class="sxs-lookup"><span data-stu-id="993e9-101">Reason for closing an <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LeaseLost">
      <MemberSignature Language="C#" Value="LeaseLost" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.EventHubs.Processor.CloseReason LeaseLost = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.Processor.CloseReason.LeaseLost" />
      <MemberSignature Language="VB.NET" Value="LeaseLost" />
      <MemberSignature Language="F#" Value="LeaseLost = 0" Usage="Microsoft.Azure.EventHubs.Processor.CloseReason.LeaseLost" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.CloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="993e9-102">Die Lease wurde verloren geht oder eine neue Prozessorinstanz gewechselt.</span><span class="sxs-lookup"><span data-stu-id="993e9-102">The lease was lost or transitioned to a new processor instance.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Shutdown">
      <MemberSignature Language="C#" Value="Shutdown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.EventHubs.Processor.CloseReason Shutdown = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.Processor.CloseReason.Shutdown" />
      <MemberSignature Language="VB.NET" Value="Shutdown" />
      <MemberSignature Language="F#" Value="Shutdown = 1" Usage="Microsoft.Azure.EventHubs.Processor.CloseReason.Shutdown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.CloseReason</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="993e9-103">Die <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> wurde heruntergefahren.</span><span class="sxs-lookup"><span data-stu-id="993e9-103">The <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> was shutdown.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>