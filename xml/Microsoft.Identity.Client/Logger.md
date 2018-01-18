<Type Name="Logger" FullName="Microsoft.Identity.Client.Logger">
  <TypeSignature Language="C#" Value="public sealed class Logger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Logger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.Logger" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Logger" />
  <TypeSignature Language="F#" Value="type Logger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="699b7-101">Rückrufe usw. konfigurieren MSAL Protokollierung-Klasse, die Entwicklern ermöglicht, Protokollebene, konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="699b7-101">MSAL Logger class that allows developers to configure log level, configure callbacks etc.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public static Microsoft.Identity.Client.Logger.LogLevel Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype Microsoft.Identity.Client.Logger/LogLevel Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.Level" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property Level As Logger.LogLevel" />
      <MemberSignature Language="F#" Value="member this.Level : Microsoft.Identity.Client.Logger.LogLevel with get, set" Usage="Microsoft.Identity.Client.Logger.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.Logger+LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="699b7-102">Konfigurierbare Protokollebene.</span><span class="sxs-lookup"><span data-stu-id="699b7-102">Configurable log level.</span></span> <span data-ttu-id="699b7-103">Standardwert ist Info.</span><span class="sxs-lookup"><span data-stu-id="699b7-103">Default value is Info.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogCallback">
      <MemberSignature Language="C#" Value="public static Microsoft.Identity.Client.LogCallback LogCallback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Identity.Client.LogCallback LogCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.LogCallback" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property LogCallback As LogCallback" />
      <MemberSignature Language="F#" Value="member this.LogCallback : Microsoft.Identity.Client.LogCallback" Usage="Microsoft.Identity.Client.Logger.LogCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.LogCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="699b7-104">Rückrufinstanz, die vom Entwickler zu nutzen, und veröffentlichen die Protokolle auf benutzerdefinierte Weise bereitgestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="699b7-104">Callback instance that can be provided by the developer to consume and publish logs in a custom manner.</span></span> <span data-ttu-id="699b7-105">Die Eigenschaft kann nur einmal festgelegt werden, und es löst ArgumentException auf, wenn zweimal aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="699b7-105">The property can only be set once and it will throw an ArgumentException if called twice.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PiiLoggingEnabled">
      <MemberSignature Language="C#" Value="public static bool PiiLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool PiiLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.Logger.PiiLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property PiiLoggingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.PiiLoggingEnabled : bool with get, set" Usage="Microsoft.Identity.Client.Logger.PiiLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="699b7-106">Kennzeichen, das aktiviert bzw. deaktiviert die Protokollierung von PII-Daten.</span><span class="sxs-lookup"><span data-stu-id="699b7-106">Flag to enable/disable logging of PII data.</span></span> <span data-ttu-id="699b7-107">PII-Protokolle werden nie an Standardeinstellung Ausgaben wie Konsole, Logcat oder NSLog geschrieben.</span><span class="sxs-lookup"><span data-stu-id="699b7-107">PII logs are never written to default outputs like Console, Logcat or NSLog.</span></span>
            <span data-ttu-id="699b7-108">Standardmäßig ist "false" festgelegt.</span><span class="sxs-lookup"><span data-stu-id="699b7-108">Default is set to false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>