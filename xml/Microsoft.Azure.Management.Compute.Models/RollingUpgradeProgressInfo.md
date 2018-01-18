<Type Name="RollingUpgradeProgressInfo" FullName="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo">
  <TypeSignature Language="C#" Value="public class RollingUpgradeProgressInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeProgressInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeProgressInfo" />
  <TypeSignature Language="F#" Value="type RollingUpgradeProgressInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6a422-101">Informationen über die Anzahl der Instanzen virtueller Computer in jeder Upgradestatus.</span><span class="sxs-lookup"><span data-stu-id="6a422-101">Information about the number of virtual machine instances in each upgrade state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeProgressInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6a422-102">Initialisiert eine neue Instanz der RollingUpgradeProgressInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a422-102">Initializes a new instance of the RollingUpgradeProgressInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeProgressInfo (Nullable&lt;int&gt; successfulInstanceCount = null, Nullable&lt;int&gt; failedInstanceCount = null, Nullable&lt;int&gt; inProgressInstanceCount = null, Nullable&lt;int&gt; pendingInstanceCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; successfulInstanceCount, valuetype System.Nullable`1&lt;int32&gt; failedInstanceCount, valuetype System.Nullable`1&lt;int32&gt; inProgressInstanceCount, valuetype System.Nullable`1&lt;int32&gt; pendingInstanceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional successfulInstanceCount As Nullable(Of Integer) = null, Optional failedInstanceCount As Nullable(Of Integer) = null, Optional inProgressInstanceCount As Nullable(Of Integer) = null, Optional pendingInstanceCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo" Usage="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo (successfulInstanceCount, failedInstanceCount, inProgressInstanceCount, pendingInstanceCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="successfulInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="failedInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="inProgressInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="pendingInstanceCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="successfulInstanceCount"><span data-ttu-id="6a422-103">Die Anzahl der Instanzen, die erfolgreich aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="6a422-103">The number of instances that have been successfully upgraded.</span></span></param>
        <param name="failedInstanceCount"><span data-ttu-id="6a422-104">Die Anzahl der Instanzen, die nicht erfolgreich aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6a422-104">The number of instances that have failed to be upgraded successfully.</span></span></param>
        <param name="inProgressInstanceCount"><span data-ttu-id="6a422-105">Die Anzahl der Instanzen, die derzeit aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6a422-105">The number of instances that are currently being upgraded.</span></span></param>
        <param name="pendingInstanceCount"><span data-ttu-id="6a422-106">Die Anzahl der Instanzen, die noch nicht begonnen haben, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6a422-106">The number of instances that have not yet begun to be upgraded.</span></span></param>
        <summary>
            <span data-ttu-id="6a422-107">Initialisiert eine neue Instanz der RollingUpgradeProgressInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a422-107">Initializes a new instance of the RollingUpgradeProgressInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FailedInstanceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FailedInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.FailedInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FailedInstanceCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.FailedInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a422-108">Ruft die Anzahl der Instanzen, die nicht erfolgreich aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6a422-108">Gets the number of instances that have failed to be upgraded successfully.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InProgressInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; InProgressInstanceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; InProgressInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.InProgressInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InProgressInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.InProgressInstanceCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.InProgressInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inProgressInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a422-109">Ruft die Anzahl der Instanzen, die derzeit aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="6a422-109">Gets the number of instances that are currently being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PendingInstanceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PendingInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.PendingInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PendingInstanceCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.PendingInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pendingInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a422-110">Ruft die Anzahl der Instanzen, die noch nicht begonnen haben, aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6a422-110">Gets the number of instances that have not yet begun to be upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuccessfulInstanceCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SuccessfulInstanceCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SuccessfulInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.SuccessfulInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuccessfulInstanceCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SuccessfulInstanceCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo.SuccessfulInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="successfulInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6a422-111">Ruft die Anzahl der Instanzen, die erfolgreich aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="6a422-111">Gets the number of instances that have been successfully upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>