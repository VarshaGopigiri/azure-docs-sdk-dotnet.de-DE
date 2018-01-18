<Type Name="ITelemetryChannel" FullName="Microsoft.ApplicationInsights.Channel.ITelemetryChannel">
  <TypeSignature Language="C#" Value="public interface ITelemetryChannel : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryChannel implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.ITelemetryChannel" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryChannel&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITelemetryChannel = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b5f98-101">Stellt einen Kommunikationskanal zum Senden von Telemetriedaten an Application Insights dar.</span><span class="sxs-lookup"><span data-stu-id="b5f98-101">Represents a communication channel for sending telemetry to application insights.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeveloperMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeveloperMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeveloperMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.DeveloperMode" />
      <MemberSignature Language="VB.NET" Value="Public Property DeveloperMode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeveloperMode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetryChannel.DeveloperMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5f98-102">Ruft ab oder legt einen Wert, der angibt, ob über diesen Kanal im Entwicklermodus befindet.</span><span class="sxs-lookup"><span data-stu-id="b5f98-102">Gets or sets a value indicating whether this channel is in developer mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointAddress">
      <MemberSignature Language="C#" Value="public string EndpointAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.EndpointAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndpointAddress : string with get, set" Usage="Microsoft.ApplicationInsights.Channel.ITelemetryChannel.EndpointAddress" />
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
            <span data-ttu-id="b5f98-103">Ruft ab oder legt die Endpunktadresse des Kanals fest.</span><span class="sxs-lookup"><span data-stu-id="b5f98-103">Gets or sets the endpoint address of the channel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Sub Flush ()" />
      <MemberSignature Language="F#" Value="abstract member Flush : unit -&gt; unit" Usage="iTelemetryChannel.Flush " />
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
            <span data-ttu-id="b5f98-104">Leert den Puffer im Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="b5f98-104">Flushes the in-memory buffer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ApplicationInsights.Channel.ITelemetry item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ApplicationInsights.Channel.ITelemetry item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.ITelemetryChannel.Send(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (item As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="iTelemetryChannel.Send item" />
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
        <Parameter Name="item" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>
            <span data-ttu-id="b5f98-105">Sendet eine Instanz des ITelemetry über diesen Kanal.</span><span class="sxs-lookup"><span data-stu-id="b5f98-105">Sends an instance of ITelemetry through the channel.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>