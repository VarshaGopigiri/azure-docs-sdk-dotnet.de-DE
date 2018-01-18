<Type Name="HostingEnvironmentDiagnostics" FullName="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics">
  <TypeSignature Language="C#" Value="public class HostingEnvironmentDiagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostingEnvironmentDiagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class HostingEnvironmentDiagnostics" />
  <TypeSignature Language="F#" Value="type HostingEnvironmentDiagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc32d-101">Diagnose für eine App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="dc32d-101">Diagnostics for an App Service Environment.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostingEnvironmentDiagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc32d-102">Initialisiert eine neue Instanz der HostingEnvironmentDiagnostics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc32d-102">Initializes a new instance of the HostingEnvironmentDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostingEnvironmentDiagnostics (string name = null, string diagnosicsOutput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string diagnosicsOutput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional diagnosicsOutput As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics : string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics" Usage="new Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics (name, diagnosicsOutput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosicsOutput" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dc32d-103">/ Namensbezeichner der Diagnose.</span><span class="sxs-lookup"><span data-stu-id="dc32d-103">Name/identifier of the diagnostics.</span></span></param>
        <param name="diagnosicsOutput"><span data-ttu-id="dc32d-104">Diagnose-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="dc32d-104">Diagnostics output.</span></span></param>
        <summary>
            <span data-ttu-id="dc32d-105">Initialisiert eine neue Instanz der HostingEnvironmentDiagnostics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dc32d-105">Initializes a new instance of the HostingEnvironmentDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosicsOutput">
      <MemberSignature Language="C#" Value="public string DiagnosicsOutput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DiagnosicsOutput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.DiagnosicsOutput" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosicsOutput As String" />
      <MemberSignature Language="F#" Value="member this.DiagnosicsOutput : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.DiagnosicsOutput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosicsOutput")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc32d-106">Ruft ab, oder legt ihn fest Diagnose-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="dc32d-106">Gets or sets diagnostics output.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc32d-107">Ruft ab, oder legt ihn fest Namensbezeichner der Diagnose.</span><span class="sxs-lookup"><span data-stu-id="dc32d-107">Gets or sets name/identifier of the diagnostics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>