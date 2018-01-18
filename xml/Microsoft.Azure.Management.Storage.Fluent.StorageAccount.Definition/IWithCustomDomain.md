<Type Name="IWithCustomDomain" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain">
  <TypeSignature Language="C#" Value="public interface IWithCustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCustomDomain" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCustomDomain" />
  <TypeSignature Language="F#" Value="type IWithCustomDomain = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d210c-101">Eine speicherkontendefinition angeben einer benutzerdefinierten Domäne mit dem Konto zuordnen.</span><span class="sxs-lookup"><span data-stu-id="d210c-101">A storage account definition specifying a custom domain to associate with the account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain customDomain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
      </Parameters>
      <Docs>
        <param name="customDomain"><span data-ttu-id="d210c-102">Der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="d210c-102">The user domain assigned to the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="d210c-103">Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="d210c-103">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d210c-104">Die nächste Phase der speicherkontendefinition.</span><span class="sxs-lookup"><span data-stu-id="d210c-104">The next stage of storage account definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d210c-105">Die benutzerdefinierten Domänennamen, der die Quelle der CNAME ist.</span><span class="sxs-lookup"><span data-stu-id="d210c-105">The custom domain name, which is the CNAME source.</span></span></param>
        <summary>
            <span data-ttu-id="d210c-106">Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="d210c-106">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d210c-107">Die nächste Phase der speicherkontendefinition.</span><span class="sxs-lookup"><span data-stu-id="d210c-107">The next stage of storage account definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (string name, bool useSubDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(string name, bool useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String, useSubDomain As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string * bool -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain (name, useSubDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d210c-108">Die benutzerdefinierten Domänennamen, der die Quelle der CNAME ist.</span><span class="sxs-lookup"><span data-stu-id="d210c-108">The custom domain name, which is the CNAME source.</span></span></param>
        <param name="useSubDomain"><span data-ttu-id="d210c-109">Gibt an, ob indirekte CName-Überprüfung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="d210c-109">Whether indirect CName validation is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="d210c-110">Gibt an, der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="d210c-110">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d210c-111">Die nächste Phase der speicherkontendefinition.</span><span class="sxs-lookup"><span data-stu-id="d210c-111">The next stage of storage account definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>