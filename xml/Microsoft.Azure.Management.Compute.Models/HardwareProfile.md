<Type Name="HardwareProfile" FullName="Microsoft.Azure.Management.Compute.Models.HardwareProfile">
  <TypeSignature Language="C#" Value="public class HardwareProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HardwareProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.HardwareProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class HardwareProfile" />
  <TypeSignature Language="F#" Value="type HardwareProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7dbf-101">Gibt die hardwareeinstellungen für die virtuelle Maschine an.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-101">Specifies the hardware settings for the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.HardwareProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7dbf-102">Initialisiert eine neue Instanz der Klasse HardwareProfile an.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-102">Initializes a new instance of the HardwareProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareProfile (string vmSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vmSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.HardwareProfile.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional vmSize As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.HardwareProfile : string -&gt; Microsoft.Azure.Management.Compute.Models.HardwareProfile" Usage="new Microsoft.Azure.Management.Compute.Models.HardwareProfile vmSize" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vmSize" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vmSize"><span data-ttu-id="a7dbf-103">Gibt die Größe des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-103">Specifies the size of the virtual machine.</span></span> <span data-ttu-id="a7dbf-104">Weitere Informationen zu Größen virtueller Computer finden Sie unter [Größen für virtuelle Maschinen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-sizes?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="a7dbf-104">For more information about virtual machine sizes, see [Sizes for virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-sizes?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="a7dbf-105">&lt;Brasilien&gt;&lt;Br&gt; verfügbaren VM-Größen richten sich nach Region und Verfügbarkeit festgelegt.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-105">&lt;br&gt;&lt;br&gt; The available VM sizes depend on region and availability set.</span></span> <span data-ttu-id="a7dbf-106">Verwenden Sie diese APIs, eine Liste der verfügbaren Größen: &lt;Br&gt;&lt;Br&gt; [Auflisten aller verfügbaren VM-Größen in einem verfügbarkeitssatz](virtualmachines-list-sizes-availability-set.md) &lt;Br&gt; &lt;Br&gt; [Auflisten aller verfügbaren VM-Größen in einer Region](virtualmachines-list-sizes-region.md) &lt;Br&gt;&lt;Br&gt; [Auflisten aller verfügbaren virtuellen Größen für die Größenänderung Computer](virtualmachines-list-sizes-for-resizing.md).</span><span class="sxs-lookup"><span data-stu-id="a7dbf-106">For a list of available sizes use these APIs: &lt;br&gt;&lt;br&gt; [List all available virtual machine sizes in an availability set](virtualmachines-list-sizes-availability-set.md) &lt;br&gt;&lt;br&gt; [List all available virtual machine sizes in a region](virtualmachines-list-sizes-region.md) &lt;br&gt;&lt;br&gt; [List all available virtual machine sizes for resizing](virtualmachines-list-sizes-for-resizing.md).</span></span> <span data-ttu-id="a7dbf-107">Folgende Werte sind möglich: "Basic_A0", "Basic_A1", "Basic_A2", "Basic_A3", "Basic_A4", "Standard_A0", "Standard_A1", "Standard_A2", "Standard_A3", "Standard_A4", "Standard_A5", "Standard_A6", "Standard_A7", "Standard_A8", "Standard_A9", "Standard_A10", "Standard_A11", "Standard_A1_v2", "Standard_A2_v2", "Standard_A4_v2", "Standard_A8_v2", "Standard_A2m_v2", "Standard_A4m_v2", "Standard_A8m_v2", "Standard_D1", "Standard_D2" , "Standard_D3", "Standard_D4", "Standard_D11", "Standard_D12", "Standard_D13", "Standard_D14", "Standard_D1_v2", "Standard_D2_v2", "Standard_D3_v2", "Standard_D4_v2", "Standard_D5_v2", "Standard_D11_v2", "Standard_D12_v2", "Standard_D13_v2", "Standard_D14_v2", "Standard_D15_v2", "Standard_DS1", "Standard_DS2", "Standard_DS3", "Standard_DS4", "Standard_DS11", "Standard_DS12", "Standard_DS13", "Standard_DS14", "Standard_DS1_v2" , "Standard_DS2_v2", "Standard_DS3_v2", "Standard_DS4_v2", "Standard_DS5_v2", "Standard_DS11_v2", "Standard_DS12_v2", "Standard_DS13_v2", "Standard_DS14_v2", "Standard_DS15_v2", "Standard_F1", "Standard_F2", "Standard_F4", "Standard_F8", "Standard_F16", "Standard_F1s", "Standard_F2s", "Standard_F4s", "Standard_F8s", "Standard_F16s", "Standard_G1", "Standard_G2", "Standard_G3", "Standard_G4", "Standard_G5", "Standard_GS1", "Standard_GS2" , "Standard_GS3", "Standard_GS4", "Standard_GS5", "Standard_H8", "Standard_H16", "Standard_H8m", "Standard_H16m", "Standard_H16r", "Standard_H16mr", "Standard_L4s", "Standard_L8s", "Standard_L16s", "Standard_L32s", "Standard_NC6", "Standard_NC12", "Standard_NC24", "Standard_NC24r", "Standard_NV6", "Standard_NV12", "VM Standard_NV24"</span><span class="sxs-lookup"><span data-stu-id="a7dbf-107">Possible values include: 'Basic_A0', 'Basic_A1', 'Basic_A2', 'Basic_A3', 'Basic_A4', 'Standard_A0', 'Standard_A1', 'Standard_A2', 'Standard_A3', 'Standard_A4', 'Standard_A5', 'Standard_A6', 'Standard_A7', 'Standard_A8', 'Standard_A9', 'Standard_A10', 'Standard_A11', 'Standard_A1_v2', 'Standard_A2_v2', 'Standard_A4_v2', 'Standard_A8_v2', 'Standard_A2m_v2', 'Standard_A4m_v2', 'Standard_A8m_v2', 'Standard_D1', 'Standard_D2', 'Standard_D3', 'Standard_D4', 'Standard_D11', 'Standard_D12', 'Standard_D13', 'Standard_D14', 'Standard_D1_v2', 'Standard_D2_v2', 'Standard_D3_v2', 'Standard_D4_v2', 'Standard_D5_v2', 'Standard_D11_v2', 'Standard_D12_v2', 'Standard_D13_v2', 'Standard_D14_v2', 'Standard_D15_v2', 'Standard_DS1', 'Standard_DS2', 'Standard_DS3', 'Standard_DS4', 'Standard_DS11', 'Standard_DS12', 'Standard_DS13', 'Standard_DS14', 'Standard_DS1_v2', 'Standard_DS2_v2', 'Standard_DS3_v2', 'Standard_DS4_v2', 'Standard_DS5_v2', 'Standard_DS11_v2', 'Standard_DS12_v2', 'Standard_DS13_v2', 'Standard_DS14_v2', 'Standard_DS15_v2', 'Standard_F1', 'Standard_F2', 'Standard_F4', 'Standard_F8', 'Standard_F16', 'Standard_F1s', 'Standard_F2s', 'Standard_F4s', 'Standard_F8s', 'Standard_F16s', 'Standard_G1', 'Standard_G2', 'Standard_G3', 'Standard_G4', 'Standard_G5', 'Standard_GS1', 'Standard_GS2', 'Standard_GS3', 'Standard_GS4', 'Standard_GS5', 'Standard_H8', 'Standard_H16', 'Standard_H8m', 'Standard_H16m', 'Standard_H16r', 'Standard_H16mr', 'Standard_L4s', 'Standard_L8s', 'Standard_L16s', 'Standard_L32s', 'Standard_NC6', 'Standard_NC12', 'Standard_NC24', 'Standard_NC24r', 'Standard_NV6', 'Standard_NV12', 'Standard_NV24'</span></span></param>
        <summary>
            <span data-ttu-id="a7dbf-108">Initialisiert eine neue Instanz der Klasse HardwareProfile an.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-108">Initializes a new instance of the HardwareProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.HardwareProfile.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.HardwareProfile.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7dbf-109">Ruft ab oder legt gibt die Größe des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-109">Gets or sets specifies the size of the virtual machine.</span></span> <span data-ttu-id="a7dbf-110">Weitere Informationen zu Größen virtueller Computer finden Sie unter [Größen für virtuelle Maschinen](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-sizes?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span><span class="sxs-lookup"><span data-stu-id="a7dbf-110">For more information about virtual machine sizes, see [Sizes for virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-sizes?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="a7dbf-111">&amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Die verfügbaren VM-Größen richten sich nach Region und Verfügbarkeit festgelegt.</span><span class="sxs-lookup"><span data-stu-id="a7dbf-111">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; The available VM sizes depend on region and availability set.</span></span> <span data-ttu-id="a7dbf-112">Verwenden Sie diese APIs, eine Liste der verfügbaren Größen: &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; [Auflisten aller verfügbaren VM-Größen in einem verfügbarkeitssatz](virtualmachines-list-sizes-availability-set.md) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; [Auflisten aller verfügbaren VM-Größen in einer Region](virtualmachines-list-sizes-region.md) &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; [Auflisten aller verfügbaren virtuellen Maschine Größen für die Größenänderung](virtualmachines-list-sizes-for-resizing.md).</span><span class="sxs-lookup"><span data-stu-id="a7dbf-112">For a list of available sizes use these APIs:  &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; [List all available virtual machine sizes in an availability set](virtualmachines-list-sizes-availability-set.md) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; [List all available virtual machine sizes in a region](virtualmachines-list-sizes-region.md) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; [List all available virtual machine sizes for resizing](virtualmachines-list-sizes-for-resizing.md).</span></span> <span data-ttu-id="a7dbf-113">Folgende Werte sind möglich: "Basic_A0", "Basic_A1", "Basic_A2", "Basic_A3", "Basic_A4", "Standard_A0", "Standard_A1", "Standard_A2", "Standard_A3", "Standard_A4", "Standard_A5", "Standard_A6", "Standard_A7", "Standard_A8", "Standard_A9", "Standard_A10", "Standard_A11", "Standard_A1_v2", "Standard_A2_v2", "Standard_A4_v2", "Standard_A8_v2", "Standard_A2m_v2", "Standard_A4m_v2", "Standard_A8m_v2", "Standard_D1", "Standard_D2" , "Standard_D3", "Standard_D4", "Standard_D11", "Standard_D12", "Standard_D13", "Standard_D14", "Standard_D1_v2", "Standard_D2_v2", "Standard_D3_v2", "Standard_D4_v2", "Standard_D5_v2", "Standard_D11_v2", "Standard_D12_v2", "Standard_D13_v2", "Standard_D14_v2", "Standard_D15_v2", "Standard_DS1", "Standard_DS2", "Standard_DS3", "Standard_DS4", "Standard_DS11", "Standard_DS12", "Standard_DS13", "Standard_DS14", "Standard_DS1_v2" , "Standard_DS2_v2", "Standard_DS3_v2", "Standard_DS4_v2", "Standard_DS5_v2", "Standard_DS11_v2", "Standard_DS12_v2", "Standard_DS13_v2", "Standard_DS14_v2", "Standard_DS15_v2", "Standard_F1", "Standard_F2", "Standard_F4", "Standard_F8", "Standard_F16", "Standard_F1s", "Standard_F2s", "Standard_F4s", "Standard_F8s", "Standard_F16s", "Standard_G1", "Standard_G2", "Standard_G3", "Standard_G4", "Standard_G5", "Standard_GS1", "Standard_GS2" , "Standard_GS3", "Standard_GS4", "Standard_GS5", "Standard_H8", "Standard_H16", "Standard_H8m", "Standard_H16m", "Standard_H16r", "Standard_H16mr", "Standard_L4s", "Standard_L8s", "Standard_L16s", "Standard_L32s", "Standard_NC6", "Standard_NC12", "Standard_NC24", "Standard_NC24r", "Standard_NV6", "Standard_NV12", "VM Standard_NV24"</span><span class="sxs-lookup"><span data-stu-id="a7dbf-113">Possible values include: 'Basic_A0', 'Basic_A1', 'Basic_A2', 'Basic_A3', 'Basic_A4', 'Standard_A0', 'Standard_A1', 'Standard_A2', 'Standard_A3', 'Standard_A4', 'Standard_A5', 'Standard_A6', 'Standard_A7', 'Standard_A8', 'Standard_A9', 'Standard_A10', 'Standard_A11', 'Standard_A1_v2', 'Standard_A2_v2', 'Standard_A4_v2', 'Standard_A8_v2', 'Standard_A2m_v2', 'Standard_A4m_v2', 'Standard_A8m_v2', 'Standard_D1', 'Standard_D2', 'Standard_D3', 'Standard_D4', 'Standard_D11', 'Standard_D12', 'Standard_D13', 'Standard_D14', 'Standard_D1_v2', 'Standard_D2_v2', 'Standard_D3_v2', 'Standard_D4_v2', 'Standard_D5_v2', 'Standard_D11_v2', 'Standard_D12_v2', 'Standard_D13_v2', 'Standard_D14_v2', 'Standard_D15_v2', 'Standard_DS1', 'Standard_DS2', 'Standard_DS3', 'Standard_DS4', 'Standard_DS11', 'Standard_DS12', 'Standard_DS13', 'Standard_DS14', 'Standard_DS1_v2', 'Standard_DS2_v2', 'Standard_DS3_v2', 'Standard_DS4_v2', 'Standard_DS5_v2', 'Standard_DS11_v2', 'Standard_DS12_v2', 'Standard_DS13_v2', 'Standard_DS14_v2', 'Standard_DS15_v2', 'Standard_F1', 'Standard_F2', 'Standard_F4', 'Standard_F8', 'Standard_F16', 'Standard_F1s', 'Standard_F2s', 'Standard_F4s', 'Standard_F8s', 'Standard_F16s', 'Standard_G1', 'Standard_G2', 'Standard_G3', 'Standard_G4', 'Standard_G5', 'Standard_GS1', 'Standard_GS2', 'Standard_GS3', 'Standard_GS4', 'Standard_GS5', 'Standard_H8', 'Standard_H16', 'Standard_H8m', 'Standard_H16m', 'Standard_H16r', 'Standard_H16mr', 'Standard_L4s', 'Standard_L8s', 'Standard_L16s', 'Standard_L32s', 'Standard_NC6', 'Standard_NC12', 'Standard_NC24', 'Standard_NC24r', 'Standard_NV6', 'Standard_NV12', 'Standard_NV24'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>