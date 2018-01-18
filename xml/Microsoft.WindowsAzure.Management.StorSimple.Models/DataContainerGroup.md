<Type Name="DataContainerGroup" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup">
  <TypeSignature Language="C#" Value="public class DataContainerGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataContainerGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class DataContainerGroup" />
  <TypeSignature Language="F#" Value="type DataContainerGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="106cb-101">Stellt jede Zeile im Raster für die Cloud im Portal</span><span class="sxs-lookup"><span data-stu-id="106cb-101">Represents each row in the cloud settings grid on the portal</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="106cb-102">Initialisiert eine neue Instanz der DataContainerGroup-Klasse.</span><span class="sxs-lookup"><span data-stu-id="106cb-102">Initializes a new instance of the DataContainerGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainerGroup (System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; dCGroup, string ineligibilityMessage, bool isDCGroupEligibleForDR);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; dCGroup, string ineligibilityMessage, bool isDCGroupEligibleForDR) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.#ctor(System.Collections.Generic.List{Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer},System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dCGroup As List(Of DRDataContainer), ineligibilityMessage As String, isDCGroupEligibleForDR As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup : System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; * string * bool -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup (dCGroup, ineligibilityMessage, isDCGroupEligibleForDR)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dCGroup" Type="System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt;" />
        <Parameter Name="ineligibilityMessage" Type="System.String" />
        <Parameter Name="isDCGroupEligibleForDR" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dCGroup">To be added.</param>
        <param name="ineligibilityMessage">To be added.</param>
        <param name="isDCGroupEligibleForDR">To be added.</param>
        <summary>
            <span data-ttu-id="106cb-103">Initialisiert eine neue Instanz der DataContainerGroup-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="106cb-103">Initializes a new instance of the DataContainerGroup class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DCGroup">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; DCGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; DCGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.DCGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DCGroup As IList(Of DRDataContainer)" />
      <MemberSignature Language="F#" Value="member this.DCGroup : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.DCGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DRDataContainer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106cb-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="106cb-104">Required.</span></span> <span data-ttu-id="106cb-105">Liste der DR-Volume-Container</span><span class="sxs-lookup"><span data-stu-id="106cb-105">List of DR volume containers</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IneligibilityMessage">
      <MemberSignature Language="C#" Value="public string IneligibilityMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IneligibilityMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.IneligibilityMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property IneligibilityMessage As String" />
      <MemberSignature Language="F#" Value="member this.IneligibilityMessage : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.IneligibilityMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106cb-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="106cb-106">Required.</span></span> <span data-ttu-id="106cb-107">Grund, warum die Datengruppe für den Container nicht für Failover geeignet ist</span><span class="sxs-lookup"><span data-stu-id="106cb-107">Reason why the data container group is not eligible for failover</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDCGroupEligibleForDR">
      <MemberSignature Language="C#" Value="public bool IsDCGroupEligibleForDR { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDCGroupEligibleForDR" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.IsDCGroupEligibleForDR" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDCGroupEligibleForDR As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDCGroupEligibleForDR : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup.IsDCGroupEligibleForDR" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106cb-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="106cb-108">Required.</span></span> <span data-ttu-id="106cb-109">Flag, das angibt, ob diese Instanz für die DR geeignet ist</span><span class="sxs-lookup"><span data-stu-id="106cb-109">Flag indicating whether this instance is eligible for DR</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>