---
    layout: post
    title: Manage Application Configuration and Secrets in Azure Kubernetes Service (AKS) - Understand Kubernetes Secrets
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-secrets-configure-app/4-concept-configmaps/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aks-secrets-configure-app.svg">
####  1. Why should we use ConfigMaps?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To decouple our configuration from our application.

<i class='far fa-square'></i> &nbsp;&nbsp;To map configuration so it's easily accessible.

<i class='far fa-square'></i> &nbsp;&nbsp;To avoid losing data.
<br />
<br />
<br />

####  2. How can you use ConfigMaps in an application?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Injecting them into variables or mounting them into the filesystem.

<i class='far fa-square'></i> &nbsp;&nbsp;As an API accessed by the container inside the pod.

<i class='far fa-square'></i> &nbsp;&nbsp;Only through kubectl.
<br />
<br />
<br />

####  3. Is the namespace a limitation for ConfigMaps?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes, the ConfigMap and the pod that's using it need to be in the same namespace.

<i class='far fa-square'></i> &nbsp;&nbsp;No, ConfigMaps are cluster-wide.

<i class='far fa-square'></i> &nbsp;&nbsp;ConfigMaps are not part of any namespace.
<br />
<br />
<br />
