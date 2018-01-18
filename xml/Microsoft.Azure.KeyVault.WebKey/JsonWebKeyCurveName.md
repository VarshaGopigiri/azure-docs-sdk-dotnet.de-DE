<Type Name="JsonWebKeyCurveName" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName">
  <TypeSignature Language="C#" Value="public static class JsonWebKeyCurveName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JsonWebKeyCurveName extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonWebKeyCurveName" />
  <TypeSignature Language="F#" Value="type JsonWebKeyCurveName = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3070a-101">Elliptic Curve Cryptography (ECC) Kurvennamen.</span><span class="sxs-lookup"><span data-stu-id="3070a-101">Elliptic Curve Cryptography (ECC) curve names.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllCurves">
      <MemberSignature Language="C#" Value="public static string[] AllCurves { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string[] AllCurves" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.AllCurves" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property AllCurves As String()" />
      <MemberSignature Language="F#" Value="member this.AllCurves : string[]" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.AllCurves" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3070a-102">Alle Kurven für "EC".</span><span class="sxs-lookup"><span data-stu-id="3070a-102">All curves for EC.</span></span> <span data-ttu-id="3070a-103">Verwenden Sie zur Vermeidung von FxCop-Verletzung Klonen</span><span class="sxs-lookup"><span data-stu-id="3070a-103">Use clone to avoid FxCop violation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyParameterSize">
      <MemberSignature Language="C#" Value="public static int GetKeyParameterSize (string curve);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 GetKeyParameterSize(string curve) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.GetKeyParameterSize(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetKeyParameterSize (curve As String) As Integer" />
      <MemberSignature Language="F#" Value="static member GetKeyParameterSize : string -&gt; int" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.GetKeyParameterSize curve" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="curve" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="curve"><span data-ttu-id="3070a-104">Die Kurve für die Größe der Key-Parameter erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="3070a-104">The curve for which key parameter size is required.</span></span></param>
        <summary>
            <span data-ttu-id="3070a-105">Gibt die erforderliche Größe in Bytes, der jede Schlüsselparameter ("X", "Y" und "D"), oder -1 zurück, die Kurve wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="3070a-105">Returns the required size, in bytes, of each key parameters (X, Y and D), or -1 if the curve is unsupported.</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="P256">
      <MemberSignature Language="C#" Value="public const string P256;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string P256" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P256" />
      <MemberSignature Language="VB.NET" Value="Public Const P256 As String " />
      <MemberSignature Language="F#" Value="val mutable P256 : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P256" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
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
    <Member MemberName="P384">
      <MemberSignature Language="C#" Value="public const string P384;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string P384" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P384" />
      <MemberSignature Language="VB.NET" Value="Public Const P384 As String " />
      <MemberSignature Language="F#" Value="val mutable P384 : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P384" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
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
    <Member MemberName="P521">
      <MemberSignature Language="C#" Value="public const string P521;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string P521" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P521" />
      <MemberSignature Language="VB.NET" Value="Public Const P521 As String " />
      <MemberSignature Language="F#" Value="val mutable P521 : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.P521" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
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
    <Member MemberName="SECP256K1">
      <MemberSignature Language="C#" Value="public const string SECP256K1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SECP256K1" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.SECP256K1" />
      <MemberSignature Language="VB.NET" Value="Public Const SECP256K1 As String " />
      <MemberSignature Language="F#" Value="val mutable SECP256K1 : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyCurveName.SECP256K1" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
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
  </Members>
</Type>