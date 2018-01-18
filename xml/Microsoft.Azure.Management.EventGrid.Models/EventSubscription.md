<Type Name="EventSubscription" FullName="Microsoft.Azure.Management.EventGrid.Models.EventSubscription">
  <TypeSignature Language="C#" Value="public class EventSubscription : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventSubscription extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Class EventSubscription&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type EventSubscription = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f7da6-101">Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="f7da6-101">Event Subscription</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-102">Initialisiert eine neue Instanz der EventSubscription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7da6-102">Initializes a new instance of the EventSubscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventSubscription (string id = null, string name = null, string type = null, string topic = null, string provisioningState = null, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination = null, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter = null, System.Collections.Generic.IList&lt;string&gt; labels = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string topic, string provisioningState, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination destination, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter filter, class System.Collections.Generic.IList`1&lt;string&gt; labels) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional topic As String = null, Optional provisioningState As String = null, Optional destination As EventSubscriptionDestination = null, Optional filter As EventSubscriptionFilter = null, Optional labels As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.EventSubscription : string * string * string * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="new Microsoft.Azure.Management.EventGrid.Models.EventSubscription (id, name, type, topic, provisioningState, destination, filter, labels)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="topic" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination" />
        <Parameter Name="filter" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter" />
        <Parameter Name="labels" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f7da6-103">Vollqualifizierte Bezeichner für die Ressource</span><span class="sxs-lookup"><span data-stu-id="f7da6-103">Fully qualified identifier of the resource</span></span></param>
        <param name="name"><span data-ttu-id="f7da6-104">Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="f7da6-104">Name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="f7da6-105">Typ der Ressource</span><span class="sxs-lookup"><span data-stu-id="f7da6-105">Type of the resource</span></span></param>
        <param name="topic"><span data-ttu-id="f7da6-106">Der Name des Themas die Ereignis-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="f7da6-106">Name of the topic of the event subscription.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f7da6-107">Der Bereitstellungsstatus der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="f7da6-107">Provisioning state of the event subscription.</span></span> <span data-ttu-id="f7da6-108">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Abgebrochen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="f7da6-108">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span></param>
        <param name="destination"><span data-ttu-id="f7da6-109">Informationen über das Ziel, in dem Ereignisse enthalten, für das Ereignisabonnement übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7da6-109">Information about the destination where events have to be delivered for the event subscription.</span></span></param>
        <param name="filter"><span data-ttu-id="f7da6-110">Informationen zu den Filter für das Ereignisabonnement.</span><span class="sxs-lookup"><span data-stu-id="f7da6-110">Information about the filter for the event subscription.</span></span></param>
        <param name="labels"><span data-ttu-id="f7da6-111">Liste der Benutzer definiert die Bezeichnungen.</span><span class="sxs-lookup"><span data-stu-id="f7da6-111">List of user defined labels.</span></span></param>
        <summary>
            <span data-ttu-id="f7da6-112">Initialisiert eine neue Instanz der EventSubscription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f7da6-112">Initializes a new instance of the EventSubscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As EventSubscriptionDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-113">Ruft ab oder legt fest, die Informationen zum Ziel, in dem Ereignisse enthalten, für das Ereignisabonnement übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f7da6-113">Gets or sets information about the destination where events have to be delivered for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As EventSubscriptionFilter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-114">Ruft ab, oder legt Sie Informationen zu den Filter für das Ereignisabonnement fest.</span><span class="sxs-lookup"><span data-stu-id="f7da6-114">Gets or sets information about the filter for the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Labels">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Labels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Labels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Labels" />
      <MemberSignature Language="VB.NET" Value="Public Property Labels As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Labels : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Labels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.labels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-115">Ruft ab oder legt die Liste der benutzerdefinierten Bezeichnungen.</span><span class="sxs-lookup"><span data-stu-id="f7da6-115">Gets or sets list of user defined labels.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-116">Ruft das Ereignisabonnement Zustand bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f7da6-116">Gets provisioning state of the event subscription.</span></span> <span data-ttu-id="f7da6-117">Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Abgebrochen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="f7da6-117">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Topic">
      <MemberSignature Language="C#" Value="public string Topic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Topic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Topic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Topic As String" />
      <MemberSignature Language="F#" Value="member this.Topic : string" Usage="Microsoft.Azure.Management.EventGrid.Models.EventSubscription.Topic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.topic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7da6-118">Ruft das Thema das Ereignisabonnement Namen ab.</span><span class="sxs-lookup"><span data-stu-id="f7da6-118">Gets name of the topic of the event subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>