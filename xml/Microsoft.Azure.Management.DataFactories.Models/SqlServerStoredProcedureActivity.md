<Type Name="SqlServerStoredProcedureActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity">
  <TypeSignature Language="C#" Value="public class SqlServerStoredProcedureActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlServerStoredProcedureActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlServerStoredProcedureActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type SqlServerStoredProcedureActivity = class&#xA;    inherit ActivityTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("SqlServerStoredProcedure")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0732f-101">Gespeicherte SQL-Prozedur-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="0732f-101">SQL Stored Procedure activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlServerStoredProcedureActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.#ctor" />
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
      <MemberSignature Language="C#" Value="public SqlServerStoredProcedureActivity (string storedProcedureName, System.Collections.Generic.IDictionary&lt;string,string&gt; storedProcedureActivityParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storedProcedureName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; storedProcedureActivityParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storedProcedureName As String, Optional storedProcedureActivityParameters As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity (storedProcedureName, storedProcedureActivityParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storedProcedureName" Type="System.String" />
        <Parameter Name="storedProcedureActivityParameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="storedProcedureName">To be added.</param>
        <param name="storedProcedureActivityParameters">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureName">
      <MemberSignature Language="C#" Value="public string StoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.StoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureName As String" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.StoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0732f-102">Name der gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="0732f-102">Stored Procedure Name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProcedureParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; StoredProcedureParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; StoredProcedureParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.StoredProcedureParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property StoredProcedureParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.StoredProcedureParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SqlServerStoredProcedureActivity.StoredProcedureParameters" />
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
            <span data-ttu-id="0732f-103">Vom Benutzer angegebener Eigenschaftensammlung, die in der gespeicherten Prozedur verwendet.</span><span class="sxs-lookup"><span data-stu-id="0732f-103">User specified property bag used in Stored Procedure.</span></span> <span data-ttu-id="0732f-104">Es gibt keine Einschränkung für den Schlüssel oder Werte, die verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="0732f-104">There is no restriction on the keys or values that can be used.</span></span> <span data-ttu-id="0732f-105">Benutzer muss zu nutzen und interpretieren entsprechend den Inhalt in ihren benutzerdefinierten gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="0732f-105">User needs to consume and interpret the content accordingly in their customized Stored Procedure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>