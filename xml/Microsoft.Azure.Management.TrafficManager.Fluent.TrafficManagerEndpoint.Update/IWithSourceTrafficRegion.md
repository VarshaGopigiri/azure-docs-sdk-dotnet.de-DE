<Type Name="IWithSourceTrafficRegion" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion">
  <TypeSignature Language="C#" Value="public interface IWithSourceTrafficRegion" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceTrafficRegion" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceTrafficRegion" />
  <TypeSignature Language="F#" Value="type IWithSourceTrafficRegion = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b39d6-101">Die Phase der Traffic Manager Endpunkt Update ermöglichen den Speicherort der externen oder geschachtelte Profil Endpunkte angeben.</span><span class="sxs-lookup"><span data-stu-id="b39d6-101">The stage of the traffic manager endpoint update allowing to specify the location of the external or nested profile endpoints.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromRegion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate FromRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate FromRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion.FromRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromRegion (location As Region) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithSourceTrafficRegion.FromRegion location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="b39d6-102">Der Speicherort.</span><span class="sxs-lookup"><span data-stu-id="b39d6-102">The location.</span></span></param>
        <summary>
            <span data-ttu-id="b39d6-103">Gibt die Region des Endpunkts, der verwendet wird, wenn die Leistungsbasierte Routingmethode TrafficRoutingMethod.PERFORMANCE für das Profil aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="b39d6-103">Specifies the region of the endpoint that will be used when the performance-based routing method TrafficRoutingMethod.PERFORMANCE is enabled on the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b39d6-104">Die nächste Phase des Updates für den Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="b39d6-104">The next stage of the endpoint update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>