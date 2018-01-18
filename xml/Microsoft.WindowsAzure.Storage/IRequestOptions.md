<Type Name="IRequestOptions" FullName="Microsoft.WindowsAzure.Storage.IRequestOptions">
  <TypeSignature Language="C#" Value="public interface IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRequestOptions" />
  <TypeSignature Language="F#" Value="type IRequestOptions = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81881-101">Eine für anforderungsoptionstypen erforderliche Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="81881-101">An interface required for request option types.</span></span>
            </summary>
    <remarks><span data-ttu-id="81881-102">Die <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />, und <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> Klassen implementieren die <see cref="T:Microsoft.WindowsAzure.Storage.IRequestOptions" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="81881-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />, and <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> classes implement the <see cref="T:Microsoft.WindowsAzure.Storage.IRequestOptions" /> interface.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81881-103">Ruft ab oder legt den Positionsmodus der Anforderung fest.</span><span class="sxs-lookup"><span data-stu-id="81881-103">Gets or sets the location mode of the request.</span></span>
            </summary>
        <value><span data-ttu-id="81881-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="81881-104">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81881-105">Ruft ab oder legt die maximale Ausführungszeit für alle möglichen Wiederholungen fest.</span><span class="sxs-lookup"><span data-stu-id="81881-105">Gets or sets the maximum execution time across all potential retries.</span></span>
            </summary>
        <value><span data-ttu-id="81881-106">Ein <see cref="T:System.TimeSpan" /> , enthält die maximale Ausführungszeit für alle möglichen Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="81881-106">A <see cref="T:System.TimeSpan" /> containing the maximum execution time across all potential retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81881-107">Ruft ab oder legt einen Wert anzugeben, ob die Daten geschrieben und gelesen werden, von der Clientbibliothek verschlüsselt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="81881-107">Gets or sets a value to indicate whether data written and read by the client library should be encrypted.</span></span>
            </summary>
        <value><span data-ttu-id="81881-108">Verwendung <c>"true"</c> um anzugeben, dass die Daten werden soll, für alle Transaktionen verschlüsselt und entschlüsselt, und andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="81881-108">Use <c>true</c> to specify that data should be encrypted/decrypted for all transactions; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81881-109">Ruft ab oder legt die wiederholungsrichtlinie für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="81881-109">Gets or sets the retry policy for the request.</span></span>
            </summary>
        <value><span data-ttu-id="81881-110">Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="81881-110">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81881-111">Ruft ab oder legt den standardmäßigen Servertimeout für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="81881-111">Gets or sets the default server timeout for the request.</span></span>
            </summary>
        <value><span data-ttu-id="81881-112">Ein <see cref="T:System.TimeSpan" /> mit dem servertimeoutintervall.</span><span class="sxs-lookup"><span data-stu-id="81881-112">A <see cref="T:System.TimeSpan" /> containing the server timeout interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>