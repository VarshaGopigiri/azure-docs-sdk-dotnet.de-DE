<Type Name="SyncGroupSchemaTable" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable">
  <TypeSignature Language="C#" Value="public class SyncGroupSchemaTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupSchemaTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupSchemaTable" />
  <TypeSignature Language="F#" Value="type SyncGroupSchemaTable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e7902-101">Eigenschaften der Tabelle im synchronisierungsgruppenschema.</span><span class="sxs-lookup"><span data-stu-id="e7902-101">Properties of table in sync group schema.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e7902-102">Initialisiert eine neue Instanz der SyncGroupSchemaTable-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e7902-102">Initializes a new instance of the SyncGroupSchemaTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTable (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; columns = null, string quotedName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; columns, string quotedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional columns As IList(Of SyncGroupSchemaTableColumn) = null, Optional quotedName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable (columns, quotedName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt;" />
        <Parameter Name="quotedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="columns"><span data-ttu-id="e7902-103">Die Liste der Spalten im synchronisierungsgruppenschema.</span><span class="sxs-lookup"><span data-stu-id="e7902-103">List of columns in sync group schema.</span></span></param>
        <param name="quotedName"><span data-ttu-id="e7902-104">In Namen von Sync Gruppe Schematabelle Anführungszeichen.</span><span class="sxs-lookup"><span data-stu-id="e7902-104">Quoted name of sync group schema table.</span></span></param>
        <summary>
            <span data-ttu-id="e7902-105">Initialisiert eine neue Instanz der SyncGroupSchemaTable-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e7902-105">Initializes a new instance of the SyncGroupSchemaTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; Columns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.Columns" />
      <MemberSignature Language="VB.NET" Value="Public Property Columns As IList(Of SyncGroupSchemaTableColumn)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7902-106">Ruft ab oder legt die Liste der Spalten im synchronisierungsgruppenschema fest.</span><span class="sxs-lookup"><span data-stu-id="e7902-106">Gets or sets list of columns in sync group schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable.QuotedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7902-107">Ruft ab oder legt in Anführungszeichen Namen des Sync-Gruppe Schematabelle.</span><span class="sxs-lookup"><span data-stu-id="e7902-107">Gets or sets quoted name of sync group schema table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>