<Type Name="AdlsBadOffsetException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException">
  <TypeSignature Language="C#" Value="public class AdlsBadOffsetException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsBadOffsetException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsBadOffsetException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsBadOffsetException = class&#xA;    inherit AdlsRemoteException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("BadOffsetException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="49d2d-101">Eine WebHDFS-Ausnahme ausgelöst, der angibt, das Anfügen oder lesen wird über einen ungültigen Offset.</span><span class="sxs-lookup"><span data-stu-id="49d2d-101">A WebHDFS exception thrown indicating the append or read is from a bad offset.</span></span> <span data-ttu-id="49d2d-102">Wird ausgelöst, wenn eine fehlerantwortcode 400 für das Anfügen und Öffnungsvorgänge (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="49d2d-102">Thrown when a 400 error response code is returned for append and open operations (Bad request).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsBadOffsetException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49d2d-103">Initialisiert eine neue Instanz der AdlsBadOffsetException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49d2d-103">Initializes a new instance of the AdlsBadOffsetException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsBadOffsetException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsBadOffsetException (javaClassName, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="javaClassName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="javaClassName"><span data-ttu-id="49d2d-104">Das vollständige Paket Klassenname für die Ausnahme ausgelöst wird, z. B. "java.lang.IllegalArgumentException".</span><span class="sxs-lookup"><span data-stu-id="49d2d-104">the full class package name for the exception thrown, such as 'java.lang.IllegalArgumentException'.</span></span></param>
        <param name="message"><span data-ttu-id="49d2d-105">die die ausgelöste Ausnahme, z. B. zugeordnete Meldung ' Ungültiger Wert für Webhdfs-Parameter "Berechtigung":... ".</span><span class="sxs-lookup"><span data-stu-id="49d2d-105">the message associated with the exception that was thrown, such as 'Invalid value for webhdfs parameter "permission":...'.</span></span></param>
        <summary>
            <span data-ttu-id="49d2d-106">Initialisiert eine neue Instanz der AdlsBadOffsetException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49d2d-106">Initializes a new instance of the AdlsBadOffsetException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>