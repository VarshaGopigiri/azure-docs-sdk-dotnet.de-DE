<Type Name="LoggerCallbackHandler" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler">
  <TypeSignature Language="C#" Value="public sealed class LoggerCallbackHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LoggerCallbackHandler extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoggerCallbackHandler" />
  <TypeSignature Language="F#" Value="type LoggerCallbackHandler = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b4b04-101">Diese Klasse dient zum Verwalten der Rückrufstatus und seine Ausführung.</span><span class="sxs-lookup"><span data-stu-id="b4b04-101">This class is responsible for managing the callback state and its execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoggerCallbackHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Callback">
      <MemberSignature Language="C#" Value="public static Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback Callback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback Callback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.Callback" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property Callback As IAdalLogCallback" />
      <MemberSignature Language="F#" Value="member this.Callback : Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.Callback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4b04-102">Rückrufimplementierung</span><span class="sxs-lookup"><span data-stu-id="b4b04-102">Callback implementation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultLogging">
      <MemberSignature Language="C#" Value="public static bool UseDefaultLogging;" />
      <MemberSignature Language="ILAsm" Value=".field public static bool UseDefaultLogging" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.UseDefaultLogging" />
      <MemberSignature Language="VB.NET" Value="Public Shared UseDefaultLogging As Boolean " />
      <MemberSignature Language="F#" Value=" staticval mutable UseDefaultLogging : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.UseDefaultLogging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4b04-103">Flag steuern, ob die standardprotokollierung ausgeführt werden soll, zusätzlich zum Aufrufen der <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.Callback" /> Handler (sofern vorhanden)</span><span class="sxs-lookup"><span data-stu-id="b4b04-103">Flag to control whether default logging should be performed in addition to calling the <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.LoggerCallbackHandler.Callback" /> handler (if any)</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>