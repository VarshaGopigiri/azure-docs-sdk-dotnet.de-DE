<Type Name="MetricRollup" FullName="Microsoft.Azure.NotificationHubs.Management.MetricRollup">
  <TypeSignature Language="C#" Value="public class MetricRollup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricRollup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.MetricRollup" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricRollup" />
  <TypeSignature Language="F#" Value="type MetricRollup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="2f93b-101">Stellt die Rollupdaten für Service Bus-Metriken dar.</span><span class="sxs-lookup"><span data-stu-id="2f93b-101">Represents the rollup data for Service Bus metrics.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricRollup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.MetricRollup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="2f93b-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Management.MetricRollup" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2f93b-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Management.MetricRollup" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retention">
      <MemberSignature Language="C#" Value="public TimeSpan Retention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Retention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricRollup.Retention" />
      <MemberSignature Language="VB.NET" Value="Public Property Retention As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Retention : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricRollup.Retention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2f93b-103">Ruft ab oder legt das Zeitintervall Beibehaltungsdauer für den Rollup zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2f93b-103">Gets or sets the time of the retention associated with the rollup.</span></span></summary>
        <value><span data-ttu-id="2f93b-104">Der Zeitpunkt der Beibehaltungsdauer für den Rollup zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2f93b-104">The time of the retention associated with the rollup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public TimeSpan TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricRollup.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricRollup.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2f93b-105">Ermittelt oder definiert das zeitkorn Rollup zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2f93b-105">Gets or sets the time grain associated with the rollup.</span></span></summary>
        <value><span data-ttu-id="2f93b-106">Das zeitkorn Rollup zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="2f93b-106">The time grain associated with the rollup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricValue&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.NotificationHubs.Management.MetricValue&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricRollup.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As ICollection(Of MetricValue)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricValue&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricRollup.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Management.MetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="2f93b-107">Ruft ab oder legt die Auflistung der Metrikwerte.</span><span class="sxs-lookup"><span data-stu-id="2f93b-107">Gets or sets the collection of metric values.</span></span></summary>
        <value><span data-ttu-id="2f93b-108">Die Auflistung der Metrikwerte.</span><span class="sxs-lookup"><span data-stu-id="2f93b-108">The collection of metric values.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>