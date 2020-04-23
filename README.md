# **About This Lab**

This lab walks end users through the process of installing and configuring HashiCorp Vault and two open-source Vault plugins created by Venafi, as well as demonstrates a couple of example use cases.

## **Background**

Issuing a machine identity today, in many organizations, can take DAYS and is often a very manual process. Naturally, that can create bottlenecks for security or PKI teams that are typically dealing with multiple product and/or application developer teams. Manual processes are also prone to human error that could otherwise be avoided by introducing some form of automation. These problems are exacerbated when organizations are using DevOps practices.

DevOps teams are used to speed AND automation, and for good reason. Therefore, they adopt tools like HashiCorp Vault to help them get the machine identities they need to secure their applications as quickly as possible. This is great for the DevOps teams, but can leave Security in the dark. Security teams need the visibility to see ALL the machine identities throughout the organization, and the capability to enforce standard policy over the machine identities that DevOps teams are issuing.

### ***vault-pki-backend-venafi***

This is a Venafi PKI Secrets Engine plugin for HashiCorp Vault that enables certificate enrollment using Venafi machine identity services.

This allows HashiCorp Vault to use Venafi to fulfill certificate requests from any supported CA, while providing the same policy tools that Venafi users expect.

### ***vault-pki-monitor-venafi***

This is a Venafi PKI Monitoring Secrets Engine for HashiCorp Vault that enforces security policy and provides certificate visibility to the enterprise.

This allows HashiCorp Vault to issue certificates using Vault at the almost instantaneous speed that DevOps teams expect, while still providing the security teams the control and visibility they require.

---

## **Accessing the Lab Environment**

You should have received lab access directly from the CloudShare platform. The lab environment will be valid for two weeks and will automatically be shut down after that time. If you require additional lab time, please reach out to paul.cleary@venafi.com.

The environment supports working directly in the browser or utilizing SSH/RDP if preferred. The credentials can be found at the beginning of this document as well as in the left-hand navigation pane of the CloudShare GUI.
