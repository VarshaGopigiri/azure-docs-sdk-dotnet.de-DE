<Type Name="BootDiagnostics" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics">
  <TypeSignature Language="C#" Value="public class BootDiagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BootDiagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class BootDiagnostics" />
  <TypeSignature Language="F#" Value="type BootDiagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0e991-101">Beschreibt die Startdiagnoseeinstellungen.</span><span class="sxs-lookup"><span data-stu-id="0e991-101">Describes Boot Diagnostics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0e991-102">Initialisiert eine neue Instanz der BootDiagnostics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0e991-102">Initializes a new instance of the BootDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnostics (Nullable&lt;bool&gt; enabled = null, string storageUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, string storageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.#ctor(System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional storageUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics : Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics (enabled, storageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="0e991-103">Gibt an, ob startdiagnoseeinstellungen auf dem virtuellen Computer aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="0e991-103">Whether boot diagnostics should be enabled on the Virtual Machine.</span></span></param>
        <param name="storageUri"><span data-ttu-id="0e991-104">URI des Speicherkontos an, der für die Platzierung der Konsolenausgabe und Screenshot verwendet.</span><span class="sxs-lookup"><span data-stu-id="0e991-104">URI of the storage account to use for placing the console output and screenshot.</span></span></param>
        <summary>
            <span data-ttu-id="0e991-105">Initialisiert eine neue Instanz der BootDiagnostics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0e991-105">Initializes a new instance of the BootDiagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0e991-106">Ruft ab oder legt fest, ob startdiagnoseeinstellungen auf dem virtuellen Computer aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="0e991-106">Gets or sets whether boot diagnostics should be enabled on the Virtual Machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public string StorageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageUri As String" />
      <MemberSignature Language="F#" Value="member this.StorageUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0e991-107">Abrufen oder Festlegen der URI des Speicherkontos an, der für die Platzierung der Konsolenausgabe und Screenshot verwendet.</span><span class="sxs-lookup"><span data-stu-id="0e991-107">Gets or sets URI of the storage account to use for placing the console output and screenshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>