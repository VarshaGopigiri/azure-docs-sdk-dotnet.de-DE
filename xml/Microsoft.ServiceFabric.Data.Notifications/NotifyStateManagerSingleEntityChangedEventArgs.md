<Type Name="NotifyStateManagerSingleEntityChangedEventArgs" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs">
  <TypeSignature Language="C#" Value="public class NotifyStateManagerSingleEntityChangedEventArgs : Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyStateManagerSingleEntityChangedEventArgs extends Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyStateManagerSingleEntityChangedEventArgs&#xA;Inherits NotifyStateManagerChangedEventArgs" />
  <TypeSignature Language="F#" Value="type NotifyStateManagerSingleEntityChangedEventArgs = class&#xA;    inherit NotifyStateManagerChangedEventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4404b-101">Stellt Daten für das DictionaryChanged-Ereignis, das von einem transaktionalen Einheit Vorgang verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="4404b-101">Provides data for the DictionaryChanged event caused by a transactional single entity operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyStateManagerSingleEntityChangedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, Microsoft.ServiceFabric.Data.IReliableState reliableState, Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, class Microsoft.ServiceFabric.Data.IReliableState reliableState, valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs.#ctor(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.IReliableState,Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, reliableState As IReliableState, action As NotifyStateManagerChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.IReliableState * Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs (transaction, reliableState, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="reliableState" Type="Microsoft.ServiceFabric.Data.IReliableState" />
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedAction" />
      </Parameters>
      <Docs>
        <param name="transaction"><span data-ttu-id="4404b-102">Eine Transaktion, die die Änderung verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="4404b-102">Transaction that the change is related to.</span></span></param>
        <param name="reliableState">
          <span data-ttu-id="4404b-103"><cref name="IReliableState" />das geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="4404b-103"><cref name="IReliableState" /> that was changed.</span></span></param>
        <param name="action"><span data-ttu-id="4404b-104">Der Typ der Änderung.</span><span class="sxs-lookup"><span data-stu-id="4404b-104">The type of the change.</span></span></param>
        <summary>
            <span data-ttu-id="4404b-105">Initialisiert eine neue Instanz der dem<cref name="NotifyStateManagerSingleEntityChangedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="4404b-105">Initializes a new instance of the <cref name="NotifyStateManagerSingleEntityChangedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableState">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IReliableState ReliableState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.IReliableState ReliableState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs.ReliableState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableState As IReliableState" />
      <MemberSignature Language="F#" Value="member this.ReliableState : Microsoft.ServiceFabric.Data.IReliableState" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs.ReliableState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IReliableState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4404b-106">Ruft den zuverlässigen Zustand ab</span><span class="sxs-lookup"><span data-stu-id="4404b-106">Gets the reliable state</span></span>
            </summary>
        <value>
            <span data-ttu-id="4404b-107">Die <cref name="IReliableState" /> der Benachrichtigung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="4404b-107">The <cref name="IReliableState" /> associated with the notification.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction Transaction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.ITransaction Transaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs.Transaction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transaction As ITransaction" />
      <MemberSignature Language="F#" Value="member this.Transaction : Microsoft.ServiceFabric.Data.ITransaction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerSingleEntityChangedEventArgs.Transaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4404b-108">Ruft die Transaktion ab.</span><span class="sxs-lookup"><span data-stu-id="4404b-108">Gets the transaction.</span></span>
            </summary>
        <value>
            <span data-ttu-id="4404b-109">Die Transaktion, die dem Vorgang zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="4404b-109">The transaction associated with the operation.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>