<Type Name="ManagedServiceIdentityTokenProvider" FullName="Microsoft.Azure.EventHubs.ManagedServiceIdentityTokenProvider">
  <TypeSignature Language="C#" Value="public class ManagedServiceIdentityTokenProvider : Microsoft.Azure.EventHubs.TokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedServiceIdentityTokenProvider extends Microsoft.Azure.EventHubs.TokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.ManagedServiceIdentityTokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedServiceIdentityTokenProvider&#xA;Inherits TokenProvider" />
  <TypeSignature Language="F#" Value="type ManagedServiceIdentityTokenProvider = class&#xA;    inherit TokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.TokenProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17808-101">Stellt die Azure Active Directory-Tokenanbieter für die Integration von Azure verwaltet Dienstidentität dar.</span><span class="sxs-lookup"><span data-stu-id="17808-101">Represents the Azure Active Directory token provider for Azure Managed Service Identity integration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedServiceIdentityTokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ManagedServiceIdentityTokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.ManagedServiceIdentityTokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;" Usage="managedServiceIdentityTokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.ManagedServiceIdentityTokenProvider/&lt;GetTokenAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="17808-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="17808-102">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="17808-103">Die Zeitspanne an, die angibt, den Timeoutwert für die Nachricht abruft, die das Sicherheitstoken</span><span class="sxs-lookup"><span data-stu-id="17808-103">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="17808-104">Ruft eine <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> für die angegebene Zielgruppe und die Dauer.</span><span class="sxs-lookup"><span data-stu-id="17808-104">Gets a <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" /> for the given audience and duration.</span></span>
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.EventHubs.SecurityToken" />
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>