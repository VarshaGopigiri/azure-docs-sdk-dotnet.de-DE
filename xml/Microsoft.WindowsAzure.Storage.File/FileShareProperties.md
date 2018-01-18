<Type Name="FileShareProperties" FullName="Microsoft.WindowsAzure.Storage.File.FileShareProperties">
  <TypeSignature Language="C#" Value="public sealed class FileShareProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileShareProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileShareProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileShareProperties" />
  <TypeSignature Language="F#" Value="type FileShareProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92b5b-101">Stellt die Systemeigenschaften für eine Freigabe dar.</span><span class="sxs-lookup"><span data-stu-id="92b5b-101">Represents the system properties for a share.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileShareProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileShareProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileShareProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.File.FileShareProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b5b-102">Ruft den ETag-Wert für die Freigabe ab.</span><span class="sxs-lookup"><span data-stu-id="92b5b-102">Gets the ETag value for the share.</span></span>
            </summary>
        <value><span data-ttu-id="92b5b-103">Der Freigabe in Anführungszeichen ETag-Wert.</span><span class="sxs-lookup"><span data-stu-id="92b5b-103">The share's quoted ETag value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileShareProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.File.FileShareProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b5b-104">Ruft die Uhrzeit der letzten Änderung der Freigabe ab.</span><span class="sxs-lookup"><span data-stu-id="92b5b-104">Gets the share's last-modified time.</span></span>
            </summary>
        <value><span data-ttu-id="92b5b-105">Uhrzeit des letzten Änderung bei der Freigabe.</span><span class="sxs-lookup"><span data-stu-id="92b5b-105">The share's last-modified time.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Quota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Quota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Quota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileShareProperties.Quota" />
      <MemberSignature Language="VB.NET" Value="Public Property Quota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Quota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.File.FileShareProperties.Quota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92b5b-106">Ruft ab oder legt die maximale Größe für die Freigabe in Gigabyte.</span><span class="sxs-lookup"><span data-stu-id="92b5b-106">Gets or sets the maximum size for the share, in gigabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>