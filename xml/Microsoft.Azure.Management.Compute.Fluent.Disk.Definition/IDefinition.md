<Type Name="IDefinition" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IDefinition">
  <TypeSignature Language="C#" Value="public interface IDefinition : Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IBlank, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinition implements class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IBlank, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithData, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromSnapshot, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithLinuxDiskSource, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithSku, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithWindowsDiskSource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinition&#xA;Implements IBeta, IBlank, ICreatable(Of IDisk), IDefinitionWithRegion(Of IWithGroup), IDefinitionWithTags(Of IWithCreate), IWithCreatableResourceGroup(Of IWithDiskSource), IWithCreateAndSize, IWithDataDiskSource, IWithDiskSource, IWithExistingResourceGroup(Of IWithDiskSource), IWithGroup, IWithGroup(Of IWithDiskSource), IWithNewResourceGroup(Of IWithDiskSource)" />
  <TypeSignature Language="F#" Value="type IDefinition = interface&#xA;    interface IBlank&#xA;    interface IDefinitionWithRegion&lt;IWithGroup&gt;&#xA;    interface IWithGroup&#xA;    interface IWithGroup&lt;IWithDiskSource&gt;&#xA;    interface IWithExistingResourceGroup&lt;IWithDiskSource&gt;&#xA;    interface IWithNewResourceGroup&lt;IWithDiskSource&gt;&#xA;    interface IWithCreatableResourceGroup&lt;IWithDiskSource&gt;&#xA;    interface IWithDiskSource&#xA;    interface IWithWindowsDiskSource&#xA;    interface IWithLinuxDiskSource&#xA;    interface IWithData&#xA;    interface IWithDataDiskSource&#xA;    interface IWithDataDiskFromVhd&#xA;    interface IWithDataDiskFromDisk&#xA;    interface IWithDataDiskFromSnapshot&#xA;    interface IWithCreateAndSize&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IDisk&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithSku&#xA;    interface IWithAvailabilityZone&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IBlank</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroup&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDiskSource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IDisk&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="10f3b-101">Die Gesamtheit der Definition des verwalteten Datenträger.</span><span class="sxs-lookup"><span data-stu-id="10f3b-101">The entirety of the managed disk definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>