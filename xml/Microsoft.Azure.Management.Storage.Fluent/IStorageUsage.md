<Type Name="IStorageUsage" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage">
  <TypeSignature Language="C#" Value="public interface IStorageUsage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageUsage implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageUsage&#xA;Implements IHasInner(Of Usage)" />
  <TypeSignature Language="F#" Value="type IStorageUsage = interface&#xA;    interface IHasInner&lt;Usage&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Usage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="21f00-101">Eine unveränderliche clientseitige Darstellung eines Azure-Speicher Ressource Nutzung Info-Objekts.</span><span class="sxs-lookup"><span data-stu-id="21f00-101">An immutable client-side representation of an Azure storage resource usage info object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f00-102">Ruft die aktuelle Anzahl der zugeordneten Ressourcen im Abonnement.</span><span class="sxs-lookup"><span data-stu-id="21f00-102">Gets the current count of the allocated resources in the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public int Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Integer" />
      <MemberSignature Language="F#" Value="member this.Limit : int" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f00-103">Ruft die maximale Anzahl der Ressourcen, die im Abonnement zugeordnet werden kann.</span><span class="sxs-lookup"><span data-stu-id="21f00-103">Gets the maximum count of the resources that can be allocated in the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.UsageName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.UsageName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As UsageName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Fluent.Models.UsageName" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.UsageName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f00-104">Ruft den Namen des Typs der Nutzung ab.</span><span class="sxs-lookup"><span data-stu-id="21f00-104">Gets the name of the type of usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As UsageUnit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.UsageUnit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f00-105">Ruft die Maßeinheit ab.</span><span class="sxs-lookup"><span data-stu-id="21f00-105">Gets the unit of measurement.</span></span> <span data-ttu-id="21f00-106">Folgende Werte sind möglich: "Count", "Byte", "Sekunden", "Prozent", "CountsPerSecond", "BytesPerSecond".</span><span class="sxs-lookup"><span data-stu-id="21f00-106">Possible values include: 'Count', 'Bytes', 'Seconds', 'Percent', 'CountsPerSecond', 'BytesPerSecond'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>