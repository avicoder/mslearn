---
    layout: post
    title: Work with Data in Azure Machine Learning 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-data-in-aml/6a-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-with-data-in-aml-badge.svg">
####  1. You have a reference to a Workspace named ws. Which code retrieves the default datastore for the workspace?


<i class='far fa-square'></i> &nbsp;&nbsp;default_ds = Datastore.get(ws, 'default')

<i class='far fa-square'></i> &nbsp;&nbsp;default_ds = ws.Datastores[0]

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;default_ds = ws.get_default_datastore()
<br />
<br />
<br />

####  2. A datastore contains a CSV file of structured data that you want to use as a Pandas dataframe. Which kind of object should you create to make it easy to do this?


<i class='far fa-square'></i> &nbsp;&nbsp;A datastore.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A tabular dataset.

<i class='far fa-square'></i> &nbsp;&nbsp;A file dataset.
<br />
<br />
<br />

####  3. You want a script to stream data directly from a file dataset. Which mode should you use?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;as_mount()

<i class='far fa-square'></i> &nbsp;&nbsp;as_download()

<i class='far fa-square'></i> &nbsp;&nbsp;as_upload()
<br />
<br />
<br />
