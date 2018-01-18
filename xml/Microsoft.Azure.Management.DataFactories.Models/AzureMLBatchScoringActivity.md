<Type Name="AzureMLBatchScoringActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchScoringActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchScoringActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchScoringActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLBatchScoringActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLBatchScoring")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b5263-101">Azure ML-Webdienst als batch scoring-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="b5263-101">Azure ML Web Service batch scoring activity.</span></span> <span data-ttu-id="b5263-102">Siehe auch <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" /> für mehr Flexibilität bietet Optionen.</span><span class="sxs-lookup"><span data-stu-id="b5263-102">See also <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" /> for more flexible options.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchScoringActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchScoringActivity (System.Collections.Generic.IDictionary&lt;string,string&gt; webServiceParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; webServiceParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity.#ctor(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (webServiceParameters As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity webServiceParameters" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="webServiceParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="webServiceParameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity.WebServiceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchScoringActivity.WebServiceParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5263-103">Schlüssel-Wert-Paare an die Azure ML-Batch-Ausführung-Dienstendpunkt übergeben werden (diese werden auch als GlobalParameters bezeichnet).</span><span class="sxs-lookup"><span data-stu-id="b5263-103">Key,Value pairs to be passed to the Azure ML Batch Execution Service Endpoint (these are also referred to as GlobalParameters).</span></span> <span data-ttu-id="b5263-104">Schlüssel müssen mit der passenden Namen des Webdiensts in definierten Parameter die Azure ML-Webdienst veröffentlicht.</span><span class="sxs-lookup"><span data-stu-id="b5263-104">Keys must match the names of web service parameters defined in published the Azure ML web service.</span></span> <span data-ttu-id="b5263-105">Werte eventuell ADF-Makros zur Ausführungszeit auf einen einzelnen Slice aufgelöst werden.</span><span class="sxs-lookup"><span data-stu-id="b5263-105">Values may include ADF macros to be resolved at each slice execution time.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>