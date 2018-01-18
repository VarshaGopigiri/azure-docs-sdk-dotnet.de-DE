<Type Name="IHasNetworkInterfaces" FullName="Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces">
  <TypeSignature Language="C#" Value="public interface IHasNetworkInterfaces : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHasNetworkInterfaces implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHasNetworkInterfaces&#xA;Implements IHasId" />
  <TypeSignature Language="F#" Value="type IHasNetworkInterfaces = interface&#xA;    interface IHasId" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ec006-101">Eine Schnittstelle verfügbar machen eine Liste der Netzwerkschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="ec006-101">Interface exposing a list of network interfaces.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPrimaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterface GetPrimaryNetworkInterface ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterface GetPrimaryNetworkInterface() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces.GetPrimaryNetworkInterface" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryNetworkInterface () As INetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryNetworkInterface : unit -&gt; Microsoft.Azure.Management.Network.Fluent.INetworkInterface" Usage="iHasNetworkInterfaces.GetPrimaryNetworkInterface " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec006-102">Ruft die primäre Netzwerkschnittstelle ab.</span><span class="sxs-lookup"><span data-stu-id="ec006-102">Gets the primary network interface.</span></span>
            <span data-ttu-id="ec006-103">Beachten Sie, dass diese Methode in einem Aufruf in die Cloud beim Abrufen der Schnittstelle für Netzwerkinformationen führen kann.</span><span class="sxs-lookup"><span data-stu-id="ec006-103">Note that this method can result in a call to the cloud to fetch the network interface information.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ec006-104">Die primäre Netzwerkschnittstelle, die dieser Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ec006-104">The primary network interface associated with this resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NetworkInterfaceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NetworkInterfaceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces.NetworkInterfaceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces.NetworkInterfaceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec006-105">Ruft die Liste der Ressourcen-IDs der Netzwerkschnittstellen, die dieser Ressource zugeordneten ab.</span><span class="sxs-lookup"><span data-stu-id="ec006-105">Gets the list of resource IDs of the network interfaces associated with this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryNetworkInterfaceId">
      <MemberSignature Language="C#" Value="public string PrimaryNetworkInterfaceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryNetworkInterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces.PrimaryNetworkInterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryNetworkInterfaceId As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryNetworkInterfaceId : string" Usage="Microsoft.Azure.Management.Network.Fluent.IHasNetworkInterfaces.PrimaryNetworkInterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec006-106">Ruft die Ressourcen-Id, der dieser Ressource zugeordneten primären Netzwerkschnittstelle ab.</span><span class="sxs-lookup"><span data-stu-id="ec006-106">Gets the resource id of the primary network interface associated with this resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>