<Type Name="IFunctionApp" FullName="Microsoft.Azure.Management.AppService.Fluent.IFunctionApp">
  <TypeSignature Language="C#" Value="public interface IFunctionApp : Microsoft.Azure.Management.AppService.Fluent.IWebAppBase, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IFunctionApp&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFunctionApp implements class Microsoft.Azure.Management.AppService.Fluent.IWebAppBase, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IFunctionApp&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFunctionApp&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, SiteInner), IHasInner(Of SiteInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IFunctionApp), IUpdatable(Of IUpdate), IWebAppBase" />
  <TypeSignature Language="F#" Value="type IFunctionApp = interface&#xA;    interface IBeta&#xA;    interface IWebAppBase&#xA;    interface IHasName&#xA;    interface IGroupableResource&lt;IAppServiceManager, SiteInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;SiteInner&gt;&#xA;    interface IRefreshable&lt;IFunctionApp&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.IWebAppBase</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IFunctionApp&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8527a-101">Eine unveränderliche clientseitige Darstellung der App ein Azure-Funktion.</span><span class="sxs-lookup"><span data-stu-id="8527a-101">An immutable client-side representation of an Azure Function App.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8527a-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="8527a-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AddFunctionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair AddFunctionKey (string functionName, string keyName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair AddFunctionKey(string functionName, string keyName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.AddFunctionKey(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddFunctionKey (functionName As String, keyName As String, keyValue As String) As NameValuePair" />
      <MemberSignature Language="F#" Value="abstract member AddFunctionKey : string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair" Usage="iFunctionApp.AddFunctionKey (functionName, keyName, keyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="keyValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddFunctionKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; AddFunctionKeyAsync (string functionName, string keyName, string keyValue, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; AddFunctionKeyAsync(string functionName, string keyName, string keyValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.AddFunctionKeyAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddFunctionKeyAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;" Usage="iFunctionApp.AddFunctionKeyAsync (functionName, keyName, keyValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="keyValue">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentSlots">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IFunctionDeploymentSlots DeploymentSlots { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.IFunctionDeploymentSlots DeploymentSlots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.DeploymentSlots" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentSlots As IFunctionDeploymentSlots" />
      <MemberSignature Language="F#" Value="member this.DeploymentSlots : Microsoft.Azure.Management.AppService.Fluent.IFunctionDeploymentSlots" Usage="Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.DeploymentSlots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IFunctionDeploymentSlots</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMasterKey">
      <MemberSignature Language="C#" Value="public string GetMasterKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetMasterKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.GetMasterKey" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMasterKey () As String" />
      <MemberSignature Language="F#" Value="abstract member GetMasterKey : unit -&gt; string" Usage="iFunctionApp.GetMasterKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8527a-103">Der Hauptschlüssel für die Funktion-app.</span><span class="sxs-lookup"><span data-stu-id="8527a-103">The master key for the function app.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetMasterKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetMasterKeyAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetMasterKeyAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.GetMasterKeyAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMasterKeyAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iFunctionApp.GetMasterKeyAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8527a-104">Der Hauptschlüssel für die Funktion-app.</span><span class="sxs-lookup"><span data-stu-id="8527a-104">The master key for the function app.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListFunctionKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; ListFunctionKeys (string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; ListFunctionKeys(string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.ListFunctionKeys(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListFunctionKeys (functionName As String) As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="abstract member ListFunctionKeys : string -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="iFunctionApp.ListFunctionKeys functionName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFunctionKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt;&gt; ListFunctionKeysAsync (string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt;&gt; ListFunctionKeysAsync(string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.ListFunctionKeysAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFunctionKeysAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;&gt;" Usage="iFunctionApp.ListFunctionKeysAsync (functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFunctionKey">
      <MemberSignature Language="C#" Value="public void RemoveFunctionKey (string functionName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveFunctionKey(string functionName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.RemoveFunctionKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFunctionKey (functionName As String, keyName As String)" />
      <MemberSignature Language="F#" Value="abstract member RemoveFunctionKey : string * string -&gt; unit" Usage="iFunctionApp.RemoveFunctionKey (functionName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <param name="keyName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFunctionKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFunctionKeyAsync (string functionName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveFunctionKeyAsync(string functionName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.RemoveFunctionKeyAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveFunctionKeyAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iFunctionApp.RemoveFunctionKeyAsync (functionName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="functionName">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.IStorageAccount StorageAccount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccount As IStorageAccount" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" Usage="Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.IStorageAccount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8527a-105">Ruft das Speicherkonto, das die Funktion app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="8527a-105">Gets the storage account associated with the function app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncTriggers">
      <MemberSignature Language="C#" Value="public void SyncTriggers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SyncTriggers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.SyncTriggers" />
      <MemberSignature Language="VB.NET" Value="Public Sub SyncTriggers ()" />
      <MemberSignature Language="F#" Value="abstract member SyncTriggers : unit -&gt; unit" Usage="iFunctionApp.SyncTriggers " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncTriggersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SyncTriggersAsync { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Threading.Tasks.Task SyncTriggersAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.SyncTriggersAsync" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncTriggersAsync As Task" />
      <MemberSignature Language="F#" Value="member this.SyncTriggersAsync : System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.IFunctionApp.SyncTriggersAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>