<Type Name="RelayedOnewayTransportElement" FullName="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement">
  <TypeSignature Language="C#" Value="public sealed class RelayedOnewayTransportElement : Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RelayedOnewayTransportElement extends Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RelayedOnewayTransportElement&#xA;Inherits ConnectionOrientedTransportElement" />
  <TypeSignature Language="F#" Value="type RelayedOnewayTransportElement = class&#xA;    inherit ConnectionOrientedTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="4522f-101">Stellt ein Konfigurationselement dar, wenn in einer benutzerdefinierten Bindung eingeschlossen ist, bezeichnet einen Kanal zum Übertragen von unidirektionaler Nachrichten über den Azure-Servicebus.</span><span class="sxs-lookup"><span data-stu-id="4522f-101">Represents a configuration element that, when included in a custom binding, specifies a channel to transfer one-way messages through the Azure Service Bus.</span></span> <span data-ttu-id="4522f-102">Diese Klasse kann nicht vererbt werden.</span><span class="sxs-lookup"><span data-stu-id="4522f-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4522f-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4522f-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="relayedOnewayTransportElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"><span data-ttu-id="4522f-104">Das Bindungselement, das die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="4522f-104">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="4522f-105">Übernimmt die Einstellungen dieses Konfigurationselements auf das angegebene Bindungselement.</span><span class="sxs-lookup"><span data-stu-id="4522f-105">Applies the settings from this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4522f-106">Ruft den Typ der aktuellen Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="4522f-106">Gets the type of the current instance.</span></span></summary>
        <value><span data-ttu-id="4522f-107">Gibt eine <see cref="T:System.Type" /> , enthält den Typ der aktuellen Instanz der Typ ist des <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />.</span><span class="sxs-lookup"><span data-stu-id="4522f-107">Returns a <see cref="T:System.Type" /> that contains the type of the current instance, which is the type of <see cref="T:Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As RelayedOnewayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.RelayedOnewayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4522f-108">Ruft ab oder legt einen XML-Wert, der das unidirektionale Verbindungsmodus beschreibt.</span><span class="sxs-lookup"><span data-stu-id="4522f-108">Gets or sets an XML value that describes the one-way connection mode.</span></span></summary>
        <value><span data-ttu-id="4522f-109">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" /> , die den Verbindungsmodus enthält.</span><span class="sxs-lookup"><span data-stu-id="4522f-109">Returns a <see cref="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" /> that contains the connection mode.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionPoolSettings As SocketConnectionPoolSettingsElement" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement with get, set" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionPoolSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4522f-110">Ruft ab oder legt einen XML-Wert, der die verbindungspooleinstellungen für die aktuelle Instanz beschreibt.</span><span class="sxs-lookup"><span data-stu-id="4522f-110">Gets or sets an XML value that describes the connection pool settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="4522f-111">Gibt eine <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" /> , enthält die verbindungspooleinstellungen, das verwendet wird, durch das Bindungselement, das auf die aktuelle Instanz angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="4522f-111">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" /> that contains the connection pool settings used by the binding element that the current instance is applied to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="relayedOnewayTransportElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"> <span data-ttu-id="4522f-112">Das Konfigurationselement, aus dem kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="4522f-112">The configuration element to copy from.</span></span></param>
        <summary><span data-ttu-id="4522f-113">Kopiert die Einstellungen des angegebenen Konfigurationselements auf die aktuelle Instanz.</span><span class="sxs-lookup"><span data-stu-id="4522f-113">Copies the settings from the specified configuration element to the current instance.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="relayedOnewayTransportElement.CreateDefaultBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="relayedOnewayTransportElement.InitializeFrom bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4522f-114">Ruft die maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange ab, oder legt diese fest.</span><span class="sxs-lookup"><span data-stu-id="4522f-114">Gets or sets the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="4522f-115">Maximal mögliche Anzahl der ausstehenden Verbindungsanforderungen in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="4522f-115">The maximum number of queued connection requests that can be pending.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4522f-116">Ruft ab, oder legt ihn fest einen XML-Wert, der den Authentifizierungstyp, der in dieses Konfigurationselement angegebene beschreibt.</span><span class="sxs-lookup"><span data-stu-id="4522f-116">Gets or sets an XML value that describes the authentication type specified in this configuration element.</span></span></summary>
        <value><span data-ttu-id="4522f-117">Gibt eine <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> , enthält den Typ der Authentifizierung verwendet werden, von den Bindungselementen, die auf die aktuelle Instanz angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="4522f-117">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the type of authentication to be used by binding elements that the current instance is applied to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>