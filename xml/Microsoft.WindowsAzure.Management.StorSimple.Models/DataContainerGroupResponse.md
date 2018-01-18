<Type Name="DataContainerGroupResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse">
  <TypeSignature Language="C#" Value="public class DataContainerGroupResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataContainerGroupResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class DataContainerGroupResponse" />
  <TypeSignature Language="F#" Value="type DataContainerGroupResponse = class" />
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
            <span data-ttu-id="efbb6-101">Stellt das DataContainerGroups Get-Aufruf zurückgegebene Objekt</span><span class="sxs-lookup"><span data-stu-id="efbb6-101">Represents the object returned by DataContainerGroups Get call</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainerGroupResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="efbb6-102">Initialisiert eine neue Instanz der DataContainerGroupResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="efbb6-102">Initializes a new instance of the DataContainerGroupResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataContainerGroupResponse (System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; dCGroups, string followUpJobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; dCGroups, string followUpJobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.#ctor(System.Collections.Generic.IList{Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dCGroups As IList(Of DataContainerGroup), followUpJobId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse (dCGroups, followUpJobId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dCGroups" Type="System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt;" />
        <Parameter Name="followUpJobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dCGroups">To be added.</param>
        <param name="followUpJobId">To be added.</param>
        <summary>
            <span data-ttu-id="efbb6-103">Initialisiert eine neue Instanz der DataContainerGroupResponse-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="efbb6-103">Initializes a new instance of the DataContainerGroupResponse class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DCGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; DCGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; DCGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.DCGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DCGroups As IList(Of DataContainerGroup)" />
      <MemberSignature Language="F#" Value="member this.DCGroups : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.DCGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efbb6-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="efbb6-104">Required.</span></span> <span data-ttu-id="efbb6-105">Liste der DataContainerGroup-Objekte</span><span class="sxs-lookup"><span data-stu-id="efbb6-105">List of DataContainerGroup objects</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FollowUpJobId">
      <MemberSignature Language="C#" Value="public string FollowUpJobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FollowUpJobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.FollowUpJobId" />
      <MemberSignature Language="VB.NET" Value="Public Property FollowUpJobId As String" />
      <MemberSignature Language="F#" Value="member this.FollowUpJobId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupResponse.FollowUpJobId" />
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
            <span data-ttu-id="efbb6-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="efbb6-106">Required.</span></span> <span data-ttu-id="efbb6-107">Die nachverfolgungs-Auftrags-ID</span><span class="sxs-lookup"><span data-stu-id="efbb6-107">The follow-up job identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>