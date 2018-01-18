<Type Name="SendTestAlertEmailRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest">
  <TypeSignature Language="C#" Value="public class SendTestAlertEmailRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SendTestAlertEmailRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class SendTestAlertEmailRequest" />
  <TypeSignature Language="F#" Value="type SendTestAlertEmailRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13d95-101">Die Anforderung zum Test warnungsbenachrichtigung per e-Mail senden</span><span class="sxs-lookup"><span data-stu-id="13d95-101">The request for sending test alert email</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SendTestAlertEmailRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13d95-102">Initialisiert eine neue Instanz der SendTestAlertEmailRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="13d95-102">Initializes a new instance of the SendTestAlertEmailRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SendTestAlertEmailRequest (System.Collections.Generic.IList&lt;string&gt; emailList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; emailList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (emailList As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest emailList" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="emailList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="emailList"><span data-ttu-id="13d95-103">Die Liste der e-Mail-IDs der Test-warnungsbenachrichtigung per e-Mail senden</span><span class="sxs-lookup"><span data-stu-id="13d95-103">The list of email IDs to send the test alert email</span></span></param>
        <summary>
            <span data-ttu-id="13d95-104">Initialisiert eine neue Instanz der SendTestAlertEmailRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="13d95-104">Initializes a new instance of the SendTestAlertEmailRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EmailList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EmailList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest.EmailList" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EmailList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest.EmailList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="emailList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13d95-105">Ruft ab oder legt die Liste der e-Mail-IDs der Test-warnungsbenachrichtigung per e-Mail senden</span><span class="sxs-lookup"><span data-stu-id="13d95-105">Gets or sets the list of email IDs to send the test alert email</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.SendTestAlertEmailRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sendTestAlertEmailRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13d95-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="13d95-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="13d95-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="13d95-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>