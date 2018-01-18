<Type Name="IWithIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPAddress" />
  <TypeSignature Language="F#" Value="type IWithIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b4774-101">Eine öffentliche IP-Adresse aktualisieren, sodass so ändern Sie die IP-Zuordnungsmethode (statisch oder dynamisch).</span><span class="sxs-lookup"><span data-stu-id="b4774-101">A public IP address update allowing to change the IP allocation method (static or dynamic).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDynamicIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithDynamicIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithDynamicIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress.WithDynamicIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDynamicIP () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDynamicIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIPAddress.WithDynamicIP " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b4774-102">Ermöglicht die dynamische Zuordnung von IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="b4774-102">Enables dynamic IP address allocation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b4774-103">Die nächste Phase des Ressource-Updates.</span><span class="sxs-lookup"><span data-stu-id="b4774-103">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithStaticIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithStaticIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress.WithStaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIPAddress.WithStaticIP " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b4774-104">Können statische IP-Adresszuordnung.</span><span class="sxs-lookup"><span data-stu-id="b4774-104">Enables static IP address allocation.</span></span>
            <span data-ttu-id="b4774-105">Verwenden Sie PublicIPAddress.ipAddress(), nachdem die öffentliche IP-Adresse aktualisiert wird, um die tatsächliche IP-Adresse für diese Ressource zugeordnet werden, von Azure zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="b4774-105">Use  PublicIPAddress.ipAddress() after the public IP address is updated to obtain the actual IP address allocated for this resource by Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b4774-106">Die nächste Phase des Ressource-Updates.</span><span class="sxs-lookup"><span data-stu-id="b4774-106">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>