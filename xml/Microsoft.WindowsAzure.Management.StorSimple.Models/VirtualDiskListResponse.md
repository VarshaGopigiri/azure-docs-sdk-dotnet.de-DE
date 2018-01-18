<Type Name="VirtualDiskListResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse">
  <TypeSignature Language="C#" Value="public class VirtualDiskListResponse : Microsoft.Azure.AzureOperationResponse, System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualDiskListResponse extends Microsoft.Azure.AzureOperationResponse implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualDiskListResponse&#xA;Inherits AzureOperationResponse&#xA;Implements IEnumerable(Of VirtualDisk)" />
  <TypeSignature Language="F#" Value="type VirtualDiskListResponse = class&#xA;    inherit AzureOperationResponse&#xA;    interface seq&lt;VirtualDisk&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="9c58a-101">Das Antwort-Modell für die Liste der virtuellen Datenträger für einen angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="9c58a-101">The response model for the list of virtual disks for a given data container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDiskListResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c58a-102">Initialisiert eine neue Instanz der VirtualDiskListResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c58a-102">Initializes a new instance of the VirtualDiskListResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of VirtualDisk)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;" Usage="virtualDiskListResponse.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c58a-103">Ruft die Sequenz von ListofVirtualDisks ab.</span><span class="sxs-lookup"><span data-stu-id="9c58a-103">Gets the sequence of ListofVirtualDisks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListofVirtualDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; ListofVirtualDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; ListofVirtualDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse.ListofVirtualDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property ListofVirtualDisks As IList(Of VirtualDisk)" />
      <MemberSignature Language="F#" Value="member this.ListofVirtualDisks : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse.ListofVirtualDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c58a-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="9c58a-104">Optional.</span></span> <span data-ttu-id="9c58a-105">Die Liste der virtuellen Datenträger im angegebenen Datencontainer für ein Gerät</span><span class="sxs-lookup"><span data-stu-id="9c58a-105">The list of virtual disks in given Data Container for a device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskListResponse.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c58a-106">Ruft die Sequenz von ListofVirtualDisks ab.</span><span class="sxs-lookup"><span data-stu-id="9c58a-106">Gets the sequence of ListofVirtualDisks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>