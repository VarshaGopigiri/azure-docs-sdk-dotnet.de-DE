<Type Name="IStateReplicator2" FullName="System.Fabric.IStateReplicator2">
  <TypeSignature Language="C#" Value="public interface IStateReplicator2 : System.Fabric.IStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateReplicator2 implements class System.Fabric.IStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateReplicator2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateReplicator2&#xA;Implements IStateReplicator" />
  <TypeSignature Language="F#" Value="type IStateReplicator2 = interface&#xA;    interface IStateReplicator" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStateReplicator</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="fb32b-101">Macht Funktionen im Zusammenhang mit Replikation, von der <see cref="T:System.Fabric.FabricReplicator" /> Klasse, mit denen <see cref="T:System.Fabric.IStateProvider" /> zum Replizieren von Zustand, um hohe Verfügbarkeit sicherzustellen.</span><span class="sxs-lookup"><span data-stu-id="fb32b-101">Exposes replication-related functions of the <see cref="T:System.Fabric.FabricReplicator" /> class that are used by <see cref="T:System.Fabric.IStateProvider" /> to replicate state to ensure high availability.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetReplicatorSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicatorSettings GetReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.ReplicatorSettings GetReplicatorSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator2.GetReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicatorSettings () As ReplicatorSettings" />
      <MemberSignature Language="F#" Value="abstract member GetReplicatorSettings : unit -&gt; System.Fabric.ReplicatorSettings" Usage="iStateReplicator2.GetReplicatorSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="fb32b-102">Ruft die Einstellungen der Replikator während der Laufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="fb32b-102">Retrieves the replicator settings during runtime.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="fb32b-103">Die aktuelle <see cref="T:System.Fabric.ReplicatorSettings" /> aus der Service Fabric-Laufzeit.</span><span class="sxs-lookup"><span data-stu-id="fb32b-103">The current <see cref="T:System.Fabric.ReplicatorSettings" /> from the Service Fabric runtime.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>