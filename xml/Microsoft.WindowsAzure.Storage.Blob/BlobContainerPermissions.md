<Type Name="BlobContainerPermissions" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions">
  <TypeSignature Language="C#" Value="public sealed class BlobContainerPermissions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobContainerPermissions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobContainerPermissions" />
  <TypeSignature Language="F#" Value="type BlobContainerPermissions = class" />
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
            <span data-ttu-id="625bf-101">Stellt die Berechtigungen für einen Container dar.</span><span class="sxs-lookup"><span data-stu-id="625bf-101">Represents the permissions for a container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobContainerPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="625bf-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="625bf-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicAccess">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType PublicAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType PublicAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions.PublicAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicAccess As BlobContainerPublicAccessType" />
      <MemberSignature Language="F#" Value="member this.PublicAccess : Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions.PublicAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="625bf-103">Ruft ab oder legt die Einstellung für den öffentlichen Zugriff für den Container.</span><span class="sxs-lookup"><span data-stu-id="625bf-103">Gets or sets the public access setting for the container.</span></span>
            </summary>
        <value><span data-ttu-id="625bf-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="625bf-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies SharedAccessPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies SharedAccessPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions.SharedAccessPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessPolicies As SharedAccessBlobPolicies" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicies : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions.SharedAccessPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="625bf-105">Ruft den Satz der freigegebenen Zugriffsrichtlinien für den Container ab.</span><span class="sxs-lookup"><span data-stu-id="625bf-105">Gets the set of shared access policies for the container.</span></span>
            </summary>
        <value><span data-ttu-id="625bf-106">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="625bf-106">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>