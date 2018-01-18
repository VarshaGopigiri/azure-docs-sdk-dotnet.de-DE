<Type Name="TransferStatus" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus">
  <TypeSignature Language="C#" Value="public sealed class TransferStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TransferStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TransferStatus" />
  <TypeSignature Language="F#" Value="type TransferStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="00dfd-101">Übertragungsstatus</span><span class="sxs-lookup"><span data-stu-id="00dfd-101">Transfer status</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00dfd-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00dfd-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferStatus (long bytesTransferred, long numberOfFilesTransferred, long numberOfFilesSkipped, long numberOfFilesFailed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 bytesTransferred, int64 numberOfFilesTransferred, int64 numberOfFilesSkipped, int64 numberOfFilesFailed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.#ctor(System.Int64,System.Int64,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (bytesTransferred As Long, numberOfFilesTransferred As Long, numberOfFilesSkipped As Long, numberOfFilesFailed As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus : int64 * int64 * int64 * int64 -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus (bytesTransferred, numberOfFilesTransferred, numberOfFilesSkipped, numberOfFilesFailed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bytesTransferred" Type="System.Int64" />
        <Parameter Name="numberOfFilesTransferred" Type="System.Int64" />
        <Parameter Name="numberOfFilesSkipped" Type="System.Int64" />
        <Parameter Name="numberOfFilesFailed" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="bytesTransferred"><span data-ttu-id="00dfd-103">Anzahl der Bytes, die übertragen wurden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-103">Number of bytes that have been transferred.</span></span></param>
        <param name="numberOfFilesTransferred"><span data-ttu-id="00dfd-104">Die Anzahl der Dateien, die übertragen wurden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-104">Number of files that have been transferred.</span></span></param>
        <param name="numberOfFilesSkipped"><span data-ttu-id="00dfd-105">Die Anzahl der Dateien, die übersprungen werden, damit Sie übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-105">Number of files that are skipped to be transferred.</span></span></param>
        <param name="numberOfFilesFailed"><span data-ttu-id="00dfd-106">Die Anzahl der Dateien, die fehlerhaft sind, übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-106">Number of files that are failed to be transferred.</span></span></param>
        <summary>
            <span data-ttu-id="00dfd-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00dfd-107">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesTransferred">
      <MemberSignature Language="C#" Value="public long BytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.BytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BytesTransferred As Long" />
      <MemberSignature Language="F#" Value="member this.BytesTransferred : int64" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.BytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00dfd-108">Ruft die Anzahl der Bytes, die übertragen wurden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-108">Gets the number of bytes that have been transferred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfFilesFailed">
      <MemberSignature Language="C#" Value="public long NumberOfFilesFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumberOfFilesFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfFilesFailed As Long" />
      <MemberSignature Language="F#" Value="member this.NumberOfFilesFailed : int64" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00dfd-109">Ruft die Anzahl der Dateien, die fehlerhaft sind, übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-109">Gets the number of files that are failed to be transferred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfFilesSkipped">
      <MemberSignature Language="C#" Value="public long NumberOfFilesSkipped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumberOfFilesSkipped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesSkipped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfFilesSkipped As Long" />
      <MemberSignature Language="F#" Value="member this.NumberOfFilesSkipped : int64" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesSkipped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00dfd-110">Ruft die Anzahl der Dateien, die übersprungen werden, damit Sie übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-110">Gets the number of files that are skipped to be transferred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfFilesTransferred">
      <MemberSignature Language="C#" Value="public long NumberOfFilesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumberOfFilesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfFilesTransferred As Long" />
      <MemberSignature Language="F#" Value="member this.NumberOfFilesTransferred : int64" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus.NumberOfFilesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00dfd-111">Ruft die Anzahl der Dateien, die übertragen wurden.</span><span class="sxs-lookup"><span data-stu-id="00dfd-111">Gets the number of files that have been transferred.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>