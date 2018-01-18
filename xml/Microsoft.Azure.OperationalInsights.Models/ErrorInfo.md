<Type Name="ErrorInfo" FullName="Microsoft.Azure.OperationalInsights.Models.ErrorInfo">
  <TypeSignature Language="C#" Value="public class ErrorInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.Models.ErrorInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorInfo" />
  <TypeSignature Language="F#" Value="type ErrorInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29168-101">Der Code und eine Nachricht für einen Fehler.</span><span class="sxs-lookup"><span data-stu-id="29168-101">The code and message for an error.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29168-102">Initialisiert eine neue Instanz der ErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29168-102">Initializes a new instance of the ErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorInfo (string code, string message, System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; details = null, Microsoft.Azure.OperationalInsights.Models.ErrorInfo innererror = null, object additionalProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; details, class Microsoft.Azure.OperationalInsights.Models.ErrorInfo innererror, object additionalProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.OperationalInsights.Models.ErrorDetail},Microsoft.Azure.OperationalInsights.Models.ErrorInfo,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As String, message As String, Optional details As IList(Of ErrorDetail) = null, Optional innererror As ErrorInfo = null, Optional additionalProperties As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.ErrorInfo : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; * Microsoft.Azure.OperationalInsights.Models.ErrorInfo * obj -&gt; Microsoft.Azure.OperationalInsights.Models.ErrorInfo" Usage="new Microsoft.Azure.OperationalInsights.Models.ErrorInfo (code, message, details, innererror, additionalProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt;" />
        <Parameter Name="innererror" Type="Microsoft.Azure.OperationalInsights.Models.ErrorInfo" />
        <Parameter Name="additionalProperties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="29168-103">Eine lesbare Fehlermeldung Computercode.</span><span class="sxs-lookup"><span data-stu-id="29168-103">A machine readable error code.</span></span></param>
        <param name="message"><span data-ttu-id="29168-104">Interaktive Workflowdienste-lesbare Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="29168-104">A human readable error message.</span></span></param>
        <param name="details"><span data-ttu-id="29168-105">Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="29168-105">error details.</span></span></param>
        <param name="innererror"><span data-ttu-id="29168-106">Interner Fehler-Details, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="29168-106">Inner error details if they exist.</span></span></param>
        <param name="additionalProperties">To be added.</param>
        <summary>
            <span data-ttu-id="29168-107">Initialisiert eine neue Instanz der ErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="29168-107">Initializes a new instance of the ErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public object AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As Object" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : obj with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorInfo.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="additionalProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            <span data-ttu-id="29168-108">Ermittelt oder definiert einen Computer lesbaren-Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="29168-108">Gets or sets a machine readable error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As IList(Of ErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.OperationalInsights.Models.ErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29168-109">Ruft ab oder legt die Fehlerdetails.</span><span class="sxs-lookup"><span data-stu-id="29168-109">Gets or sets error details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Innererror">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationalInsights.Models.ErrorInfo Innererror { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.OperationalInsights.Models.ErrorInfo Innererror" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Innererror" />
      <MemberSignature Language="VB.NET" Value="Public Property Innererror As ErrorInfo" />
      <MemberSignature Language="F#" Value="member this.Innererror : Microsoft.Azure.OperationalInsights.Models.ErrorInfo with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Innererror" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innererror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.ErrorInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29168-110">Ruft ab oder legt die internen Fehlerdetails fest, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="29168-110">Gets or sets inner error details if they exist.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29168-111">Ermittelt oder definiert eine menschlichen lesbare Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="29168-111">Gets or sets a human readable error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.ErrorInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="errorInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29168-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="29168-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29168-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="29168-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>