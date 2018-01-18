<Type Name="ComputeNodeFillType" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType">
  <TypeSignature Language="C#" Value="public enum ComputeNodeFillType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeFillType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeFillType" />
  <TypeSignature Language="F#" Value="type ComputeNodeFillType = " />
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
            <span data-ttu-id="88797-101">Definiert Werte für ComputeNodeFillType an.</span><span class="sxs-lookup"><span data-stu-id="88797-101">Defines values for ComputeNodeFillType.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Pack">
      <MemberSignature Language="C#" Value="Pack" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType Pack = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType.Pack" />
      <MemberSignature Language="VB.NET" Value="Pack" />
      <MemberSignature Language="F#" Value="Pack = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType.Pack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="pack")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="88797-102">Wie viele Aufgaben wie möglich (MaxTasksPerNode) sollte auf jeden Knoten im Pool zugewiesen werden, bevor alle Aufgaben auf den nächsten Knoten im Pool zugewiesen sind.</span><span class="sxs-lookup"><span data-stu-id="88797-102">As many tasks as possible (maxTasksPerNode) should be assigned to each node in the pool before any tasks are assigned to the next node in the pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Spread">
      <MemberSignature Language="C#" Value="Spread" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType Spread = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType.Spread" />
      <MemberSignature Language="VB.NET" Value="Spread" />
      <MemberSignature Language="F#" Value="Spread = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType.Spread" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="spread")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="88797-103">Aufgaben sollten gleichmäßig allen Knoten im Pool zugewiesen werden.</span><span class="sxs-lookup"><span data-stu-id="88797-103">Tasks should be assigned evenly across all nodes in the pool.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>