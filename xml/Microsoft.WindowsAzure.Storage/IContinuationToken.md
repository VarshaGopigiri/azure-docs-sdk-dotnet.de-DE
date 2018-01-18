<Type Name="IContinuationToken" FullName="Microsoft.WindowsAzure.Storage.IContinuationToken">
  <TypeSignature Language="C#" Value="public interface IContinuationToken" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContinuationToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IContinuationToken" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContinuationToken" />
  <TypeSignature Language="F#" Value="type IContinuationToken = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3e185-101">Eine für fortsetzungstokentypen erforderliche Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3e185-101">An interface required for continuation token types.</span></span>
            </summary>
    <remarks><span data-ttu-id="3e185-102">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />, und <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> Klassen implementieren die <see cref="T:Microsoft.WindowsAzure.Storage.IContinuationToken" /> Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3e185-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />, <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />, and <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> classes implement the <see cref="T:Microsoft.WindowsAzure.Storage.IContinuationToken" /> interface.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt; TargetLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.StorageLocation&gt; TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IContinuationToken.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLocation As Nullable(Of StorageLocation)" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.IContinuationToken.TargetLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.StorageLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e185-103">Ruft den Speicherort, dem das Token gilt.</span><span class="sxs-lookup"><span data-stu-id="3e185-103">Gets the location that the token applies to.</span></span>
            </summary>
        <value><span data-ttu-id="3e185-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="3e185-104">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>