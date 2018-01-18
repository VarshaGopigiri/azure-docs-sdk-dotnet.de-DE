<Type Name="RetryPolicy" FullName="Microsoft.Azure.ServiceBus.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ecde-101">Stellt eine Abstraktion für die Wiederholung Messagingvorgänge dar.</span><span class="sxs-lookup"><span data-stu-id="8ecde-101">Represents an abstraction for retrying messaging operations.</span></span> <span data-ttu-id="8ecde-102">Benutzer sollten diese Klasse nicht implementiert, und verwenden stattdessen eine der bereitgestellten Implementierungen.</span><span class="sxs-lookup"><span data-stu-id="8ecde-102">Users should not implement this class, and instead should use one of the provided implementations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.ServiceBus.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.ServiceBus.RetryPolicy" Usage="Microsoft.Azure.ServiceBus.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ecde-103">Gibt die standardmäßige wiederholungsrichtlinie <see cref="T:Microsoft.Azure.ServiceBus.RetryExponential" />.</span><span class="sxs-lookup"><span data-stu-id="8ecde-103">Returns the default retry policy, <see cref="T:Microsoft.Azure.ServiceBus.RetryExponential" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="public virtual bool IsRetryableException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsRetryableException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member IsRetryableException : Exception -&gt; bool&#xA;override this.IsRetryableException : Exception -&gt; bool" Usage="retryPolicy.IsRetryableException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary>
            <span data-ttu-id="8ecde-104">Legt fest, ob die Ausnahme, die wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="8ecde-104">Determines whether or not the exception can be retried.</span></span>
            </summary>
        <returns><span data-ttu-id="8ecde-105">Einen booleschen Wert, der angibt, ob der Vorgang wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="8ecde-105">A bool indicating whether or not the operation can be retried.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServerBusy">
      <MemberSignature Language="C#" Value="public bool IsServerBusy { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServerBusy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryPolicy.IsServerBusy" />
      <MemberSignature Language="VB.NET" Value="Public Property IsServerBusy As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServerBusy : bool with get, set" Usage="Microsoft.Azure.ServiceBus.RetryPolicy.IsServerBusy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ecde-106">Legt fest, ob der Server ein ausgelastet Fehler zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="8ecde-106">Determines whether or not the server returned a busy error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected abstract bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryPolicy.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOperation">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RunOperation (Func&lt;System.Threading.Tasks.Task&gt; operation, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RunOperation(class System.Func`1&lt;class System.Threading.Tasks.Task&gt; operation, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryPolicy.RunOperation(System.Func{System.Threading.Tasks.Task},System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RunOperation (operation As Func(Of Task), operationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.RunOperation : Func&lt;System.Threading.Tasks.Task&gt; * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="retryPolicy.RunOperation (operation, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.RetryPolicy/&lt;RunOperation&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="System.Func&lt;System.Threading.Tasks.Task&gt;" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="8ecde-107">Ein <see cref="T:System.Func`2" /> ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="8ecde-107">A <see cref="T:System.Func`2" /> to be executed.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="8ecde-108">Das Timeout für den gesamten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8ecde-108">The timeout for the entire operation.</span></span></param>
        <summary>
            <span data-ttu-id="8ecde-109">Führt eine <see cref="T:System.Func`2" />, mit der aktuellen RetryPolicy.</span><span class="sxs-lookup"><span data-stu-id="8ecde-109">Runs a <see cref="T:System.Func`2" />, using the current RetryPolicy.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusyExceptionMessage">
      <MemberSignature Language="C#" Value="public string ServerBusyExceptionMessage { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerBusyExceptionMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryPolicy.ServerBusyExceptionMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerBusyExceptionMessage As String" />
      <MemberSignature Language="F#" Value="member this.ServerBusyExceptionMessage : string with get, set" Usage="Microsoft.Azure.ServiceBus.RetryPolicy.ServerBusyExceptionMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ecde-110">Ruft die Ausnahmemeldung ab, wenn ein Server ausgelastet-Fehler zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="8ecde-110">Gets the exception message when a server busy error is returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>