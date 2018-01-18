<Type Name="RestoreRequestInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner">
  <TypeSignature Language="C#" Value="public class RestoreRequestInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreRequestInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreRequestInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RestoreRequestInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="16cce-101">Beschreibung der eine Anforderung zum Wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="16cce-101">Description of a restore request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequestInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="16cce-102">Initialisiert eine neue Instanz der RestoreRequestInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="16cce-102">Initializes a new instance of the RestoreRequestInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequestInner (string id = null, string name = null, string kind = null, string type = null, string storageAccountUrl = null, string blobName = null, Nullable&lt;bool&gt; overwrite = null, string siteName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null, Nullable&lt;bool&gt; ignoreDatabases = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; operationType = null, Nullable&lt;bool&gt; adjustConnectionStrings = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string storageAccountUrl, string blobName, valuetype System.Nullable`1&lt;bool&gt; overwrite, string siteName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames, valuetype System.Nullable`1&lt;bool&gt; ignoreDatabases, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; operationType, valuetype System.Nullable`1&lt;bool&gt; adjustConnectionStrings, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional overwrite As Nullable(Of Boolean) = null, Optional siteName As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null, Optional ignoreDatabases As Nullable(Of Boolean) = null, Optional operationType As Nullable(Of BackupRestoreOperationType) = null, Optional adjustConnectionStrings As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner : string * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner (id, name, kind, type, storageAccountUrl, blobName, overwrite, siteName, databases, ignoreConflictingHostNames, ignoreDatabases, operationType, adjustConnectionStrings, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreDatabases" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="operationType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt;" />
        <Parameter Name="adjustConnectionStrings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="storageAccountUrl">To be added.</param>
        <param name="blobName">To be added.</param>
        <param name="overwrite">To be added.</param>
        <param name="siteName">To be added.</param>
        <param name="databases">To be added.</param>
        <param name="ignoreConflictingHostNames">To be added.</param>
        <param name="ignoreDatabases">To be added.</param>
        <param name="operationType">To be added.</param>
        <param name="adjustConnectionStrings">To be added.</param>
        <param name="hostingEnvironment">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdjustConnectionStrings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdjustConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdjustConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.AdjustConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property AdjustConnectionStrings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdjustConnectionStrings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.AdjustConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adjustConnectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-103">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn SiteConfig.ConnectionStrings in neue app; festgelegt werden soll, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code &amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="16cce-103">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if SiteConfig.ConnectionStrings should be set in new app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-104">Ruft ab, oder legt ihn fest Name eines BLOB, das die Sicherung enthält.</span><span class="sxs-lookup"><span data-stu-id="16cce-104">Gets or sets name of a blob which contains the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-105">Ruft ab oder legt die Auflistung von Datenbanken, die wiederhergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="16cce-105">Gets or sets collection of databases which should be restored.</span></span> <span data-ttu-id="16cce-106">Diese Liste muss die Liste der Datenbanken, die in der Sicherung überein.</span><span class="sxs-lookup"><span data-stu-id="16cce-106">This list has to match the list of databases included in the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-107">Ruft ab, oder legt Sie Name des app Service-Umgebung, fest, wenn (nur erforderlich, wenn eine app auf einer App Service-Umgebung wiederhergestellt wird).</span><span class="sxs-lookup"><span data-stu-id="16cce-107">Gets or sets app Service Environment name, if needed (only when restoring an app to an App Service Environment).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-108">Ruft ab oder legt sie fest Änderungen eine Logik beim Wiederherstellen einer Apps mit benutzerdefinierten Domänen.</span><span class="sxs-lookup"><span data-stu-id="16cce-108">Gets or sets changes a logic when restoring an app with custom domains.</span></span> <span data-ttu-id="16cce-109">&amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; um benutzerdefinierte Domänen automatisch zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="16cce-109">&amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to remove custom domains automatically.</span></span> <span data-ttu-id="16cce-110">Wenn &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; benutzerdefinierte Domänen werden in der app-Objekt hinzugefügt, wenn wird wiederhergestellt, sondern, die möglicherweise kann aufgrund von Konflikten während des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="16cce-110">If &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;, custom domains are added to the app's object when it is being restored, but that might fail due to conflicts during the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreDatabases">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreDatabases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.IgnoreDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreDatabases As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreDatabases : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.IgnoreDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreDatabases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; OperationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationType As Nullable(Of BackupRestoreOperationType)" />
      <MemberSignature Language="F#" Value="member this.OperationType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupRestoreOperationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-111">Ruft ab oder legt ihn fest Vorgang.</span><span class="sxs-lookup"><span data-stu-id="16cce-111">Gets or sets operation type.</span></span> <span data-ttu-id="16cce-112">Folgende Werte sind möglich: "Default", "Klonen", "Verschieben"</span><span class="sxs-lookup"><span data-stu-id="16cce-112">Possible values include: 'Default', 'Clone', 'Relocation'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-113">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Ziel-app; der Restore-Vorgang überschrieben werden kann, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="16cce-113">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the restore operation can overwrite target app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="16cce-114">&amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; ist erforderlich, wenn Sie versuchen, über eine vorhandene app wiederherzustellen.</span><span class="sxs-lookup"><span data-stu-id="16cce-114">&amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; is needed if trying to restore over an existing app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-115">Ruft ab oder legt den Namen einer App fest.</span><span class="sxs-lookup"><span data-stu-id="16cce-115">Gets or sets name of an app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RestoreRequestInner.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16cce-116">Ruft ab oder legt die SAS-URL auf den Container fest.</span><span class="sxs-lookup"><span data-stu-id="16cce-116">Gets or sets SAS URL to the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>