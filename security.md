# Security and privacy
To us, nothing has a higher priority than security and privacy. We have laid out Serverauditor's infrastructure in such a way that security risks are minimized. This chapter reviews our major concerns and how we've addressed them.

## Data encryption
Sensitive user data such as hosts, port forwarding, keys, and so on **are encrypted** on the client-side, before being stored locally. The encryption being used on Android is AES-256 and ‘[industry-standard encryption techniques](https://support.apple.com/en-us/HT202303)’ on iOS. 

## Secure cloud
In case you have a premium account, user data will be synchronized with all your devices. To do so, we use our own **Zero-knowledge data storage**. Before synchronization, **all data will be encrypted** on the client side, using AES-256 and your personal master password. Only encrypted data is being synchronized with our Servers, and neither the SecretKey nor your master password is stored on our servers.

The Serverauditor's Servers are hosted through [AWS](https://aws.amazon.com/what-is-cloud-computing/), momentarily the most reliable cloud ecosystem available. 

## Assurance programs
Security *of* the cloud is managed by Amazon, while we manage the security *in* the cloud. Severauditor applies the [AWS Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/?nc1=h_ls). That means that **your data is protected both against both external and internal threats**.   

To ensure top level security we participate in competent [assurance programs](https://aws.amazon.com/compliance/pci-data-privacy-protection-hipaa-soc-fedramp-faqs/).

## Non-disclosure and privacy policies
Private in the cloud. We ***do not*** provide any kind of information about any user account to any third party. Furthermore, it is **impossible to access any data unauthenticated**, not by us, neither by you nor by  any organization or government.

For more information, please see our [Privacy Policy](https://serverauditor.com/privacy_policy.html).
 [programs](http://aws.amazon.com/ru/compliance/)