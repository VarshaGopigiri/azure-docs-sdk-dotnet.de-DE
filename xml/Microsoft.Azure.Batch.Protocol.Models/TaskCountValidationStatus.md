<Type Name="TaskCountValidationStatus" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus">
  <TypeSignature Language="C#" Value="public enum TaskCountValidationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskCountValidationStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskCountValidationStatus" />
  <TypeSignature Language="F#" Value="type TaskCountValidationStatus = " />
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
            <span data-ttu-id="9997b-101">Definiert Werte für TaskCountValidationStatus an.</span><span class="sxs-lookup"><span data-stu-id="9997b-101">Defines values for TaskCountValidationStatus.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Unvalidated">
      <MemberSignature Language="C#" Value="Unvalidated" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus Unvalidated = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus.Unvalidated" />
      <MemberSignature Language="VB.NET" Value="Unvalidated" />
      <MemberSignature Language="F#" Value="Unvalidated = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus.Unvalidated" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="unvalidated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9997b-102">Der Batch-Dienst wurde nicht in der Lage, überprüfen Sie, dass für die Task-Status in der Liste Aufgaben-API gemeldeten Status zählt.</span><span class="sxs-lookup"><span data-stu-id="9997b-102">The Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span> <span data-ttu-id="9997b-103">Die ValidationStatus möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.</span><span class="sxs-lookup"><span data-stu-id="9997b-103">The validationStatus may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Validated">
      <MemberSignature Language="C#" Value="Validated" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus Validated = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus.Validated" />
      <MemberSignature Language="VB.NET" Value="Validated" />
      <MemberSignature Language="F#" Value="Validated = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus.Validated" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="validated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9997b-104">Der Batch-Dienst ist die Anzahl der Status für die Task-Status in der Liste Aufgaben-API gemeldeten überprüft wurde.</span><span class="sxs-lookup"><span data-stu-id="9997b-104">The Batch service has validated the state counts against the task states as reported in the List Tasks API.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>