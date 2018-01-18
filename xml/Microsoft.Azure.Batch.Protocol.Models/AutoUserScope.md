<Type Name="AutoUserScope" FullName="Microsoft.Azure.Batch.Protocol.Models.AutoUserScope">
  <TypeSignature Language="C#" Value="public enum AutoUserScope" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AutoUserScope extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AutoUserScope" />
  <TypeSignature Language="VB.NET" Value="Public Enum AutoUserScope" />
  <TypeSignature Language="F#" Value="type AutoUserScope = " />
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
            <span data-ttu-id="239a7-101">Definiert Werte für AutoUserScope an.</span><span class="sxs-lookup"><span data-stu-id="239a7-101">Defines values for AutoUserScope.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="Pool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope Pool = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.AutoUserScope.Pool" />
      <MemberSignature Language="VB.NET" Value="Pool" />
      <MemberSignature Language="F#" Value="Pool = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserScope.Pool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="pool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoUserScope</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="239a7-102">Gibt an, dass der Task als das allgemeine Auto-Benutzerkonto ausgeführt wird, die auf jedem Knoten in einem Pool erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="239a7-102">Specifies that the task runs as the common auto user account which is created on every node in a pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="Task" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.AutoUserScope Task = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.AutoUserScope.Task" />
      <MemberSignature Language="VB.NET" Value="Task" />
      <MemberSignature Language="F#" Value="Task = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.AutoUserScope.Task" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="task")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoUserScope</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="239a7-103">Gibt an, dass der Dienst einen neuen Benutzer für den Task erstellen soll.</span><span class="sxs-lookup"><span data-stu-id="239a7-103">Specifies that the service should create a new user for the task.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>