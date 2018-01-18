<Type Name="SecurityRuleAssociations" FullName="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations">
  <TypeSignature Language="C#" Value="public class SecurityRuleAssociations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityRuleAssociations extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityRuleAssociations" />
  <TypeSignature Language="F#" Value="type SecurityRuleAssociations = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b3332-101">Alle Sicherheitsregeln der Netzwerkschnittstelle zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="b3332-101">All security rules associated with the network interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRuleAssociations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3332-102">Initialisiert eine neue Instanz der SecurityRuleAssociations-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b3332-102">Initializes a new instance of the SecurityRuleAssociations class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRuleAssociations (Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation networkInterfaceAssociation = null, Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation subnetAssociation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; defaultSecurityRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation networkInterfaceAssociation, class Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation subnetAssociation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; defaultSecurityRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; effectiveSecurityRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.#ctor(Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation,Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations : Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation * Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations (networkInterfaceAssociation, subnetAssociation, defaultSecurityRules, effectiveSecurityRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaceAssociation" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation" />
        <Parameter Name="subnetAssociation" Type="Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation" />
        <Parameter Name="defaultSecurityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;" />
        <Parameter Name="effectiveSecurityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaceAssociation">To be added.</param>
        <param name="subnetAssociation">To be added.</param>
        <param name="defaultSecurityRules"><span data-ttu-id="b3332-103">Die Auflistung von Standard-Sicherheitsregeln der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="b3332-103">Collection of default security rules of the network security group.</span></span></param>
        <param name="effectiveSecurityRules"><span data-ttu-id="b3332-104">Die Auflistung der effektiven Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="b3332-104">Collection of effective security rules.</span></span></param>
        <summary>
            <span data-ttu-id="b3332-105">Initialisiert eine neue Instanz der SecurityRuleAssociations-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b3332-105">Initializes a new instance of the SecurityRuleAssociations class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; DefaultSecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; DefaultSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.DefaultSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultSecurityRules As IList(Of SecurityRuleInner)" />
      <MemberSignature Language="F#" Value="member this.DefaultSecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.DefaultSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultSecurityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3332-106">Abrufen oder Festlegen der Auflistung von Standard-Sicherheitsregeln der Netzwerksicherheitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="b3332-106">Gets or sets collection of default security rules of the network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EffectiveSecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; EffectiveSecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.EffectiveSecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property EffectiveSecurityRules As IList(Of EffectiveNetworkSecurityRule)" />
      <MemberSignature Language="F#" Value="member this.EffectiveSecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.EffectiveSecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="effectiveSecurityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3332-107">Abrufen oder Festlegen der Auflistung der effektiven Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="b3332-107">Gets or sets collection of effective security rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceAssociation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation NetworkInterfaceAssociation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation NetworkInterfaceAssociation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.NetworkInterfaceAssociation" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceAssociation As NetworkInterfaceAssociation" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceAssociation : Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.NetworkInterfaceAssociation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaceAssociation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceAssociation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetAssociation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation SubnetAssociation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation SubnetAssociation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.SubnetAssociation" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetAssociation As SubnetAssociation" />
      <MemberSignature Language="F#" Value="member this.SubnetAssociation : Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleAssociations.SubnetAssociation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetAssociation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.SubnetAssociation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>