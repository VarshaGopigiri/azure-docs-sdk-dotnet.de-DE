<Type Name="BlobContainerProperties" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties">
  <TypeSignature Language="C#" Value="public sealed class BlobContainerProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobContainerProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobContainerProperties" />
  <TypeSignature Language="F#" Value="type BlobContainerProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="47f78-101">Stellt die Systemeigenschaften für einen Container dar.</span><span class="sxs-lookup"><span data-stu-id="47f78-101">Represents the system properties for a container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobContainerProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47f78-102">Ruft den ETag-Wert für den Container ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-102">Gets the ETag value for the container.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-103">Eine Zeichenfolge, die mit dem Container in Anführungszeichen ETag-Wert.</span><span class="sxs-lookup"><span data-stu-id="47f78-103">A string containing the container's quoted ETag value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47f78-104">Ruft die Uhrzeit der letzten Änderung des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-104">Gets the container's last-modified time.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-105">Ein <see cref="T:System.DateTimeOffset" /> , das den Container Last-modified-Zeit im UTC-Format enthält.</span><span class="sxs-lookup"><span data-stu-id="47f78-105">A <see cref="T:System.DateTimeOffset" /> containing the container's last-modified time, in UTC format.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As LeaseDuration" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseDuration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47f78-106">Ruft die Leasedauer des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-106">Gets the container's lease duration.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-107">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseDuration" /> Objekt, das Leasedauer des Containers angibt.</span><span class="sxs-lookup"><span data-stu-id="47f78-107">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseDuration" /> object that indicates the container's lease duration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseState As LeaseState" />
      <MemberSignature Language="F#" Value="member this.LeaseState : Microsoft.WindowsAzure.Storage.Blob.LeaseState" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47f78-108">Ruft Leasezustand des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-108">Gets the container's lease state.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-109">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseState" /> Objekt, das Leasezustand des Containers angibt.</span><span class="sxs-lookup"><span data-stu-id="47f78-109">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseState" /> object that indicates the container's lease state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStatus">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseStatus As LeaseStatus" />
      <MemberSignature Language="F#" Value="member this.LeaseStatus : Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47f78-110">Ruft Leasestatus des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-110">Gets the container's lease status.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-111">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseStatus" /> -Objekt, das Leasestatus des Containers angibt.</span><span class="sxs-lookup"><span data-stu-id="47f78-111">A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.LeaseStatus" /> object that indicates the container's lease status.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicAccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType&gt; PublicAccess { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType&gt; PublicAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.PublicAccess" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicAccess As Nullable(Of BlobContainerPublicAccessType)" />
      <MemberSignature Language="F#" Value="member this.PublicAccess : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties.PublicAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="47f78-112">Ruft den öffentlichen Zugriff für den Container ab.</span><span class="sxs-lookup"><span data-stu-id="47f78-112">Gets the public access for the container.</span></span>
            </summary>
        <value><span data-ttu-id="47f78-113">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> , die angibt, dass die Stufe des öffentlichen Zugriffs, der für den Container zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="47f78-113">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> that specifies the level of public access that is allowed on the container.</span></span></value>
        <remarks><span data-ttu-id="47f78-114">Dieses Feld sollte nur festgelegt werden mithilfe des Containers Create()--Methode oder SetPermissions()-Methode</span><span class="sxs-lookup"><span data-stu-id="47f78-114">This field should only be set using the container's Create() method or SetPermissions() method</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>