<Type Name="StartTaskState" FullName="Microsoft.Azure.Batch.Protocol.Models.StartTaskState">
  <TypeSignature Language="C#" Value="public enum StartTaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StartTaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.StartTaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum StartTaskState" />
  <TypeSignature Language="F#" Value="type StartTaskState = " />
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
            <span data-ttu-id="85d78-101">Definiert Werte für StartTaskState an.</span><span class="sxs-lookup"><span data-stu-id="85d78-101">Defines values for StartTaskState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState Completed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.StartTaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="85d78-102">Die Startaufgabe mit Exitcode 0 (null) beendet wurde oder die Startaufgabe ausgefallen und das Wiederholungslimit erreicht wurde, oder der startaufgabenvorgang wurde aufgrund von Vorbereitung Taskfehler (z. B. Fehler beim Herunterladen von Ressourcen-Datei) nicht ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="85d78-102">The start task has exited with exit code 0, or the start task has failed and the retry limit has reached, or the start task process did not run due to task preparation errors (such as resource file download failures).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState Running = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.StartTaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="85d78-103">Die Startaufgabe wird derzeit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="85d78-103">The start task is currently running.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>