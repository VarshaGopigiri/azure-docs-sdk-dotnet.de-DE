<Type Name="IAppConfiguration" FullName="Microsoft.Azure.Mobile.Server.Config.IAppConfiguration">
  <TypeSignature Language="C#" Value="public interface IAppConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppConfiguration" />
  <TypeSignature Language="F#" Value="type IAppConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a5b3c-101">Bietet einen Mechanismus zum Ändern der <see cref="T:System.Web.Http.HttpConfiguration" /> einer Mobile-App.</span><span class="sxs-lookup"><span data-stu-id="a5b3c-101">Provides a mechanism for modifying the <see cref="T:System.Web.Http.HttpConfiguration" /> of a Mobile App.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public void ApplyTo (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplyTo(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplyTo (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member ApplyTo : System.Web.Http.HttpConfiguration -&gt; unit" Usage="iAppConfiguration.ApplyTo config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config"><span data-ttu-id="a5b3c-102">Die <see cref="T:System.Web.Http.HttpConfiguration" /> an jeden Aufruf des übergebenen <see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" />.</span><span class="sxs-lookup"><span data-stu-id="a5b3c-102">The <see cref="T:System.Web.Http.HttpConfiguration" /> passed to each invocation of <see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" />.</span></span></param>
        <summary>
            <span data-ttu-id="a5b3c-103">Aufrufe <see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" /> auf jedem registrierten <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />.</span><span class="sxs-lookup"><span data-stu-id="a5b3c-103">Calls <see cref="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider.Initialize(System.Web.Http.HttpConfiguration)" /> on every registered <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterConfigProvider">
      <MemberSignature Language="C#" Value="public void RegisterConfigProvider (Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterConfigProvider(class Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IAppConfiguration.RegisterConfigProvider(Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterConfigProvider (provider As IMobileAppExtensionConfigProvider)" />
      <MemberSignature Language="F#" Value="abstract member RegisterConfigProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider -&gt; unit" Usage="iAppConfiguration.RegisterConfigProvider provider" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="a5b3c-104">Die zu registrierende <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" />.</span><span class="sxs-lookup"><span data-stu-id="a5b3c-104">The <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" /> to register.</span></span></param>
        <summary>
            <span data-ttu-id="a5b3c-105">Fügt eine <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" /> zur Liste der Anbieter, die aufgerufen wird, indem Sie die <see cref="M:Microsoft.Azure.Mobile.Server.Config.AppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="a5b3c-105">Adds an <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppExtensionConfigProvider" /> to the list of providers that will be called by the <see cref="M:Microsoft.Azure.Mobile.Server.Config.AppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" /> method.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>