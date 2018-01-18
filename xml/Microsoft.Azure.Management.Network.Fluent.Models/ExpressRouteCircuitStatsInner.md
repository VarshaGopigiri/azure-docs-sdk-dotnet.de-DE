<Type Name="ExpressRouteCircuitStatsInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitStatsInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitStatsInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitStatsInner" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitStatsInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ef6df-101">Enthält Statistiken, die das peering zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ef6df-101">Contains stats associated with the peering.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitStatsInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ef6df-102">Initialisiert eine neue Instanz der ExpressRouteCircuitStatsInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ef6df-102">Initializes a new instance of the ExpressRouteCircuitStatsInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitStatsInner (Nullable&lt;long&gt; primarybytesIn = null, Nullable&lt;long&gt; primarybytesOut = null, Nullable&lt;long&gt; secondarybytesIn = null, Nullable&lt;long&gt; secondarybytesOut = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; primarybytesIn, valuetype System.Nullable`1&lt;int64&gt; primarybytesOut, valuetype System.Nullable`1&lt;int64&gt; secondarybytesIn, valuetype System.Nullable`1&lt;int64&gt; secondarybytesOut) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primarybytesIn As Nullable(Of Long) = null, Optional primarybytesOut As Nullable(Of Long) = null, Optional secondarybytesIn As Nullable(Of Long) = null, Optional secondarybytesOut As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner (primarybytesIn, primarybytesOut, secondarybytesIn, secondarybytesOut)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primarybytesIn" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="primarybytesOut" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="secondarybytesIn" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="secondarybytesOut" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="primarybytesIn"><span data-ttu-id="ef6df-103">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-103">Gets BytesIn of the peering.</span></span></param>
        <param name="primarybytesOut"><span data-ttu-id="ef6df-104">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-104">Gets BytesOut of the peering.</span></span></param>
        <param name="secondarybytesIn"><span data-ttu-id="ef6df-105">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-105">Gets BytesIn of the peering.</span></span></param>
        <param name="secondarybytesOut"><span data-ttu-id="ef6df-106">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-106">Gets BytesOut of the peering.</span></span></param>
        <summary>
            <span data-ttu-id="ef6df-107">Initialisiert eine neue Instanz der ExpressRouteCircuitStatsInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ef6df-107">Initializes a new instance of the ExpressRouteCircuitStatsInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarybytesIn">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrimarybytesIn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrimarybytesIn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.PrimarybytesIn" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarybytesIn As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrimarybytesIn : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.PrimarybytesIn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarybytesIn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef6df-108">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-108">Gets BytesIn of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimarybytesOut">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrimarybytesOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrimarybytesOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.PrimarybytesOut" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimarybytesOut As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrimarybytesOut : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.PrimarybytesOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primarybytesOut")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef6df-109">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-109">Gets BytesOut of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarybytesIn">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SecondarybytesIn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SecondarybytesIn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.SecondarybytesIn" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarybytesIn As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SecondarybytesIn : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.SecondarybytesIn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarybytesIn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef6df-110">Ruft die BytesIn von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-110">Gets BytesIn of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondarybytesOut">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SecondarybytesOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SecondarybytesOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.SecondarybytesOut" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondarybytesOut As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SecondarybytesOut : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner.SecondarybytesOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondarybytesOut")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef6df-111">Ruft die BytesOut von peering ab.</span><span class="sxs-lookup"><span data-stu-id="ef6df-111">Gets BytesOut of the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>