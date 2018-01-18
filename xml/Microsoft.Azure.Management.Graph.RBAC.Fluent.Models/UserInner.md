<Type Name="UserInner" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner">
  <TypeSignature Language="C#" Value="public class UserInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner" />
  <TypeSignature Language="VB.NET" Value="Public Class UserInner" />
  <TypeSignature Language="F#" Value="type UserInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3bed5-101">Active Directory-Benutzerinformationen.</span><span class="sxs-lookup"><span data-stu-id="3bed5-101">Active Directory user information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-102">Initialisiert eine neue Instanz der UserInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3bed5-102">Initializes a new instance of the UserInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInner (string objectId = null, string objectType = null, string userPrincipalName = null, string displayName = null, string signInName = null, string mail = null, string mailNickname = null, string usageLocation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string objectId, string objectType, string userPrincipalName, string displayName, string signInName, string mail, string mailNickname, string usageLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional objectId As String = null, Optional objectType As String = null, Optional userPrincipalName As String = null, Optional displayName As String = null, Optional signInName As String = null, Optional mail As String = null, Optional mailNickname As String = null, Optional usageLocation As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner (objectId, objectType, userPrincipalName, displayName, signInName, mail, mailNickname, usageLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="objectType" Type="System.String" />
        <Parameter Name="userPrincipalName" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="signInName" Type="System.String" />
        <Parameter Name="mail" Type="System.String" />
        <Parameter Name="mailNickname" Type="System.String" />
        <Parameter Name="usageLocation" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="objectId">To be added.</param>
        <param name="objectType">To be added.</param>
        <param name="userPrincipalName">To be added.</param>
        <param name="displayName">To be added.</param>
        <param name="signInName">To be added.</param>
        <param name="mail">To be added.</param>
        <param name="mailNickname">To be added.</param>
        <param name="usageLocation">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-103">Ruft ab oder legt den Anzeigenamen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="3bed5-103">Gets or sets the display name of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mail">
      <MemberSignature Language="C#" Value="public string Mail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Mail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.Mail" />
      <MemberSignature Language="VB.NET" Value="Public Property Mail As String" />
      <MemberSignature Language="F#" Value="member this.Mail : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.Mail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-104">Ruft ab oder legt die primäre e-Mail-Adresse des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="3bed5-104">Gets or sets the primary email address of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MailNickname">
      <MemberSignature Language="C#" Value="public string MailNickname { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MailNickname" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.MailNickname" />
      <MemberSignature Language="VB.NET" Value="Public Property MailNickname As String" />
      <MemberSignature Language="F#" Value="member this.MailNickname : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.MailNickname" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mailNickname")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-105">Ruft ab oder legt die e-Mail-Alias für den Benutzer.</span><span class="sxs-lookup"><span data-stu-id="3bed5-105">Gets or sets the mail alias for the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-106">Ruft ab oder legt die Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="3bed5-106">Gets or sets the object ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectType">
      <MemberSignature Language="C#" Value="public string ObjectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.ObjectType" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectType As String" />
      <MemberSignature Language="F#" Value="member this.ObjectType : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.ObjectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-107">Ruft ab oder legt den Objekttyp fest.</span><span class="sxs-lookup"><span data-stu-id="3bed5-107">Gets or sets the object type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignInName">
      <MemberSignature Language="C#" Value="public string SignInName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SignInName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.SignInName" />
      <MemberSignature Language="VB.NET" Value="Public Property SignInName As String" />
      <MemberSignature Language="F#" Value="member this.SignInName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.SignInName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="signInName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-108">Ruft ab oder legt den Anmeldenamen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="3bed5-108">Gets or sets the sign-in name of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageLocation">
      <MemberSignature Language="C#" Value="public string UsageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.UsageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property UsageLocation As String" />
      <MemberSignature Language="F#" Value="member this.UsageLocation : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.UsageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserPrincipalName">
      <MemberSignature Language="C#" Value="public string UserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.UserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.UserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner.UserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bed5-109">Ruft ab oder legt den Prinzipalnamen des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="3bed5-109">Gets or sets the principal name of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>