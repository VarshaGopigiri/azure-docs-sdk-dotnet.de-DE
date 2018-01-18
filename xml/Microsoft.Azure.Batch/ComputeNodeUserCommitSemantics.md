<Type Name="ComputeNodeUserCommitSemantics" FullName="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics">
  <TypeSignature Language="C#" Value="public enum ComputeNodeUserCommitSemantics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeUserCommitSemantics extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeUserCommitSemantics" />
  <TypeSignature Language="F#" Value="type ComputeNodeUserCommitSemantics = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="a1bed-101">Informiert die Commit() Aufruf, der der Zustand zwischen dem Client und Server übertragen, entweder wird einen Benutzer erstellen oder Update-Benutzer-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a1bed-101">Informs the Commit() call that the state transfer between the client and server is either a create-user or update-user operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddUser">
      <MemberSignature Language="C#" Value="AddUser" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics AddUser = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser" />
      <MemberSignature Language="VB.NET" Value="AddUser" />
      <MemberSignature Language="F#" Value="AddUser = 0" Usage="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1bed-102">Der Commit-Vorgang wird einen neuen Benutzer hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a1bed-102">The Commit operation is adding a new user.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UpdateUser">
      <MemberSignature Language="C#" Value="UpdateUser" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics UpdateUser = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.UpdateUser" />
      <MemberSignature Language="VB.NET" Value="UpdateUser" />
      <MemberSignature Language="F#" Value="UpdateUser = 1" Usage="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.UpdateUser" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1bed-103">Der Commit-Vorgang aktualisiert einen vorhandenen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="a1bed-103">The Commit operation is updating an existing user.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>