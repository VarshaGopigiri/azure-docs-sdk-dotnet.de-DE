<Type Name="ExtensibleEnumConverter&lt;T&gt;" FullName="Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class ExtensibleEnumConverter&lt;T&gt; : Microsoft.Azure.Search.Serialization.ConverterBase where T : ExtensibleEnum&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExtensibleEnumConverter`1&lt;(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt;) T&gt; extends Microsoft.Azure.Search.Serialization.ConverterBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ExtensibleEnumConverter(Of T)&#xA;Inherits ConverterBase" />
  <TypeSignature Language="F#" Value="type ExtensibleEnumConverter&lt;'T (requires 'T :&gt; ExtensibleEnum&lt;'T&gt;)&gt; = class&#xA;    inherit ConverterBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Serialization.ConverterBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="a0ed7-101">Serialisiert und deserialisiert "extensible Enumerationen" in und aus JSON.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-101">Serializes and deserializes "extensible enums" to and from JSON.</span></span> <span data-ttu-id="a0ed7-102">Erweiterbare Enumerationen sind z. B. Enumerationen, dass sie bekannte Werte aufweisen, jedoch mit neuen Werten erweiterbar werden, und die Werte auf Zeichenfolgen und nicht ganze Zahlen basieren.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-102">Extensible enums are like enumerations in that they have well-known values, but they are extensible with new values and the values are based on strings instead of integers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExtensibleEnumConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a0ed7-103">Initialisiert eine neue Instanz der ExtensibleEnumConverter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-103">Initializes a new instance of the ExtensibleEnumConverter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExtensibleEnumConverter (string factoryMethodName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string factoryMethodName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (factoryMethodName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; : string -&gt; Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter&lt;'T (requires 'T :&gt; Microsoft.Azure.Search.Models.ExtensibleEnum&lt;'T&gt;)&gt; factoryMethodName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="factoryMethodName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="factoryMethodName">
            <span data-ttu-id="a0ed7-104">Der Name des eine öffentliche statische Methode, die eine Instanz des Typs T ein String-Wert erstellt werden soll; Standardwert ist "Erstellen".</span><span class="sxs-lookup"><span data-stu-id="a0ed7-104">The name of a public static method that creates an instance of type T given a string value; Default is "Create".</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0ed7-105">Initialisiert eine neue Instanz der ExtensibleEnumConverter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-105">Initializes a new instance of the ExtensibleEnumConverter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanConvert">
      <MemberSignature Language="C#" Value="public override bool CanConvert (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanConvert(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1.CanConvert(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanConvert (objectType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanConvert : Type -&gt; bool" Usage="extensibleEnumConverter.CanConvert objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType"><span data-ttu-id="a0ed7-106">Der Typ für den Test.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-106">The type to test against.</span></span></param>
        <summary>
            <span data-ttu-id="a0ed7-107">Gibt an, ob dieser Konverter kann Serialisieren oder Deserialisieren von Objekten des angegebenen Typs.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-107">Indicates whether this converter can serialize or deserialize objects of the given type.</span></span>
            </summary>
        <returns><span data-ttu-id="a0ed7-108">"true", wenn ObjectType von ExtensibleEnum, abgeleitet wird "false" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-108">true if objectType derives from ExtensibleEnum, false otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="extensibleEnumConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="objectType" Type="System.Type" />
        <Parameter Name="existingValue" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="a0ed7-109">Der JSON-Reader.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-109">The JSON reader.</span></span></param>
        <param name="objectType"><span data-ttu-id="a0ed7-110">Von dieser Methode ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-110">Ignored by this method.</span></span></param>
        <param name="existingValue"><span data-ttu-id="a0ed7-111">Von dieser Methode ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-111">Ignored by this method.</span></span></param>
        <param name="serializer"><span data-ttu-id="a0ed7-112">Von dieser Methode ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-112">Ignored by this method.</span></span></param>
        <summary>
            <span data-ttu-id="a0ed7-113">Deserialisiert eine Zeichenfolge in eine ExtensibleEnum an.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-113">Deserializes a string into an ExtensibleEnum.</span></span>
            </summary>
        <returns><span data-ttu-id="a0ed7-114">Eine Instanz des Typs T oder null, wenn die aktuelle JSON-Token ist null.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-114">An instance of type T, or null if the current JSON token is null.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="extensibleEnumConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="Newtonsoft.Json.JsonWriter" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="a0ed7-115">Der JSON-Writer.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-115">The JSON writer.</span></span></param>
        <param name="value"><span data-ttu-id="a0ed7-116">Der zu serialisierende Wert.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-116">The value to serialize.</span></span></param>
        <param name="serializer"><span data-ttu-id="a0ed7-117">Von dieser Methode ignoriert.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-117">Ignored by this method.</span></span></param>
        <summary>
            <span data-ttu-id="a0ed7-118">Serialisiert ein ExtensibleEnum in eine JSON-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="a0ed7-118">Serializes an ExtensibleEnum to a JSON string.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>