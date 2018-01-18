<Type Name="DataDiskImage" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage">
  <TypeSignature Language="C#" Value="public class DataDiskImage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDiskImage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDiskImage" />
  <TypeSignature Language="F#" Value="type DataDiskImage = class" />
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
            <span data-ttu-id="c6a2d-101">Enthält Informationen zu Images den Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-101">Contains the data disk images information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDiskImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6a2d-102">Initialisiert eine neue Instanz der DataDiskImage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-102">Initializes a new instance of the DataDiskImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDiskImage (Nullable&lt;int&gt; lun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage.#ctor(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lun As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage lun" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="c6a2d-103">Die Anzahl der LUN für einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-103">The LUN number for a data disk.</span></span> <span data-ttu-id="c6a2d-104">Dieser Wert wird verwendet, um Datenträger-Imagedatei in der "vmimage" Daten zu identifizieren, und muss daher für jeden Datenträger eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-104">This value is used to identify data disk image inside the VMImage and therefore it must be unique for each data disk.</span></span></param>
        <summary>
            <span data-ttu-id="c6a2d-105">Initialisiert eine neue Instanz der DataDiskImage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-105">Initializes a new instance of the DataDiskImage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Lun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage.Lun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Lun : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DataDiskImage.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6a2d-106">Ruft die Anzahl der LUN für einen Datenträger.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-106">Gets the LUN number for a data disk.</span></span> <span data-ttu-id="c6a2d-107">Dieser Wert wird verwendet, um Datenträger-Imagedatei in der "vmimage" Daten zu identifizieren, und muss daher für jeden Datenträger eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="c6a2d-107">This value is used to identify data disk image inside the VMImage and therefore it must be unique for each data disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>