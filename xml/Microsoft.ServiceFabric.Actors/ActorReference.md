<Type Name="ActorReference" FullName="Microsoft.ServiceFabric.Actors.ActorReference">
  <TypeSignature Language="C#" Value="public sealed class ActorReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ActorReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ActorReference" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorReference" />
  <TypeSignature Language="F#" Value="type ActorReference = class&#xA;    interface IActorReference" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ActorReference", Namespace="urn:actors")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a055b-101">Kapselung eines Verweises auf ein Akteur für die Serialisierung.</span><span class="sxs-lookup"><span data-stu-id="a055b-101">Encapsulation of a reference to an actor for serialization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a055b-102">Initialisiert eine neue Instanz der ActorReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a055b-102">Initializes a new instance of the ActorReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorId">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.ActorId ActorId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.ActorId ActorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.ActorReference.ActorId" />
      <MemberSignature Language="VB.NET" Value="Public Property ActorId As ActorId" />
      <MemberSignature Language="F#" Value="member this.ActorId : Microsoft.ServiceFabric.Actors.ActorId with get, set" Usage="Microsoft.ServiceFabric.Actors.ActorReference.ActorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ActorId", Order=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a055b-103">Ruft ab oder legt die <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> des Darstellers.</span><span class="sxs-lookup"><span data-stu-id="a055b-103">Gets or sets the <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor.</span></span>
            </summary>
        <value>
          <span data-ttu-id="a055b-104"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />des Darstellers.</span><span class="sxs-lookup"><span data-stu-id="a055b-104"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bind">
      <MemberSignature Language="C#" Value="public object Bind (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Bind(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorReference.Bind(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function Bind (actorInterfaceType As Type) As Object" />
      <MemberSignature Language="F#" Value="abstract member Bind : Type -&gt; obj&#xA;override this.Bind : Type -&gt; obj" Usage="actorReference.Bind actorInterfaceType" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.IActorReference.Bind(System.Type)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="a055b-105">Akteur-Schnittstelle für das erstellte <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> implementieren.</span><span class="sxs-lookup"><span data-stu-id="a055b-105">Actor interface for the created <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> to implement.</span></span></param>
        <summary>
            <span data-ttu-id="a055b-106">Erstellt ein <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> , eine Akteur-Schnittstelle implementiert, für die der Akteur, der mithilfe der <see cref="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy(System.Type,System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="a055b-106">Creates an <see cref="T:Microsoft.ServiceFabric.Actors.Client.ActorProxy" /> that implements an actor interface for the actor using the <see cref="M:Microsoft.ServiceFabric.Actors.Client.ActorProxyFactory.CreateActorProxy(System.Type,System.Uri,Microsoft.ServiceFabric.Actors.ActorId,System.String)" /> method.</span></span>
                </summary>
        <returns><span data-ttu-id="a055b-107">Ein Akteur-Proxy-Objekt, das implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> und TActorInterface.</span><span class="sxs-lookup"><span data-stu-id="a055b-107">An actor proxy object that implements <see cref="T:Microsoft.ServiceFabric.Actors.Client.IActorProxy" /> and TActorInterface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.ActorReference Get (object actor);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.ActorReference Get(object actor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorReference.Get(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Get (actor As Object) As ActorReference" />
      <MemberSignature Language="F#" Value="static member Get : obj -&gt; Microsoft.ServiceFabric.Actors.ActorReference" Usage="Microsoft.ServiceFabric.Actors.ActorReference.Get actor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorReference</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actor" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="actor"><span data-ttu-id="a055b-108">Akteur abzurufenden Objekts <see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" /> für.</span><span class="sxs-lookup"><span data-stu-id="a055b-108">Actor object to get <see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" /> for.</span></span></param>
        <summary>
            <span data-ttu-id="a055b-109">Ruft <see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" /> für die der Akteur.</span><span class="sxs-lookup"><span data-stu-id="a055b-109">Gets <see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" /> for the actor.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="a055b-110"><see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" />Objekt für die der Akteur.</span><span class="sxs-lookup"><span data-stu-id="a055b-110"><see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" /> object for the actor.</span></span></returns>
        <remarks><span data-ttu-id="a055b-111">Ein null-Wert wird zurückgegeben, wenn Akteur als null übergeben wird.</span><span class="sxs-lookup"><span data-stu-id="a055b-111">A null value is returned if actor is passed as null.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerName">
      <MemberSignature Language="C#" Value="public string ListenerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.ActorReference.ListenerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenerName As String" />
      <MemberSignature Language="F#" Value="member this.ListenerName : string with get, set" Usage="Microsoft.ServiceFabric.Actors.ActorReference.ListenerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="ListenerName", Order=2)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a055b-112">Ruft ab oder legt den Namen des Listeners im Dienst Akteur zu verwenden, bei der Kommunikation mit dem Akteur-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a055b-112">Gets or sets the name of the listener in the actor service to use when communicating with the actor service.</span></span>
            </summary>
        <value><span data-ttu-id="a055b-113">Der Name des Listeners</span><span class="sxs-lookup"><span data-stu-id="a055b-113">The name of the listener</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUri">
      <MemberSignature Language="C#" Value="public Uri ServiceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.ActorReference.ServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceUri : Uri with get, set" Usage="Microsoft.ServiceFabric.Actors.ActorReference.ServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="ServiceUri", Order=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a055b-114">Ruft die Uri des Diensts Akteur, die den Akteur in Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="a055b-114">Gets Uri of the actor service that hosts the actor in service fabric cluster.</span></span>
            </summary>
        <value><span data-ttu-id="a055b-115">Dienst-Uri den Akteur in Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="a055b-115">Service Uri which hosts the actor in service fabric cluster.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>