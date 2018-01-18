<Type Name="FabricImageStoreException" FullName="System.Fabric.FabricImageStoreException">
  <TypeSignature Language="C#" Value="public class FabricImageStoreException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricImageStoreException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricImageStoreException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricImageStoreException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricImageStoreException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="cdf6b-101">Die Ausnahme ausgelöst, wenn ist ImageStore Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-101">The exception that is thrown when perform ImageStore operations.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-102">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para><span data-ttu-id="cdf6b-103">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-103">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> -Klasse mit einem angegebenen Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-104">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : string -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="cdf6b-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-106">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-106">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" /> and a specified error message.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricImageStoreException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="cdf6b-107">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-107">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="cdf6b-108">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-108">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="cdf6b-109">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-109">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-110">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> Klasse aus einem serialisierten Objekt, mit einem angegebenen Kontext.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-110">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class from a serialized object data, with a specified context.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : string * Exception -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="cdf6b-111">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-111">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="cdf6b-112">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-112">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="cdf6b-113">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-113">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-114">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-114">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="cdf6b-115">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-115">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="cdf6b-116">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-116">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-117">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> -Klasse mit der angegebenen Fehlermeldung und der Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-117">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with specified error message and error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricImageStoreException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="cdf6b-118">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-118">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="cdf6b-119">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-119">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="cdf6b-120">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-120">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="cdf6b-121">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-121">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-122">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> -Klasse aus einem serialisierten Objektdaten mit angegebenen Kontext und Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-122">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class from a serialized object data, with specified context and error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricImageStoreException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricImageStoreException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricImageStoreException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricImageStoreException" Usage="new System.Fabric.FabricImageStoreException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="cdf6b-123">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-123">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="cdf6b-124">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-124">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="cdf6b-125">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-125">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="cdf6b-126">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-126">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="cdf6b-127">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricImageStoreException" /> Nachricht Klasse mit einer angegebenen Fehlermeldung, der einen Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme und eine angegebene Fehlercode ist.</span><span class="sxs-lookup"><span data-stu-id="cdf6b-127">Initializes a new instance of <see cref="T:System.Fabric.FabricImageStoreException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>