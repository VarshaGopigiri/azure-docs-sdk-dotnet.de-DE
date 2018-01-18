<Type Name="IDefinition" FullName="Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IDefinition">
  <TypeSignature Language="C#" Value="public interface IDefinition : Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IBlank, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithAgentPool, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithDiagnostics, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxRootUsername, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxSshKey, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterLeafDomainLabel, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterNodeCount, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator, Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithServicePrincipalProfile, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IContainerService&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinition implements class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IBlank, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithAgentPool, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinux, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxRootUsername, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxSshKey, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterLeafDomainLabel, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterNodeCount, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator, class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithServicePrincipalProfile, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IContainerService&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinition&#xA;Implements IBlank, ICreatable(Of IContainerService), IDefinitionWithRegion(Of IWithGroup), IDefinitionWithTags(Of IWithCreate), IWithAgentPool, IWithCreatableResourceGroup(Of IWithOrchestrator), IWithCreate, IWithDiagnostics, IWithExistingResourceGroup(Of IWithOrchestrator), IWithGroup, IWithGroup(Of IWithOrchestrator), IWithLinuxRootUsername, IWithLinuxSshKey, IWithMasterLeafDomainLabel, IWithMasterNodeCount, IWithNewResourceGroup(Of IWithOrchestrator), IWithOrchestrator, IWithServicePrincipalProfile" />
  <TypeSignature Language="F#" Value="type IDefinition = interface&#xA;    interface IBlank&#xA;    interface IDefinitionWithRegion&lt;IWithGroup&gt;&#xA;    interface IWithGroup&#xA;    interface IWithGroup&lt;IWithOrchestrator&gt;&#xA;    interface IWithExistingResourceGroup&lt;IWithOrchestrator&gt;&#xA;    interface IWithNewResourceGroup&lt;IWithOrchestrator&gt;&#xA;    interface IWithCreatableResourceGroup&lt;IWithOrchestrator&gt;&#xA;    interface IWithOrchestrator&#xA;    interface IWithMasterNodeCount&#xA;    interface IWithMasterLeafDomainLabel&#xA;    interface IWithLinux&#xA;    interface IWithLinuxRootUsername&#xA;    interface IWithLinuxSshKey&#xA;    interface IWithAgentPool&#xA;    interface IWithServicePrincipalProfile&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IContainerService&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithDiagnostics" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IBlank</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithAgentPool</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithDiagnostics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxRootUsername</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithLinuxSshKey</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterLeafDomainLabel</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithMasterNodeCount</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithServicePrincipalProfile</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithOrchestrator&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.ContainerService.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IContainerService&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>