<Type Name="CrossDomainController" FullName="Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController">
  <TypeSignature Language="C#" Value="public class CrossDomainController : System.Web.Http.ApiController" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CrossDomainController extends System.Web.Http.ApiController" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController" />
  <TypeSignature Language="VB.NET" Value="Public Class CrossDomainController&#xA;Inherits ApiController" />
  <TypeSignature Language="F#" Value="type CrossDomainController = class&#xA;    inherit ApiController" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Web.Http.ApiController</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Mobile.Server.Config.MobileAppController</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Web.Http.Description.ApiExplorerSettings(IgnoreApi=true)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e43ff-101">Dieser Controller gibt Dateien, die für ältere Browser domänenübergreifende Kommunikation zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="e43ff-101">This controller returns files that support cross-domain communication for older browsers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CrossDomainController ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bridge">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt; Bridge (string origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.IHttpActionResult&gt; Bridge(string origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.Bridge(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Bridge (origin As String) As Task(Of IHttpActionResult)" />
      <MemberSignature Language="F#" Value="member this.Bridge : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;" Usage="crossDomainController.Bridge origin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController/&lt;Bridge&gt;d__2))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.AllowAnonymous</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.HttpGet</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="origin" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="origin"><span data-ttu-id="e43ff-102">Ursprung überprüfen</span><span class="sxs-lookup"><span data-stu-id="e43ff-102">Origin to verify</span></span></param>
        <summary>
             <span data-ttu-id="e43ff-103">Eine Seite, die beim Hosten in einer <c>Iframe</c>, postMessage Nachrichten von genehmigten Ursprüngen akzeptiert und wird als derselben Domäne Ajax-Anforderung für die Laufzeit weiterleiten.</span><span class="sxs-lookup"><span data-stu-id="e43ff-103">A page that, when hosted in an <c>iframe</c>, will accept postMessage messages from approved origins and will forward them as a same-domain ajax request to the runtime.</span></span> <span data-ttu-id="e43ff-104">Dies ist erforderlich, für die <c>IframeBridge</c> transport in <c>MobileApps.Web.js</c>, wie von IE8-9 verwendet.</span><span class="sxs-lookup"><span data-stu-id="e43ff-104">This is needed for the <c>IframeBridge</c> transport in <c>MobileApps.Web.js</c>, as used by IE8-9.</span></span>
             </summary>
        <returns><span data-ttu-id="e43ff-105">Ein <see cref="T:System.Web.Http.IHttpActionResult" />, der das Ergebnis darstellt.</span><span class="sxs-lookup"><span data-stu-id="e43ff-105">An <see cref="T:System.Web.Http.IHttpActionResult" /> representing the result.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="protected override void Initialize (System.Web.Http.Controllers.HttpControllerContext controllerContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Initialize(class System.Web.Http.Controllers.HttpControllerContext controllerContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.Initialize(System.Web.Http.Controllers.HttpControllerContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Initialize (controllerContext As HttpControllerContext)" />
      <MemberSignature Language="F#" Value="override this.Initialize : System.Web.Http.Controllers.HttpControllerContext -&gt; unit" Usage="crossDomainController.Initialize controllerContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerContext" Type="System.Web.Http.Controllers.HttpControllerContext" />
      </Parameters>
      <Docs>
        <param name="controllerContext">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginReceiver">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt; LoginReceiver (string completionOrigin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.IHttpActionResult&gt; LoginReceiver(string completionOrigin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.LoginReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginReceiver (completionOrigin As String) As Task(Of IHttpActionResult)" />
      <MemberSignature Language="F#" Value="member this.LoginReceiver : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;" Usage="crossDomainController.LoginReceiver completionOrigin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController/&lt;LoginReceiver&gt;d__3))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.AllowAnonymous</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.HttpGet</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="completionOrigin" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Web.Http.FromUri(Name="completion_origin")</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="completionOrigin">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>