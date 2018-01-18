<Type Name="AllowRule" FullName="Microsoft.Azure.NotificationHubs.Messaging.AllowRule">
  <TypeSignature Language="C#" Value="public class AllowRule : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AllowRule extends Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" />
  <TypeSignature Language="VB.NET" Value="Public Class AllowRule&#xA;Inherits AuthorizationRule" />
  <TypeSignature Language="F#" Value="type AllowRule = class&#xA;    inherit AuthorizationRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AllowRule", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="79e3a-101">Stellt die Regel zum Zulassen des dar.</span><span class="sxs-lookup"><span data-stu-id="79e3a-101">Represents the rule to allow.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AllowRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="79e3a-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79e3a-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule (string issuerName, Microsoft.Azure.NotificationHubs.Messaging.AllowRuleClaimType claimType, string claimValue, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string issuerName, valuetype Microsoft.Azure.NotificationHubs.Messaging.AllowRuleClaimType claimType, string claimValue, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AllowRule.#ctor(System.String,Microsoft.Azure.NotificationHubs.Messaging.AllowRuleClaimType,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.NotificationHubs.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (issuerName As String, claimType As AllowRuleClaimType, claimValue As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.AllowRule : string * Microsoft.Azure.NotificationHubs.Messaging.AllowRuleClaimType * string * seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; -&gt; Microsoft.Azure.NotificationHubs.Messaging.AllowRule" Usage="new Microsoft.Azure.NotificationHubs.Messaging.AllowRule (issuerName, claimType, claimValue, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="claimType" Type="Microsoft.Azure.NotificationHubs.Messaging.AllowRuleClaimType" />
        <Parameter Name="claimValue" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="79e3a-103">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" /> Name, der den Anspruchsaussteller.</span><span class="sxs-lookup"><span data-stu-id="79e3a-103">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" /> name of the claim issuer.</span></span></param>
        <param name="claimType"><span data-ttu-id="79e3a-104">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" /> Typ des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="79e3a-104">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" /> type of the claim.</span></span></param>
        <param name="claimValue"><span data-ttu-id="79e3a-105">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" /> Wert des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="79e3a-105">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" /> value of the claim.</span></span></param>
        <param name="rights"><span data-ttu-id="79e3a-106">Die Liste der möglichen <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />.</span><span class="sxs-lookup"><span data-stu-id="79e3a-106">The list of possible <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />.</span></span></param>
        <summary><span data-ttu-id="79e3a-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" />-Klasse mit den angegebenen Parametern.</span><span class="sxs-lookup"><span data-stu-id="79e3a-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" /> class with the specified parameters.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AllowRule (string issuerName, string claimType, string claimValue, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string issuerName, string claimType, string claimValue, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AllowRule.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.NotificationHubs.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (issuerName As String, claimType As String, claimValue As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.AllowRule : string * string * string * seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt; -&gt; Microsoft.Azure.NotificationHubs.Messaging.AllowRule" Usage="new Microsoft.Azure.NotificationHubs.Messaging.AllowRule (issuerName, claimType, claimValue, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="claimType" Type="System.String" />
        <Parameter Name="claimValue" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="issuerName"><span data-ttu-id="79e3a-108">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" /> Name, der den Anspruchsaussteller.</span><span class="sxs-lookup"><span data-stu-id="79e3a-108">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.IssuerName" /> name of the claim issuer.</span></span></param>
        <param name="claimType"><span data-ttu-id="79e3a-109">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" /> Typ des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="79e3a-109">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimType" /> type of the claim.</span></span></param>
        <param name="claimValue"><span data-ttu-id="79e3a-110">Die <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" /> Wert des Anspruchs.</span><span class="sxs-lookup"><span data-stu-id="79e3a-110">The <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.ClaimValue" /> value of the claim.</span></span></param>
        <param name="rights"><span data-ttu-id="79e3a-111">Die Liste der möglichen <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />.</span><span class="sxs-lookup"><span data-stu-id="79e3a-111">The list of possible <see cref="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule.Rights" />.</span></span></param>
        <summary><span data-ttu-id="79e3a-112">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79e3a-112">Initializes a new instance of <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AllowRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public override string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AllowRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Messaging.AllowRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="79e3a-113">Ruft ab, oder legt ihn fest Schlüssel zulassen Regelname.</span><span class="sxs-lookup"><span data-stu-id="79e3a-113">Gets or sets the allow rule key name.</span></span></summary>
        <value><span data-ttu-id="79e3a-114">Der zulassen Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="79e3a-114">The allow rule key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>