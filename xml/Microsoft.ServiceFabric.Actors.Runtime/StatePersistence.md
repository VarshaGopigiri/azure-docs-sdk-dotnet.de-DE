<Type Name="StatePersistence" FullName="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence">
  <TypeSignature Language="C#" Value="public enum StatePersistence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StatePersistence extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />
  <TypeSignature Language="VB.NET" Value="Public Enum StatePersistence" />
  <TypeSignature Language="F#" Value="type StatePersistence = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="658b6-101">Gibt an, wie actorzustands für einen Akteur-Dienst gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="658b6-101">Indicates how actor state is stored for an actor service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="658b6-102">Der Akteur wird kein Zustand gespeichert.</span><span class="sxs-lookup"><span data-stu-id="658b6-102">No state is stored for the actor.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Persisted">
      <MemberSignature Language="C#" Value="Persisted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence Persisted = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.Persisted" />
      <MemberSignature Language="VB.NET" Value="Persisted" />
      <MemberSignature Language="F#" Value="Persisted = 2" Usage="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.Persisted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="658b6-103">Der Akteur-Status wird auf lokalem Datenträger mithilfe eines Anbieters persistenten Status beibehalten.</span><span class="sxs-lookup"><span data-stu-id="658b6-103">The actor state is persisted to local disk using a persistent state provider.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Volatile">
      <MemberSignature Language="C#" Value="Volatile" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence Volatile = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.Volatile" />
      <MemberSignature Language="VB.NET" Value="Volatile" />
      <MemberSignature Language="F#" Value="Volatile = 1" Usage="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence.Volatile" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="658b6-104">Der Akteur-Status ist nur mithilfe eines flüchtigen Zustand-Anbieters im Arbeitsspeicher beibehalten.</span><span class="sxs-lookup"><span data-stu-id="658b6-104">The actor state is kept in-memory only using a volatile state provider.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>