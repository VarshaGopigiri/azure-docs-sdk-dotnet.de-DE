<Type Name="IWithSslCert" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert">
  <TypeSignature Language="C#" Value="public interface IWithSslCert" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCert" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslCert" />
  <TypeSignature Language="F#" Value="type IWithSslCert = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="47688-101">Die Phase der Definition einer Anwendung-Gateway ermöglicht, fügen ein SSL-Zertifikat von HTTPS-Listener verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="47688-101">The stage of an application gateway definition allowing to add an SSL certificate to be used by HTTPS listeners.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSslCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSslCert.DefineSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSslCertificate (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSslCertificate : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithSslCert.DefineSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewaySslCertificate.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="47688-102">Ein eindeutiger Name für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="47688-102">A unique name for the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="47688-103">Beginn der Definition einer neuen Anwendung Gateway SSL-Zertifikat an das Gateway für die Verwendung in HTTPS-Listener angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="47688-103">Begins the definition of a new application gateway SSL certificate to be attached to the gateway for use in HTTPS listeners.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="47688-104">Die erste Phase der Definition des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="47688-104">The first stage of the certificate definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>