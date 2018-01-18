<Type Name="UpgradeRecommendedElasticPoolProperties" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties">
  <TypeSignature Language="C#" Value="public class UpgradeRecommendedElasticPoolProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpgradeRecommendedElasticPoolProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class UpgradeRecommendedElasticPoolProperties" />
  <TypeSignature Language="F#" Value="type UpgradeRecommendedElasticPoolProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="652a3-101">Stellt die Eigenschaften eines Azure SQL empfohlen elastische Pools aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-101">Represents the properties of a Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradeRecommendedElasticPoolProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="652a3-102">Initialisiert eine neue Instanz der UpgradeRecommendedElasticPoolProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="652a3-102">Initializes a new instance of the UpgradeRecommendedElasticPoolProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradeRecommendedElasticPoolProperties (string name, Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions edition, Nullable&lt;int&gt; dtu = null, Nullable&lt;int&gt; storageMb = null, Nullable&lt;int&gt; databaseDtuMin = null, Nullable&lt;int&gt; databaseDtuMax = null, System.Collections.Generic.IList&lt;string&gt; databaseCollection = null, Nullable&lt;bool&gt; includeAllDatabases = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions edition, valuetype System.Nullable`1&lt;int32&gt; dtu, valuetype System.Nullable`1&lt;int32&gt; storageMb, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMax, class System.Collections.Generic.IList`1&lt;string&gt; databaseCollection, valuetype System.Nullable`1&lt;bool&gt; includeAllDatabases) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.#ctor(System.String,Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, edition As TargetElasticPoolEditions, Optional dtu As Nullable(Of Integer) = null, Optional storageMb As Nullable(Of Integer) = null, Optional databaseDtuMin As Nullable(Of Integer) = null, Optional databaseDtuMax As Nullable(Of Integer) = null, Optional databaseCollection As IList(Of String) = null, Optional includeAllDatabases As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties : string * Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties (name, edition, dtu, storageMb, databaseDtuMin, databaseDtuMax, databaseCollection, includeAllDatabases)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="edition" Type="Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageMb" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMin" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMax" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseCollection" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="includeAllDatabases" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="652a3-103">Der Name des Azure SQL empfohlen elastischen Pools aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-103">The name of the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="edition"><span data-ttu-id="652a3-104">Die Zieledition für die Azure SQL empfohlen elastischen Pool aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="652a3-104">The target edition for the Azure SQL Recommended Elastic Pool being upgraded.</span></span> <span data-ttu-id="652a3-105">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="652a3-105">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="652a3-106">Die DTU-Garantie für die Azure SQL empfohlen elastischen Pool aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="652a3-106">The DTU guarantee for the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="storageMb"><span data-ttu-id="652a3-107">Die Speicherobergrenze in MB für den Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-107">The storage limit in MB for the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="652a3-108">Die DTU-Garantie für die Datenbank für den Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-108">The DTU guarantee for database for the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="652a3-109">Die DTU-Obergrenze für die Datenbank für den Azure SQL empfohlen elastischen Pool aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="652a3-109">The DTU cap for database for the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="databaseCollection"><span data-ttu-id="652a3-110">Die Liste der Datenbanknamen in der Azure SQL empfohlen elastischen Pool zu aktualisierenden zu versetzen.</span><span class="sxs-lookup"><span data-stu-id="652a3-110">The list of database names to be put in the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <param name="includeAllDatabases"><span data-ttu-id="652a3-111">Ruft ab oder legt fest, ob alle Datenbanken in der Azure SQL empfohlen elastischen Pool zu versetzen aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-111">Gets or sets whether all databases to be put in the Azure SQL Recommended Elastic Pool being upgraded.</span></span></param>
        <summary>
            <span data-ttu-id="652a3-112">Initialisiert eine neue Instanz der UpgradeRecommendedElasticPoolProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="652a3-112">Initializes a new instance of the UpgradeRecommendedElasticPoolProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseCollection">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DatabaseCollection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DatabaseCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseCollection" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseCollection As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DatabaseCollection : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DatabaseCollection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-113">Ruft ab oder legt die Liste der Datenbanknamen in der Azure SQL empfohlen elastischen Pool zu aktualisierenden zu versetzen.</span><span class="sxs-lookup"><span data-stu-id="652a3-113">Gets or sets the list of database names to be put in the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DatabaseDtuMax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-114">Ruft ab oder legt die DTU-Obergrenze für die Datenbank für den Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-114">Gets or sets the DTU cap for database for the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DatabaseDtuMin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-115">Ermittelt oder definiert die DTU-Garantie für die Datenbank für den Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-115">Gets or sets the DTU guarantee for database for the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-116">Ermittelt oder definiert die DTU-Garantie für die Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-116">Gets or sets the DTU guarantee for the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As TargetElasticPoolEditions" />
      <MemberSignature Language="F#" Value="member this.Edition : Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.TargetElasticPoolEditions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-117">Ermittelt oder definiert die Zieledition für die Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-117">Gets or sets the target edition for the Azure SQL Recommended Elastic Pool being upgraded.</span></span> <span data-ttu-id="652a3-118">Folgende Werte sind möglich: "Basic", "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="652a3-118">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeAllDatabases">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IncludeAllDatabases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IncludeAllDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.IncludeAllDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeAllDatabases As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IncludeAllDatabases : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.IncludeAllDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="IncludeAllDatabases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-119">Ruft ab oder legt fest, ob alle Datenbanken in der Azure SQL empfohlen elastischen Pool zu versetzen aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-119">Gets or sets whether all databases to be put in the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-120">Ruft ab oder legt den Namen des Azure SQL empfohlen elastischen Pools aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-120">Gets or sets the name of the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StorageMb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StorageMb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.StorageMb" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StorageMb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.StorageMb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="StorageMb")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="652a3-121">Ruft ab oder legt die Speicherobergrenze in MB für den Azure SQL empfohlen elastischen Pool aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="652a3-121">Gets or sets the storage limit in MB for the Azure SQL Recommended Elastic Pool being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeRecommendedElasticPoolProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="upgradeRecommendedElasticPoolProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="652a3-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="652a3-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="652a3-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="652a3-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>