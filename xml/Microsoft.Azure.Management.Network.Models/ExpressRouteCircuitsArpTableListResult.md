<Type Name="ExpressRouteCircuitsArpTableListResult" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitsArpTableListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitsArpTableListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitsArpTableListResult" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsArpTableListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f8ce-101">Die Antwort für ListArpTable Verbindungen-API für Express Route zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-101">Response for ListArpTable associated with the Express Route Circuits API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsArpTableListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f8ce-102">Initialisiert eine neue Instanz der ExpressRouteCircuitsArpTableListResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-102">Initializes a new instance of the ExpressRouteCircuitsArpTableListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitsArpTableListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; value = null, string nextLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; value, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As IList(Of ExpressRouteCircuitArpTable) = null, Optional nextLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult (value, nextLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt;" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="8f8ce-103">Ruft die Liste der ARP-Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-103">Gets list of the ARP table.</span></span></param>
        <param name="nextLink"><span data-ttu-id="8f8ce-104">Die URL zum Abrufen des nächsten Satzes von Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-104">The URL to get the next set of results.</span></span></param>
        <summary>
            <span data-ttu-id="8f8ce-105">Initialisiert eine neue Instanz der ExpressRouteCircuitsArpTableListResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-105">Initializes a new instance of the ExpressRouteCircuitsArpTableListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f8ce-106">Ruft ab oder legt die URL zum Abrufen des nächsten Satzes von Ergebnissen.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-106">Gets or sets the URL to get the next set of results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of ExpressRouteCircuitArpTable)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitArpTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f8ce-107">Ruft die Liste der ARP-Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8f8ce-107">Gets list of the ARP table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>