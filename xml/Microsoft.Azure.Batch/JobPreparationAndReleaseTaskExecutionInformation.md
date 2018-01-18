<Type Name="JobPreparationAndReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationAndReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobPreparationAndReleaseTaskExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5f565-101">Der Status des Auftrags Preparation Task und Auftrag Version Task auf einen Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="5f565-101">The status of the Job Preparation task and Job Release task on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ComputeNodeId">
      <MemberSignature Language="C#" Value="public string ComputeNodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputeNodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.ComputeNodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeId As String" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeId : string" Usage="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.ComputeNodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f565-102">Ruft die Id des Serverknotens ab.</span><span class="sxs-lookup"><span data-stu-id="5f565-102">Gets the id of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeNodeUrl">
      <MemberSignature Language="C#" Value="public string ComputeNodeUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputeNodeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.ComputeNodeUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeUrl As String" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeUrl : string" Usage="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.ComputeNodeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f565-103">Ruft die URL des Serverknotens ab.</span><span class="sxs-lookup"><span data-stu-id="5f565-103">Gets the URL of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTaskExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobPreparationTaskExecutionInformation As JobPreparationTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTaskExecutionInformation : Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation" Usage="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f565-104">Ruft Details zu den <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask">Auftrag Preparation Task</see> auf diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="5f565-104">Gets details of the <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask">Job Preparation task</see> on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTaskExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobReleaseTaskExecutionInformation As JobReleaseTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTaskExecutionInformation : Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation" Usage="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobReleaseTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f565-105">Ruft Details zu den <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask">Task Auftrag freigeben</see> auf diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="5f565-105">Gets details of the <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask">Job Release task</see> on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string" Usage="Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f565-106">Ruft die Id des Pools mit der Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="5f565-106">Gets the id of the pool containing the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>