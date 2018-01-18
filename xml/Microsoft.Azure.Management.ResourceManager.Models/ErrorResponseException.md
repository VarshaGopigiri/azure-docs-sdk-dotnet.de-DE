<Type Name="ErrorResponseException" FullName="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
  <TypeSignature Language="C#" Value="public class ErrorResponseException : Microsoft.Rest.RestException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponseException extends Microsoft.Rest.RestException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponseException&#xA;Inherits RestException" />
  <TypeSignature Language="F#" Value="type ErrorResponseException = class&#xA;    inherit RestException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.RestException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="126da-101">Ausnahme für eine ungültige Antwort mit ErrorResponse Informationen.</span><span class="sxs-lookup"><span data-stu-id="126da-101">Exception thrown for an invalid response with ErrorResponse information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="126da-102">Initialisiert eine neue Instanz der ErrorResponseException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="126da-102">Initializes a new instance of the ErrorResponseException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException : string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="126da-103">Die Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="126da-103">The exception message.</span></span></param>
        <summary>
            <span data-ttu-id="126da-104">Initialisiert eine neue Instanz der ErrorResponseException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="126da-104">Initializes a new instance of the ErrorResponseException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponseException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException : string * Exception -&gt; Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="126da-105">Die Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="126da-105">The exception message.</span></span></param>
        <param name="innerException"><span data-ttu-id="126da-106">Beschreibung der eingeschlossenen Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="126da-106">Inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="126da-107">Initialisiert eine neue Instanz der ErrorResponseException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="126da-107">Initializes a new instance of the ErrorResponseException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As ErrorResponse" />
      <MemberSignature Language="F#" Value="member this.Body : Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="126da-108">Ruft ab oder legt die Body-Objekt.</span><span class="sxs-lookup"><span data-stu-id="126da-108">Gets or sets the body object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpRequestMessageWrapper Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpRequestMessageWrapper Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Rest.HttpRequestMessageWrapper with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpRequestMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="126da-109">Ruft Informationen über die zugeordneten HTTP-Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="126da-109">Gets information about the associated HTTP request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.HttpResponseMessageWrapper Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.HttpResponseMessageWrapper Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpResponseMessageWrapper" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Rest.HttpResponseMessageWrapper with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.HttpResponseMessageWrapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="126da-110">Ruft Informationen über die zugeordneten HTTP-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="126da-110">Gets information about the associated HTTP response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>