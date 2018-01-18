<Type Name="IWithHostNameBinding&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameBinding&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameBinding`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostNameBinding(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithHostNameBinding&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="0e536-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="0e536-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="0e536-102">Die Phase der Web-app aktualisieren, sodass Hostnamen-Bindungen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="0e536-102">The stage of the web app update allowing host name binding to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineHostnameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineHostnameBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.DefineHostnameBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineHostnameBinding () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineHostnameBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithHostNameBinding.DefineHostnameBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0e536-103">Startet die Definition einen neuen Hostnamen-Bindungen.</span><span class="sxs-lookup"><span data-stu-id="0e536-103">Starts the definition of a new host name binding.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e536-104">Die erste Phase eines Hostnamens Bindung Updates.</span><span class="sxs-lookup"><span data-stu-id="0e536-104">The first stage of a hostname binding update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedHostnameBindings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithManagedHostnameBindings (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithManagedHostnameBindings(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithManagedHostnameBindings(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithManagedHostnameBindings (domain As IAppServiceDomain, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedHostnameBindings : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithManagedHostnameBindings (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="0e536-105">Der Azure verwaltete Domäne.</span><span class="sxs-lookup"><span data-stu-id="0e536-105">The Azure managed domain.</span></span></param>
        <param name="hostnames"><span data-ttu-id="0e536-106">Die Liste der untergeordneten Domänen.</span><span class="sxs-lookup"><span data-stu-id="0e536-106">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="0e536-107">Definiert eine Liste von Hostnamen für eine Azure verwalteten Domäne konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="0e536-107">Defines a list of host names of an Azure managed domain.</span></span> <span data-ttu-id="0e536-108">Der DNS-Eintragstyp wird standardmäßig für CNAME mit Ausnahme der Servicelevel-Stammdomäne sein (".</span><span class="sxs-lookup"><span data-stu-id="0e536-108">The DNS record type is defaulted to be CNAME except for the root level domain (".</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e536-109">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="0e536-109">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutHostnameBinding (string hostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutHostnameBinding(string hostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithoutHostnameBinding(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutHostnameBinding (hostname As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutHostnameBinding : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithoutHostnameBinding hostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="0e536-110">Der Hostname zum Aufheben der Bindung.</span><span class="sxs-lookup"><span data-stu-id="0e536-110">The hostname to unbind.</span></span></param>
        <summary>
            <span data-ttu-id="0e536-111">Hebt die Bindung eines Hostnamens aus der Web-app.</span><span class="sxs-lookup"><span data-stu-id="0e536-111">Unbinds a hostname from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e536-112">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="0e536-112">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithThirdPartyHostnameBinding (string domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithThirdPartyHostnameBinding(string domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithThirdPartyHostnameBinding(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyHostnameBinding (domain As String, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyHostnameBinding : string * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithThirdPartyHostnameBinding (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="0e536-113">Der Name der externen Domäne.</span><span class="sxs-lookup"><span data-stu-id="0e536-113">The external domain name.</span></span></param>
        <param name="hostnames"><span data-ttu-id="0e536-114">Die Liste der untergeordneten Domänen.</span><span class="sxs-lookup"><span data-stu-id="0e536-114">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="0e536-115">Definiert eine Liste von Hostnamen einer extern erworbener App-Domäne.</span><span class="sxs-lookup"><span data-stu-id="0e536-115">Defines a list of host names of an externally purchased domain.</span></span> <span data-ttu-id="0e536-116">Die Hostnamen müssen vor der Hand, zeigen Sie auf die Web-app konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="0e536-116">The hostnames must be configured before hand to point to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0e536-117">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="0e536-117">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>