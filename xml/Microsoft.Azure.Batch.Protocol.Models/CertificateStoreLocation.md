<Type Name="CertificateStoreLocation" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation">
  <TypeSignature Language="C#" Value="public enum CertificateStoreLocation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateStoreLocation extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateStoreLocation" />
  <TypeSignature Language="F#" Value="type CertificateStoreLocation = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="07f9b-101">Definiert Werte für CertificateStoreLocation an.</span><span class="sxs-lookup"><span data-stu-id="07f9b-101">Defines values for CertificateStoreLocation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentUser">
      <MemberSignature Language="C#" Value="CurrentUser" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation CurrentUser = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation.CurrentUser" />
      <MemberSignature Language="VB.NET" Value="CurrentUser" />
      <MemberSignature Language="F#" Value="CurrentUser = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation.CurrentUser" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="currentuser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="07f9b-102">Zertifikate sollten in den Speicher CurrentUser-Zertifikatspeicher installiert werden.</span><span class="sxs-lookup"><span data-stu-id="07f9b-102">Certificates should be installed to the CurrentUser certificate store.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LocalMachine">
      <MemberSignature Language="C#" Value="LocalMachine" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation LocalMachine = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation.LocalMachine" />
      <MemberSignature Language="VB.NET" Value="LocalMachine" />
      <MemberSignature Language="F#" Value="LocalMachine = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation.LocalMachine" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="localmachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateStoreLocation</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="07f9b-103">Zertifikate sollten in den Zertifikatspeicher LocalMachine installiert werden.</span><span class="sxs-lookup"><span data-stu-id="07f9b-103">Certificates should be installed to the LocalMachine certificate store.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>