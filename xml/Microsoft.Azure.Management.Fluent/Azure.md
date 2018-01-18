<Type Name="Azure" FullName="Microsoft.Azure.Management.Fluent.Azure">
  <TypeSignature Language="C#" Value="public class Azure : Microsoft.Azure.Management.Fluent.IAzure, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Azure extends System.Object implements class Microsoft.Azure.Management.Fluent.IAzure, class Microsoft.Azure.Management.Fluent.IAzureBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Fluent.Azure" />
  <TypeSignature Language="VB.NET" Value="Public Class Azure&#xA;Implements IAzure, IBeta" />
  <TypeSignature Language="F#" Value="type Azure = class&#xA;    interface IAzure&#xA;    interface IAzureBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Fluent.IAzure</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessManagement">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Fluent.IAccessManagement AccessManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Fluent.IAccessManagement AccessManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.AccessManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessManagement As IAccessManagement" />
      <MemberSignature Language="F#" Value="member this.AccessManagement : Microsoft.Azure.Management.Fluent.IAccessManagement" Usage="Microsoft.Azure.Management.Fluent.Azure.AccessManagement" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.AccessManagement</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Fluent.IAccessManagement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ApplicationGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationGateways As IApplicationGateways" />
      <MemberSignature Language="F#" Value="member this.ApplicationGateways : Microsoft.Azure.Management.Network.Fluent.IApplicationGateways" Usage="Microsoft.Azure.Management.Fluent.Azure.ApplicationGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.ApplicationGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-101">Einstiegspunkt für die Verwaltung des Anwendungsgateways</span><span class="sxs-lookup"><span data-stu-id="068c3-101">entry point to managing application gateways</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager AppServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager AppServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.AppServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServices As IAppServiceManager" />
      <MemberSignature Language="F#" Value="member this.AppServices : Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager" Usage="Microsoft.Azure.Management.Fluent.Azure.AppServices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.AppServices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-102">Einstiegspunkt für die Verwaltung von app-Dienste</span><span class="sxs-lookup"><span data-stu-id="068c3-102">entry point to managing app services</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Fluent.Azure.IAuthenticated Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials azureCredentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Fluent.Azure/IAuthenticated Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials azureCredentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Fluent.Azure.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials)" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials -&gt; Microsoft.Azure.Management.Fluent.Azure.IAuthenticated" Usage="Microsoft.Azure.Management.Fluent.Azure.Authenticate azureCredentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Fluent.Azure+IAuthenticated</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="azureCredentials" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" />
      </Parameters>
      <Docs>
        <param name="azureCredentials">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Fluent.Azure.IAuthenticated Authenticate (string authFile);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Fluent.Azure/IAuthenticated Authenticate(string authFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Fluent.Azure.Authenticate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Authenticate (authFile As String) As Azure.IAuthenticated" />
      <MemberSignature Language="F#" Value="static member Authenticate : string -&gt; Microsoft.Azure.Management.Fluent.Azure.IAuthenticated" Usage="Microsoft.Azure.Management.Fluent.Azure.Authenticate authFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Fluent.Azure+IAuthenticated</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authFile" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authFile">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Fluent.Azure.IAuthenticated Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string tenantId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Fluent.Azure/IAuthenticated Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Fluent.Azure.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.Fluent.Azure.IAuthenticated" Usage="Microsoft.Azure.Management.Fluent.Azure.Authenticate (restClient, tenantId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Fluent.Azure+IAuthenticated</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="tenantId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient">To be added.</param>
        <param name="tenantId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySets AvailabilitySets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySets AvailabilitySets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.AvailabilitySets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySets As IAvailabilitySets" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySets : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySets" Usage="Microsoft.Azure.Management.Fluent.Azure.AvailabilitySets" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.AvailabilitySets</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-103">Einstiegspunkt für die Verwaltung von Verfügbarkeitsgruppen</span><span class="sxs-lookup"><span data-stu-id="068c3-103">entry point to managing availability sets</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.IBatchAccounts BatchAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Fluent.IBatchAccounts BatchAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.BatchAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BatchAccounts As IBatchAccounts" />
      <MemberSignature Language="F#" Value="member this.BatchAccounts : Microsoft.Azure.Management.Batch.Fluent.IBatchAccounts" Usage="Microsoft.Azure.Management.Fluent.Azure.BatchAccounts" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.BatchAccounts</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.IBatchAccounts</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-104">Einstiegspunkt für die Verwaltung von Azure Batch-Konten</span><span class="sxs-lookup"><span data-stu-id="068c3-104">entry point to managing Azure Batch accounts</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CdnProfiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.ICdnProfiles CdnProfiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfiles CdnProfiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.CdnProfiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CdnProfiles As ICdnProfiles" />
      <MemberSignature Language="F#" Value="member this.CdnProfiles : Microsoft.Azure.Management.Cdn.Fluent.ICdnProfiles" Usage="Microsoft.Azure.Management.Fluent.Azure.CdnProfiles" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.CdnProfiles</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.ICdnProfiles</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-105">Einstiegspunkt für die Verwaltung von CDN-Profile</span><span class="sxs-lookup"><span data-stu-id="068c3-105">entry point to managing CDN profiles</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Fluent.Azure.IConfigurable Configure ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Fluent.Azure/IConfigurable Configure() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Fluent.Azure.Configure" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Configure () As Azure.IConfigurable" />
      <MemberSignature Language="F#" Value="static member Configure : unit -&gt; Microsoft.Azure.Management.Fluent.Azure.IConfigurable" Usage="Microsoft.Azure.Management.Fluent.Azure.Configure " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Fluent.Azure+IConfigurable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Fluent.IContainerGroups ContainerGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Fluent.IContainerGroups ContainerGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ContainerGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerGroups As IContainerGroups" />
      <MemberSignature Language="F#" Value="member this.ContainerGroups : Microsoft.Azure.Management.ContainerInstance.Fluent.IContainerGroups" Usage="Microsoft.Azure.Management.Fluent.Azure.ContainerGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.ContainerGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Fluent.IContainerGroups</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistries">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Fluent.IRegistries ContainerRegistries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Fluent.IRegistries ContainerRegistries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ContainerRegistries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerRegistries As IRegistries" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistries : Microsoft.Azure.Management.ContainerRegistry.Fluent.IRegistries" Usage="Microsoft.Azure.Management.Fluent.Azure.ContainerRegistries" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.ContainerRegistries</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Fluent.IRegistries</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerService.Fluent.IContainerServices ContainerServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerService.Fluent.IContainerServices ContainerServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ContainerServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerServices As IContainerServices" />
      <MemberSignature Language="F#" Value="member this.ContainerServices : Microsoft.Azure.Management.ContainerService.Fluent.IContainerServices" Usage="Microsoft.Azure.Management.Fluent.Azure.ContainerServices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.ContainerServices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerService.Fluent.IContainerServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CosmosDBAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.CosmosDB.Fluent.ICosmosDBAccounts CosmosDBAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.CosmosDB.Fluent.ICosmosDBAccounts CosmosDBAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.CosmosDBAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CosmosDBAccounts As ICosmosDBAccounts" />
      <MemberSignature Language="F#" Value="member this.CosmosDBAccounts : Microsoft.Azure.Management.CosmosDB.Fluent.ICosmosDBAccounts" Usage="Microsoft.Azure.Management.Fluent.Azure.CosmosDBAccounts" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.CosmosDBAccounts</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.CosmosDB.Fluent.ICosmosDBAccounts</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deployments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IDeployments Deployments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IDeployments Deployments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Deployments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Deployments As IDeployments" />
      <MemberSignature Language="F#" Value="member this.Deployments : Microsoft.Azure.Management.ResourceManager.Fluent.IDeployments" Usage="Microsoft.Azure.Management.Fluent.Azure.Deployments" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Deployments</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IDeployments</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-106">Einstiegspunkt zum Verwalten von Bereitstellungen</span><span class="sxs-lookup"><span data-stu-id="068c3-106">entry point to managing deployments</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDisks Disks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IDisks Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Disks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Disks As IDisks" />
      <MemberSignature Language="F#" Value="member this.Disks : Microsoft.Azure.Management.Compute.Fluent.IDisks" Usage="Microsoft.Azure.Management.Fluent.Azure.Disks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Disks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDisks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsZones">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.IDnsZones DnsZones { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.IDnsZones DnsZones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.DnsZones" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsZones As IDnsZones" />
      <MemberSignature Language="F#" Value="member this.DnsZones : Microsoft.Azure.Management.Dns.Fluent.IDnsZones" Usage="Microsoft.Azure.Management.Fluent.Azure.DnsZones" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.DnsZones</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.IDnsZones</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-107">Einstiegspunkt für die Verwaltung von DNS-Zonen</span><span class="sxs-lookup"><span data-stu-id="068c3-107">entry point to managing DNS zones</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits ExpressRouteCircuits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits ExpressRouteCircuits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ExpressRouteCircuits" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuits As IExpressRouteCircuits" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuits : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits" Usage="Microsoft.Azure.Management.Fluent.Azure.ExpressRouteCircuits" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.ExpressRouteCircuits</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription GetCurrentSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription GetCurrentSubscription() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Fluent.Azure.GetCurrentSubscription" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentSubscription () As ISubscription" />
      <MemberSignature Language="F#" Value="abstract member GetCurrentSubscription : unit -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription&#xA;override this.GetCurrentSubscription : unit -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription" Usage="azure.GetCurrentSubscription " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Fluent.IAzure.GetCurrentSubscription</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns><span data-ttu-id="068c3-108">das aktuell ausgewählte Abonnement für diesen Client authentifiziert wird, für die Zusammenarbeit mit</span><span class="sxs-lookup"><span data-stu-id="068c3-108">the currently selected subscription this client is authenticated to work with</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KubernetesClusters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerService.Fluent.IKubernetesClusters KubernetesClusters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerService.Fluent.IKubernetesClusters KubernetesClusters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.KubernetesClusters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KubernetesClusters As IKubernetesClusters" />
      <MemberSignature Language="F#" Value="member this.KubernetesClusters : Microsoft.Azure.Management.ContainerService.Fluent.IKubernetesClusters" Usage="Microsoft.Azure.Management.Fluent.Azure.KubernetesClusters" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.KubernetesClusters</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerService.Fluent.IKubernetesClusters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.LoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancers As ILoadBalancers" />
      <MemberSignature Language="F#" Value="member this.LoadBalancers : Microsoft.Azure.Management.Network.Fluent.ILoadBalancers" Usage="Microsoft.Azure.Management.Fluent.Azure.LoadBalancers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.LoadBalancers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-109">Einstiegspunkt für die Verwaltung von virtuellen Lastenausgleichsmodule</span><span class="sxs-lookup"><span data-stu-id="068c3-109">entry point to managing virtual load balancers</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways LocalNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways LocalNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.LocalNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalNetworkGateways As ILocalNetworkGateways" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateways : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways" Usage="Microsoft.Azure.Management.Fluent.Azure.LocalNetworkGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.LocalNetworkGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementLocks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Locks.Fluent.IManagementLocks ManagementLocks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Locks.Fluent.IManagementLocks ManagementLocks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ManagementLocks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagementLocks As IManagementLocks" />
      <MemberSignature Language="F#" Value="member this.ManagementLocks : Microsoft.Azure.Management.Locks.Fluent.IManagementLocks" Usage="Microsoft.Azure.Management.Fluent.Azure.ManagementLocks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.ManagementLocks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Locks.Fluent.IManagementLocks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As INetworkInterfaces" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces" Usage="Microsoft.Azure.Management.Fluent.Azure.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.NetworkInterfaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-110">Einstiegspunkt für die Verwaltung von Netzwerkschnittstellen</span><span class="sxs-lookup"><span data-stu-id="068c3-110">entry point to managing network interfaces</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Networks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworks Networks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworks Networks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Networks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Networks As INetworks" />
      <MemberSignature Language="F#" Value="member this.Networks : Microsoft.Azure.Management.Network.Fluent.INetworks" Usage="Microsoft.Azure.Management.Fluent.Azure.Networks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Networks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-111">Einstiegspunkt für die Verwaltung von virtuellen Netzwerken</span><span class="sxs-lookup"><span data-stu-id="068c3-111">entry point to managing virtual networks</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.NetworkSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroups As INetworkSecurityGroups" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroups : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups" Usage="Microsoft.Azure.Management.Fluent.Azure.NetworkSecurityGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.NetworkSecurityGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-112">Einstiegspunkt für die Verwaltung von netzwerksicherheitsgruppen</span><span class="sxs-lookup"><span data-stu-id="068c3-112">entry point to managing network security groups</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWatchers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkWatchers NetworkWatchers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkWatchers NetworkWatchers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.NetworkWatchers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWatchers As INetworkWatchers" />
      <MemberSignature Language="F#" Value="member this.NetworkWatchers : Microsoft.Azure.Management.Network.Fluent.INetworkWatchers" Usage="Microsoft.Azure.Management.Fluent.Azure.NetworkWatchers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.NetworkWatchers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkWatchers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddresses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.PublicIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddresses As IPublicIPAddresses" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddresses : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses" Usage="Microsoft.Azure.Management.Fluent.Azure.PublicIPAddresses" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.PublicIPAddresses</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-113">Einstiegspunkt für die öffentliche IP-Adressen verwalten</span><span class="sxs-lookup"><span data-stu-id="068c3-113">entry point to managing public IP addresses</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisCaches">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.IRedisCaches RedisCaches { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Fluent.IRedisCaches RedisCaches" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.RedisCaches" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisCaches As IRedisCaches" />
      <MemberSignature Language="F#" Value="member this.RedisCaches : Microsoft.Azure.Management.Redis.Fluent.IRedisCaches" Usage="Microsoft.Azure.Management.Fluent.Azure.RedisCaches" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.RedisCaches</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.IRedisCaches</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-114">Einstiegspunkt zum Verwalten von Redis-caches</span><span class="sxs-lookup"><span data-stu-id="068c3-114">entry point to managing Redis caches</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups ResourceGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups ResourceGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ResourceGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroups As IResourceGroups" />
      <MemberSignature Language="F#" Value="member this.ResourceGroups : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups" Usage="Microsoft.Azure.Management.Fluent.Azure.ResourceGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.ResourceGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-115">Einstiegspunkt für die Verwaltung von Ressourcengruppen</span><span class="sxs-lookup"><span data-stu-id="068c3-115">entry point to managing resource groups</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Search.Fluent.ISearchServices SearchServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Search.Fluent.ISearchServices SearchServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.SearchServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchServices As ISearchServices" />
      <MemberSignature Language="F#" Value="member this.SearchServices : Microsoft.Azure.Management.Search.Fluent.ISearchServices" Usage="Microsoft.Azure.Management.Fluent.Azure.SearchServices" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.SearchServices</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Fluent.ISearchServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces ServiceBusNamespaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces ServiceBusNamespaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.ServiceBusNamespaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusNamespaces As IServiceBusNamespaces" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespaces : Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces" Usage="Microsoft.Azure.Management.Fluent.Azure.ServiceBusNamespaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.ServiceBusNamespaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshots">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.ISnapshots Snapshots { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.ISnapshots Snapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Snapshots" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Snapshots As ISnapshots" />
      <MemberSignature Language="F#" Value="member this.Snapshots : Microsoft.Azure.Management.Compute.Fluent.ISnapshots" Usage="Microsoft.Azure.Management.Fluent.Azure.Snapshots" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Snapshots</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.ISnapshots</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlServers SqlServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Fluent.ISqlServers SqlServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.SqlServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServers As ISqlServers" />
      <MemberSignature Language="F#" Value="member this.SqlServers : Microsoft.Azure.Management.Sql.Fluent.ISqlServers" Usage="Microsoft.Azure.Management.Fluent.Azure.SqlServers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.SqlServers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlServers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-116">Einstiegspunkt für die Verwaltung von SQL Server</span><span class="sxs-lookup"><span data-stu-id="068c3-116">entry point to managing SQL servers</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.IStorageAccounts StorageAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.IStorageAccounts StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccounts As IStorageAccounts" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : Microsoft.Azure.Management.Storage.Fluent.IStorageAccounts" Usage="Microsoft.Azure.Management.Fluent.Azure.StorageAccounts" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.StorageAccounts</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.IStorageAccounts</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-117">Einstiegspunkt für die Verwaltung von Speicherkonten</span><span class="sxs-lookup"><span data-stu-id="068c3-117">entry point to managing storage accounts</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.Fluent.Azure.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-118">die aktuell ausgewählte Abonnement-ID dieser Client wird authentifiziert, um das Arbeiten mit</span><span class="sxs-lookup"><span data-stu-id="068c3-118">the currently selected subscription ID this client is authenticated to work with</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscriptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions Subscriptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions Subscriptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Subscriptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscriptions As ISubscriptions" />
      <MemberSignature Language="F#" Value="member this.Subscriptions : Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions" Usage="Microsoft.Azure.Management.Fluent.Azure.Subscriptions" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Subscriptions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-119">Abonnements, die diese authentifizierte Client hat Zugriff auf</span><span class="sxs-lookup"><span data-stu-id="068c3-119">subscriptions that this authenticated client has access to</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerProfiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfiles TrafficManagerProfiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfiles TrafficManagerProfiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.TrafficManagerProfiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerProfiles As ITrafficManagerProfiles" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerProfiles : Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfiles" Usage="Microsoft.Azure.Management.Fluent.Azure.TrafficManagerProfiles" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.TrafficManagerProfiles</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfiles</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-120">Einstiegspunkt für die Verwaltung von Traffic Manager-Profile</span><span class="sxs-lookup"><span data-stu-id="068c3-120">entry point to managing Traffic Manager profiles</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.IVaults Vaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.IVaults Vaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.Vaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Vaults As IVaults" />
      <MemberSignature Language="F#" Value="member this.Vaults : Microsoft.Azure.Management.KeyVault.Fluent.IVaults" Usage="Microsoft.Azure.Management.Fluent.Azure.Vaults" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.Vaults</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.IVaults</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-121">Einstiegspunkt für die Verwaltung von Azure Key Tresoren</span><span class="sxs-lookup"><span data-stu-id="068c3-121">entry point to managing Azure key vaults</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineCustomImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImages VirtualMachineCustomImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImages VirtualMachineCustomImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualMachineCustomImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineCustomImages As IVirtualMachineCustomImages" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineCustomImages : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImages" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualMachineCustomImages" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.VirtualMachineCustomImages</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImages</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensionImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImages VirtualMachineExtensionImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImages VirtualMachineExtensionImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualMachineExtensionImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensionImages As IVirtualMachineExtensionImages" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensionImages : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImages" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualMachineExtensionImages" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.VirtualMachineExtensionImages</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImages</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-122">Einstiegspunkt für die Verwaltung von virtuellen Computerimages-Erweiterung</span><span class="sxs-lookup"><span data-stu-id="068c3-122">entry point to managing virtual machine extension images</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages VirtualMachineImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages VirtualMachineImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualMachineImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImages As IVirtualMachineImages" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImages : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualMachineImages" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.VirtualMachineImages</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImages</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-123">Einstiegspunkt für die Verwaltung von Images virtueller Computer</span><span class="sxs-lookup"><span data-stu-id="068c3-123">entry point to managing virtual machine images</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachines VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachines VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachines" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachines" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualMachines" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.VirtualMachines</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachines</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-124">Einstiegspunkt für die Verwaltung virtueller Computer</span><span class="sxs-lookup"><span data-stu-id="068c3-124">entry point to managing virtual machines</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSets VirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSets VirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSets As IVirtualMachineScaleSets" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSets : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSets" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualMachineScaleSets" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzure.VirtualMachineScaleSets</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-125">Einstiegspunkt für die Verwaltung von VM-skalierungsgruppen</span><span class="sxs-lookup"><span data-stu-id="068c3-125">entry point to managing virtual machine scale sets</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways VirtualNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways VirtualNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.VirtualNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGateways As IVirtualNetworkGateways" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateways : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways" Usage="Microsoft.Azure.Management.Fluent.Azure.VirtualNetworkGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.VirtualNetworkGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IWebApps WebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.IWebApps WebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Fluent.Azure.WebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebApps As IWebApps" />
      <MemberSignature Language="F#" Value="member this.WebApps : Microsoft.Azure.Management.AppService.Fluent.IWebApps" Usage="Microsoft.Azure.Management.Fluent.Azure.WebApps" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Fluent.IAzureBeta.WebApps</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IWebApps</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="068c3-126">Einstiegspunkt für die Verwaltung von Web-apps</span><span class="sxs-lookup"><span data-stu-id="068c3-126">entry point to managing web apps</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>