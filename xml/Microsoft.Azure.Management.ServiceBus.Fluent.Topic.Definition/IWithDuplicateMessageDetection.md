<Type Name="IWithDuplicateMessageDetection" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection">
  <TypeSignature Language="C#" Value="public interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDuplicateMessageDetection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDuplicateMessageDetection" />
  <TypeSignature Language="F#" Value="type IWithDuplicateMessageDetection = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80af6-101">Die Phase der themadefinition, sodass Dauer des Verlaufs Erkennung doppelter Nachrichten an.</span><span class="sxs-lookup"><span data-stu-id="80af6-101">The stage of the topic definition allowing to specify duration of the duplicate message detection history.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDuplicateMessageDetection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDuplicateMessageDetection (TimeSpan duplicateDetectionHistoryDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDuplicateMessageDetection(valuetype System.TimeSpan duplicateDetectionHistoryDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDuplicateMessageDetection.WithDuplicateMessageDetection(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDuplicateMessageDetection (duplicateDetectionHistoryDuration As TimeSpan) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDuplicateMessageDetection : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithDuplicateMessageDetection.WithDuplicateMessageDetection duplicateDetectionHistoryDuration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="duplicateDetectionHistoryDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="duplicateDetectionHistoryDuration"><span data-ttu-id="80af6-102">Die Dauer des Verlaufs.</span><span class="sxs-lookup"><span data-stu-id="80af6-102">Duration of the history.</span></span></param>
        <summary>
            <span data-ttu-id="80af6-103">Gibt die Dauer des Verlaufs Erkennung doppelter Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="80af6-103">Specifies the duration of the duplicate message detection history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="80af6-104">Die nächste Phase der themadefinition.</span><span class="sxs-lookup"><span data-stu-id="80af6-104">The next stage of topic definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>