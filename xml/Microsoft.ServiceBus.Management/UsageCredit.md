<Type Name="UsageCredit" FullName="Microsoft.ServiceBus.Management.UsageCredit">
  <TypeSignature Language="C#" Value="public class UsageCredit : IEquatable&lt;Microsoft.ServiceBus.Management.UsageCredit&gt;, System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageCredit extends System.Object implements class System.IEquatable`1&lt;class Microsoft.ServiceBus.Management.UsageCredit&gt;, class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.UsageCredit" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageCredit&#xA;Implements IEquatable(Of UsageCredit), IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type UsageCredit = class&#xA;    interface IExtensibleDataObject&#xA;    interface IEquatable&lt;UsageCredit&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceBus.Management.UsageCredit&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="UsageCredit", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="598bb-101">Stellt die Verwendung Guthaben Management dar.</span><span class="sxs-lookup"><span data-stu-id="598bb-101">Represents the usage credit management.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageCredit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceBus.Management.UsageCredit other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceBus.Management.UsageCredit other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.Equals(Microsoft.ServiceBus.Management.UsageCredit)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As UsageCredit) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceBus.Management.UsageCredit -&gt; bool" Usage="usageCredit.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.Management.UsageCredit" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="598bb-102">Das andere Nutzung Guthaben, verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="598bb-102">The other usage credit to compare.</span></span></param>
        <summary><span data-ttu-id="598bb-103">Gibt an, ob diese Instanz mit einem anderen Verwendung Kreditkarte identisch ist.</span><span class="sxs-lookup"><span data-stu-id="598bb-103">Specifies whether this instance is equal with another usage credit.</span></span></summary>
        <returns><span data-ttu-id="598bb-104">"true", wenn diese Instanz mit einem anderen Verwendung Kreditkarte gleich ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="598bb-104">true if this instance is equal with another usage credit; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-105">Ruft ab oder legt das Objekt, das Daten speichert</span><span class="sxs-lookup"><span data-stu-id="598bb-105">Gets or sets the object that stores data</span></span></summary>
        <value><span data-ttu-id="598bb-106">Das Objekt, das Daten speichert</span><span class="sxs-lookup"><span data-stu-id="598bb-106">The object that stores data</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="Identifier", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-107">Ruft ab oder legt die Kreditkarten-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="598bb-107">Gets or sets the credit identifier.</span></span></summary>
        <value><span data-ttu-id="598bb-108">Die Kreditkarten-ID.</span><span class="sxs-lookup"><span data-stu-id="598bb-108">The credit identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="KeyName", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-109">Ruft ab oder legt der Schlüsselname der Kredit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="598bb-109">Gets or sets the key name associated with the credit.</span></span></summary>
        <value><span data-ttu-id="598bb-110">Der Schlüsselname der Kredit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="598bb-110">The key name associated with the credit.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceName">
      <MemberSignature Language="C#" Value="public string NamespaceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NamespaceName" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceName As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceName : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NamespaceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-111">Ruft ab oder legt den Namespacenamen der Kredit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="598bb-111">Gets or sets the namespace name associated with the credit.</span></span></summary>
        <value><span data-ttu-id="598bb-112">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="598bb-112">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NHBasicUnit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NHBasicUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NHBasicUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NHBasicUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property NHBasicUnit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NHBasicUnit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NHBasicUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NHBasicUnit", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-113">Ruft ab oder legt die Basisebene Einheit des benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="598bb-113">Gets or sets the Basic Tier unit of the notification hub.</span></span></summary>
        <value><span data-ttu-id="598bb-114">Die grundlegende Einheit des benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="598bb-114">The basic unit of the notification hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NHStandardUnit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NHStandardUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NHStandardUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.NHStandardUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property NHStandardUnit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NHStandardUnit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.NHStandardUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="NHStandardUnit", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-115">Ruft ab oder legt die Standardebene Einheit des benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="598bb-115">Gets or sets the Standard Tier unit of the notification hub.</span></span></summary>
        <value><span data-ttu-id="598bb-116">Die Standardeinheit für den benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="598bb-116">The standard unit of the notification hub.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestorService">
      <MemberSignature Language="C#" Value="public string RequestorService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestorService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.RequestorService" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestorService As String" />
      <MemberSignature Language="F#" Value="member this.RequestorService : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.RequestorService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="RequestorService", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-117">Ruft ab oder legt der anforderer-Dienst.</span><span class="sxs-lookup"><span data-stu-id="598bb-117">Gets or sets the requestor service.</span></span></summary>
        <value><span data-ttu-id="598bb-118">Der anforderer-Dienst.</span><span class="sxs-lookup"><span data-stu-id="598bb-118">The requestor service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Revision">
      <MemberSignature Language="C#" Value="public long Revision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Revision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.Revision" />
      <MemberSignature Language="VB.NET" Value="Public Property Revision As Long" />
      <MemberSignature Language="F#" Value="member this.Revision : int64 with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.Revision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=false, Name="Revision", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-119">Abrufen oder Festlegen der Kreditkarten-Prüfung.</span><span class="sxs-lookup"><span data-stu-id="598bb-119">Gets or sets the credit revision.</span></span></summary>
        <value><span data-ttu-id="598bb-120">Die Kreditkarten-Revision.</span><span class="sxs-lookup"><span data-stu-id="598bb-120">The credit revision.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Management.UsageCredit.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Management.UsageCredit.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-121">Gibt die Verwendung Kreditkarten-Serialisierungsprogramm.</span><span class="sxs-lookup"><span data-stu-id="598bb-121">Specifies the usage credit serializer.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-122">Abrufen oder Festlegen der Azure-Abonnement-ID, die das Guthaben zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="598bb-122">Gets or sets the Azure subscription ID associated with the credit.</span></span></summary>
        <value><span data-ttu-id="598bb-123">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="598bb-123">Returns <see cref="T:System.String" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.UsageCredit.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="usageCredit.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="598bb-124">Gibt eine Zeichenfolgendarstellung <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span><span class="sxs-lookup"><span data-stu-id="598bb-124">Returns a string representation of <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span></span></summary>
        <returns><span data-ttu-id="598bb-125">Eine Zeichenfolgendarstellung von <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span><span class="sxs-lookup"><span data-stu-id="598bb-125">A string representation of <see cref="T:Microsoft.ServiceBus.Management.UsageCredit" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.UsageCredit.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime with get, set" Usage="Microsoft.ServiceBus.Management.UsageCredit.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="UpdatedAt", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="598bb-126">Ruft ab oder legt das letzte Datum, an die Kreditkarten-Details aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="598bb-126">Gets or sets the last date when the credit details were updated.</span></span></summary>
        <value><span data-ttu-id="598bb-127">Das letzte Datum, wann die Kreditkarten-Details aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="598bb-127">The last date when the credit details were updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>