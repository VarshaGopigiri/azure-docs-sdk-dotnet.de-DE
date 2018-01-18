<Type Name="FailoverGroupUpdate" FullName="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate">
  <TypeSignature Language="C#" Value="public class FailoverGroupUpdate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FailoverGroupUpdate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class FailoverGroupUpdate" />
  <TypeSignature Language="F#" Value="type FailoverGroupUpdate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2aa3b-101">Eine Failover-Gruppe eine updateanforderung.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-101">A failover group update request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-102">Initialisiert eine neue Instanz der FailoverGroupUpdate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-102">Initializes a new instance of the FailoverGroupUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FailoverGroupUpdate (Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint = null, Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint = null, System.Collections.Generic.IList&lt;string&gt; databases = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint readWriteEndpoint, class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint readOnlyEndpoint, class System.Collections.Generic.IList`1&lt;string&gt; databases, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.#ctor(Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint,Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint,System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional readWriteEndpoint As FailoverGroupReadWriteEndpoint = null, Optional readOnlyEndpoint As FailoverGroupReadOnlyEndpoint = null, Optional databases As IList(Of String) = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint * Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate (readWriteEndpoint, readOnlyEndpoint, databases, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="readWriteEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint" />
        <Parameter Name="readOnlyEndpoint" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="readWriteEndpoint"><span data-ttu-id="2aa3b-103">Lese-/ Schreibzugriff Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-103">Read-write endpoint of the failover group instance.</span></span></param>
        <param name="readOnlyEndpoint"><span data-ttu-id="2aa3b-104">Nur-Lese Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-104">Read-only endpoint of the failover group instance.</span></span></param>
        <param name="databases"><span data-ttu-id="2aa3b-105">Die Liste der Datenbanken in der Gruppe "Failover".</span><span class="sxs-lookup"><span data-stu-id="2aa3b-105">List of databases in the failover group.</span></span></param>
        <param name="tags"><span data-ttu-id="2aa3b-106">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-106">Resource tags.</span></span></param>
        <summary>
            <span data-ttu-id="2aa3b-107">Initialisiert eine neue Instanz der FailoverGroupUpdate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-107">Initializes a new instance of the FailoverGroupUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-108">Ruft ab oder legt die Liste der Datenbanken in der Gruppe "Failover" fest.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-108">Gets or sets list of databases in the failover group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOnlyEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint ReadOnlyEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.ReadOnlyEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadOnlyEndpoint As FailoverGroupReadOnlyEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadOnlyEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.ReadOnlyEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readOnlyEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadOnlyEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-109">Ruft ab, oder legt ihn fest-nur-Lese-Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-109">Gets or sets read-only endpoint of the failover group instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadWriteEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint ReadWriteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.ReadWriteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadWriteEndpoint As FailoverGroupReadWriteEndpoint" />
      <MemberSignature Language="F#" Value="member this.ReadWriteEndpoint : Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.ReadWriteEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readWriteEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.FailoverGroupReadWriteEndpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-110">Abrufen oder Festlegen von Lese-/ Schreibzugriff-Endpunkt der Gruppeninstanz Failover.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-110">Gets or sets read-write endpoint of the failover group instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-111">Ermittelt oder Ressourcen-Tags definiert.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-111">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="failoverGroupUpdate.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2aa3b-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2aa3b-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2aa3b-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2aa3b-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>