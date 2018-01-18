<Type Name="ContainerServiceDiagnosticsProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceDiagnosticsProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceDiagnosticsProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceDiagnosticsProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceDiagnosticsProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceDiagnosticsProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0b805-101">Initialisiert eine neue Instanz der ContainerServiceDiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b805-101">Initializes a new instance of the ContainerServiceDiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceDiagnosticsProfile (Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics vmDiagnostics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics vmDiagnostics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vmDiagnostics As ContainerServiceVMDiagnostics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile vmDiagnostics" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vmDiagnostics" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics" />
      </Parameters>
      <Docs>
        <param name="vmDiagnostics"><span data-ttu-id="0b805-102">Profil für den Container Dienst VM-Diagnose-Agent.</span><span class="sxs-lookup"><span data-stu-id="0b805-102">Profile for the container service VM diagnostic agent.</span></span></param>
        <summary>
            <span data-ttu-id="0b805-103">Initialisiert eine neue Instanz der ContainerServiceDiagnosticsProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0b805-103">Initializes a new instance of the ContainerServiceDiagnosticsProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceDiagnosticsProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0b805-104">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0b805-104">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0b805-105">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0b805-105">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics VmDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics VmDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile.VmDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property VmDiagnostics As ContainerServiceVMDiagnostics" />
      <MemberSignature Language="F#" Value="member this.VmDiagnostics : Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceDiagnosticsProfile.VmDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceVMDiagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0b805-106">Ruft ab oder legt Profil für den Container Dienst VM-Diagnose-Agent fest.</span><span class="sxs-lookup"><span data-stu-id="0b805-106">Gets or sets profile for the container service VM diagnostic agent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>