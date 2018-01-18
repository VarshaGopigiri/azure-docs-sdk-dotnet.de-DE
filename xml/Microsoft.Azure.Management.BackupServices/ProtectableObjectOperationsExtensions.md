<Type Name="ProtectableObjectOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectableObjectOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectableObjectOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse ListCSM (this Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse ListCSM(class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSM(Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSM : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSM (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="307c7-101">Verweis auf die Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations.</span><span class="sxs-lookup"><span data-stu-id="307c7-101">Reference to the Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="307c7-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="307c7-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="307c7-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="307c7-103">Required.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="307c7-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="307c7-104">Optional.</span></span> <span data-ttu-id="307c7-105">Abfrageparameter Schützbare Objekte hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="307c7-105">Protectable objects query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="307c7-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="307c7-106">Optional.</span></span> <span data-ttu-id="307c7-107">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="307c7-107">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="307c7-108">Rufen Sie die Liste aller Elemente</span><span class="sxs-lookup"><span data-stu-id="307c7-108">Get the list of all items</span></span>
            </summary>
        <returns>
            <span data-ttu-id="307c7-109">Die Definition einer CSMItemListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="307c7-109">The definition of a CSMItemListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync (this Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync(class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSMAsync(Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSMAsync : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSMAsync (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="307c7-110">Verweis auf die Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations.</span><span class="sxs-lookup"><span data-stu-id="307c7-110">Reference to the Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="307c7-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="307c7-111">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="307c7-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="307c7-112">Required.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="307c7-113">Optional.</span><span class="sxs-lookup"><span data-stu-id="307c7-113">Optional.</span></span> <span data-ttu-id="307c7-114">Abfrageparameter Schützbare Objekte hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="307c7-114">Protectable objects query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="307c7-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="307c7-115">Optional.</span></span> <span data-ttu-id="307c7-116">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="307c7-116">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="307c7-117">Rufen Sie die Liste aller Elemente</span><span class="sxs-lookup"><span data-stu-id="307c7-117">Get the list of all items</span></span>
            </summary>
        <returns>
            <span data-ttu-id="307c7-118">Die Definition einer CSMItemListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="307c7-118">The definition of a CSMItemListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>