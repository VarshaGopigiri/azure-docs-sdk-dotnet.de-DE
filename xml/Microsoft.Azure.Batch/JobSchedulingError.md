<Type Name="JobSchedulingError" FullName="Microsoft.Azure.Batch.JobSchedulingError">
  <TypeSignature Language="C#" Value="public class JobSchedulingError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSchedulingError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobSchedulingError" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulingError" />
  <TypeSignature Language="F#" Value="type JobSchedulingError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="4e54e-101">Ein Fehler vom Batch-Dienst beim Planen eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4e54e-101">An error encountered by the Batch service when scheduling a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.ErrorCategory Category { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.ErrorCategory Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSchedulingError.Category" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Category As ErrorCategory" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Batch.Common.ErrorCategory" Usage="Microsoft.Azure.Batch.JobSchedulingError.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ErrorCategory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e54e-102">Ruft die Kategorie des Auftrags Planungsfehler ab.</span><span class="sxs-lookup"><span data-stu-id="4e54e-102">Gets the category of the job scheduling error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSchedulingError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.JobSchedulingError.Code" />
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
            <span data-ttu-id="4e54e-103">Ruft einen Code für die auftragsplanung Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="4e54e-103">Gets a code for the job scheduling error.</span></span> <span data-ttu-id="4e54e-104">Finden Sie unter <see cref="T:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes" /> mögliche Werte.</span><span class="sxs-lookup"><span data-stu-id="4e54e-104">See <see cref="T:Microsoft.Azure.Batch.Common.JobSchedulingErrorCodes" /> for possible values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt; Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NameValuePair&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSchedulingError.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As IReadOnlyList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;" Usage="Microsoft.Azure.Batch.JobSchedulingError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e54e-105">Ruft eine Liste der zusätzliche Fehlerinformationen zum Planungsfehler.</span><span class="sxs-lookup"><span data-stu-id="4e54e-105">Gets a list of additional error details related to the scheduling error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSchedulingError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Batch.JobSchedulingError.Message" />
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
            <span data-ttu-id="4e54e-106">Ruft eine Meldung mit einer Beschreibung der auftragsplanung Fehler, die für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</span><span class="sxs-lookup"><span data-stu-id="4e54e-106">Gets a message describing the job scheduling error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>