<Type Name="BatchError" FullName="Microsoft.Azure.Batch.Protocol.Models.BatchError">
  <TypeSignature Language="C#" Value="public class BatchError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.BatchError" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchError" />
  <TypeSignature Language="F#" Value="type BatchError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b101-101">Eine Fehlerantwort aus dem Azure Batch-Dienst empfangen.</span><span class="sxs-lookup"><span data-stu-id="8b101-101">An error response received from the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8b101-102">Initialisiert eine neue Instanz der BatchError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8b101-102">Initializes a new instance of the BatchError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchError (string code = null, Microsoft.Azure.Batch.Protocol.Models.ErrorMessage message = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, class Microsoft.Azure.Batch.Protocol.Models.ErrorMessage message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.BatchError.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.ErrorMessage,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As ErrorMessage = null, Optional values As IList(Of BatchErrorDetail) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.BatchError : string * Microsoft.Azure.Batch.Protocol.Models.ErrorMessage * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.BatchError" Usage="new Microsoft.Azure.Batch.Protocol.Models.BatchError (code, message, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="Microsoft.Azure.Batch.Protocol.Models.ErrorMessage" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt;" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="8b101-103">Ein Bezeichner für den Fehler.</span><span class="sxs-lookup"><span data-stu-id="8b101-103">An identifier for the error.</span></span> <span data-ttu-id="8b101-104">Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="8b101-104">Codes are invariant and are intended to be consumed programmatically.</span></span></param>
        <param name="message"><span data-ttu-id="8b101-105">Eine Meldung, die Beschreibung des Fehlers, der für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</span><span class="sxs-lookup"><span data-stu-id="8b101-105">A message describing the error, intended to be suitable for display in a user interface.</span></span></param>
        <param name="values"><span data-ttu-id="8b101-106">Eine Auflistung von Schlüssel-Wert-Paaren, die zusätzliche Informationen über den Fehler enthält.</span><span class="sxs-lookup"><span data-stu-id="8b101-106">A collection of key-value pairs containing additional details about the error.</span></span></param>
        <summary>
            <span data-ttu-id="8b101-107">Initialisiert eine neue Instanz der BatchError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8b101-107">Initializes a new instance of the BatchError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b101-108">Ruft ab oder legt einen Bezeichner für den Fehler.</span><span class="sxs-lookup"><span data-stu-id="8b101-108">Gets or sets an identifier for the error.</span></span> <span data-ttu-id="8b101-109">Codes sind unveränderlich und programmgesteuert genutzt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="8b101-109">Codes are invariant and are intended to be consumed programmatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ErrorMessage Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ErrorMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As ErrorMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.Azure.Batch.Protocol.Models.ErrorMessage with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ErrorMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b101-110">Abrufen oder festlegen eine Nachricht, die Beschreibung des Fehlers, der für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</span><span class="sxs-lookup"><span data-stu-id="8b101-110">Gets or sets a message describing the error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.BatchError.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of BatchErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.BatchError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.BatchErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b101-111">Ruft ab oder legt eine Auflistung von Schlüssel-Wert-Paaren, die zusätzliche Informationen über den Fehler enthält.</span><span class="sxs-lookup"><span data-stu-id="8b101-111">Gets or sets a collection of key-value pairs containing additional details about the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>