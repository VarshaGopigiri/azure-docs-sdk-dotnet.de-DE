<Type Name="StsUriElementCollection" FullName="Microsoft.ServiceBus.Configuration.StsUriElementCollection">
  <TypeSignature Language="C#" Value="public sealed class StsUriElementCollection : System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StsUriElementCollection extends System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.StsUriElementCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StsUriElementCollection&#xA;Inherits ConfigurationElementCollection" />
  <TypeSignature Language="F#" Value="type StsUriElementCollection = class&#xA;    inherit ConfigurationElementCollection" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElementCollection</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Configuration.ConfigurationCollection(typeof(Microsoft.ServiceBus.Configuration.StsUriElement), AddItemName="stsUri", CollectionType=System.Configuration.ConfigurationElementCollectionType.BasicMap)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="e0b9d-101">Stellt eine Auflistung der URI-Element für den Sicherheitstokendienst dar.</span><span class="sxs-lookup"><span data-stu-id="e0b9d-101">Represents a URI element collection for the Security Token Service.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StsUriElementCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.StsUriElementCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="e0b9d-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Configuration.StsUriElementCollection" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0b9d-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.StsUriElementCollection" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; Addresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; Addresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.StsUriElementCollection.Addresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Addresses As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.Addresses : seq&lt;Uri&gt;" Usage="Microsoft.ServiceBus.Configuration.StsUriElementCollection.Addresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="e0b9d-103">Ruft die Adressen des Elements in der Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="e0b9d-103">Gets the addresses of the element in the collection.</span></span></summary>
        <value><span data-ttu-id="e0b9d-104">Die Adressen des Elements in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="e0b9d-104">The addresses of the element in the collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewElement">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationElement CreateNewElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Configuration.ConfigurationElement CreateNewElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.StsUriElementCollection.CreateNewElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateNewElement () As ConfigurationElement" />
      <MemberSignature Language="F#" Value="override this.CreateNewElement : unit -&gt; System.Configuration.ConfigurationElement" Usage="stsUriElementCollection.CreateNewElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementName">
      <MemberSignature Language="C#" Value="protected override string ElementName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElementName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.StsUriElementCollection.ElementName" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property ElementName As String" />
      <MemberSignature Language="F#" Value="member this.ElementName : string" Usage="Microsoft.ServiceBus.Configuration.StsUriElementCollection.ElementName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetElementKey">
      <MemberSignature Language="C#" Value="protected override object GetElementKey (System.Configuration.ConfigurationElement element);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object GetElementKey(class System.Configuration.ConfigurationElement element) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.StsUriElementCollection.GetElementKey(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetElementKey (element As ConfigurationElement) As Object" />
      <MemberSignature Language="F#" Value="override this.GetElementKey : System.Configuration.ConfigurationElement -&gt; obj" Usage="stsUriElementCollection.GetElementKey element" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="element" Type="System.Configuration.ConfigurationElement" />
      </Parameters>
      <Docs>
        <param name="element">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsElementName">
      <MemberSignature Language="C#" Value="protected override bool IsElementName (string elementName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsElementName(string elementName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.StsUriElementCollection.IsElementName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsElementName (elementName As String) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsElementName : string -&gt; bool" Usage="stsUriElementCollection.IsElementName elementName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elementName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="elementName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>