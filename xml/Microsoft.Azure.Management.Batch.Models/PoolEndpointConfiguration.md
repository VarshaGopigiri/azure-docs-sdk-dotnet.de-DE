<Type Name="PoolEndpointConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class PoolEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type PoolEndpointConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce73e-101">Die Endpunktkonfiguration für einen Pool.</span><span class="sxs-lookup"><span data-stu-id="ce73e-101">The endpoint configuration for a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce73e-102">Initialisiert eine neue Instanz der PoolEndpointConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce73e-102">Initializes a new instance of the PoolEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; inboundNatPools);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; inboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.InboundNatPool})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundNatPools As IList(Of InboundNatPool))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; -&gt; Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration inboundNatPools" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundNatPools"><span data-ttu-id="ce73e-103">Eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="ce73e-103">A list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span></param>
        <summary>
            <span data-ttu-id="ce73e-104">Initialisiert eine neue Instanz der PoolEndpointConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce73e-104">Initializes a new instance of the PoolEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce73e-105">Ruft ab oder legt eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="ce73e-105">Gets or sets a list of inbound NAT pools that can be used to address specific ports on an individual compute node externally.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ce73e-106">Die maximale Anzahl von eingehenden NAT-Pools pro Batch-Pool ist 5.</span><span class="sxs-lookup"><span data-stu-id="ce73e-106">The maximum number of inbound NAT pools per Batch pool is 5.</span></span> <span data-ttu-id="ce73e-107">Wenn die maximale Anzahl von eingehenden NAT-Pools überschritten, wird die Anforderung mit HTTP-Statuscode 400 schlägt fehl.</span><span class="sxs-lookup"><span data-stu-id="ce73e-107">If the maximum number of inbound NAT pools is exceeded the request fails with HTTP status code 400.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolEndpointConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce73e-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ce73e-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce73e-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ce73e-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>