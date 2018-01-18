<Type Name="CertificateVisibility" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility">
  <TypeSignature Language="C#" Value="public enum CertificateVisibility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateVisibility extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateVisibility" />
  <TypeSignature Language="F#" Value="type CertificateVisibility = " />
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
            <span data-ttu-id="3b5c4-101">Definiert Werte für CertificateVisibility an.</span><span class="sxs-lookup"><span data-stu-id="3b5c4-101">Defines values for CertificateVisibility.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RemoteUser">
      <MemberSignature Language="C#" Value="RemoteUser" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility RemoteUser = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.RemoteUser" />
      <MemberSignature Language="VB.NET" Value="RemoteUser" />
      <MemberSignature Language="F#" Value="RemoteUser = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.RemoteUser" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="remoteuser")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5c4-102">Das Zertifikat sollte sichtbar zu den Benutzerkonten, unter dem Benutzer den Knoten Remotezugriff auf.</span><span class="sxs-lookup"><span data-stu-id="3b5c4-102">The certificate should be visibile to the user accounts under which users remotely access the node.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="StartTask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility StartTask = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.StartTask" />
      <MemberSignature Language="VB.NET" Value="StartTask" />
      <MemberSignature Language="F#" Value="StartTask = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.StartTask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="starttask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5c4-103">Das Zertifikat sollte für das Benutzerkonto, das sichtbar sein, unter denen die Startaufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="3b5c4-103">The certificate should be visible to the user account under which the start task is run.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="Task" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility Task = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.Task" />
      <MemberSignature Language="VB.NET" Value="Task" />
      <MemberSignature Language="F#" Value="Task = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility.Task" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="task")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateVisibility</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b5c4-104">Das Zertifikat sollte sichtbar zu den Benutzerkonten, unter welcher Auftrag die Tasks ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="3b5c4-104">The certificate should be visibile to the user accounts under which job tasks are run.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>