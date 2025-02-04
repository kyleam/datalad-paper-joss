---
title: 'DataLad: distributed system for joint management of code, data, and their relationship'
tags:
  - Python
  - command line
  - version control
  - data management
  - data distribution
  - data provenance
  - reproducibility
authors:
 - name: Yaroslav O. Halchenko^[co-first author]  # 4655 commits, issues: opened 1399 participated in 649
   orcid: 0000-0003-3456-2493
   affiliation: 1
 - name: Kyle Meyer  # 2152 commits, issues: opened 85 participated in 398
   affiliation: 1
 - name: Benjamin Poldrack  # 1898 commits, issues: opened 82 participated in 461
   orcid: 0000-0001-7628-0801
   affiliation: 2
 - name: Debanjum Singh Solanky  # 212 commits, issues: opened 7 participated in 12
   orcid: 0000-0002-0774-6564
   affiliation: 1
 - name: Adina S. Wagner  # 98 commits, issues: opened 36 participated in 45
   orcid: 0000-0003-2917-3450
   affiliation: 2
 - name: Jason Gors  # 60 commits, issues: opened 2 participated in 1
   affiliation: 1
 - name: Dave MacFarlane  # 30 commits, issues: opened 4 participated in 4
   affiliation: 3 # add full names if not yet listed, or indexes if already are
 - name: Dorian Pustina  # 0 commits, issues: opened 30 participated in 5
   orcid: 0000-0002-2834-7220
   affiliation: 4
 - name: Vanessa Sochat  # 16 commits, issues: opened 8 participated in 4
   orcid: 0000-0002-4387-3819
   affiliation: 5
 - name: Satrajit S. Ghosh  # 0 commits, issues: opened 7 participated in 13
   orcid: 0000-0002-5312-6729
   affiliation:  6
 - name: Christian Mönch  # 11 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-3092-0612
   affiliation:  2
 - name: Christopher J. Markiewicz  # 5 commits, issues: opened 5 participated in 6
   orcid: 0000-0002-6533-164X
   affiliation: 7
 - name: Laura Waite  # 2 commits, issues: opened 11 participated in 2
   orcid: 0000-0003-2213-7465
   affiliation: 2
 - name: Ilya Shlyakhter  # 0 commits, issues: opened 12 participated in 3
   orcid: 0000-0002-9854-5118
   affiliation: 8
 - name: Alejandro de la Vega  # 4 commits, issues: opened 7 participated in 3
   orcid: 0000-0001-9062-3778
   affiliation:  9
 - name: Soichi Hayashi  # 1 commits, issues: opened 10 participated in 1
   orcid: 0000-0003-3641-3491
   affiliation:  10
 - name: Christian Olaf Häusler  # 10 commits, issues: opened 2 participated in 0
   orcid: 0000-0002-0936-317X
   affiliation: "2, 11"
 - name: Jean-Baptiste Poline  # 0 commits, issues: opened 2 participated in 7
   orcid: 0000-0002-9794-749X 
   affiliation: 12
# - name: Taylor Olson  # 7 commits, issues: opened 1 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Chris Gorgolewski  # 0 commits, issues: opened 5 participated in 3
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Simon Dube  # 0 commits, issues: opened 6 participated in 1
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
 - name: Tobias Kadelka  # 0 commits, issues: opened 4 participated in 3
   orcid: 0000-0002-0152-3490
   affiliation: 2
 - name: Kusti Skytén  # 1 commits, issues: opened 4 participated in 1
   orcid: 0000-0001-7460-1157
   affiliation: 13
 - name: Dorota Jarecka  # 0 commits, issues: opened 5 participated in 1
   orcid: 0000-0001-8282-2988
   affiliation: 6
 - name: David Kennedy  # 0 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-9377-0797
   affiliation:  14
 - name: Ted Strauss  # 0 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-1927-666X
   affiliation:  15
# - name: Anisha Keshavan  # 3 commits, issues: opened 1 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Arvind Sharma  # 0 commits, issues: opened 4 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
 - name: Matt Cieslak  # 2 commits, issues: opened 2 participated in 0
   orcid: 0000-0002-1931-4734
   affiliation:  16
 - name: Peter Vavra  # 0 commits, issues: opened 3 participated in 1
   orcid: 0000-0001-8432-5459
   affiliation: 17
 - name: Horea-Ioan Ioanas  # 1 commits, issues: opened 3 participated in 0
   orcid: 0000-0001-7037-2449
   affiliation: 18
 - name: Robin Schneider  # 1 commits, issues: opened 1 participated in 1
   orcid: 0000-0003-1952-5459
   affiliation: 19
 - name: Mika Pflüger  # perspective: https://github.com/datalad/datalad/pull/5592
   orcid: 0000-0002-7814-8916
   affiliation: 20
 - name: Simon B. Eickhoff
   orcid: 0000-0001-6363-2759
   affiliation: "2, 11"
 - name: Michael Hanke^[co-first author]  # 4158 commits, issues: opened 1097 participated in 780
   orcid: 0000-0001-6398-6370
   affiliation: "2, 11"
affiliations:
 - name: Center for Open Neuroscience, Department of Psychological and Brain Sciences, Dartmouth College, Hanover, NH, USA
   index: 1
 - name: Institute of Neuroscience and Medicine, Brain & Behaviour (INM-7), Research Centre Jülich, Jülich, Germany
   index: 2
 - name: McGill Centre for Integrative Neuroscience, Montreal, Canada
   index: 3
 - name: CHDI Management/CHDI Foundation, Princeton, NJ, USA
   index: 4
 - name: Lawrence Livermore National Lab, Livermore, CA, USA
   index: 5
 - name: Massachusetts Institute of Technology, Cambridge, MA, USA
   index: 6
 - name: Stanford University, Stanford, CA, USA
   index: 7
 - name: Quest Diagnostics, Marlborough, MA, USA
   index: 8
 - name: The University of Austin at Austin, Austin, TX, USA
   index: 9
 - name: Indiana University, Bloomington, IN, USA
   index: 10
 - name: Institute of Systems Neuroscience, Medical Faculty, Heinrich Heine University Düsseldorf, Düsseldorf, Germany
   index: 11
 - name: Faculty of Medicine and Health Sciences, McConnell Brain Imaging Centre, McGill University, Montreal, Canada
   index: 12
 - name: University of Oslo, Oslo, Norway
   index: 13
 - name: University of Massachusetts Medical School, Worcester, MA, USA
   index: 14
 - name: Montreal Neurological Institute, McGill University, Montreal, Canada
   index: 15
 - name: University of Pennsylvania, Philadelphia, PA
   index: 16
 - name: Department of Biological Psychology, Otto-von-Guericke-University Magdeburg, Magdeburg, Germany
   index: 17
 - name: Department of Biological Engineering, Massachusetts Institute of Technology, Cambridge, USA
   index: 18
 - name: Independent Developer, Germany
   index: 19
 - name: Potsdam Institute for Climate Impact Research (PIK) e. V., Potsdam, Germany
   index: 20
date: 24 March 2021
bibliography: paper.bib

---

# Summary

DataLad is a Python-based tool for the joint management of code, data, and their relationship, built on top of a versatile system for data logistics ([git-annex](https://git-annex.branchable.com)) and the most popular distributed version control system ([Git](https://git-scm.com)).
It adapts principles of open-source software development and distribution to address the technical challenges of data management, data sharing, and digital provenance collection across the life cycle of digital objects.
DataLad aims to make data management as easy as managing code.
It streamlines procedures to consume, publish, and update data, for data of any size or type, and to link them as precisely versioned, lightweight dependencies.
DataLad helps to make science more reproducible and FAIR [@FAIR2016].
It can capture complete and actionable process provenance of data transformations to enable automatic re-computation.
The DataLad project ([datalad.org](http://datalad.org)) delivers a completely open, pioneering platform for flexible decentralized research data management (RDM) [@Hanke_2021].
It features a Python and a command-line interface, an extensible architecture, and does not depend on any centralized services but facilitates interoperability with a plurality of existing tools and services.
In order to maximize its utility and target audience, DataLad is available for all major operating systems, and can be integrated into established workflows and environments with minimal friction.


# Statement of Need

Code, data and computing environments are core components of scientific projects.
While the collaborative development and use of research software and code is streamlined with established procedures and infrastructures, such as software distributions, distributed version control systems, and social coding portals like GitHub, other components of scientific projects are not as transparently managed or accessible.
Data consumption is complicated by disconnected data portals that require a large variety of different data access and authentication methods.
Compared with code in software development, data tend not to be as precisely identified because data versioning is rarely or only coarsely practiced.
Scientific computation is not reproducible enough, because data provenance, the information of how a digital file came to be, is often incomplete and rarely automatically captured.
Last but not least, in the absence of standardized data *packages*, there is no uniform way to declare actionable data dependencies and derivative relationships between inputs and outputs of a computation.
DataLad aims to solve these issues by providing streamlined, transparent management of code, data, computing environments, and their relationship.
It provides targeted interfaces and interoperability adapters to established scientific and commercial tools and services to set up unobstructed, unified access to all elements of scientific projects.
This unique set of features enables workflows that are particularly suited for reproducible science, such as actionable process provenance capture for arbitrary command execution that affords automatic re-execution.<!-- km: I think this use of "afford", while correct, is likely to throw some readers off -->
To this end, it builds on and extends two established tools for version control and transport logistics, Git and git-annex.

## Why Git and git-annex?

Git is the most popular version control system for software development[^1].
It is a distributed content management system, specifically tuned towards managing and collaborating on text files, and excels at making all committed content reliably and efficiently available to all clones of a repository.
At the same time, Git is not designed to efficiently handle large (e.g., over a gigabyte) or binary files [see, e.g., @opensource:git-binary].
This makes it hard or impossible to use Git directly for distributed data storage with tailored access to individual files.
Git-annex takes advantage of Git's ability to efficiently manage textual information to overcome this limitation.<!-- km: I think this sentence could be dropped. -->
File content handled by git-annex is placed into a managed repository annex, which avoids committing the file content directly to Git.
Instead, git-annex commits a compact reference, typically derived from the checksum of a file's content, that enables identification and association of a file name with the content.
Using these identifiers, git-annex tracks content availability across all repository clones and external resources such as URLs pointing to individual files on the web.
Upon user request, git-annex automatically manages data transport to and from a local repository annex at a granularity of individual files.
With this simple approach, git-annex enables separate and optimized implementations for identification and transport of arbitrarily large files, using an extensible set of protocols, while retaining the distributed nature and compatibility with versatile workflows for versioning and collaboration provided by Git.

[^1]: https://en.wikipedia.org/wiki/Git#Adoption

## What does DataLad add to Git and git-annex?

<!-- MIH thinks: #1 nesting, #2 reproducible execution, #3 additional software adaptors for concrete services relevant for science -->

**Easy to use modularization.**
Research workflows impose additional demands for an efficient research data management platform besides version control and data transport.
Many research datasets contain millions of files, but a large number of files precludes managing such a dataset in a single Git repository, even if the total storage demand is not huge.
Partitioning such datasets into smaller, linked components (e.g., one subdataset per sample in a dataset comprising thousands) allows for scalable management.
Research datasets and projects can also be heterogeneous, comprising different data sources or evolving data across different processing stages, and with different pace.
Beyond scalability, modularization into homogeneous components also enables efficient reuse of a selected subset of datasets and for recording a derivative relationship between datasets.
Git's *submodule* mechanism provides a way to nest individual repositories via unambiguously versioned linkage, but Git operations must still be performed within each individual repository.
To achieve modularity without impeding usability, DataLad simplifies working with the resulting hierarchies of Git repositories via recursive operations across dataset boundaries.
With this, DataLad provides a "mono-repo"-like user experience in datasets with arbitrarily deep nesting, and makes it trivial to operate on individual files deep in the hierarchy or entire trees of datasets.
A testament of this is [datasets.datalad.org](http://datasets.datalad.org), created as the project's initial goal to provide a data distribution with unified access to already available public data archives in neuroscience, such as [crcns.org](http://crcns.org) and [openfmri.org](http://openfmri.org).
It is curated by the DataLad team and provides, at the time of publication, streamlined access to over 260 TBs of data across over 5,000 subdatasets from a wide range of projects and dozens of archives in a fully modularized way.

**Re-executable annotation of changes.**
Digital provenance is crucial for the trustworthiness and reproducibility of a research result, and contributes to the reusability aspect of the FAIR principles [@FAIR2016].
<!-- Git captures provenance by annotating a patch (an exact difference between two versions that could be applied to another version of the text file), with a commit message (a freeform, human-readable text description of the introduced changes). -->
<!-- km: I think the above comes too close to reading as though Git tracks changes/differences directly -->
Knowing which code and data were used is essential, but, for changes that are programmatically introduced, how a command or script was invoked is another key piece of information to capture.
One approach is to include this information in the Git commit message that accompanies a change, but doing so manually is tedious and error prone.
To solve this, DataLad supports executing a command and automatically generating a commit message that includes a structured record with comprehensive details on the invocation.
In addition to providing reliable information about past command-line invocations, these machine-readable records make it possible to easily re-execute commands (e.g., to verify if a result is computationally reproducible or to apply an analog change to a different dataset state).

<!--AW:removed the sentence below as YOH suggested
Such annotation is not sufficient to introduce changes by following the description, if they cannot be completely represented by such a patch. -->
<!-- YOH: may be strip above sentence away... I am just trying to lead somehow into "semantic" description of the change.
  E.g. that if author was very good with the description of change, some smart AI could have redone it following the description
  and not the patch.  The simplest analog could be "replaced word X with Y" where the patch would contain exact difference, but
  either will not be applicable or just would miss some Xs if applied to a vastly different version -->


**Targeted interfaces and interoperability adapters.**
Interoperability with scientific or commercial computing and storage services allows researchers to integrate data management routines into their established workflows with minimal friction.
Git can already interact with other local or remote repositories via standard or custom network transport protocols.
DataLad implements support for additional services that require custom protocols, such as the Open Science Framework (OSF) [@datalad-osf:zenodo].
Git-annex readily provides access to a wide range of external data storage resources via a large set of protocols.
DataLad builds on this support and adds, for example, more fine-grained access (e.g.
direct access to individual components contained in an archive hosted on cloud storage) or specialized services, such as XNAT ([www.xnat.org](http://www.xnat.org)).
Efficient and seamless access to scientific data is implemented using
the *special remote* protocol provided by git-annex [@git-annex:special_remotes_protocol], through which external tools, like DataLad, can provide custom transport functionality transparently to a user.
With this approach, DataLad and other projects can jointly facilitate access to an ever-growing collection of resources [@git-annex:special_remotes] and overcome technological limitations of storage solutions, like file size or inode limits.


# Overview of the DataLad and its ecosystem

## Design principles

Besides the free software nature and open processes of the DataLad project, the development of DataLad is guided by four principles to ensure its open and domain agnostic nature, to maximize the long-term utility of its datasets and to minimize users' technical debt:

- Datasets and the files they comprise are the only two recognized entities
- A dataset is a Git repository with an *optional* annex
- Minimization of custom procedures and data structures
- Complete decentralization, with no required central server or service, but maximum interoperability with existing 3rd-party resources and infrastructure

In conjunction, these principles aim to reduce the risk of adoption for DataLad users. 
They foster the resilience of an ecosystem using DataLad datasets as a standard package format for any digital objects by avoiding any critical dependency on service deployments governed by central entities, and even on DataLad itself, for access to any resources managed with DataLad.

## DataLad core

The `datalad` Python package provides both a Python library and a command line tool which expose core DataLad functionality to fulfill a wide range of decentralized RDM use cases for any domain.
All DataLad commands operate on *DataLad datasets*.
On a technical level, these datasets are Git repositories with additional metadata.
On a conceptual level, they constitute an overlay structure that allows to version control files of any size, track and publish files in a distributed fashion, and record, publish, and execute actionable provenance of files and file transformations.
\autoref{fig:one} summarizes key commands and concepts for local or distributed data and provenance management.

![Schematic overview of a dataset, datasets nesting, and selected commands for content and dataset management. A more comprehensive cheatsheet is provided in the DataLad handbook [@datalad-handbook:cheatsheet]. \label{fig:one}](figures/fig1.png)

DataLad's features can be flexibly integrated into standard scientific workflows.
For example, by using the concept of dataset nesting to modularize the evolution of a research project, DataLad can fulfill the YODA principles for reproducible science [@yoda:myyoda], and, with this simple paradigm, facilitate efficient access, composition, scalability, reuse, sharing, and reproducibility of results (see \autoref{fig:two}).
With core commands that aim to simplify operation of the underlying tools, DataLad makes RDM workflows more accessible to novices and experts alike. Importantly, compatibility with all Git/git-annex functionality is retained.

![DataLad datasets are reusable modular components, which can be nested to establish a complete provenance trail all the way from a publication to the original data. Various access schemes to datasets and data are provided, and further extensibility is a key architectural property.\label{fig:two}](figures/datalad-nesting-access.png)


## Extensions

Like Git and git-annex, DataLad core is a generic tool that is not specifically tuned to particular data types or use cases. It offers a robust foundation to build more specialized solutions on top of.
*DataLad extensions*, stand-alone Python packages with additional DataLad functionality, extend DataLad with domain-focused or technology-specific features.
A dedicated [datalad-extension-template](https://github.com/datalad/datalad-extension-template) repository provides a starting point for creating new DataLad extensions.
Some established extensions include:

- [datalad-container](https://github.com/datalad/datalad-container) [@datalad-container:zenodo] to simplify management and use of Docker and Singularity containers typically containing complete computational environments
- [datalad-crawler](https://github.com/datalad/datalad-crawler) [@datalad-crawler:zenodo] to automate creation and updates of DataLad datasets from external resources
- [datalad-neuroimaging](https://github.com/datalad/datalad-neuroimaging) [@datalad-neuroimaging:zenodo] to provide neuroimaging-specific procedures and metadata extractors
- [datalad-osf](https://github.com/datalad/datalad-osf/) [@datalad-osf:zenodo] to collaborate using DataLad through the Open Science Framework (OSF)

The same mechanism of extensions is used for rapid development of new functionality to later be moved into the core tool (e.g., [datalad-metalad](https://github.com/datalad/datalad-metalad/)).
The [datalad-extensions](https://github.com/datalad/datalad-extensions/) repository provides a list of extensions and continuous integration testing of their released versions against released and development versions of the DataLad core. 


## External uses and integrations

[comment1]: <> (TODO: probably here cite some examples of scientific papers in the wild which used DataLad)

DataLad can be used as an independent tool to access and manage data (see e.g. @Wittkuhn_2021, @datasets:LAAC-LSCP)
or as a core technology behind another tool or a larger platform.
[TemplateFlow](http://templateflow.github.io/) [@Ciric_2021] uses DataLad for the management of neuroimaging templates.
[OpenNeuro](http://openneuro.org) uses DataLad for data logistics with data deposition to a public S3 bucket.
[CONP-PCNO](https://github.com/CONP-PCNO/) adopts aforementioned features for modular composition and nesting to deliver a rich collection of datasets with public or restricted access to data.
[ReproMan](http://reproman.repronim.org) integrates with DataLad to provide version control and data logistics.
[www.datalad.org/integrations.html](https://www.datalad.org/integrations.html) provides a more complete list of DataLad usage and integration with other projects, and @Hanke_2021 provides a systematic depiction of DataLad as a system for decentralized RDM used by a number of projects.


## Documentation

Developer-focused technical documentation at [docs.datalad.org](http://docs.datalad.org), with detailed descriptions of the command line and Python interfaces, is automatically generated from the DataLad core repository.
A comprehensive [handbook](http://handbook.datalad.org) [@datalad-handbook:zenodo] provides user-oriented documentation with an introduction to research data management, and numerous use case descriptions for novice and advanced users of all backgrounds [@datalad-handbook:use-cases].

## Installation

The handbook provides [installation instructions](http://handbook.datalad.org/r.html?install) for all major operating systems.
DataLad releases are distributed through [PyPI](https://pypi.org/project/datalad), [Debian](https://tracker.debian.org/pkg/datalad), [NeuroDebian](http://neuro.debian.net/pkgs/datalad.html), [brew](https://formulae.brew.sh/formula/datalad), and [conda-forge](https://anaconda.org/conda-forge/datalad).
The [datalad-installer](https://github.com/datalad/datalad-installer) (also available from PyPI) streamlines the installation of DataLad and its dependencies, in particular git-annex, across a range of deployment scenarios, such as continuous integration systems, or high-performance computing (HPC) environments.

## Development

DataLad has been developed openly in a public repository ([github.com/datalad/datalad](https://github.com/datalad/datalad)) since its inception in 2013.
At the time of this publication, the repository amassed over 13.5k commits, 2.5k merged PRs, and 2.3k closed (+700 open) issues from over 30 contributors.
Issue tracker, labels, milestones, and pull requests are used to coordinate development.
The development process of DataLad is not isolated from its foundational building blocks.
For every new feature or bug fix the most appropriate software layer is determined to maximize the size of the benefitting user base and, importantly, also the associated developer audience.
This strategy aims to achieve a robust integration with the larger open source software ecosystem, and simultaneously minimize the total technical debt carried solely by the DataLad development team.
Consequently, DataLad development is tightly connected to and involves frequent communication with the git-annex project and its main developer Joey Hess [@git-annex:projects-datalad].
To guarantee robust operation across various deployments, DataLad heavily utilizes continuous integration platforms (Appveyor, GitHub actions, and Travis CI) for testing DataLad core, building and testing git-annex (in a dedicated [github.com/datalad/git-annex](https://github.com/datalad/git-annex)), and integration testing 
with DataLad extensions ([datalad-extensions](https://github.com/datalad/datalad-extensions/)).

## Contributions

DataLad is free and open source software and encourages unconstrained use and reuse in any context.
Therefore, DataLad is released under [DFSG](https://en.wikipedia.org/wiki/Debian_Free_Software_Guidelines)- and [OSI](https://opensource.org/osd)-compliant MIT/Expat license.
License terms for reused components in the code-base are provided in the [COPYING](https://github.com/datalad/datalad/blob/master/COPYING) file.
The project aims to promote contributions rather than detached developments in forks and anyone is highly welcome to contribute to DataLad in any form under these terms.
Technical and procedural guidelines for such contributions can be found in the [CONTRIBUTING.md](https://github.com/datalad/datalad/blob/master/CONTRIBUTING.md) file shipped within DataLad's source repository.
Contributors are acknowledged on the project website, and also credited in the form of co-authorship in the Zenodo-based archival of software releases.
All co-authors of this paper as well as the contributors acknowledged below have added to the project with code- or non-code-based contributions, and we thank past, present, and future contributors of this community for their involvement and work.

[comment2]: <> (# Author Contributions: if desired/needed -- or drop altogether.)
<!-- BEN: Looks like drop to me. Don't see a value in listing number of commits
or whatever metric at a particular point in time.-->

# Conflicts of interest

There are no conflicts to declare.

# Acknowledgements

DataLad development was facilitated by a senior adviser Dr. James V. Haxby (Dartmouth College).
We express our gratitude to Joey Hess for the development and maintenance of git-annex, and for years of productive collaboration with the DataLad team.
We would like to extend our gratitude to 
Joey Zhou,
Matteo Visconti di Oleggio Castello,
John T. Wodder II,
Satya Ortiz-Gagné,
Jörg Stadler,
Andrew Connolly,
John Lee,
Nolan Nichols,
Elizabeth DuPre,
Cécile Madjar,
Gergana Alteva,
Timo Dickscheid,
Alex Waite,
[TODOADD: notable contributors]
for notable contributions to the codebase, bug reports, recommendations, and promotion of DataLad.

DataLad development was made possible thanks to support by 
NSF [1429999](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1429999), 
[1912266](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1912266) 
(PI: Halchenko) and BMBF 01GQ1411, 01GQ1905 (PI: Hanke)
through the [CRCNS](https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=5147) program.
It received significant contributions from ReproNim [1P41EB019936-01A1](https://projectreporter.nih.gov/project_info_details.cfm?aid=8999833&map=y) (PI: Kennedy) and DANDI [5R24MH117295-02](https://projectreporter.nih.gov/project_info_description.cfm?aid=9981835&icde=53349087) (PIs: Ghosh, Halchenko) NIH projects.
It also received contributions from the Canadian Open Neuroscience Platform and the NeuroHub (Co-PI: Poline) projects thanks in part to funding from a Brain Canada Platform Support Grant Competition Award in addition to funds and in-kind support from sponsor organizations, and from the Canada First Research Excellence Fund, awarded through the Healthy Brains, Healthy Lives initiative at McGill University, and the Brain Canada Foundation with support from Health Canada.
This development was supported by the European Regional Development Fund (Project: Center for Behavioral Brain Sciences Magdeburg, Imaging Platform, PI: Hanke), the European Union’s Horizon 2020 research and innovation programme under grant agreements [Human Brain Project (SGA3, H2020-EU.3.1.5.3, grant no. 945539; Co-Investigators: Eickhoff, Hanke)](https://cordis.europa.eu/project/id/945539), and [Virtual Brain Cloud (H2020-EU.3.1.5.3, grant no. 826421; PI: Eickhoff)](https://cordis.europa.eu/project/id/826421), the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under grants [SFB 1451 (431549029; Co-PIs: Eickhoff, Hanke)](https://gepris.dfg.de/gepris/projekt/431549029) and [IRTG 2150 (269953372; Co-PIs: Eickhoff, Hanke)](https://gepris.dfg.de/gepris/projekt/269953372).


# References
