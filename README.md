# chocolatey-package-requests
Please submit your package requests as issues here

### Terminology

* RFP - Request for Package - this is for packages that do not exist
* RFM - Request for Maintainer(s) - this is for packages that do exist, but need new maintainers

### How To Create a Request

* Search and vote up an existing request or create a new request, using either "RFP - packagename" or "RFM - packagename"
* Explain a bit about the software if you can and possible hopes for what a package would look like

### How To Create Packages for a Request

* Determine there is a package you can pick up.
* Comment on the issue that you would like to pick it up.
* The issue will get labelled as assigned, awaiting approval
* When the package gets approved by the moderation process, close the issue (or ask for it to be closed).

**Note**: If you are taking over maintenance for a package, you also need to be added ot the list of maintainers. Use the contact admins link from the package page, point to the particular issue in this repository, and ask to be added.

### Package Request Status

The package requests repository uses Labels to show the current status of a request (this is heavily influented by user/maintainer feedback).
The main Labels are as follows with the corresponding meaning:

* [Status: Available for maintainer(s)](https://github.com/chocolatey/chocolatey-package-requests/labels/Status%3A%20Available%20For%20Maintainer%28s%29): As the name implies, this request is ready to be picked up by any maintainer that would like to work on creating/updating the request.
  * For new packages *(RFP)*, this means that the request have been accepted as a package that can be hosted on the community repository and the package do not exist.
  * For existing packages *(RFM)*, this means that the repository members have verified that the co-maintainer do not wish to continue working on the package, is unresponsive, and no outstanding questions are needed before handing the package over to a new maintainer.
* [Status: Triage](https://github.com/chocolatey/chocolatey-package-requests/labels/Status%3A%20Triage):
  * For new package *(RFP)*, this label is unlikely to be used, unless a member of the repository have any questions needed to be answered before a maintainer can pick the request up.
  * For existing package *(RFM)*, this label means that the members of the repository have been unable to verify that the [Package Triage](https://chocolatey.org/docs/package-triage-process#the-triage-process) process have been followed, or a repository member have a question before a new maintainer can be added.
* [Status: In Progress](https://github.com/chocolatey/chocolatey-package-requests/labels/Status%3A%20In%20Progress): A user have mentioned that they have started to work on the request, and/or a new maintainer have been added to the existing package.
* [Status: Review](https://github.com/chocolatey/chocolatey-package-requests/labels/Status%3A%20Review): A package for the current request have been submitted to chocolatey.org, and is currently awaiting a review from the chocolatey community moderators.
* [Status: Published](https://github.com/chocolatey/chocolatey-package-requests/labels/Status%3A%20Published): The package for the current request have been approved on the chocolatey community repository, and is now available for everyone to use.
* [Blocked Upstream](https://github.com/chocolatey/chocolatey-package-requests/labels/Blocked%20Upstream): There are known issues that need to be resolved before a package can be created for the current request. (This can be everything from needing to embedd a package for a software that does not grant any distribution rights, download is blocked behind a login form, additional headers needed to be sent with the download request, and more...).
* [Duplicate](https://github.com/chocolatey/chocolatey-package-requests/labels/Duplicate): The current request is a duplicate of a previous open request.
