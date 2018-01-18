<Type Name="IApplication" FullName="Microsoft.Azure.Management.Batch.Fluent.IApplication">
  <TypeSignature Language="C#" Value="public interface IApplication : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Batch.Fluent.IApplication,Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Batch.Fluent.IApplication&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplication implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Batch.Fluent.IApplication, class Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Batch.Fluent.IApplication&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.IApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplication&#xA;Implements IChildResource(Of IBatchAccount), IExternalChildResource(Of IApplication, IBatchAccount), IHasInner(Of ApplicationInner), IHasParent(Of IBatchAccount), IRefreshable(Of IApplication)" />
  <TypeSignature Language="F#" Value="type IApplication = interface&#xA;    interface IExternalChildResource&lt;IApplication, IBatchAccount&gt;&#xA;    interface IChildResource&lt;IBatchAccount&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IBatchAccount&gt;&#xA;    interface IRefreshable&lt;IApplication&gt;&#xA;    interface IHasInner&lt;ApplicationInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Batch.Fluent.IApplication,Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Batch.Fluent.IBatchAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Batch.Fluent.IApplication&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1d134-101">Eine unveränderliche clientseitige Darstellung einer Anwendung der Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="1d134-101">An immutable client-side representation of an Azure Batch account application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationPackages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Batch.Fluent.IApplicationPackage&gt; ApplicationPackages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackage&gt; ApplicationPackages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IApplication.ApplicationPackages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationPackages As IReadOnlyDictionary(Of String, IApplicationPackage)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackages : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Batch.Fluent.IApplicationPackage&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.IApplication.ApplicationPackages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Batch.Fluent.IApplicationPackage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d134-102">Ruft die Anwendungspakete ab.</span><span class="sxs-lookup"><span data-stu-id="1d134-102">Gets application packages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultVersion">
      <MemberSignature Language="C#" Value="public string DefaultVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IApplication.DefaultVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultVersion : string" Usage="Microsoft.Azure.Management.Batch.Fluent.IApplication.DefaultVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d134-103">Ruft die Standardversion für die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="1d134-103">Gets the default version for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IApplication.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.Batch.Fluent.IApplication.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d134-104">Ruft den Anzeigenamen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="1d134-104">Gets the display name of the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatesAllowed">
      <MemberSignature Language="C#" Value="public bool UpdatesAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UpdatesAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.IApplication.UpdatesAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatesAllowed As Boolean" />
      <MemberSignature Language="F#" Value="member this.UpdatesAllowed : bool" Usage="Microsoft.Azure.Management.Batch.Fluent.IApplication.UpdatesAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d134-105">Ruft "true", wenn automatische Updates zulässig sind, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="1d134-105">Gets true if automatic updates are allowed, otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>