<Type Name="NoRetry" FullName="Microsoft.Azure.NotificationHubs.NoRetry">
  <TypeSignature Language="C#" Value="public sealed class NoRetry : Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NoRetry extends Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NoRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoRetry&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type NoRetry = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a642e-101">Stellt eine wiederholungsrichtlinie auf, die keine Wiederholungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a642e-101">Represents a retry policy that performs no retries.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NoRetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a642e-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NoRetry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a642e-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NoRetry" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.NotificationHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.NotificationHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NoRetry.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="noRetry.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a642e-103">Erstellt eine Kopie dieser Instanz.</span><span class="sxs-lookup"><span data-stu-id="a642e-103">Creates a copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="a642e-104">Die erstellte Kopie dieser Instanz.</span><span class="sxs-lookup"><span data-stu-id="a642e-104">The created copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected override bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NoRetry.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsRetryableException : Exception -&gt; bool" Usage="noRetry.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException"></param>
        <summary>
            <span data-ttu-id="a642e-105">Bestimmen Sie, ob die Ausnahme ist in Ordnung, um einen Wiederholungsversuch</span><span class="sxs-lookup"><span data-stu-id="a642e-105">Determine if the exception is ok to retry</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a642e-106">Wenn dies auf "false" zurückgeben, wird keine Wiederholung stattfinden.</span><span class="sxs-lookup"><span data-stu-id="a642e-106">if this return false, no retry will take place.</span></span>
            <span data-ttu-id="a642e-107">Andernfalls verwenden wir die OnShouldRetry() zum Ermitteln, wann zu wiederholen.</span><span class="sxs-lookup"><span data-stu-id="a642e-107">Otherwise we will use the OnShouldRetry() to determine when to retry.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NoRetry.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="noRetry.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime"></param>
        <param name="currentRetryCount"></param>
        <param name="retryInterval"></param>
        <summary>
            <span data-ttu-id="a642e-108">Berechnen Sie das Wiederholungsintervall für die wiederholungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="a642e-108">Calculate the retry interval for the retry policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a642e-109">Wenn diese Methode "true" zurückgeben, erfolgt wiederholen Sie den Vorgang nach Thread RetryInteval Zeitraum im Leerlauf.</span><span class="sxs-lookup"><span data-stu-id="a642e-109">If this method return true, retry will take place after thread idle for retryInteval amount of time.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>