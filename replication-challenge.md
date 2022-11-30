# Replication Challenge

## Goals

The Replication Challenge starts with a reproduced article, or an attempt to reproduce an article. It then proposes an enhancement or improvement, in line with the [ACRE Guide list of Improvements](https://bitss.github.io/ACRE/improvements.html)

## Acceptance to start

The first step is an accepted reproducibility report. The report will be reviewed to ensure that failure to reproduce is not due to replicator error, but rather is a fact in the original package. The reproducibility report will be made public.

## Acceptance of final deliverable

The final deliverable should satisfy certain criteria in order to be eligible for the final payment of the Challenge:

- at a minimum, the replication should be push-button reproducible. It should have a single controller file (`main.do`, `principal.py`, etc.) driving the analysis.
  - an exception is when data needs to be downloaded. This should be clear to the replicator. For internal assessment, the data should be provided to  Marie and Lars (Dropbox, Drive, capsules)
- the replication package should have a README, separate from the original authors' README, detailing the necessary steps, and the changes and enhancements made
  - Referencing a Git log or similar for the changes is acceptable. A summary of the changes should be provided.
- the changes made to the replication package should be tracked in a Github repository
  - the Github repository can remain private until the end of the project
  - you should add users `larsvilhuber` and `marieconnolly` as "Readers" of your repository
  - > The maintenance of the Github repository is not required of those replicating an RDC project
- the replication package should be deposited in a public repository (Dataverse, CodeOcean, Zenodo are acceptable as well), with a public license no more restrictive than the original authors' license.
  - For users of WholeTale, exporting to Dataverse or Zenodo is the way to go.

The Replication Challenge Team (Lars, Marie, Abel) will assist replicators to achieve this outcome, see timeline.

## Process and timeline

We will meet once a month to keep everybody on track, and to provide guidance (and in some cases, tutorials). A tentative timeline is shown below. All meetings will be on Zoom, unless otherwise indicated.

### 30 June 2022

No meeting. Please submit the reproducibility check (based on REPLICATION.md) for the chosen article (or designate one that you have already uploaded), and provide a brief description of your plan to improve on the  existing replication package. Refer to the possible [paths to improve on a replication package at ACRE](https://bitss.github.io/ACRE/improvements.html).

### 15 July 2022

No meeting. Lars and Marie will confirm that the proposed project of improvement is acceptable. Once you have received this approval, you are ready to start on the improvement part.

### 1 September  2022: 13h00 - 14h00

We will all meet and assess everybody's progress. At this meeting, you should be prepared to

- briefly describe what you have done (a draft report is encouraged)
- briefly describe any difficulties you may have run into, and any with which we can help.

Tutorial (optional, as needed)

- After the status update, we will provide a brief tutorial and debug session on maintaining a Github repository.


### 3 October 2022 10h00-11h00

At this time, we want to see additional progress, but we will also take the time to talk about how to best share and structure the improved replication package.  At this meeting, you should be prepared to


- briefly describe what you have done (a draft report is **required**, and should be available within the Github repository)
- briefly describe any difficulties you may have run into, and any with which we can help.


Tutorial (optional, as needed)

- After the status update, we will provide a brief tutorial on how to create releases on Github, and how to publish releases from Github to Dataverse or Zenodo.
  - Follow-up: the tutorial was about how to use Github to convey the necessary information. [Notes](https://github.com/larsvilhuber/reproduction-105683-sp3-dwxhg9/blob/lars/NOTES.md). Participants were emailed a link to a recording. Others should contact Marie if they want to watch the tutorial.

### 1 November 2022 9h30-10h30

At this time, you should be close to wrapping up the replication challenge. At this meeting, you should be prepared to

- describe what you have done (a draft report is **required**, and should be available within the Github repository. It should be near final.)
- RDC replicators should be ready to package up their code in a format amenable for release by Statistics Canada. This includes having a confidentialized (reduced) report.


Tutorial (optional, as needed)

- After the status update, we will provide a brief tutorial on how to record the replication on the [SSRP](https://www.socialsciencereproduction.org/).

### 30 November 2022 9h30-10h30

At this time, you should be ready to wrap up the replication challenge. At this meeting, you should be prepared to

- Present a releasable draft report (should be available within the Github repository). At this meeting, we will hope to be able to sign-off on the report. 
- You should have "pre-release" on Github, tagging the state of the code
- You should understand how to publish the package to Dataverse or Zenodo
  - You should not yet do that. We will do it during/after the meeting.
- RDC replicators should have packaged up their code in a format amenable for release by Statistics Canada, and should be ready to submit it. 

### 15 December 2022

No meeting. Lars and/or Marie will have reviewed all the reports and packages, and will sign off. The Challenge will have been succesful. 
