<Type Name="LinuxVMDiskEncryptionConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration">
  <TypeSignature Language="C#" Value="public sealed class LinuxVMDiskEncryptionConfiguration : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinuxVMDiskEncryptionConfiguration extends Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1&lt;class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinuxVMDiskEncryptionConfiguration&#xA;Inherits VirtualMachineEncryptionConfiguration(Of LinuxVMDiskEncryptionConfiguration)" />
  <TypeSignature Language="F#" Value="type LinuxVMDiskEncryptionConfiguration = class&#xA;    inherit VirtualMachineEncryptionConfiguration&lt;LinuxVMDiskEncryptionConfiguration&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="d879b-101">Geben Sie für Einstellungen für die Verschlüsselung auf einem virtuellen Linux-Computer angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d879b-101">Type representing encryption settings to be applied to a Linux virtual machine.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxVMDiskEncryptionConfiguration (string keyVaultId, string aadClientId, string aadSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyVaultId, string aadClientId, string aadSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyVaultId As String, aadClientId As String, aadSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration (keyVaultId, aadClientId, aadSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="aadClientId" Type="System.String" />
        <Parameter Name="aadSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyVaultId"><span data-ttu-id="d879b-102">Die Ressourcen-Id des schlüsseltresors auf den Datenträger-Verschlüsselungsschlüssel zu speichern.</span><span class="sxs-lookup"><span data-stu-id="d879b-102">The resource id of the key vault to store the disk encryption key.</span></span></param>
        <param name="aadClientId"><span data-ttu-id="d879b-103">Client-Id einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</span><span class="sxs-lookup"><span data-stu-id="d879b-103">Client id of an AAD application which has permission to the key vault.</span></span></param>
        <param name="aadSecret"><span data-ttu-id="d879b-104">Der geheime Clientschlüssel, der AadClientId entspricht.</span><span class="sxs-lookup"><span data-stu-id="d879b-104">Client secret corresponding to the aadClientId.</span></span></param>
        <summary>
             <span data-ttu-id="d879b-105">LinuxVMDiskEncryptionSettings wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="d879b-105">Creates LinuxVMDiskEncryptionSettings.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function OsType () As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="override this.OsType : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="linuxVMDiskEncryptionConfiguration.OsType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPassPhrase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration WithPassPhrase (string passPhrase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration WithPassPhrase(string passPhrase) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.WithPassPhrase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPassPhrase (passPhrase As String) As LinuxVMDiskEncryptionConfiguration" />
      <MemberSignature Language="F#" Value="member this.WithPassPhrase : string -&gt; Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" Usage="linuxVMDiskEncryptionConfiguration.WithPassPhrase passPhrase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="passPhrase" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="passPhrase"><span data-ttu-id="d879b-106">Die Passphrase.</span><span class="sxs-lookup"><span data-stu-id="d879b-106">The pass phrase.</span></span></param>
        <summary>
             <span data-ttu-id="d879b-107">Gibt die Passphrase zum Verschlüsseln von Linux-Betriebssystem oder Daten Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="d879b-107">Specifies the pass phrase for encrypting Linux OS or data disks.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d879b-108">LinuxVMDiskEncryptionSettings.</span><span class="sxs-lookup"><span data-stu-id="d879b-108">LinuxVMDiskEncryptionSettings.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>