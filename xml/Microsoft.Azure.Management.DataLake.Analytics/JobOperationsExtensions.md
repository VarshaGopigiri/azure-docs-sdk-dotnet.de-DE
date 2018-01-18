<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f3b2c-101">Erweiterungsmethoden für JobOperations.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-101">Extension methods for JobOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Build (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Build(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Build(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Build (operations As IJobOperations, accountName As String, parameters As BuildJobParameters) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Build : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Build (operations, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-103">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-103">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f3b2c-104">Die Parameter für einen Auftrag zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-104">The parameters to build a job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-105">Erstellt (kompiliert) dem angegebenen Auftrag in das angegebene Data Lake Analytics-Konto für Auftrags korrektheits- und Validierung.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-105">Builds (compiles) the specified job in the specified Data Lake Analytics account for job correctness and validation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; BuildAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; BuildAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.BuildAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BuildAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.BuildAsync (operations, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;BuildAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-106">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-107">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-107">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f3b2c-108">Die Parameter für einen Auftrag zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-108">The parameters to build a job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-110">Erstellt (kompiliert) dem angegebenen Auftrag in das angegebene Data Lake Analytics-Konto für Auftrags korrektheits- und Validierung.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-110">Builds (compiles) the specified job in the specified Data Lake Analytics account for job correctness and validation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public static void Cancel (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Cancel(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Cancel(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Cancel (operations As IJobOperations, accountName As String, jobIdentity As Guid)" />
      <MemberSignature Language="F#" Value="static member Cancel : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Cancel (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-111">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-112">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-112">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-113">JobInfo-ID auf "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="f3b2c-113">JobInfo ID to cancel.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-114">Bricht den laufenden Auftrag gemäß der Auftrags-ID ab</span><span class="sxs-lookup"><span data-stu-id="f3b2c-114">Cancels the running job specified by the job ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CancelAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CancelAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;CancelAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-115">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-116">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-116">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-117">JobInfo-ID auf "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="f3b2c-117">JobInfo ID to cancel.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-119">Bricht den laufenden Auftrag gemäß der Auftrags-ID ab</span><span class="sxs-lookup"><span data-stu-id="f3b2c-119">Cancels the running job specified by the job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Create (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Create(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobOperations, accountName As String, jobIdentity As Guid, parameters As CreateJobParameters) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Create (operations, accountName, jobIdentity, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-120">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-121">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-121">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-122">Die Auftrags-ID (eine GUID) für den Auftrag gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-122">The job ID (a GUID) for the job being submitted.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f3b2c-123">Die Parameter für einen Auftrag zu senden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-123">The parameters to submit a job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-124">Übermittelt einen Auftrag für das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-124">Submits a job to the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; CreateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; CreateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CreateAsync (operations, accountName, jobIdentity, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;CreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-125">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-126">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-126">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-127">Die Auftrags-ID (eine GUID) für den Auftrag gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-127">The job ID (a GUID) for the job being submitted.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f3b2c-128">Die Parameter für einen Auftrag zu senden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-128">The parameters to submit a job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-130">Übermittelt einen Auftrag für das angegebene Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-130">Submits a job to the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Exists(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Exists (operations As IJobOperations, accountName As String, jobIdentity As Guid) As Boolean" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Exists (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-131">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-132">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-132">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-133">So testen Sie das Vorhandensein des JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-133">JobInfo ID to test the existence of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-134">Überprüft das Vorhandensein von Auftragsinformationen für die angegebene Auftrags-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-134">Tests the existence of job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ExistsAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-135">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-136">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-136">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-137">So testen Sie das Vorhandensein des JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-137">JobInfo ID to test the existence of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-139">Überprüft das Vorhandensein von Auftragsinformationen für die angegebene Auftrags-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-139">Tests the existence of job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Get (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Get(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Get (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-140">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-141">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-141">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-142">JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-142">JobInfo ID.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-143">Ruft die Auftragsinformationen für die angegebene Auftrags-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-143">Gets the job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-144">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-145">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-145">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-146">JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-146">JobInfo ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-148">Ruft die Auftragsinformationen für die angegebene Auftrags-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-148">Gets the job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugDataPath">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath GetDebugDataPath (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath GetDebugDataPath(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPath(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDebugDataPath (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobDataPath" />
      <MemberSignature Language="F#" Value="static member GetDebugDataPath : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPath (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-149">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-150">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-150">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-151">JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-151">JobInfo ID.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-152">Ruft den Auftrag Daten Debuginformationen gemäß der Auftrags-ID</span><span class="sxs-lookup"><span data-stu-id="f3b2c-152">Gets the job debug data information specified by the job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugDataPathAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt; GetDebugDataPathAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt; GetDebugDataPathAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPathAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDebugDataPathAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPathAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetDebugDataPathAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-153">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-154">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-154">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-155">JobInfo-ID.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-155">JobInfo ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-157">Ruft den Auftrag Daten Debuginformationen gemäß der Auftrags-ID</span><span class="sxs-lookup"><span data-stu-id="f3b2c-157">Gets the job debug data information specified by the job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics GetStatistics (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics GetStatistics(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatistics(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStatistics (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobStatistics" />
      <MemberSignature Language="F#" Value="static member GetStatistics : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatistics (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-158">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-159">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-159">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-160">Auftrags-ID Informationen auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-160">Job Information ID.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-161">Ruft die Statistiken des angegebenen Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-161">Gets statistics of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt; GetStatisticsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt; GetStatisticsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatisticsAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatisticsAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatisticsAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetStatisticsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-162">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-163">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-163">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="f3b2c-164">Auftrags-ID Informationen auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-164">Job Information ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-166">Ruft die Statistiken des angegebenen Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-166">Gets statistics of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobOperations, accountName As String, Optional odataQuery As ODataQuery(Of JobInformation) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of JobInformationBasic)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.List (operations, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-167">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-168">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-168">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f3b2c-169">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-169">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="f3b2c-170">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-170">OData Select statement.</span></span> <span data-ttu-id="f3b2c-171">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-171">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="f3b2c-172">Optional.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-172">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="f3b2c-173">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="f3b2c-173">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="f3b2c-174">Optional.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-174">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-175">Listet die Aufträge auf, wenn vorhanden, die das angegebene Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-175">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="f3b2c-176">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-176">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListAsync (operations, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-177">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="f3b2c-178">Das Azure Data Lake Analytics-Konto zum Ausführen des auftragsvorgänge auf.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-178">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="f3b2c-179">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-179">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="f3b2c-180">OData-Select-Anweisung.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-180">OData Select statement.</span></span> <span data-ttu-id="f3b2c-181">Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-181">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="f3b2c-182">Optional.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-182">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="f3b2c-183">Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true".</span><span class="sxs-lookup"><span data-stu-id="f3b2c-183">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="f3b2c-184">Optional.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-184">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-186">Listet die Aufträge auf, wenn vorhanden, die das angegebene Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-186">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="f3b2c-187">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-187">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobOperations, nextPageLink As String) As IPage(Of JobInformationBasic)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f3b2c-189">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-190">Listet die Aufträge auf, wenn vorhanden, die das angegebene Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-190">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="f3b2c-191">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-191">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f3b2c-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-192">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f3b2c-193">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-193">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f3b2c-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f3b2c-195">Listet die Aufträge auf, wenn vorhanden, die das angegebene Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-195">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="f3b2c-196">Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f3b2c-196">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>