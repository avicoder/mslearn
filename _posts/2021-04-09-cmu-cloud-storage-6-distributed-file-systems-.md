---
    layout: post
    title: Cloud storage overview - Distributed file systems
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-storage/6-distributed-file-systems/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/cloud-storage-overview.svg">
####  1. The Hadoop Distributed File System (HDFS) allows for files to be created only once in its namespace. A file, once written, may not be updated or appended to. What file-sharing semantics does HDFS follow?


<i class='far fa-square'></i> &nbsp;&nbsp;Session semantics

<i class='far fa-square'></i> &nbsp;&nbsp;Atomic transactions

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Immutable semantics

<i class='far fa-square'></i> &nbsp;&nbsp;UNIX semantics
<br />
<br />
<br />

####  2. Dropbox is a cloud service that allows users to store and share files on the cloud. Users can install a client application that automatically syncs files from the user's local file system to the cloud. When a shared file is opened for writing, Dropbox waits for the application to close the file before committing the changes to the cloud. Files can be updated by any client. What file-sharing semantics does Dropbox follow?


<i class='far fa-square'></i> &nbsp;&nbsp;Atomic transactions

<i class='far fa-square'></i> &nbsp;&nbsp;UNIX semantics

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Session semantics

<i class='far fa-square'></i> &nbsp;&nbsp;Immutable semantics
<br />
<br />
<br />
