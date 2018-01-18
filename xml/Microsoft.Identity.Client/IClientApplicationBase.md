<Type Name="IClientApplicationBase" FullName="Microsoft.Identity.Client.IClientApplicationBase">
  <TypeSignature Language="C#" Value="public interface IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IClientApplicationBase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cdf4d-101">Enthält allgemeine Validierungsmethoden</span><span class="sxs-lookup"><span data-stu-id="cdf4d-101">Component containing common validation methods</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="cdf4d-102">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="cdf4d-102">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="cdf4d-103">Benutzer, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-103">User for which the token is requested.</span></span> <see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <summary>
            <span data-ttu-id="cdf4d-104">Versucht, das Zugriffstoken aus dem Cache abzurufen.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-104">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="cdf4d-105">Zugriffstoken wird als Übereinstimmung betrachtet, wenn er mindestens der angeforderten Bereiche enthält.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-105">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="cdf4d-106">Dies bedeutet, dass ein Zugriffstoken mit mehr Gültigkeitsbereiche als angeforderten ebenfalls zurückgegeben werden konnte.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-106">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="cdf4d-107">Wenn das Zugriffstoken abgelaufen ist oder bald abläuft (innerhalb von 5-Minuten-Fenster), wird Aktualisierungstoken (falls verfügbar), ein neues Zugriffstoken abzurufen, durch einen Netzwerkaufruf verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-107">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes"><span data-ttu-id="cdf4d-108">Array von Bereichen, die für die Ressource angefordert</span><span class="sxs-lookup"><span data-stu-id="cdf4d-108">Array of scopes requested for resource</span></span></param>
        <param name="user"><span data-ttu-id="cdf4d-109">Benutzer, die für die das Token angefordert wird<see cref="T:Microsoft.Identity.Client.IUser" /></span><span class="sxs-lookup"><span data-stu-id="cdf4d-109">User for which the token is requested <see cref="T:Microsoft.Identity.Client.IUser" /></span></span></param>
        <param name="authority"><span data-ttu-id="cdf4d-110">Spezifische Stelle, die für die das Token angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-110">Specific authority for which the token is requested.</span></span> <span data-ttu-id="cdf4d-111">Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</span><span class="sxs-lookup"><span data-stu-id="cdf4d-111">Passing a different value than configured does not change the configured value</span></span></param>
        <param name="forceRefresh"><span data-ttu-id="cdf4d-112">Bei "true", API ignoriert das Zugriffstoken im Cache und versuchen zum Abrufen neuer Zugriffstokens mithilfe des aktualisierungstokens, falls verfügbar</span><span class="sxs-lookup"><span data-stu-id="cdf4d-112">If TRUE, API will ignore the access token in the cache and attempt to acquire new access token using the refresh token if available</span></span></param>
        <summary>
            <span data-ttu-id="cdf4d-113">Versucht, das Zugriffstoken aus dem Cache abzurufen.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-113">Attempts to acquire the access token from cache.</span></span> <span data-ttu-id="cdf4d-114">Zugriffstoken wird als Übereinstimmung betrachtet, wenn er mindestens der angeforderten Bereiche enthält.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-114">Access token is considered a match if it AT LEAST contains all the requested scopes.</span></span>
            <span data-ttu-id="cdf4d-115">Dies bedeutet, dass ein Zugriffstoken mit mehr Gültigkeitsbereiche als angeforderten ebenfalls zurückgegeben werden konnte.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-115">This means that an access token with more scopes than requested could be returned as well.</span></span> <span data-ttu-id="cdf4d-116">Wenn das Zugriffstoken abgelaufen ist oder bald abläuft (innerhalb von 5-Minuten-Fenster), wird Aktualisierungstoken (falls verfügbar), ein neues Zugriffstoken abzurufen, durch einen Netzwerkaufruf verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-116">If access token is expired or close to expiration (within 5 minute window), then refresh token (if available) is used to acquire a new access token by making a network call.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <Summary>
            <span data-ttu-id="cdf4d-117">Autorität für die bereitgestellten, durch die Entwickler oder Default-Behörde, die von der Bibliothek verwendet.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-117">Authority provided by the developer or default authority used by the library.</span></span>
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdf4d-118">Ein Standardwert wird festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-118">Will be a default value.</span></span> <span data-ttu-id="cdf4d-119">Kann vom Entwickler überschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-119">Can be overridden by the developer.</span></span> <span data-ttu-id="cdf4d-120">Einmal festgelegt, wird Anwendung an den Client-ID gebunden.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-120">Once set, application will bind to the client Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdf4d-121">Bezeichner der Komponente verbrauchte MSAL und es dient für Bibliotheken-SDKs, die MSAL nutzen.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-121">Identifier of the component consuming MSAL and it is intended for libraries/SDKs that consume MSAL.</span></span> <span data-ttu-id="cdf4d-122">Dadurch können für Mehrdeutigkeit zwischen MSAL-Nutzung durch die app Vs MSAL Verwendung von Komponentenbibliotheken.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-122">This will allow for disambiguation between MSAL usage by the app vs MSAL usage by component libraries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="iClientApplicationBase.GetUser identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.IUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="cdf4d-123">Benutzer-ID</span><span class="sxs-lookup"><span data-stu-id="cdf4d-123">user identifier</span></span></param>
        <summary>
            <span data-ttu-id="cdf4d-124">Benutzer von Bezeichner von Benutzern verfügbar im Cache abrufen.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-124">Get user by identifier from users available in the cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectUri">
      <MemberSignature Language="C#" Value="public string RedirectUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdf4d-125">Umleitungs-Uri im Portal konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-125">Redirect Uri configured in the portal.</span></span> <span data-ttu-id="cdf4d-126">Sie müssen einen Standardwert.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-126">Will have a default value.</span></span> <span data-ttu-id="cdf4d-127">Nicht erforderlich, wenn der Entwickler den Standardclient-ID verwendet wird</span><span class="sxs-lookup"><span data-stu-id="cdf4d-127">Not required if the developer is using the default client Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="iClientApplicationBase.Remove user" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="user"><span data-ttu-id="cdf4d-128">Instanz des Benutzers, der entfernt werden muss</span><span class="sxs-lookup"><span data-stu-id="cdf4d-128">instance of the user that needs to be removed</span></span></param>
        <summary>
            <span data-ttu-id="cdf4d-129">Entfernt alle zwischengespeicherte Token für den angegebenen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-129">Removes all cached tokens for the specified user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceParameters">
      <MemberSignature Language="C#" Value="public string SliceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdf4d-130">Legt fest oder ruft die benutzerdefinierten Abfrageparameter, die an den STS zu Testzwecken Dogfood gesendet werden können.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-130">Sets or Gets the custom query parameters that may be sent to the STS for dogfood testing.</span></span> <span data-ttu-id="cdf4d-131">Dieser Parameter sollte nicht vom Entwickler festgelegt werden, da es negative Auswirkungen auf die Anwendung möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-131">This parameter should not be set by the developers as it may have adverse effect on the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Identity.Client.IUser&gt; Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.IClientApplicationBase.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdf4d-132">Gibt eine benutzerzentrierte Ansicht über den Cache, der eine Liste aller verfügbaren Benutzer im Cache bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-132">Returns a user-centric view over the cache that provides a list of all the available users in the cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
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
            <span data-ttu-id="cdf4d-133">Ruft ab einen Wert, der angibt, ob die Adressüberprüfung auf ON festgelegt ist, oder deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="cdf4d-133">Gets a value indicating whether address validation is ON or OFF.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>