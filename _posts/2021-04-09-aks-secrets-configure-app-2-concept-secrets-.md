---
    layout: post
    title: Manage Application Configuration and Secrets in Azure Kubernetes Service (AKS) - Understand Kubernetes Secrets
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-secrets-configure-app/2-concept-secrets/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aks-secrets-configure-app.svg">
####  1. Why are Kubernetes Secrets safer than plain text values?


<i class='far fa-square'></i> &nbsp;&nbsp;Because they encrypt the data.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;They don't let sensitive information open to all users, concealing them in a workload.

<i class='far fa-square'></i> &nbsp;&nbsp;They store the information elsewhere.
<br />
<br />
<br />

####  2. How can you use Secrets in an application?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Injecting them into variables or mounting them into the filesystem.

<i class='far fa-square'></i> &nbsp;&nbsp;As an API accessed by the container inside the pod.

<i class='far fa-square'></i> &nbsp;&nbsp;Only through kubectl.
<br />
<br />
<br />

####  3. How is base64 used in secrets?


<i class='far fa-square'></i> &nbsp;&nbsp;Secrets can be created using base64 encoding or plain text, but are always mounted as plain text.

<i class='far fa-square'></i> &nbsp;&nbsp;Secrets can only be created using base64 encoding, and are always mounted as base64 encoded.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Secrets can be created using base64 encoding or plain text, but are always mounted as base64.
<br />
<br />
<br />
