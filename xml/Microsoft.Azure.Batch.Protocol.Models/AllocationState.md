<Type Name="AllocationState" FullName="Microsoft.Azure.Batch.Protocol.Models.AllocationState">
  <TypeSignature Language="C#" Value="public enum AllocationState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AllocationState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AllocationState" />
  <TypeSignature Language="VB.NET" Value="Public Enum AllocationState" />
  <TypeSignature Language="F#" Value="type AllocationState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a99b7-101">Definiert Werte für AllocationState an.</span><span class="sxs-lookup"><span data-stu-id="a99b7-101">Defines values for AllocationState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Resizing">
      <MemberSignature Language="C#" Value="Resizing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.AllocationState Resizing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.AllocationState.Resizing" />
      <MemberSignature Language="VB.NET" Value="Resizing" />
      <MemberSignature Language="F#" Value="Resizing = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.AllocationState.Resizing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="resizing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a99b7-102">Der Pool wird Größenänderung; d. h. berechnen Knoten werden hinzugefügt oder aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="a99b7-102">The pool is resizing; that is, compute nodes are being added to or removed from the pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Steady">
      <MemberSignature Language="C#" Value="Steady" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.AllocationState Steady = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.AllocationState.Steady" />
      <MemberSignature Language="VB.NET" Value="Steady" />
      <MemberSignature Language="F#" Value="Steady = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.AllocationState.Steady" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="steady")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a99b7-103">Der Pool ist keine Größe.</span><span class="sxs-lookup"><span data-stu-id="a99b7-103">The pool is not resizing.</span></span> <span data-ttu-id="a99b7-104">Es sind keine Änderungen auf die Anzahl der Knoten im Pool ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a99b7-104">There are no changes to the number of nodes in the pool in progress.</span></span> <span data-ttu-id="a99b7-105">Ein Pool geht in diesen Zustand, bei der Erstellung und wenn für den Pool so ändern Sie die Anzahl der Knoten keine Vorgänge ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a99b7-105">A pool enters this state when it is created and when no operations are being performed on the pool to change the number of nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopping">
      <MemberSignature Language="C#" Value="Stopping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.AllocationState Stopping = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.AllocationState.Stopping" />
      <MemberSignature Language="VB.NET" Value="Stopping" />
      <MemberSignature Language="F#" Value="Stopping = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.AllocationState.Stopping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="stopping")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a99b7-106">Pool wurde ihre Größe ändern, aber der Benutzer hat angefordert, dass die Größenänderung beendet wird, aber die beendigungsanforderung wurde noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="a99b7-106">The pool was resizing, but the user has requested that the resize be stopped, but the stop request has not yet been completed.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>