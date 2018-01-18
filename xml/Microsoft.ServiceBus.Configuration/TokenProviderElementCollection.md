<Type Name="TokenProviderElementCollection" FullName="Microsoft.ServiceBus.Configuration.TokenProviderElementCollection">
  <TypeSignature Language="C#" Value="public sealed class TokenProviderElementCollection : System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenProviderElementCollection extends System.Configuration.ConfigurationElementCollection" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TokenProviderElementCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenProviderElementCollection&#xA;Inherits ConfigurationElementCollection" />
  <TypeSignature Language="F#" Value="type TokenProviderElementCollection = class&#xA;    inherit ConfigurationElementCollection" />
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
      <AttributeName>System.Configuration.ConfigurationCollection(typeof(Microsoft.ServiceBus.Configuration.TokenProviderElement), CollectionType=System.Configuration.ConfigurationElementCollectionType.AddRemoveClearMap)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="83968-101">Stellt eine Auflistung von Elementen für den Anbieter von Sicherheitstoken dar.</span><span class="sxs-lookup"><span data-stu-id="83968-101">Represents a collection of elements for the token provider.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenProviderElementCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TokenProviderElementCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewElement">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationElement CreateNewElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Configuration.ConfigurationElement CreateNewElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TokenProviderElementCollection.CreateNewElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateNewElement () As ConfigurationElement" />
      <MemberSignature Language="F#" Value="override this.CreateNewElement : unit -&gt; System.Configuration.ConfigurationElement" Usage="tokenProviderElementCollection.CreateNewElement " />
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
    <Member MemberName="GetElementKey">
      <MemberSignature Language="C#" Value="protected override object GetElementKey (System.Configuration.ConfigurationElement element);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance object GetElementKey(class System.Configuration.ConfigurationElement element) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TokenProviderElementCollection.GetElementKey(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetElementKey (element As ConfigurationElement) As Object" />
      <MemberSignature Language="F#" Value="override this.GetElementKey : System.Configuration.ConfigurationElement -&gt; obj" Usage="tokenProviderElementCollection.GetElementKey element" />
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
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.TokenProviderElement this[string name] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.TokenProviderElement Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TokenProviderElementCollection.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(name As String) As TokenProviderElement" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.ServiceBus.Configuration.TokenProviderElement" Usage="Microsoft.ServiceBus.Configuration.TokenProviderElementCollection.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.TokenProviderElement</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="83968-102">Name des Elements.</span><span class="sxs-lookup"><span data-stu-id="83968-102">The name of the item.</span></span></param>
        <summary><span data-ttu-id="83968-103">Ruft ein Element in der Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="83968-103">Gets an item in the collection.</span></span></summary>
        <value><span data-ttu-id="83968-104">Ein Element in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="83968-104">An item in the collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>