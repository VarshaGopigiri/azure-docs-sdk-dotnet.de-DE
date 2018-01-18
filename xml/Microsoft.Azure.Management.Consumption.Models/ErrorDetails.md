<Type Name="ErrorDetails" FullName="Microsoft.Azure.Management.Consumption.Models.ErrorDetails">
  <TypeSignature Language="C#" Value="public class ErrorDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.Models.ErrorDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorDetails" />
  <TypeSignature Language="F#" Value="type ErrorDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="edd7b-101">Die Details des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="edd7b-101">The details of the error.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="edd7b-102">Initialisiert eine neue Instanz der Klasse ErrorDetails an.</span><span class="sxs-lookup"><span data-stu-id="edd7b-102">Initializes a new instance of the ErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorDetails (string code = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.ErrorDetails.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Consumption.Models.ErrorDetails : string * string -&gt; Microsoft.Azure.Management.Consumption.Models.ErrorDetails" Usage="new Microsoft.Azure.Management.Consumption.Models.ErrorDetails (code, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="edd7b-103">Fehlercode</span><span class="sxs-lookup"><span data-stu-id="edd7b-103">Error code.</span></span></param>
        <param name="message"><span data-ttu-id="edd7b-104">Die Fehlermeldung, der angibt, warum der Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="edd7b-104">Error message indicating why the operation failed.</span></span></param>
        <summary>
            <span data-ttu-id="edd7b-105">Initialisiert eine neue Instanz der Klasse ErrorDetails an.</span><span class="sxs-lookup"><span data-stu-id="edd7b-105">Initializes a new instance of the ErrorDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.ErrorDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.Consumption.Models.ErrorDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="edd7b-106">Ruft den Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="edd7b-106">Gets error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.ErrorDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.Consumption.Models.ErrorDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="edd7b-107">Ruft Fehlermeldung, der angibt, warum der Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="edd7b-107">Gets error message indicating why the operation failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>