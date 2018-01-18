<Type Name="Ecdsa256" FullName="Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256">
  <TypeSignature Language="C#" Value="public class Ecdsa256 : Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Ecdsa256 extends Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256" />
  <TypeSignature Language="VB.NET" Value="Public Class Ecdsa256&#xA;Inherits Ecdsa" />
  <TypeSignature Language="F#" Value="type Ecdsa256 = class&#xA;    inherit Ecdsa" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4415b-101">ECDSA darstellt mit einer generischen 256-Bit-Kurve.</span><span class="sxs-lookup"><span data-stu-id="4415b-101">Represents ECDSA with a generic 256 bit curve.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Ecdsa256 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlgorithmName">
      <MemberSignature Language="C#" Value="public const string AlgorithmName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AlgorithmName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256.AlgorithmName" />
      <MemberSignature Language="VB.NET" Value="Public Const AlgorithmName As String " />
      <MemberSignature Language="F#" Value="val mutable AlgorithmName : string" Usage="Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256.AlgorithmName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSignatureTransform">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform (System.Security.Cryptography.AsymmetricAlgorithm key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform(class System.Security.Cryptography.AsymmetricAlgorithm key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.Algorithms.Ecdsa256.CreateSignatureTransform(System.Security.Cryptography.AsymmetricAlgorithm)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateSignatureTransform (key As AsymmetricAlgorithm) As ISignatureTransform" />
      <MemberSignature Language="F#" Value="override this.CreateSignatureTransform : System.Security.Cryptography.AsymmetricAlgorithm -&gt; Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform" Usage="ecdsa256.CreateSignatureTransform key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Security.Cryptography.AsymmetricAlgorithm" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>