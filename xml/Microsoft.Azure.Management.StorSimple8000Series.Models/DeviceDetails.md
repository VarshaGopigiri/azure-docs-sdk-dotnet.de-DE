<Type Name="DeviceDetails" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails">
  <TypeSignature Language="C#" Value="public class DeviceDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceDetails" />
  <TypeSignature Language="F#" Value="type DeviceDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7c9e-101">Die Gerätedetails in Bezug auf die Endpunkt-Anzahl und die Anzahl der Volume-Container zusätzliche.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-101">The additional device details regarding the end point count and volume container count.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7c9e-102">Initialisiert eine neue Instanz der DeviceDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-102">Initializes a new instance of the DeviceDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceDetails (Nullable&lt;int&gt; endpointCount = null, Nullable&lt;int&gt; volumeContainerCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; endpointCount, valuetype System.Nullable`1&lt;int32&gt; volumeContainerCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional endpointCount As Nullable(Of Integer) = null, Optional volumeContainerCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails : Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails (endpointCount, volumeContainerCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="volumeContainerCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="endpointCount"><span data-ttu-id="a7c9e-103">Die Gesamtanzahl von Endpunkten, die derzeit auf dem Gerät (d. h. die Anzahl der Volumes) werden.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-103">The total number of endpoints that are currently on the device ( i.e. number of volumes).</span></span></param>
        <param name="volumeContainerCount"><span data-ttu-id="a7c9e-104">Die Gesamtanzahl der volumecontainer auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-104">The total number of volume containers on the device.</span></span></param>
        <summary>
            <span data-ttu-id="a7c9e-105">Initialisiert eine neue Instanz der DeviceDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-105">Initializes a new instance of the DeviceDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EndpointCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EndpointCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.EndpointCount" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EndpointCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.EndpointCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7c9e-106">Ruft ab oder legt die Gesamtanzahl der Endpunkte, die derzeit auf dem Gerät (d. h. die Anzahl der Volumes) werden.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-106">Gets or sets the total number of endpoints that are currently on the device ( i.e. number of volumes).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumeContainerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumeContainerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.VolumeContainerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumeContainerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails.VolumeContainerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeContainerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7c9e-107">Ruft ab oder legt die Gesamtanzahl der volumecontainer auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="a7c9e-107">Gets or sets the total number of volume containers on the device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>