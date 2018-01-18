<Type Name="TableInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.TableInner">
  <TypeSignature Language="C#" Value="public class TableInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner" />
  <TypeSignature Language="VB.NET" Value="Public Class TableInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type TableInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0ca13-101">Stellt eine Azure SQL-Datenbanktabelle dar.</span><span class="sxs-lookup"><span data-stu-id="0ca13-101">Represents an Azure SQL Database table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0ca13-102">Initialisiert eine neue Instanz der TableInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0ca13-102">Initializes a new instance of the TableInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt; tableType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt; columns = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; recommendedIndexes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt; tableType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt; columns, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; recommendedIndexes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TableType},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional tableType As Nullable(Of TableType) = null, Optional columns As IList(Of ColumnInner) = null, Optional recommendedIndexes As IList(Of RecommendedIndexInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.TableInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.TableInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.TableInner (location, id, name, type, tags, tableType, columns, recommendedIndexes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tableType" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt;" />
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt;" />
        <Parameter Name="recommendedIndexes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="tableType"><span data-ttu-id="0ca13-103">Der Typ der Azure SQL-Datenbanktabelle.</span><span class="sxs-lookup"><span data-stu-id="0ca13-103">The type of Azure SQL Database table.</span></span>
            <span data-ttu-id="0ca13-104">Folgende Werte sind möglich: "BaseTable", "Anzeigen"</span><span class="sxs-lookup"><span data-stu-id="0ca13-104">Possible values include: 'BaseTable', 'View'</span></span></param>
        <param name="columns"><span data-ttu-id="0ca13-105">Die Spalten aus dieser Tabelle.</span><span class="sxs-lookup"><span data-stu-id="0ca13-105">The columns from this table.</span></span></param>
        <param name="recommendedIndexes"><span data-ttu-id="0ca13-106">Die empfohlenen Indizes für diese Tabelle.</span><span class="sxs-lookup"><span data-stu-id="0ca13-106">The recommended indices for this table.</span></span></param>
        <summary>
            <span data-ttu-id="0ca13-107">Initialisiert eine neue Instanz der TableInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0ca13-107">Initializes a new instance of the TableInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt; Columns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.Columns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Columns As IList(Of ColumnInner)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ColumnInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ca13-108">Ruft die Spalten aus dieser Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="0ca13-108">Gets the columns from this table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndexes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; RecommendedIndexes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; RecommendedIndexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.RecommendedIndexes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndexes As IList(Of RecommendedIndexInner)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndexes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.RecommendedIndexes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendedIndexes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ca13-109">Ruft die empfohlenen Indizes für diese Tabelle.</span><span class="sxs-lookup"><span data-stu-id="0ca13-109">Gets the recommended indices for this table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt; TableType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt; TableType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.TableType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableType As Nullable(Of TableType)" />
      <MemberSignature Language="F#" Value="member this.TableType : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.TableInner.TableType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tableType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TableType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ca13-110">Ruft den Typ der Azure SQL-Datenbanktabelle.</span><span class="sxs-lookup"><span data-stu-id="0ca13-110">Gets the type of Azure SQL Database table.</span></span> <span data-ttu-id="0ca13-111">Folgende Werte sind möglich: "BaseTable", "Anzeigen"</span><span class="sxs-lookup"><span data-stu-id="0ca13-111">Possible values include: 'BaseTable', 'View'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>