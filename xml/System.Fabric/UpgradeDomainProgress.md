<Type Name="UpgradeDomainProgress" FullName="System.Fabric.UpgradeDomainProgress">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeDomainProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainProgress" />
  <TypeSignature Language="F#" Value="type UpgradeDomainProgress = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="7474f-101">Stellt die Details zum upgradeverlauf von Knoten in der upgradedomäne.</span><span class="sxs-lookup"><span data-stu-id="7474f-101">Represents the upgrade progress details of nodes in the upgrade domain.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeProgressList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt; NodeProgressList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.NodeUpgradeProgress&gt; NodeProgressList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.UpgradeDomainProgress.NodeProgressList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeProgressList As IList(Of NodeUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.NodeProgressList : System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt;" Usage="System.Fabric.UpgradeDomainProgress.NodeProgressList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7474f-102">Ruft die Liste der <see cref="T:System.Fabric.NodeUpgradeProgress" /> , um Details zum upgradeverlauf von Knoten in der aktuellen upgradedomäne anzugeben.</span><span class="sxs-lookup"><span data-stu-id="7474f-102">Gets the list of <see cref="T:System.Fabric.NodeUpgradeProgress" /> that indicate upgrade progress details of nodes in the current upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7474f-103">Die Liste der <see cref="T:System.Fabric.NodeUpgradeProgress" /> , um Details zum upgradeverlauf von Knoten in der aktuellen upgradedomäne anzugeben.</span><span class="sxs-lookup"><span data-stu-id="7474f-103">The list of <see cref="T:System.Fabric.NodeUpgradeProgress" /> that indicate upgrade progress details of nodes in the current upgrade domain.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.UpgradeDomainProgress.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.UpgradeDomainProgress.UpgradeDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7474f-104">Ruft ab oder legt den Namen der upgradedomäne Upgrade durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="7474f-104">Gets or sets the name of the upgrade domain going through upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7474f-105">Der Name der upgradedomäne Upgrade durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="7474f-105">The name of the upgrade domain going through upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>