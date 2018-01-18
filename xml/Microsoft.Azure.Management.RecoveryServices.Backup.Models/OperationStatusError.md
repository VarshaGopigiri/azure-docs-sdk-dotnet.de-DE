<Type Name="OperationStatusError" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError">
  <TypeSignature Language="C#" Value="public class OperationStatusError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationStatusError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationStatusError" />
  <TypeSignature Language="F#" Value="type OperationStatusError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="48e28-101">Fehlerinformationen Status Vorgangsaufruf zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="48e28-101">Error information associated with operation status call.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="48e28-102">Initialisiert eine neue Instanz der OperationStatusError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="48e28-102">Initializes a new instance of the OperationStatusError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusError (string code = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError : string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError (code, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="48e28-103">Der Fehlercode des vorgangsfehlers.</span><span class="sxs-lookup"><span data-stu-id="48e28-103">Error code of the operation failure.</span></span></param>
        <param name="message"><span data-ttu-id="48e28-104">Die Fehlermeldung angezeigt, wenn der Fehler beim Vorgang.</span><span class="sxs-lookup"><span data-stu-id="48e28-104">Error message displayed if the operation failure.</span></span></param>
        <summary>
            <span data-ttu-id="48e28-105">Initialisiert eine neue Instanz der OperationStatusError-Klasse.</span><span class="sxs-lookup"><span data-stu-id="48e28-105">Initializes a new instance of the OperationStatusError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
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
            <span data-ttu-id="48e28-106">Ruft ab, oder legt ihn fest Fehlercode, der der Fehler beim Vorgang.</span><span class="sxs-lookup"><span data-stu-id="48e28-106">Gets or sets error code of the operation failure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
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
            <span data-ttu-id="48e28-107">Ruft ab oder legt die Fehlermeldung angezeigt, wenn der Fehler beim Vorgang.</span><span class="sxs-lookup"><span data-stu-id="48e28-107">Gets or sets error message displayed if the operation failure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>