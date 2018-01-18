<Type Name="DpmErrorInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo">
  <TypeSignature Language="C#" Value="public class DpmErrorInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmErrorInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmErrorInfo" />
  <TypeSignature Language="F#" Value="type DpmErrorInfo = class" />
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
            <span data-ttu-id="147f9-101">Informationen zum DPM spezifische Fehler.</span><span class="sxs-lookup"><span data-stu-id="147f9-101">DPM workload-specific error information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmErrorInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="147f9-102">Initialisiert eine neue Instanz der DpmErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="147f9-102">Initializes a new instance of the DpmErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmErrorInfo (string errorString = null, System.Collections.Generic.IList&lt;string&gt; recommendations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorString, class System.Collections.Generic.IList`1&lt;string&gt; recommendations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional errorString As String = null, Optional recommendations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo (errorString, recommendations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorString" Type="System.String" />
        <Parameter Name="recommendations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="errorString"><span data-ttu-id="147f9-103">Lokalisierte fehlermeldungs-Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="147f9-103">Localized error string.</span></span></param>
        <param name="recommendations"><span data-ttu-id="147f9-104">Liste von lokalisierten Empfehlungen für die oben Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="147f9-104">List of localized recommendations for above error code.</span></span></param>
        <summary>
            <span data-ttu-id="147f9-105">Initialisiert eine neue Instanz der DpmErrorInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="147f9-105">Initializes a new instance of the DpmErrorInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorString">
      <MemberSignature Language="C#" Value="public string ErrorString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.ErrorString" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorString As String" />
      <MemberSignature Language="F#" Value="member this.ErrorString : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.ErrorString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="147f9-106">Ruft ab, oder legt ihn fest lokalisierte Fehlerzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="147f9-106">Gets or sets localized error string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Recommendations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Recommendations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="147f9-107">Ruft ab, oder legt ihn fest lokalisierte Empfehlungen für oben Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="147f9-107">Gets or sets list of localized recommendations for above error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>