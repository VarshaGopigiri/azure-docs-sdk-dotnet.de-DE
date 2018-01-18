<Type Name="LinkTarget" FullName="Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget">
  <TypeSignature Language="C#" Value="public class LinkTarget" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinkTarget extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget" />
  <TypeSignature Language="VB.NET" Value="Public Class LinkTarget" />
  <TypeSignature Language="F#" Value="type LinkTarget = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3cc98-101">Die Metadaten für einen Arbeitsbereich angezeigt, der mit einem Azure-Abonnement verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="3cc98-101">Metadata for a workspace that isn't linked to an Azure subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkTarget ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3cc98-102">Initialisiert eine neue Instanz der Klasse LinkTarget an.</span><span class="sxs-lookup"><span data-stu-id="3cc98-102">Initializes a new instance of the LinkTarget class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkTarget (string customerId = null, string displayName = null, string workspaceName = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string customerId, string displayName, string workspaceName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional customerId As String = null, Optional displayName As String = null, Optional workspaceName As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget : string * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget (customerId, displayName, workspaceName, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="customerId" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customerId"><span data-ttu-id="3cc98-103">Die GUID, die den Arbeitsbereich eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="3cc98-103">The GUID that uniquely identifies the workspace.</span></span> </param>
        <param name="displayName"><span data-ttu-id="3cc98-104">Der Anzeigename des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="3cc98-104">The display name of the workspace.</span></span></param>
        <param name="workspaceName"><span data-ttu-id="3cc98-105">Der Name des DNS-Arbeitsbereich "ungültig".</span><span class="sxs-lookup"><span data-stu-id="3cc98-105">The DNS valid workspace name.</span></span></param>
        <param name="location"><span data-ttu-id="3cc98-106">Der Speicherort des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="3cc98-106">The location of the workspace.</span></span></param>
        <summary>
            <span data-ttu-id="3cc98-107">Initialisiert eine neue Instanz der Klasse LinkTarget an.</span><span class="sxs-lookup"><span data-stu-id="3cc98-107">Initializes a new instance of the LinkTarget class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomerId">
      <MemberSignature Language="C#" Value="public string CustomerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.CustomerId" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomerId As String" />
      <MemberSignature Language="F#" Value="member this.CustomerId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.CustomerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cc98-108">Ruft ab oder legt die GUID, die den Arbeitsbereich eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="3cc98-108">Gets or sets the GUID that uniquely identifies the workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cc98-109">Ruft ab oder legt den Anzeigenamen des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="3cc98-109">Gets or sets the display name of the workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cc98-110">Ruft ab oder legt den Speicherort des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="3cc98-110">Gets or sets the location of the workspace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkspaceName">
      <MemberSignature Language="C#" Value="public string WorkspaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkspaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.WorkspaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkspaceName As String" />
      <MemberSignature Language="F#" Value="member this.WorkspaceName : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget.WorkspaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workspaceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3cc98-111">Ruft ab oder legt den Namen der DNS-Arbeitsbereich "ungültig" fest.</span><span class="sxs-lookup"><span data-stu-id="3cc98-111">Gets or sets the DNS valid workspace name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>