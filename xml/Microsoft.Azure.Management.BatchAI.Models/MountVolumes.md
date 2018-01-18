<Type Name="MountVolumes" FullName="Microsoft.Azure.Management.BatchAI.Models.MountVolumes">
  <TypeSignature Language="C#" Value="public class MountVolumes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MountVolumes extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.MountVolumes" />
  <TypeSignature Language="VB.NET" Value="Public Class MountVolumes" />
  <TypeSignature Language="F#" Value="type MountVolumes = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="393ae-101">Details der Volumes auf dem Cluster bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="393ae-101">Details of volumes to mount on the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MountVolumes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="393ae-102">Initialisiert eine neue Instanz der MountVolumes-Klasse.</span><span class="sxs-lookup"><span data-stu-id="393ae-102">Initializes a new instance of the MountVolumes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MountVolumes (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; azureFileShares = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; azureBlobFileSystems = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; fileServers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; unmanagedFileSystems = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; azureFileShares, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; azureBlobFileSystems, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; fileServers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; unmanagedFileSystems) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.FileServerReference},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional azureFileShares As IList(Of AzureFileShareReference) = null, Optional azureBlobFileSystems As IList(Of AzureBlobFileSystemReference) = null, Optional fileServers As IList(Of FileServerReference) = null, Optional unmanagedFileSystems As IList(Of UnmanagedFileSystemReference) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.MountVolumes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.MountVolumes" Usage="new Microsoft.Azure.Management.BatchAI.Models.MountVolumes (azureFileShares, azureBlobFileSystems, fileServers, unmanagedFileSystems)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="azureFileShares" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt;" />
        <Parameter Name="azureBlobFileSystems" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt;" />
        <Parameter Name="fileServers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt;" />
        <Parameter Name="unmanagedFileSystems" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt;" />
      </Parameters>
      <Docs>
        <param name="azureFileShares"><span data-ttu-id="393ae-103">Setupkonfiguration für Azure-Dateifreigabe.</span><span class="sxs-lookup"><span data-stu-id="393ae-103">Azure File Share setup configuration.</span></span></param>
        <param name="azureBlobFileSystems"><span data-ttu-id="393ae-104">Konfiguration von Azure Blob-FileSystem-Setup.</span><span class="sxs-lookup"><span data-stu-id="393ae-104">Azure Blob FileSystem setup configuration.</span></span></param>
        <param name="fileServers"><span data-ttu-id="393ae-105">Verweise auf eine Liste der Dateiserver, die auf dem Clusterknoten eingebunden werden.</span><span class="sxs-lookup"><span data-stu-id="393ae-105">References to a list of file servers that are mounted to the cluster node.</span></span></param>
        <param name="unmanagedFileSystems"><span data-ttu-id="393ae-106">Verweise auf eine Liste der Dateiserver, die auf dem Clusterknoten eingebunden werden.</span><span class="sxs-lookup"><span data-stu-id="393ae-106">References to a list of file servers that are mounted to the cluster node.</span></span></param>
        <summary>
            <span data-ttu-id="393ae-107">Initialisiert eine neue Instanz der MountVolumes-Klasse.</span><span class="sxs-lookup"><span data-stu-id="393ae-107">Initializes a new instance of the MountVolumes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobFileSystems">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; AzureBlobFileSystems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; AzureBlobFileSystems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.AzureBlobFileSystems" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureBlobFileSystems As IList(Of AzureBlobFileSystemReference)" />
      <MemberSignature Language="F#" Value="member this.AzureBlobFileSystems : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountVolumes.AzureBlobFileSystems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureBlobFileSystems")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureBlobFileSystemReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="393ae-108">Ruft ab, oder legt ihn fest Setupkonfiguration für Azure Blob-Dateisystem.</span><span class="sxs-lookup"><span data-stu-id="393ae-108">Gets or sets azure Blob FileSystem setup configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="393ae-109">Verweise auf Azure-BLOB-Sicherung, die auf den Clusterknoten eingebunden werden.</span><span class="sxs-lookup"><span data-stu-id="393ae-109">References to Azure Blob FUSE that are to be mounted to the cluster nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureFileShares">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; AzureFileShares { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; AzureFileShares" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.AzureFileShares" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureFileShares As IList(Of AzureFileShareReference)" />
      <MemberSignature Language="F#" Value="member this.AzureFileShares : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountVolumes.AzureFileShares" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureFileShares")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.AzureFileShareReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="393ae-110">Ruft ab, oder legt ihn fest Setupkonfiguration für Azure-Dateifreigabe.</span><span class="sxs-lookup"><span data-stu-id="393ae-110">Gets or sets azure File Share setup configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="393ae-111">Verweise auf Azure-Dateifreigaben, die auf den Clusterknoten eingebunden werden.</span><span class="sxs-lookup"><span data-stu-id="393ae-111">References to Azure File Shares that are to be mounted to the cluster nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; FileServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; FileServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.FileServers" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServers As IList(Of FileServerReference)" />
      <MemberSignature Language="F#" Value="member this.FileServers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountVolumes.FileServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.FileServerReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="393ae-112">Ermittelt oder definiert Verweise auf eine Liste der Dateiserver, die bereitgestellt werden, auf den Clusterknoten.</span><span class="sxs-lookup"><span data-stu-id="393ae-112">Gets or sets references to a list of file servers that are mounted to the cluster node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmanagedFileSystems">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; UnmanagedFileSystems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; UnmanagedFileSystems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.MountVolumes.UnmanagedFileSystems" />
      <MemberSignature Language="VB.NET" Value="Public Property UnmanagedFileSystems As IList(Of UnmanagedFileSystemReference)" />
      <MemberSignature Language="F#" Value="member this.UnmanagedFileSystems : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.MountVolumes.UnmanagedFileSystems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unmanagedFileSystems")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="393ae-113">Ermittelt oder definiert Verweise auf eine Liste der Dateiserver, die bereitgestellt werden, auf den Clusterknoten.</span><span class="sxs-lookup"><span data-stu-id="393ae-113">Gets or sets references to a list of file servers that are mounted to the cluster node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>