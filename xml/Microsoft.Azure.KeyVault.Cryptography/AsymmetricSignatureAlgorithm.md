<Type Name="AsymmetricSignatureAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class AsymmetricSignatureAlgorithm : Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AsymmetricSignatureAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AsymmetricSignatureAlgorithm&#xA;Inherits SignatureAlgorithm" />
  <TypeSignature Language="F#" Value="type AsymmetricSignatureAlgorithm = class&#xA;    inherit SignatureAlgorithm" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0e9e1-101">Abstrakte asymmetrische Signaturalgorithmus</span><span class="sxs-lookup"><span data-stu-id="0e9e1-101">Abstract Asymmetric Signature algorithm</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AsymmetricSignatureAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSignatureTransform">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform (System.Security.Cryptography.AsymmetricAlgorithm key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform(class System.Security.Cryptography.AsymmetricAlgorithm key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm.CreateSignatureTransform(System.Security.Cryptography.AsymmetricAlgorithm)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateSignatureTransform (key As AsymmetricAlgorithm) As ISignatureTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateSignatureTransform : System.Security.Cryptography.AsymmetricAlgorithm -&gt; Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform" Usage="asymmetricSignatureAlgorithm.CreateSignatureTransform key" />
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
        <param name="key"><span data-ttu-id="0e9e1-102">Der asymmetrische Schlüssel verwenden.</span><span class="sxs-lookup"><span data-stu-id="0e9e1-102">The asymmetric key to use.</span></span></param>
        <summary>
            <span data-ttu-id="0e9e1-103">Erstellt eine Signatur Transformation-Implementierung, die zum Signieren oder überprüfen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="0e9e1-103">Creates a signature transformation implementation that may be used to sign or verify.</span></span>
            </summary>
        <returns><span data-ttu-id="0e9e1-104">Eine ISignatureTransform-Implementierung.</span><span class="sxs-lookup"><span data-stu-id="0e9e1-104">An ISignatureTransform implementation.</span></span></returns>
        <remarks><span data-ttu-id="0e9e1-105">Die Implementierung für die Transformation "Grunde verwendet" angegebenen AsymmetricAlgorithm; Aufrufer sollten Dispose nicht auf die AsymmetricAlgorithm aufrufen, bis zum Abschluss der Transformation Implementierung verwenden.</span><span class="sxs-lookup"><span data-stu-id="0e9e1-105">The transform implementation "borrows" the supplied AsymmetricAlgorithm; callers should not call Dispose on the AsymmetricAlgorithm until use of the transform implementation is complete.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>