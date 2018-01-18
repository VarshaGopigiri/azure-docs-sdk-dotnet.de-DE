<Type Name="ServiceEndpointRole" FullName="System.Fabric.ServiceEndpointRole">
  <TypeSignature Language="C#" Value="public enum ServiceEndpointRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceEndpointRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceEndpointRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceEndpointRole" />
  <TypeSignature Language="F#" Value="type ServiceEndpointRole = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="d33e9-101">Zählt die Arten der möglichen Rollen eines Dienstendpunkts.</span><span class="sxs-lookup"><span data-stu-id="d33e9-101">Enumerates the kinds of possible roles of a service endpoint.</span></span> </para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServiceEndpointRole Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServiceEndpointRole.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ServiceEndpointRole.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d33e9-102">Gibt an, dass Service Fabric die Rolle "Endpoint" klassifizieren können nicht.</span><span class="sxs-lookup"><span data-stu-id="d33e9-102">Indicates that Service Fabric cannot classify the service endpoint role.</span></span> </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="StatefulPrimary">
      <MemberSignature Language="C#" Value="StatefulPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServiceEndpointRole StatefulPrimary = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServiceEndpointRole.StatefulPrimary" />
      <MemberSignature Language="VB.NET" Value="StatefulPrimary" />
      <MemberSignature Language="F#" Value="StatefulPrimary = 2" Usage="System.Fabric.ServiceEndpointRole.StatefulPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d33e9-103">Gibt an, dass die Rolle "Endpoint" eine zustandsbehaftete primären Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="d33e9-103">Indicates that the service endpoint role is a stateful Primary replica.</span></span> </para>
        </summary>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StatefulSecondary">
      <MemberSignature Language="C#" Value="StatefulSecondary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServiceEndpointRole StatefulSecondary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServiceEndpointRole.StatefulSecondary" />
      <MemberSignature Language="VB.NET" Value="StatefulSecondary" />
      <MemberSignature Language="F#" Value="StatefulSecondary = 3" Usage="System.Fabric.ServiceEndpointRole.StatefulSecondary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d33e9-104">Gibt an, dass die Rolle "Endpoint" eine zustandsbehaftete sekundäres Replikat ist.</span><span class="sxs-lookup"><span data-stu-id="d33e9-104">Indicates that the service endpoint role is a stateful Secondary replica.</span></span> </para>
        </summary>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Stateless">
      <MemberSignature Language="C#" Value="Stateless" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ServiceEndpointRole Stateless = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ServiceEndpointRole.Stateless" />
      <MemberSignature Language="VB.NET" Value="Stateless" />
      <MemberSignature Language="F#" Value="Stateless = 1" Usage="System.Fabric.ServiceEndpointRole.Stateless" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServiceEndpointRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d33e9-105">Gibt an, dass die Rolle "Endpoint" zustandslos ist.</span><span class="sxs-lookup"><span data-stu-id="d33e9-105">Indicates that the service endpoint role is stateless.</span></span> </para>
        </summary>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>