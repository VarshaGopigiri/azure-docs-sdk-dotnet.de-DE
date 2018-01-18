<Type Name="TelemetryDebugWriter" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter">
  <TypeSignature Language="C#" Value="public class TelemetryDebugWriter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TelemetryDebugWriter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter" />
  <TypeSignature Language="VB.NET" Value="Public Class TelemetryDebugWriter" />
  <TypeSignature Language="F#" Value="type TelemetryDebugWriter = class&#xA;    interface IDebugOutput" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="08854-101">Schreibt die Telemetrie-Elemente, um die Ausgabe zu debuggen.</span><span class="sxs-lookup"><span data-stu-id="08854-101">Writes telemetry items to debug output.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryDebugWriter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTracingDisabled">
      <MemberSignature Language="C#" Value="public static bool IsTracingDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool IsTracingDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter.IsTracingDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property IsTracingDisabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTracingDisabled : bool with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter.IsTracingDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08854-102">Ruft ab oder legt einen Wert, der angibt, ob beim Schreiben der Telemetrie-Elemente, um die Ausgabe zu Debuggen aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="08854-102">Gets or sets a value indicating whether writing telemetry items to debug output is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteTelemetry">
      <MemberSignature Language="C#" Value="public static void WriteTelemetry (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry, string filteredBy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteTelemetry(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry, string filteredBy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter.WriteTelemetry(Microsoft.ApplicationInsights.Channel.ITelemetry,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteTelemetry (telemetry As ITelemetry, Optional filteredBy As String = null)" />
      <MemberSignature Language="F#" Value="static member WriteTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry * string -&gt; unit" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryDebugWriter.WriteTelemetry (telemetry, filteredBy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
        <Parameter Name="filteredBy" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="08854-103">Element schreiben.</span><span class="sxs-lookup"><span data-stu-id="08854-103">Item to write.</span></span></param>
        <param name="filteredBy"><span data-ttu-id="08854-104">Wenn angegeben, gibt Sie an der Telemetrie-Element wurde herausgefiltert und nicht an die API gesendeten.</span><span class="sxs-lookup"><span data-stu-id="08854-104">If specified, indicates the telemetry item was filtered out and not sent to the API.</span></span></param>
        <summary>
            <span data-ttu-id="08854-105">Schreiben des angegebenen <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Element aus, um die Ausgabe zu debuggen.</span><span class="sxs-lookup"><span data-stu-id="08854-105">Write the specified <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> item to debug output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>