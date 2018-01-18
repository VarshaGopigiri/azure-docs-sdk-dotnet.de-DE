<Type Name="IWithExpiredMessageMovedToDeadLetterQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue">
  <TypeSignature Language="C#" Value="public interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="F#" Value="type IWithExpiredMessageMovedToDeadLetterQueue = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="44acf-101">Die Stufe der die Warteschlangendefinition zulassen, um anzugeben, ob die ablaufmeldung für eine in sekundären Dead Letter-Warteschlange verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="44acf-101">The stage of the queue definition allowing to specify whether expired message can be moved to secondary dead-letter queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpiredMessageMovedToDeadLetterQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpiredMessageMovedToDeadLetterQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpiredMessageMovedToDeadLetterQueue() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpiredMessageMovedToDeadLetterQueue () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpiredMessageMovedToDeadLetterQueue : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44acf-102">Gibt an, die abgelaufene Nachricht an die Dead Letter-Warteschlange verschoben werden muss.</span><span class="sxs-lookup"><span data-stu-id="44acf-102">Specifies that expired message must be moved to dead-letter queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="44acf-103">Die nächste Phase der Warteschlange aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="44acf-103">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpiredMessageMovedToDeadLetterQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterQueue() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue.WithoutExpiredMessageMovedToDeadLetterQueue" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpiredMessageMovedToDeadLetterQueue () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpiredMessageMovedToDeadLetterQueue : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterQueue.WithoutExpiredMessageMovedToDeadLetterQueue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44acf-104">Gibt an, die abgelaufene Nachricht nicht an die Dead Letter-Warteschlange verschoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="44acf-104">Specifies that expired message should not be moved to dead-letter queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="44acf-105">Die nächste Phase der Warteschlange aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="44acf-105">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>