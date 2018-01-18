<Type Name="DataLakeStoreAccount" FullName="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount">
  <TypeSignature Language="C#" Value="public class DataLakeStoreAccount : Microsoft.Azure.Management.DataLake.Store.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreAccount extends Microsoft.Azure.Management.DataLake.Store.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d8600-101">Data Lake-Speicher-Kontoinformationen</span><span class="sxs-lookup"><span data-stu-id="d8600-101">Data Lake Store account information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d8600-102">Initialisiert eine neue Instanz der DataLakeStoreAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d8600-102">Initializes a new instance of the DataLakeStoreAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreAccount (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity identity = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; encryptionState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; encryptionProvisioningState = null, Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig encryptionConfig = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; firewallRules = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; trustedIdProviders = null, string defaultGroup = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; currentTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity identity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; encryptionState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; encryptionProvisioningState, class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig encryptionConfig, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; firewallState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; firewallRules, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; trustedIdProviderState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; trustedIdProviders, string defaultGroup, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; currentTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState},Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider},System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; * Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount (location, id, name, type, tags, identity, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId, encryptionState, encryptionProvisioningState, encryptionConfig, firewallState, firewallRules, trustedIdProviderState, trustedIdProviders, defaultGroup, newTier, currentTier, firewallAllowAzureIps)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="encryptionState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt;" />
        <Parameter Name="encryptionProvisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;" />
        <Parameter Name="encryptionConfig" Type="Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt;" />
        <Parameter Name="firewallRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;" />
        <Parameter Name="trustedIdProviderState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt;" />
        <Parameter Name="trustedIdProviders" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;" />
        <Parameter Name="defaultGroup" Type="System.String" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" />
        <Parameter Name="currentTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="d8600-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="d8600-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="d8600-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="d8600-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="d8600-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="d8600-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="d8600-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="d8600-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="d8600-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="d8600-107">Resource tags</span></span></param>
        <param name="identity"><span data-ttu-id="d8600-108">Die Key Vault Verschlüsselung Identität, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="d8600-108">The Key Vault encryption identity, if any.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="d8600-109">Der Bereitstellungsstatus des Data Lake-Speicher an.</span><span class="sxs-lookup"><span data-stu-id="d8600-109">the provisioning status of the Data Lake Store account.</span></span> <span data-ttu-id="d8600-110">Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="d8600-110">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span></param>
        <param name="state"><span data-ttu-id="d8600-111">der Status des Data Lake-Speicher an.</span><span class="sxs-lookup"><span data-stu-id="d8600-111">the state of the Data Lake Store account.</span></span>
            <span data-ttu-id="d8600-112">Folgende Werte sind möglich: "Aktiv", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="d8600-112">Possible values include: 'Active', 'Suspended'</span></span></param>
        <param name="creationTime"><span data-ttu-id="d8600-113">die Erstellungszeit des Kontos.</span><span class="sxs-lookup"><span data-stu-id="d8600-113">the account creation time.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="d8600-114">Zeitpunkt der letzten Änderung des Kontos.</span><span class="sxs-lookup"><span data-stu-id="d8600-114">the account last modified time.</span></span></param>
        <param name="endpoint"><span data-ttu-id="d8600-115">der vollständige CName-Endpunkt für dieses Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-115">the full CName endpoint for this account.</span></span></param>
        <param name="accountId"><span data-ttu-id="d8600-116">Der eindeutige Bezeichner, der diesen Data Lake-Speicher-Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d8600-116">The unique identifier associated with this Data Lake Store account.</span></span></param>
        <param name="encryptionState"><span data-ttu-id="d8600-117">Speichern Sie der aktuelle Status der Verschlüsselung für diese Data Lake Konto aus.</span><span class="sxs-lookup"><span data-stu-id="d8600-117">The current state of encryption for this Data Lake store account.</span></span> <span data-ttu-id="d8600-118">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-118">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="encryptionProvisioningState"><span data-ttu-id="d8600-119">Der aktuelle Status der Verschlüsselung für diese Data Lake-Speicher-Konto bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="d8600-119">The current state of encryption provisioning for this Data Lake store account.</span></span> <span data-ttu-id="d8600-120">Folgende Werte sind möglich: "Erstellen", "erfolgreich"</span><span class="sxs-lookup"><span data-stu-id="d8600-120">Possible values include: 'Creating', 'Succeeded'</span></span></param>
        <param name="encryptionConfig"><span data-ttu-id="d8600-121">Die Konfiguration des Key Vault-Verschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="d8600-121">The Key Vault encryption configuration.</span></span></param>
        <param name="firewallState"><span data-ttu-id="d8600-122">Speichern Sie der aktuelle Status der Firewall IP-Adresse für diesen Data Lake Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-122">The current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="d8600-123">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-123">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallRules"><span data-ttu-id="d8600-124">Die Liste der Firewallregeln, die mit diesem Data Lake-Speicher-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="d8600-124">The list of firewall rules associated with this Data Lake store account.</span></span></param>
        <param name="trustedIdProviderState"><span data-ttu-id="d8600-125">Der aktuelle Status der Funktion für die vertrauenswürdige Anbieter für diesen Data Lake speichern Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-125">The current state of the trusted identity provider feature for this Data Lake store account.</span></span>
            <span data-ttu-id="d8600-126">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-126">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="trustedIdProviders"><span data-ttu-id="d8600-127">Die Liste der vertrauenswürdigen Identitätsanbieter, die mit diesem Data Lake-Speicher-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="d8600-127">The list of trusted identity providers associated with this Data Lake store account.</span></span></param>
        <param name="defaultGroup"><span data-ttu-id="d8600-128">die Standardgruppe des Besitzers für alle neuen Ordnern und Dateien in das Data Lake-Speicher-Konto erstellt.</span><span class="sxs-lookup"><span data-stu-id="d8600-128">the default owner group for all new folders and files created in the Data Lake Store account.</span></span></param>
        <param name="newTier"><span data-ttu-id="d8600-129">die Verpflichtung-Ebene für den nächsten Monat verwenden.</span><span class="sxs-lookup"><span data-stu-id="d8600-129">the commitment tier to use for next month.</span></span>
            <span data-ttu-id="d8600-130">Folgende Werte sind möglich: "Nutzung", "Commitment_1TB", "Commitment_10TB", "Commitment_100TB", "Commitment_500TB", "Commitment_1PB", "Commitment_5PB"</span><span class="sxs-lookup"><span data-stu-id="d8600-130">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span></param>
        <param name="currentTier"><span data-ttu-id="d8600-131">verwendet für den aktuellen Monat Verpflichtung-Ebene.</span><span class="sxs-lookup"><span data-stu-id="d8600-131">the commitment tier in use for the current month.</span></span> <span data-ttu-id="d8600-132">Folgende Werte sind möglich: "Nutzung", "Commitment_1TB", "Commitment_10TB", "Commitment_100TB", "Commitment_500TB", "Commitment_1PB", "Commitment_5PB"</span><span class="sxs-lookup"><span data-stu-id="d8600-132">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span></param>
        <param name="firewallAllowAzureIps"><span data-ttu-id="d8600-133">Der aktuelle Status des zulassen oder untersagen von IP-Adressen, die in Azure über die Firewall stammen.</span><span class="sxs-lookup"><span data-stu-id="d8600-133">The current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span>
            <span data-ttu-id="d8600-134">Wenn die Firewall deaktiviert ist, ist dies nicht erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d8600-134">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="d8600-135">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-135">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="d8600-136">Initialisiert eine neue Instanz der DataLakeStoreAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d8600-136">Initializes a new instance of the DataLakeStoreAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-137">Ruft den eindeutigen Bezeichner dieses Data Lake-Speicher-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d8600-137">Gets the unique identifier associated with this Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-138">Ruft die Erstellungszeit des Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="d8600-138">Gets the account creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; CurrentTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; CurrentTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CurrentTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.CurrentTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.CurrentTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-139">Ruft die Verpflichtung-Ebene verwendet für den aktuellen Monat an.</span><span class="sxs-lookup"><span data-stu-id="d8600-139">Gets the commitment tier in use for the current month.</span></span> <span data-ttu-id="d8600-140">Folgende Werte sind möglich: "Nutzung", "Commitment_1TB", "Commitment_10TB", "Commitment_100TB", "Commitment_500TB", "Commitment_1PB", "Commitment_5PB"</span><span class="sxs-lookup"><span data-stu-id="d8600-140">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultGroup">
      <MemberSignature Language="C#" Value="public string DefaultGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.DefaultGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultGroup As String" />
      <MemberSignature Language="F#" Value="member this.DefaultGroup : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.DefaultGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-141">Ruft ab oder legt die Standardgruppe des Besitzers für alle neuen Ordnern und Dateien in das Data Lake-Speicher-Konto erstellt.</span><span class="sxs-lookup"><span data-stu-id="d8600-141">Gets or sets the default owner group for all new folders and files created in the Data Lake Store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig EncryptionConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig EncryptionConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionConfig As EncryptionConfig" />
      <MemberSignature Language="F#" Value="member this.EncryptionConfig : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-142">Ruft ab oder legt die Verschlüsselungskonfiguration Key Vault.</span><span class="sxs-lookup"><span data-stu-id="d8600-142">Gets or sets the Key Vault encryption configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; EncryptionProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt; EncryptionProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionProvisioningState As Nullable(Of EncryptionProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.EncryptionProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-143">Ruft den aktuellen Status der Verschlüsselung für diese Data Lake-Speicher-Konto bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="d8600-143">Gets the current state of encryption provisioning for this Data Lake store account.</span></span> <span data-ttu-id="d8600-144">Folgende Werte sind möglich: "Erstellen", "erfolgreich"</span><span class="sxs-lookup"><span data-stu-id="d8600-144">Possible values include: 'Creating', 'Succeeded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; EncryptionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; EncryptionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionState" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionState As Nullable(Of EncryptionState)" />
      <MemberSignature Language="F#" Value="member this.EncryptionState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.EncryptionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.EncryptionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-145">Ruft ab oder legt den aktuellen Status der Verschlüsselung für diese Data Lake-Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-145">Gets or sets the current state of encryption for this Data Lake store account.</span></span> <span data-ttu-id="d8600-146">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-146">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-147">Ruft den vollständigen CName-Endpunkt für dieses Konto an.</span><span class="sxs-lookup"><span data-stu-id="d8600-147">Gets the full CName endpoint for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallAllowAzureIps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallAllowAzureIps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallAllowAzureIpsState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-148">Ruft ab oder legt den aktuellen Zustand des zulassen oder untersagen von IP-Adressen, die in Azure über die Firewall stammen.</span><span class="sxs-lookup"><span data-stu-id="d8600-148">Gets or sets the current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span> <span data-ttu-id="d8600-149">Wenn die Firewall deaktiviert ist, ist dies nicht erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d8600-149">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="d8600-150">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-150">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; FirewallRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallRules As IList(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-151">Ruft ab oder legt die Liste der Firewallregeln, die mit diesem Data Lake-Speicher-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="d8600-151">Gets or sets the list of firewall rules associated with this Data Lake store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.FirewallState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.FirewallState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-152">Ruft ab oder legt den aktuellen Status der Firewall IP-Adresse für diesen Data Lake-Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-152">Gets or sets the current state of the IP address firewall for this Data Lake store account.</span></span> <span data-ttu-id="d8600-153">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-153">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As EncryptionIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.Models.EncryptionIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-154">Ruft ab oder legt die Identität des Key Vault-Verschlüsselung, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="d8600-154">Gets or sets the Key Vault encryption identity, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-155">Ruft die Uhrzeit der letzten Änderung des Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="d8600-155">Gets the account last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.NewTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.newTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-156">Ermittelt oder definiert die Verpflichtung-Ebene für den nächsten Monat verwenden.</span><span class="sxs-lookup"><span data-stu-id="d8600-156">Gets or sets the commitment tier to use for next month.</span></span> <span data-ttu-id="d8600-157">Folgende Werte sind möglich: "Nutzung", "Commitment_1TB", "Commitment_10TB", "Commitment_100TB", "Commitment_500TB", "Commitment_1PB", "Commitment_5PB"</span><span class="sxs-lookup"><span data-stu-id="d8600-157">Possible values include: 'Consumption', 'Commitment_1TB', 'Commitment_10TB', 'Commitment_100TB', 'Commitment_500TB', 'Commitment_1PB', 'Commitment_5PB'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeStoreAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-158">Ruft den Bereitstellungsstatus des Data Lake-Speicher-Kontos an.</span><span class="sxs-lookup"><span data-stu-id="d8600-158">Gets the provisioning status of the Data Lake Store account.</span></span>
            <span data-ttu-id="d8600-159">Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="d8600-159">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeStoreAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-160">Ruft den Status des Kontos Data Lake-Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="d8600-160">Gets the state of the Data Lake Store account.</span></span> <span data-ttu-id="d8600-161">Folgende Werte sind möglich: "Aktiv", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="d8600-161">Possible values include: 'Active', 'Suspended'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedIdProviders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; TrustedIdProviders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; TrustedIdProviders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviders" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedIdProviders As IList(Of TrustedIdProvider)" />
      <MemberSignature Language="F#" Value="member this.TrustedIdProviders : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trustedIdProviders")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-162">Ruft ab oder legt die Liste der vertrauenswürdigen Identitätsanbieter, die mit diesem Data Lake-Speicher-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="d8600-162">Gets or sets the list of trusted identity providers associated with this Data Lake store account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrustedIdProviderState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; TrustedIdProviderState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviderState" />
      <MemberSignature Language="VB.NET" Value="Public Property TrustedIdProviderState As Nullable(Of TrustedIdProviderState)" />
      <MemberSignature Language="F#" Value="member this.TrustedIdProviderState : Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.TrustedIdProviderState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trustedIdProviderState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProviderState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8600-163">Ruft ab oder legt den aktuellen Zustand des Funktion für die vertrauenswürdige Anbieter für diesen Data Lake-Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="d8600-163">Gets or sets the current state of the trusted identity provider feature for this Data Lake store account.</span></span> <span data-ttu-id="d8600-164">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="d8600-164">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.DataLakeStoreAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeStoreAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d8600-165">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="d8600-165">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8600-166">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="d8600-166">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>