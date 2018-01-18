<Type Name="SqlManager" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlManager">
  <TypeSignature Language="C#" Value="public class SqlManager : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;, Microsoft.Azure.Management.Sql.Fluent.ISqlManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlManager extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManagerBase, class Microsoft.Azure.Management.Sql.Fluent.ISqlManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlManager" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlManager&#xA;Inherits Manager(Of ISqlManagementClient)&#xA;Implements IHasInner(Of ISqlManagementClient), IManager(Of ISqlManagementClient), ISqlManager" />
  <TypeSignature Language="F#" Value="type SqlManager = class&#xA;    inherit Manager&lt;ISqlManagementClient&gt;&#xA;    interface ISqlManager&#xA;    interface IManager&lt;ISqlManagementClient&gt;&#xA;    interface IHasInner&lt;ISqlManagementClient&gt;&#xA;    interface IManagerBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Sql.Fluent.ISqlManager</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlManager (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlManager.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.SqlManager : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlManager" Usage="new Microsoft.Azure.Management.Sql.Fluent.SqlManager (restClient, subscriptionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Fluent.ISqlManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Fluent.ISqlManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Authenticate (credentials As AzureCredentials, subscriptionId As String) As ISqlManager" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlManager" Usage="Microsoft.Azure.Management.Sql.Fluent.SqlManager.Authenticate (credentials, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="credentials">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Fluent.ISqlManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Fluent.ISqlManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.Sql.Fluent.ISqlManager" Usage="Microsoft.Azure.Management.Sql.Fluent.SqlManager.Authenticate (restClient, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient"> <span data-ttu-id="0977d-101">die RestClient für API-Aufrufe verwendet werden soll</span><span class="sxs-lookup"><span data-stu-id="0977d-101">the RestClient to be used for API calls</span></span></param>
        <param name="subscriptionId"> <span data-ttu-id="0977d-102">das Abonnement</span><span class="sxs-lookup"><span data-stu-id="0977d-102">the subscription</span></span></param>
        <summary>
            <span data-ttu-id="0977d-103">Erstellt eine Instanz des SqlManager, die Sql-Management-API-Einstiegspunkte verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="0977d-103">Creates an instance of SqlManager that exposes Sql management API entry points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0977d-104">Die SqlManager</span><span class="sxs-lookup"><span data-stu-id="0977d-104">The SqlManager</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Fluent.SqlManager.IConfigurable Configure ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Fluent.SqlManager/IConfigurable Configure() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlManager.Configure" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Configure () As SqlManager.IConfigurable" />
      <MemberSignature Language="F#" Value="static member Configure : unit -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlManager.IConfigurable" Usage="Microsoft.Azure.Management.Sql.Fluent.SqlManager.Configure " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlManager+IConfigurable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.ISqlServers SqlServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Fluent.ISqlServers SqlServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.SqlManager.SqlServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServers As ISqlServers" />
      <MemberSignature Language="F#" Value="member this.SqlServers : Microsoft.Azure.Management.Sql.Fluent.ISqlServers" Usage="Microsoft.Azure.Management.Sql.Fluent.SqlManager.SqlServers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Sql.Fluent.ISqlManager.SqlServers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.ISqlServers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>