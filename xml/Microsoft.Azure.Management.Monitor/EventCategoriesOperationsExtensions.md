<Type Name="EventCategoriesOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventCategoriesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventCategoriesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventCategoriesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventCategoriesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="65bd4-101">Erweiterungsmethoden für EventCategoriesOperations.</span><span class="sxs-lookup"><span data-stu-id="65bd4-101">Extension methods for EventCategoriesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; List (this Microsoft.Azure.Management.Monitor.IEventCategoriesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt; List(class Microsoft.Azure.Management.Monitor.IEventCategoriesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IEventCategoriesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IEventCategoriesOperations) As IEnumerable(Of LocalizableString)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IEventCategoriesOperations -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;" Usage="Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IEventCategoriesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65bd4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="65bd4-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65bd4-103">Ruft die Liste der verfügbaren Ereigniskategorien, die in den Protokollen Aktivitätsdienst unterstützt. &lt;Br&gt;die aktuelle Liste enthält die folgenden: Verwaltung, Sicherheit, ServiceHealth, Warnung, Empfehlung und Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="65bd4-103">Get the list of available event categories supported in the Activity Logs Service.&lt;br&gt;The current list includes the following: Administrative, Security, ServiceHealth, Alert, Recommendation, Policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IEventCategoriesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IEventCategoriesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IEventCategoriesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IEventCategoriesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.EventCategoriesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IEventCategoriesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="65bd4-104">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="65bd4-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="65bd4-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="65bd4-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="65bd4-106">Ruft die Liste der verfügbaren Ereigniskategorien, die in den Protokollen Aktivitätsdienst unterstützt. &lt;Br&gt;die aktuelle Liste enthält die folgenden: Verwaltung, Sicherheit, ServiceHealth, Warnung, Empfehlung und Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="65bd4-106">Get the list of available event categories supported in the Activity Logs Service.&lt;br&gt;The current list includes the following: Administrative, Security, ServiceHealth, Alert, Recommendation, Policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>