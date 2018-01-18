<Type Name="IWithImageOrPublisher&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithImageOrPublisher&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithImageOrPublisher&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithImageOrPublisher`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithImageOrPublisher`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithImageOrPublisher(Of ParentT)&#xA;Implements IWithPublisher(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithImageOrPublisher&lt;'ParentT&gt; = interface&#xA;    interface IWithPublisher&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="8f504-101">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="8f504-101">The stage of the parent update to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="8f504-102">Die Stufe der Erweiterung des virtuellen Computers, sodass Erweiterung Bild angeben, oder geben Sie Namen des Verlegers der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="8f504-102">The stage of the virtual machine extension allowing to specify extension image or specify name of the virtual machine extension publisher.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithImageOrPublisher`1.WithImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithImage (image As IVirtualMachineExtensionImage) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageOrPublisher.WithImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage" />
      </Parameters>
      <Docs>
        <param name="image"><span data-ttu-id="8f504-103">Das Bild.</span><span class="sxs-lookup"><span data-stu-id="8f504-103">The image.</span></span></param>
        <summary>
            <span data-ttu-id="8f504-104">Gibt an, das Image des virtuellen Computers Erweiterung verwenden.</span><span class="sxs-lookup"><span data-stu-id="8f504-104">Specifies the virtual machine extension image to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8f504-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8f504-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>