<Type Name="ServiceReplicaStatusFilter" FullName="System.Fabric.Query.ServiceReplicaStatusFilter">
  <TypeSignature Language="C#" Value="public enum ServiceReplicaStatusFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceReplicaStatusFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceReplicaStatusFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceReplicaStatusFilter" />
  <TypeSignature Language="F#" Value="type ServiceReplicaStatusFilter = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="ad4cb-101">Listet den Filter für den Abgleich der Replikatstatus für Replikate, die von der Abfrage zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-101">Enumerates the filter used for matching the replica status for replicas that should be returned by query.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-102">Gibt alle Replikate zurück.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-102">Returns all replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-103">Gibt alle Replikate als gelöschte Replikate zurück.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-103">Returns all replicas other than dropped replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Down">
      <MemberSignature Language="C#" Value="Down" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter Down = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.Down" />
      <MemberSignature Language="VB.NET" Value="Down" />
      <MemberSignature Language="F#" Value="Down = 8" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.Down" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-104">Gibt alle unten Replikate.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-104">Returns all down replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Dropped">
      <MemberSignature Language="C#" Value="Dropped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter Dropped = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.Dropped" />
      <MemberSignature Language="VB.NET" Value="Dropped" />
      <MemberSignature Language="F#" Value="Dropped = 16" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.Dropped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-105">Gibt alle gelöschte Replikate zurück.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-105">Returns all Dropped replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InBuild">
      <MemberSignature Language="C#" Value="InBuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter InBuild = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.InBuild" />
      <MemberSignature Language="VB.NET" Value="InBuild" />
      <MemberSignature Language="F#" Value="InBuild = 1" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.InBuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-106">Gibt alle InBuild-Replikaten zurück.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-106">Returns all InBuild replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter Ready = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 4" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-107">Gibt bereit nur Replikate.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-107">Returns only ready replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Standby">
      <MemberSignature Language="C#" Value="Standby" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatusFilter Standby = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatusFilter.Standby" />
      <MemberSignature Language="VB.NET" Value="Standby" />
      <MemberSignature Language="F#" Value="Standby = 2" Usage="System.Fabric.Query.ServiceReplicaStatusFilter.Standby" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatusFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ad4cb-108">Gibt alle StandBy-Replikaten zurück.</span><span class="sxs-lookup"><span data-stu-id="ad4cb-108">Returns all StandBy replicas.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>