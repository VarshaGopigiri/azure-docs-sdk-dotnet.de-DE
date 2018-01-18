<Type Name="TestErrorEvent" FullName="System.Fabric.Chaos.DataStructures.TestErrorEvent">
  <TypeSignature Language="C#" Value="public sealed class TestErrorEvent : System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit TestErrorEvent extends System.Fabric.Chaos.DataStructures.ChaosEvent" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.TestErrorEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TestErrorEvent&#xA;Inherits ChaosEvent" />
  <TypeSignature Language="F#" Value="type TestErrorEvent = class&#xA;    inherit ChaosEvent" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Chaos.DataStructures.ChaosEvent</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="868b4-101">Stellt das Chaos-Ereignis, das erstellt wird, wenn im Chaos Ausführung des Tests ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="868b4-101">Represents the Chaos event that is created when a failure happens in Chaos test execution.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.TestErrorEvent.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="testErrorEvent.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br"><span data-ttu-id="868b4-102">Ein BinaryReader-Objekt</span><span class="sxs-lookup"><span data-stu-id="868b4-102">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="868b4-103">Liest den Status dieses Objekts aus Bytearray.</span><span class="sxs-lookup"><span data-stu-id="868b4-103">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException"><span data-ttu-id="868b4-104">Das Ende des Streams erreicht ist.</span><span class="sxs-lookup"><span data-stu-id="868b4-104">The end of the stream is reached.</span></span> </exception>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="868b4-105">Ein E/A-Fehler tritt auf.</span><span class="sxs-lookup"><span data-stu-id="868b4-105">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.TestErrorEvent.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string" Usage="System.Fabric.Chaos.DataStructures.TestErrorEvent.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="868b4-106">Ruft die Zeichenfolgendarstellung der Grund für den Validierungsfehler ab</span><span class="sxs-lookup"><span data-stu-id="868b4-106">Gets the string representation of the reason for the validation failure</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.TestErrorEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="testErrorEvent.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="868b4-107">Ruft eine Zeichenfolgendarstellung eines Test Error-Ereignis ab.</span><span class="sxs-lookup"><span data-stu-id="868b4-107">Gets a string representation of the test error event.</span></span>
            </summary>
        <returns><span data-ttu-id="868b4-108">Eine Zeichenfolgendarstellung eines Test Error-Ereignis.</span><span class="sxs-lookup"><span data-stu-id="868b4-108">A string representation of the test error event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.TestErrorEvent.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="testErrorEvent.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw"><span data-ttu-id="868b4-109">Ein BinaryWriter-Objekt.</span><span class="sxs-lookup"><span data-stu-id="868b4-109">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="868b4-110">Schreibt den Status dieses Objekts in ein Bytearray.</span><span class="sxs-lookup"><span data-stu-id="868b4-110">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="868b4-111">Ein E/A-Fehler tritt auf.</span><span class="sxs-lookup"><span data-stu-id="868b4-111">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
  </Members>
</Type>