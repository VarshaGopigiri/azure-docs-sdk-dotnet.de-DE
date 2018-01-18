<Type Name="FabricEndpointNotFoundException" FullName="System.Fabric.FabricEndpointNotFoundException">
  <TypeSignature Language="C#" Value="public sealed class FabricEndpointNotFoundException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit FabricEndpointNotFoundException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricEndpointNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricEndpointNotFoundException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricEndpointNotFoundException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="2f18a-101">Die Ausnahme, die ausgelöst wird, wenn der angegebene Endpunkt nicht gefunden wird.</span><span class="sxs-lookup"><span data-stu-id="2f18a-101">The exception that is thrown when the specified endpoint is not found.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricEndpointNotFoundException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricEndpointNotFoundException.#ctor" />
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
            <span data-ttu-id="2f18a-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.FabricEndpointNotFound" />.</span><span class="sxs-lookup"><span data-stu-id="2f18a-102">Initializes a new instance of <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricEndpointNotFound" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricEndpointNotFoundException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricEndpointNotFoundException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricEndpointNotFoundException : string -&gt; System.Fabric.FabricEndpointNotFoundException" Usage="new System.Fabric.FabricEndpointNotFoundException message" />
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
          <para><span data-ttu-id="2f18a-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="2f18a-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="2f18a-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.FabricEndpointNotFound" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="2f18a-104">Initializes a new instance of <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricEndpointNotFound" /> and a specified error message.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricEndpointNotFoundException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricEndpointNotFoundException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricEndpointNotFoundException : string * Exception -&gt; System.Fabric.FabricEndpointNotFoundException" Usage="new System.Fabric.FabricEndpointNotFoundException (message, inner)" />
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
          <para><span data-ttu-id="2f18a-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="2f18a-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="2f18a-106">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="2f18a-106">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="2f18a-107">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="2f18a-107">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="2f18a-108">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="2f18a-108">Initializes a new instance of <see cref="T:System.Fabric.FabricEndpointNotFoundException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>