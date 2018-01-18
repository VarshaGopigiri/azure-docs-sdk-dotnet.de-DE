<Type Name="IDeploymentOperation" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation">
  <TypeSignature Language="C#" Value="public interface IDeploymentOperation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeploymentOperation implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeploymentOperation&#xA;Implements IHasInner(Of DeploymentOperationInner), IIndexable, IRefreshable(Of IDeploymentOperation)" />
  <TypeSignature Language="F#" Value="type IDeploymentOperation = interface&#xA;    interface IIndexable&#xA;    interface IRefreshable&lt;IDeploymentOperation&gt;&#xA;    interface IHasInner&lt;DeploymentOperationInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1f774-101">Eine unveränderliche clientseitige Darstellung von einem Bereitstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="1f774-101">An immutable client-side representation of a deployment operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-102">die Bereitstellungsvorgangs-id</span><span class="sxs-lookup"><span data-stu-id="1f774-102">the deployment operation id</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-103">der Status der Bereitstellung Ressource wird bereitgestellt</span><span class="sxs-lookup"><span data-stu-id="1f774-103">the state of the provisioning resource being deployed</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public string StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As String" />
      <MemberSignature Language="F#" Value="member this.StatusCode : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-104">der Statuscode des Vorgangs. =</span><span class="sxs-lookup"><span data-stu-id="1f774-104">the operation status code.=</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public object StatusMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusMessage As Object" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : obj" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-105">die Statusmeldung des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="1f774-105">the operation status message</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.TargetResource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetResource As TargetResource" />
      <MemberSignature Language="F#" Value="member this.TargetResource : Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.TargetResource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-106">die Zielressource</span><span class="sxs-lookup"><span data-stu-id="1f774-106">the target resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IDeploymentOperation.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="1f774-107">das Datum und die Uhrzeit des Vorgangs</span><span class="sxs-lookup"><span data-stu-id="1f774-107">the date and time of the operation</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>