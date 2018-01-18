<Type Name="ResourceUsage" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage">
  <TypeSignature Language="C#" Value="public class ResourceUsage : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceUsage extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceUsage&#xA;Inherits Wrapper(Of ResourceUsageInner)" />
  <TypeSignature Language="F#" Value="type ResourceUsage = class&#xA;    inherit Wrapper&lt;ResourceUsageInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="58e2e-101">Die Ausgabe von Check-Ressourcenverwendung API.</span><span class="sxs-lookup"><span data-stu-id="58e2e-101">Output of check resource usage API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceUsage (Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.#ctor(Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inner As ResourceUsageInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage : Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage inner" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner" />
      </Parameters>
      <Docs>
        <param name="inner">To be added.</param>
        <summary>
            <span data-ttu-id="58e2e-102">Initialisiert eine neue Instanz der Klasse ResourceUsage.</span><span class="sxs-lookup"><span data-stu-id="58e2e-102">Initializes a new instance of the ResourceUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public int CurrentValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentValue As Integer" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58e2e-103">Ruft ab, oder legt ihn fest Istwert des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="58e2e-103">Gets or sets actual value of the resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public int Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Integer" />
      <MemberSignature Language="F#" Value="member this.Limit : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58e2e-104">Ruft ab, oder legt ihn fest Kontingent des Ressourcentyps.</span><span class="sxs-lookup"><span data-stu-id="58e2e-104">Gets or sets quota of the resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58e2e-105">Ruft ab, oder legt ihn fest Ressourcentyp der Verwendungen.</span><span class="sxs-lookup"><span data-stu-id="58e2e-105">Gets or sets resource type of the usages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58e2e-106">Ruft ab, oder legt ihn fest Einheit der Verwendung.</span><span class="sxs-lookup"><span data-stu-id="58e2e-106">Gets or sets unit of the usage.</span></span> <span data-ttu-id="58e2e-107">z. B. die Anzahl der.</span><span class="sxs-lookup"><span data-stu-id="58e2e-107">e.g. Count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>