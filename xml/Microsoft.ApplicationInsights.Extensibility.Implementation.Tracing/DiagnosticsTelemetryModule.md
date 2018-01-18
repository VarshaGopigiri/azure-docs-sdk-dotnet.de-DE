<Type Name="DiagnosticsTelemetryModule" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule">
  <TypeSignature Language="C#" Value="public sealed class DiagnosticsTelemetryModule : IDisposable, Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager, Microsoft.ApplicationInsights.Extensibility.ITelemetryModule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DiagnosticsTelemetryModule extends System.Object implements class Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager, class Microsoft.ApplicationInsights.Extensibility.ITelemetryModule, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DiagnosticsTelemetryModule&#xA;Implements IDisposable, IHeartbeatPropertyManager, ITelemetryModule" />
  <TypeSignature Language="F#" Value="type DiagnosticsTelemetryModule = class&#xA;    interface ITelemetryModule&#xA;    interface IHeartbeatPropertyManager&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Extensibility.ITelemetryModule</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="04975-101">Verwenden Sie Telemetrie Diagnosemodul SDK interne Probleme mit dem Portal und VS Debug-Fenster "Ausgabe" melden.</span><span class="sxs-lookup"><span data-stu-id="04975-101">Use diagnostics telemetry module to report SDK internal problems to the portal and VS debug output window.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsTelemetryModule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04975-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="04975-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddHeartbeatProperty">
      <MemberSignature Language="C#" Value="public bool AddHeartbeatProperty (string propertyName, string propertyValue, bool isHealthy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool AddHeartbeatProperty(string propertyName, string propertyValue, bool isHealthy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.AddHeartbeatProperty(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddHeartbeatProperty (propertyName As String, propertyValue As String, isHealthy As Boolean) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member AddHeartbeatProperty : string * string * bool -&gt; bool&#xA;override this.AddHeartbeatProperty : string * string * bool -&gt; bool" Usage="diagnosticsTelemetryModule.AddHeartbeatProperty (propertyName, propertyValue, isHealthy)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager.AddHeartbeatProperty(System.String,System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="propertyValue" Type="System.String" />
        <Parameter Name="isHealthy" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">To be added.</param>
        <param name="propertyValue">To be added.</param>
        <param name="isHealthy">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsInstrumentationKey">
      <MemberSignature Language="C#" Value="public string DiagnosticsInstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DiagnosticsInstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.DiagnosticsInstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsInstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsInstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.DiagnosticsInstrumentationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04975-103">Ruft ab, oder legt ihn fest instrumentierungsschlüssel für die Diagnose.</span><span class="sxs-lookup"><span data-stu-id="04975-103">Gets or sets instrumentation key for diagnostics.</span></span> <span data-ttu-id="04975-104">Verwenden Sie zum SDK interne Probleme, separate instrumentierungsschlüssel reporting umleiten.</span><span class="sxs-lookup"><span data-stu-id="04975-104">Use to redirect SDK internal problems reporting to the separate instrumentation key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="diagnosticsTelemetryModule.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04975-105">Verwirft dieses Objekt.</span><span class="sxs-lookup"><span data-stu-id="04975-105">Disposes this object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludedHeartbeatProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExcludedHeartbeatProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExcludedHeartbeatProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.ExcludedHeartbeatProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExcludedHeartbeatProperties As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExcludedHeartbeatProperties : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.ExcludedHeartbeatProperties" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager.ExcludedHeartbeatProperties</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~DiagnosticsTelemetryModule ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="diagnosticsTelemetryModule.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04975-106">Schließt eine Instanz von der <see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="04975-106">Finalizes an instance of the <see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HeartbeatInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HeartbeatInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HeartbeatInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.HeartbeatInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HeartbeatInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HeartbeatInterval : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.HeartbeatInterval" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager.HeartbeatInterval</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.Initialize(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (configuration As TelemetryConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; unit&#xA;override this.Initialize : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; unit" Usage="diagnosticsTelemetryModule.Initialize configuration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Extensibility.ITelemetryModule.Initialize(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configuration" Type="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
      </Parameters>
      <Docs>
        <param name="configuration"><span data-ttu-id="04975-107">Telemetrie-Konfiguration für dieses Modul Telemetrie verwenden.</span><span class="sxs-lookup"><span data-stu-id="04975-107">Telemetry configuration to use for this telemetry module.</span></span></param>
        <summary>
            <span data-ttu-id="04975-108">Initialisiert dieses Telemetrie-Modul.</span><span class="sxs-lookup"><span data-stu-id="04975-108">Initializes this telemetry module.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHeartbeatEnabled">
      <MemberSignature Language="C#" Value="public bool IsHeartbeatEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsHeartbeatEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.IsHeartbeatEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsHeartbeatEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsHeartbeatEnabled : bool with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.IsHeartbeatEnabled" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager.IsHeartbeatEnabled</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetHeartbeatProperty">
      <MemberSignature Language="C#" Value="public bool SetHeartbeatProperty (string propertyName, string propertyValue = null, Nullable&lt;bool&gt; isHealthy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool SetHeartbeatProperty(string propertyName, string propertyValue, valuetype System.Nullable`1&lt;bool&gt; isHealthy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.SetHeartbeatProperty(System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Function SetHeartbeatProperty (propertyName As String, Optional propertyValue As String = null, Optional isHealthy As Nullable(Of Boolean) = null) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member SetHeartbeatProperty : string * string * Nullable&lt;bool&gt; -&gt; bool&#xA;override this.SetHeartbeatProperty : string * string * Nullable&lt;bool&gt; -&gt; bool" Usage="diagnosticsTelemetryModule.SetHeartbeatProperty (propertyName, propertyValue, isHealthy)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.IHeartbeatPropertyManager.SetHeartbeatProperty(System.String,System.String,System.Nullable{System.Boolean})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="propertyValue" Type="System.String" />
        <Parameter Name="isHealthy" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="propertyName">To be added.</param>
        <param name="propertyValue">To be added.</param>
        <param name="isHealthy">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public string Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As String" />
      <MemberSignature Language="F#" Value="member this.Severity : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.Tracing.DiagnosticsTelemetryModule.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04975-109">Ruft ab, oder legt ihn fest Diagnose Telemetrie Modul LogLevel-Konfigurationseinstellung.</span><span class="sxs-lookup"><span data-stu-id="04975-109">Gets or sets diagnostics Telemetry Module LogLevel configuration setting.</span></span> <span data-ttu-id="04975-110">Mögliche Werte LogAlways "," Kritisch "," Fehler "," Warnung "," Information "und" ausführlich.</span><span class="sxs-lookup"><span data-stu-id="04975-110">Possible values LogAlways, Critical, Error, Warning, Informational and Verbose.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>