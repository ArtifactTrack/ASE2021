# ASE2021 Artefact Evaluation 

## Details of the Badges

### Available

This badge is applied to papers in which associated artifacts have been made permanently available for retrieval.

We consider temporary drives (e.g., Dropbox, Google Drive) to be non-persistent, same as individual/institutional websites of the submitting authors, as these are prone to changes.
We ask that authors use Zenodo as this service is persistent and also offers the possibility to assign a DOI.
Artifacts do not need to have been formally evaluated in order for an article to receive this badge. In addition, they need not be complete in the sense described above. They simply need to be relevant to the study and add value beyond the text in the article. Such artifacts could be something as simple as the data from which the figures are drawn, or as complex as a complete software system under study.

### Reusable

The artifacts must meet the following requirements.

documented: At minimum, an inventory of artifacts is included, and sufficient description provided to enable the artifacts to be exercised.
consistent: The artifacts are relevant to the associated paper, and contribute in some inherent way to the generation of its main results.
complete: To the extent possible, all components relevant to the paper in question are included. (Proprietary artifacts need not be included. If they are required to exercise the package then this should be documented, along with instructions on how to obtain them. Proxies for proprietary data should be included so as to demonstrate the analysis.)
exercisable: Included scripts and / or software used to generate the results in the associated paper can be successfully executed, and
Authors are strongly encouraged to target their artifact submissions for Reusable as the purpose of artifact badges is, among other things, to facilitate reuse and repurposing, which may not be achieved at the Functional level.

### Reproduced

This badge is applied to papers in which the main results of the paper have been successfully obtained by a person or team other than the original authors of the work, with, at least in part, artifacts provided by the original authors.

Example: If Asha published a paper with artifacts in 2019, and Tim published a replication in 2020 using the artifacts, then Asha can now apply for the Replicated badge on the 2019 paper.

### Replicated

This badge is applied to papers in which the main results of the paper have been successfully obtained by a person or team other than the author, but without any artifacts provided by the original authors.

Example: If Janet published a paper in 2018 with no artifacts, and Miles published a paper with artifacts in 2020 that independently obtained the main result, then Janet can apply for the Reproduced badge on the 2018 paper.



Papers with such badges contain reusable products that other researchers can use to bootstrap their own research. Experience shows that such papers earn increased citations and greater prestige in the research community. Artifacts of interest include (but are not limited to) the following.

Software, which are implementations of systems or algorithms potentially useful in other studies.
Data repositories, which are data (e.g., logging data, system traces, survey raw data) that can be used for multiple software engineering approaches.
Frameworks, which are tools and services illustrating new approaches to software engineering that could be used by other researchers in different contexts.
This list is not exhaustive, so the authors are asked to email the chairs before submitting if their proposed artifact is not on this list.



## Submission

Authors are to our HotCRP website https://ase20201-artifact-evaluation.hotcrp.com

Note that that there are two separate separate submission procedures: - One for available and reusable artifacts - Another for replicated and reproduced badges

### Submission for available and reusable artifacts

All submittors must make their repositories available using the following steps.

Create a Github repo.
Register the repo at Zenodo.org. For details on that process, see https://guides.github.com/activities/citable-code.
Make a release at Github, at which time Zenodo will automatically grab a copy of that repo and issue a Digital Object Identifier (DOI) e.g. https://doi.org/10.5281/zenodo.4308746.
Submit that DOI to us.
Your Github repo should have documentation files explaining how to obtain the artifact package, how to unpack the artifact, how to get started, and how to use the artifacts in sufficient detail. The artifact submission must describe only the technicalities of the artifacts and uses of the artifact that are not already described in the paper. The submission should contain the following documents (in markdown plain text format).

A README.md main file describing what the artifact does and where it can be obtained (with hidden links and access password if necessary).
A LICENSE.md file describing the distribution rights. Note that to score “available” or higher, then that license needs to be some form of open source license.
An INSTALL.md file with installation instructions. These instructions should include notes illustrating a very basic usage example or a method to test the installation. This could be, for instance, information on what output to expect that confirms that the code is installed and working; and that the code is doing something interesting and useful. IMPORTANT, there should be a clear description of how to reproduce the results presented in the paper.
A copy of the accepted paper in pdf format.
Authors may update their research artifacts after submission only for changes requested by reviewers in the rebuttal phase. To update artifacts: (1) Go to Github; (2) Make your changes; (3) Make a new release; (4) Make a comment in HotCrp that “in response to comment XYZ we have made a new release that addresses that issues as follows: ABC”

### Submission for replicated and reproduced badges

Submit a one page (max) pdf documenting the maturity of the artifact. This needs to include:

TITLE: A (Partial)? (Replication|Reproduction) of XYZ. Please add the term partial to your title if only some of the original work could be replicated/reproduced.
WHO: name the original authors (and paper) and the authors that performed the replication/reproduction. Include contact information (emails). Mark one author as the corresponding author.
IMPORTANT: include also a web link to a publically available URL directory containing (a) the original paper (that is being reproduced) and (b) any subsequent paper(s)/documents/reports that do the reproduction.
IMPORTANT: include also a web link to a publically available URL directory containing (a) the original paper (that is being reproduced) and (b) any subsequent paper(s)/documents/reports that do the reproduction.
WHAT: describe the “thing” being replicated/reproduced;
WHY: clearly state why that “thing” is interesting/important;
PLATFORM: being the operating system where this artifact was mostly developed on;
HOW: say how it was done first;
WHERE: describe the replication/reproduction. If the replication/reproduction was only partial, then explain what parts could be achieved or had to be missed.
DISCUSSION: What aspects of this “thing” made it easier/harder to replicate/reproduce. What are the lessons learned from this work that would enable more replication/reproduction in the future for other kinds of tasks or other kinds of research.
Review

The ASE artifact evaluation track uses a single-blind review process. All artifacts will receive two reviews.

Two PC members will review each abstract, possibly reaching out to the authors of the abstract or original paper. Abstracts will be ranked as follows.

If PC members do not find sufficient substantive evidence for replication/reproduction, the abstract will be rejected.
Any abstract that is judged to be unnecessarily critical of prior work will be rejected (*).
The remaining abstracts will be sorted according to (a) interestingness and (b) correctness.
The top ranked abstracts will be invited to give lightning talks.
(*) Our goal is to foster a positive environment that supports and rewards researchers for conducting replications and reproductions. To that end, we require that all abstracts and presentations pay due respect to the work they are reproducing/replicating. Criticism of prior work is acceptable only as part of a balanced and substantive discussion of prior accomplishments.

Note that prior to reviewing, there may be some interactions to handle setup and install. Before the actual evaluation reviewers will check the integrity of the artifact and look for any possible setup problems that may prevent it from being properly evaluated (e.g., corrupted or missing files, VM won’t start, immediate crashes on the simplest example, etc.). The Evaluation Committee may contact the authors to request clarifications on the basic installation and start-up procedures or to resolve simple installation problems. Artifact evaluation can be rejected for artifacts whose configuration and installation takes an undue amount of time.
