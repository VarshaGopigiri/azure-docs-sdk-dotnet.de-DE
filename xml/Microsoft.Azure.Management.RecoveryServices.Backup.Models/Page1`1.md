<Type Name="Page1&lt;T&gt;" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class Page1&lt;T&gt; : Microsoft.Rest.Azure.IPage&lt;T&gt;, System.Collections.Generic.IEnumerable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Page1`1&lt;T&gt; extends System.Object implements class Microsoft.Rest.Azure.IPage`1&lt;!T&gt;, class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1`1" />
  <TypeSignature Language="VB.NET" Value="Public Class Page1(Of T)&#xA;Implements IEnumerable(Of T), IPage(Of T)" />
  <TypeSignature Language="F#" Value="type Page1&lt;'T&gt; = class&#xA;    interface IPage&lt;'T&gt;&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IPage&lt;T&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T"><span data-ttu-id="2c18e-101">Typ der Seite Inhalt Elemente</span><span class="sxs-lookup"><span data-stu-id="2c18e-101">Type of the page content items</span></span></typeparam>
    <summary>
            <span data-ttu-id="2c18e-102">Definiert eine Seite in Azure Antworten.</span><span class="sxs-lookup"><span data-stu-id="2c18e-102">Defines a page in Azure responses.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Page1 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;T&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!T&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'T&gt;" Usage="page1.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2c18e-103">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="2c18e-103">Returns an enumerator that iterates through the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="2c18e-104">Ein ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="2c18e-104">A an enumerator that can be used to iterate through the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextPageLink">
      <MemberSignature Language="C#" Value="public string NextPageLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextPageLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1`1.NextPageLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextPageLink As String" />
      <MemberSignature Language="F#" Value="member this.NextPageLink : string" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1&lt;'T&gt;.NextPageLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2c18e-105">Ruft den Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="2c18e-105">Gets the link to the next page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.Page1`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2c18e-106">Gibt einen Enumerator zurück, der die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="2c18e-106">Returns an enumerator that iterates through the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="2c18e-107">Ein ein Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="2c18e-107">A an enumerator that can be used to iterate through the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>