<Type Name="MappingDifferenceResolution" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution">
  <TypeSignature Language="C#" Value="public enum MappingDifferenceResolution" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MappingDifferenceResolution extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution" />
  <TypeSignature Language="VB.NET" Value="Public Enum MappingDifferenceResolution" />
  <TypeSignature Language="F#" Value="type MappingDifferenceResolution = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="a521d-101">Auflösungsstrategie zum Auflösen von Zuordnung Unterschiede.</span><span class="sxs-lookup"><span data-stu-id="a521d-101">Resolution strategy for resolving mapping differences.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Ignore">
      <MemberSignature Language="C#" Value="Ignore" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution Ignore = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.Ignore" />
      <MemberSignature Language="VB.NET" Value="Ignore" />
      <MemberSignature Language="F#" Value="Ignore = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.Ignore" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a521d-102">Ignorieren Sie den Unterschied vorläufig.</span><span class="sxs-lookup"><span data-stu-id="a521d-102">Ignore the difference for now.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="KeepShardMapMapping">
      <MemberSignature Language="C#" Value="KeepShardMapMapping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution KeepShardMapMapping = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.KeepShardMapMapping" />
      <MemberSignature Language="VB.NET" Value="KeepShardMapMapping" />
      <MemberSignature Language="F#" Value="KeepShardMapMapping = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.KeepShardMapMapping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a521d-103">Verwenden Sie die Zuordnung in der shardzuordnung vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a521d-103">Use the mapping present in shard map.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="KeepShardMapping">
      <MemberSignature Language="C#" Value="KeepShardMapping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution KeepShardMapping = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.KeepShardMapping" />
      <MemberSignature Language="VB.NET" Value="KeepShardMapping" />
      <MemberSignature Language="F#" Value="KeepShardMapping = 2" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution.KeepShardMapping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a521d-104">Verwenden Sie die Zuordnung in den Shard.</span><span class="sxs-lookup"><span data-stu-id="a521d-104">Use the mapping in the shard.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>