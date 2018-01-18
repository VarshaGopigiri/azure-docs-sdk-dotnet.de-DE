<Type Name="IWithAccessPolicy" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy">
  <TypeSignature Language="C#" Value="public interface IWithAccessPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAccessPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAccessPolicy" />
  <TypeSignature Language="F#" Value="type IWithAccessPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1aa0-101">Ein schlüsseltresors aktualisieren, sodass Zugriffsrichtlinien geändert, angefügt oder entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="b1aa0-101">A key vault update allowing access policies to be modified, attached, or removed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt; DefineAccessPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt; DefineAccessPolicy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.DefineAccessPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAccessPolicy () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAccessPolicy : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;" Usage="iWithAccessPolicy.DefineAccessPolicy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b1aa0-102">Startet die Definition einer neuen Richtlinie für den Zugriff auf diesen schlüsseltresor hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="b1aa0-102">Begins the definition of a new access policy to be added to this key vault.</span></span>
            </summary>
        <returns><span data-ttu-id="b1aa0-103">die erste Phase der Richtliniendefinition Zugriff</span><span class="sxs-lookup"><span data-stu-id="b1aa0-103">the first stage of the access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate UpdateAccessPolicy (string objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate UpdateAccessPolicy(string objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.UpdateAccessPolicy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAccessPolicy (objectId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateAccessPolicy : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithAccessPolicy.UpdateAccessPolicy objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="b1aa0-104">ObjectId der Objekt-ID des Active Directory-Identität der Zugriffsrichtlinie gilt für</span><span class="sxs-lookup"><span data-stu-id="b1aa0-104">objectId the object ID of the Active Directory identity the access policy is for</span></span></param>
        <summary>
            <span data-ttu-id="b1aa0-105">Startet das Update von einer vorhandenen Richtlinie für den Zugriff auf diesen schlüsseltresor angefügt.</span><span class="sxs-lookup"><span data-stu-id="b1aa0-105">Begins the update of an existing access policy attached to this key vault.</span></span>
            </summary>
        <returns><span data-ttu-id="b1aa0-106">der Update-Phase der Richtliniendefinition Zugriff</span><span class="sxs-lookup"><span data-stu-id="b1aa0-106">the update stage of the access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithAccessPolicy (Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithAccessPolicy(class Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.WithAccessPolicy(Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAccessPolicy (accessPolicy As IAccessPolicy) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAccessPolicy : Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate" Usage="iWithAccessPolicy.WithAccessPolicy accessPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessPolicy" Type="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy" />
      </Parameters>
      <Docs>
        <param name="accessPolicy"><span data-ttu-id="b1aa0-107">AccessPolicy der vorhandenen Zugriffsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="b1aa0-107">accessPolicy the existing access policy</span></span></param>
        <summary>
            <span data-ttu-id="b1aa0-108">Fügen Sie einer vorhandenen Zugriffsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="b1aa0-108">Attach an existing access policy.</span></span>
            </summary>
        <returns><span data-ttu-id="b1aa0-109">die schlüsseltresor-Update-Phase</span><span class="sxs-lookup"><span data-stu-id="b1aa0-109">the key vault update stage</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithoutAccessPolicy (string objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate WithoutAccessPolicy(string objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IWithAccessPolicy.WithoutAccessPolicy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAccessPolicy (objectId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAccessPolicy : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate" Usage="iWithAccessPolicy.WithoutAccessPolicy objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="b1aa0-110">ObjectId der Objekt-ID des Active Directory-Identität der Zugriffsrichtlinie gilt für</span><span class="sxs-lookup"><span data-stu-id="b1aa0-110">objectId the object ID of the Active Directory identity the access policy is for</span></span></param>
        <summary>
            <span data-ttu-id="b1aa0-111">Entfernen Sie eine Zugriffsrichtlinie aus der Zugriffsliste der Richtlinie ein.</span><span class="sxs-lookup"><span data-stu-id="b1aa0-111">Remove an access policy from the access policy list.</span></span>
            </summary>
        <returns><span data-ttu-id="b1aa0-112">die schlüsseltresor-Update-Phase</span><span class="sxs-lookup"><span data-stu-id="b1aa0-112">the key vault update stage</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>