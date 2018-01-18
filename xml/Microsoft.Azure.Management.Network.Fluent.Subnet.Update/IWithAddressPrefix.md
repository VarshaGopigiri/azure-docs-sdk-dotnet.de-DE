<Type Name="IWithAddressPrefix" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix">
  <TypeSignature Language="C#" Value="public interface IWithAddressPrefix" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddressPrefix" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddressPrefix" />
  <TypeSignature Language="F#" Value="type IWithAddressPrefix = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="85e85-101">Die Stufe der Subnetz Update ermöglicht so ändern Sie den Adressraum des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="85e85-101">The stage of the subnet update allowing to change the address space for the subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix.WithAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressPrefix (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithAddressPrefix.WithAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="85e85-102">Die IP-Adresse Speicherplatz Präfix mithilfe der CIDR-Notation.</span><span class="sxs-lookup"><span data-stu-id="85e85-102">The IP address space prefix using the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="85e85-103">Gibt den IP-Adressraum des Subnetzes innerhalb des Adressraums des Netzwerks an.</span><span class="sxs-lookup"><span data-stu-id="85e85-103">Specifies the IP address space of the subnet, within the address space of the network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85e85-104">Die nächste Stufe.</span><span class="sxs-lookup"><span data-stu-id="85e85-104">The next stage.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>