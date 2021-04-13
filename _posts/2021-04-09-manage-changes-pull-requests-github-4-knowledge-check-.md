---
    layout: post
    title: Manage repository changes by using pull requests on GitHub 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/manage-changes-pull-requests-github/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/github/manage-changes-pull-requests-github.svg">
####  1. What is not a good reason to create a pull request?


<i class='far fa-square'></i> &nbsp;&nbsp;You would like to receive feedback on prospective changes before merging your feature branch into master.

<i class='far fa-square'></i> &nbsp;&nbsp;You want to merge your bug fix branch into master, but do not have permission.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Your branch cannot be merged into master due to upstream changes made since you created it. Creating a pull request will let the other contributor know they need to pull their changes out so you can put yours in.
<br />
<br />
<br />

####  2. How can you ensure that pull requests for a given area of the repository are not merged unless certain users or teams have approved?


<i class='far fa-square'></i> &nbsp;&nbsp;Clearly explain the pull request policy in CONTRIBUTING.md.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a CODEOWNERS file and enable required reviews.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a table mapping directory paths to required users in SECURITY.md.
<br />
<br />
<br />

####  3. You have been requested to review a pull request. As you read through it, you notice several minor coding errors and typos. How should you handle the review?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Start a review and fix obvious typos inline. Add comments in places that require further discussion or offer educational value. Complete the review with changes requested.

<i class='far fa-square'></i> &nbsp;&nbsp;Leave single comments for each issue you come across, but do not change the code. For typos, include the correct spelling of the word as a reference. Approve the pull request if you trust the author to implement your suggestions.

<i class='far fa-square'></i> &nbsp;&nbsp;Reject the pull request. We can't risk any bugs accidentally being merged into an important branch.
<br />
<br />
<br />
