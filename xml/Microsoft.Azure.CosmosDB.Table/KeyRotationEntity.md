<Type Name="KeyRotationEntity" FullName="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity">
  <TypeSignature Language="C#" Value="public class KeyRotationEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyRotationEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyRotationEntity" />
  <TypeSignature Language="F#" Value="type KeyRotationEntity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="195da-101">Eine Entität, die für die Schlüsselrotation verwendet</span><span class="sxs-lookup"><span data-stu-id="195da-101">An entity used for key rotation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="195da-102">Ruft ab oder legt das aktuelle ETag der Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-102">Gets or sets the entity's current ETag.</span></span>
            </summary>
        <value><span data-ttu-id="195da-103">Eine Zeichenfolge, die das ETag für die Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="195da-103">A string containing the ETag for the entity.</span></span></value>
        <remarks><span data-ttu-id="195da-104">Legen Sie diesen Wert auf "\*" auf eine Entität als Teil eines Updatevorgangs Blind zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="195da-104">Set this value to '\*' to blindly overwrite an entity as part of an update operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.EntityProperty this[string key] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.Azure.CosmosDB.Table.EntityProperty" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="195da-105">Eine Zeichenfolge, die mit dem Namen der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="195da-105">A string containing the name of the property.</span></span></param>
        <summary>
            <span data-ttu-id="195da-106">Ruft ab oder legt die Entitätseigenschaft erhält den Namen der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="195da-106">Gets or sets the entity's property, given the name of the property.</span></span>
            </summary>
        <value><span data-ttu-id="195da-107">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="195da-107">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="195da-108">Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-108">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="195da-109">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-109">A string containing the partition key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IReadOnlyDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="195da-110">Ruft die Eigenschaften in der Tabellenentität nach Eigenschaftsname indiziert ab.</span><span class="sxs-lookup"><span data-stu-id="195da-110">Gets the properties in the table entity, indexed by property name.</span></span>
            </summary>
        <value><span data-ttu-id="195da-111">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften der Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="195da-111">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="195da-112">Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-112">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="195da-113">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-113">A string containing the row key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="195da-114">Ruft ab oder legt den Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-114">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="195da-115">Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel für die Entität.</span><span class="sxs-lookup"><span data-stu-id="195da-115">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>