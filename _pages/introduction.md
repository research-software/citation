---
title: "Research software citation: An introduction"
permalink: "/introduction/"
toc: true
sidebar:
  nav: introduction
---

Today, **software is an integral part of scientific research**. It is
used to, e.g., create, process, and analyze research data, and model and
simulate complex processes.

Despite its critical function for research, however, it is **not
properly embedded in scientific systems of acknowledgement and
reputation**. Across disciplines, journal articles, monographs and other
traditional forms of scholarly output are still the de facto norm of
credit distribution via citation.

The situation has been gradually improving for some forms of research
products - notably research data - as stakeholders acknowledge their
importance for the reproducibility, verifiability and sustainability of
research. Yet, software is often still **neglected as the irreplaceable
link** between hypotheses, (raw) data, and research results and
scientific findings.

Arguably, the scholarly ecosystem as such, or at least its processes for
acknowledging and crediting research efforts in any form, would have to
be transformed into a more ideal state for software to assume its proper
place. But until this can be achieved - if it is possible at all - **the
current system should be leveraged** in order to crete a level(er)
playing field for software in science.

One obvious lever is **software citation**.

The state of software citation
------------------------------

Software citation seems to be hard, and for different reasons.

### 1. Researchers don't know how to reference software

The ways how software is acknowledged in research publications, for
example, is haphazard. Common examples include the following, with
decreasing value in terms of acknowledgement of software (cf. Howison &
Bullard [(2016)](#software-citation-practices)).

-   Citation of a publication describing the software
-   Citation of a user guide
-   Citation of a software project website
-   Including a URL to a software project website in the text
-   Including the name of the software in the text
-   Not including a mention of the software at all

Even the superficially beneficial examples - such as a citation of a
publication describing the software - are not sufficient, as the authors
of the publication may differ from the authors of the software, and
because while software keeps changing, it is impossible to keep software
publications up to date, or to publish something new for each version of
the software.

One main cause for these unsatisfactory citation practices is the
following.

### 2. Software authors don't publish their software in a citation-friendly manner

There are many ways to publish software, and not all of them are
citation-friendly. You can send binaries to colleagues per email,
provide them for download from a project website, tag a specific state
of the source code on a source code repository platform, deploy build
artifacts to a language-specific repository, etc.

These methods, however, aren't usually on par with the digital
publication practices for other scientific publications, where, e.g., a
paper is deposited and given an identifier, such as a DOI, which can be
used to uniquely identify the citation target in a concise and reliable
manner.

Additionally, software authors often fail to visibly provide the
metadata required for suitable citation.

### 3. Software citation metadata is not provided (visibly)

It is easy to cite a book or article, because usually the metadata
needed for citation is part of the artifact itself: Authors are listed
at least with their family names, and in a determined order; The title
of the work is provided as it is a major part of the work's identity;
The time, place of publication are provided, as is any sort of accession
number (such as journal issue and volume numbers) that may be needed to
unambiguously identify a work.

With software, a product name is sometimes all that is easily
recoverable, and perhaps a version identifier.

The above paragraphs, thus, define three key issues for the citation of
research software which need to be solved.

Solutions
---------

Thankfully, the scholarly community is increasingly determined to tackle
these issues, and for some of them, solutions have been found or are
being developed.

### A principles-driven culture change for software citation

The [FORCE11 Software Citation Working
Group](https://www.force11.org/group/software-citation-working-group)
has published a seminal paper, outlining the principles of software
citation in science:

> Smith, Arfon M., Katz, Daniel S., Niemeyer, Kyle E., & FORCE11
> Software Citation Working Group. (2016). Software citation principles.
> *PeerJ Computer Science*, *2*, e86.
> <https://doi.org/10.7717/peerj-cs.86>.

The paper can and should be the baseline for future endeavours in
research software citation, and is a must-read for everyone involved or
interested in the topic. Ideally, it is the starting point for a real
culture change.

### Structured software (citation) metadata

Structured metadata is a reliable foundation for enabling better
software citation. Two projects specifically are developing schemas and
implementations for the provision of software (citation) metadata:

-   [CodeMeta](https://codemeta.github.io/) provides an exchange schema
    for general software metadata, and an implementation in JSON-LD.
-   [Citation File Format](https://citation-file-format.github.io/)
    provides a schema for software citation metadata, and a machine- and
    human-readable (and writable) format, tailored towards software
    citation use cases.

### Workflows for software citation

Increasingly, stakeholders such as repositories, indexers, etc. develop
workflows for the creation, (re-)use, and distribution of software
metadata. Much of this work is linking back to the [FORCE11 Software
Citation Implementation Working
Group](https://www.force11.org/group/software-citation-implementation-working-group),
whose website and [GitHub
site](https://github.com/force11/force11-sciwg) provide a good access
point for tracking and contributing these endeavours.

References
----------

1.  <a name="software-citation-practices"/>Howison, James, & Bullard, Julia. (2016). Software in the
    scientific literature: Problems with seeing, finding, and using
    software mentioned in the biology literature. *Journal of the
    Association for Information Science and Technology*, *67*(9),
    2137--2155.
    <https://doi.org/10.1002/asi.23538>.
