---
title: "Research software citation for researchers"
permalink: "/researchers/"
toc: true
sidebar:
  nav: researchers
---

As a researcher, you may be unsure about the right way to cite a
software that you have used for your research which you are preparing
for publication.[^1]
f
As a matter of fact, the citation of software in scientific publications
is hard, as it is far less standardized than that of, say, journal
articles.

You may ask yourself *what* exactly you should give as a reference in
this context. Is mentioning the software name enough? Should you add the
URL to the software website, if it exists? Or to the source code
repository, if you know where to find it? Is it sufficient to cite a
manual? And what about the exact version of the software you have
actually used?

Also, you will most likely be faced with the task of finding the
location of the necessary *metadata* to create your reference in a
specific format.

The following two sections will hopefully help you with both issues.

How to cite software "correctly"
--------------------------------

There is in fact a community-developed set of best practices for citing
software in your research. It has been defined in a paper:

> Smith, Arfon M., Katz, Daniel S., Niemeyer, Kyle E., & FORCE11
> Software Citation Working Group. (2016). Software citation principles.
> *PeerJ Computer Science*, *2*, e86.
> <https://doi.org/10.7717/peerj-cs.86>.

You can always refer to that paper and extract the specific suggestions
for your use case, but to provide a shortcut, the following is a digest
of the principles[^2] that should guide you in
citing a software in your research publication.

### Software should be cited on the same basis as any other research product

-   Add a reference to the software to your list of references, and cite
    it in the text as you would cite other work, such as a book or
    journal paper.

### Cite the software itself

This may sound obvious, but is important to stress.

-   Cite the software itself under all circumstances.
-   If there is a paper or other publication about the software that is
    important to your work, cite that as well, but also cite the
    software product.
-   If the authors of a software request that you cite a software paper,
    cite it, but also cite the software product.

### Cite the exact version of the software

-   If you have a version identifier (e.g., a version number) for the
    software you have used, cite that and include the version number in
    the reference.
-   If you don't have a version identifier, cite the software project as
    such.

### Cite the software using its unique identifier

Software, just like any other research product, can be given a unique
identifier, such as a DOI.

-   If you have a unique identifier for a software, include it in the
    reference if you would do so for other research products as well
    (paper, books, etc.).
-   If a software does not have a DOI or other unique identifier,
    include its version identifier (e.g., a version number) and the URL
    of its origin (i.e., the source code repository; or -- less ideal --
    its artifact repository, or download page) in the reference.
-   If you don't have a version identifier for the software, you could
    provide a commit hash or revision number and the repository URL.

### Cite the source code

-   When software is accessible as both source code and another type --
    an executable, a container, a virtual machine -- cite the source
    code.

### Cite the authors of the software

Research products have authors, and software is no different. In order
to enable fair distribution of credit and acknowledgement, make sure
that your reference includes the authors of the software, just like for
any other research product you are citing.

-   Include the authors of the software in your reference.

### Cite the release date of the software

A software's release date is the equivalence to a book's or journal's
publication date, so it should be included in the citation.

-   Include the release date of the software in your reference.

Where to find the respective metadata
-------------------------------------

Metadata for software citation may be hard to find, but if the authors
followed best practices you should be able to find them in one of the
following places.

### CITATION file

-   Look for a file called `CITATION.cff` in the
    root folder of the source code repository, or in the installation
    folder of the software itself. The [Citation File
    Format](http://citation-file-format.github.io/) is easy to read, so
    you should be able to extract the necessary metadata without
    problems. Additionally, it is modeled based on the *Software
    citation principles* [(Smith et al., 2016)](#principles) and
    requires the minimally necessary set of metadata by design.
-   If there is no such file, look for a file called
    `CITATION` with any other file extension in the
    root folder of the source code repository, or in the installation
    folder of the software itself. These files will often contain a
    plain-text description of how the software authors request the
    software to be cited, sometimes with a BibTeX snippet included.

### Metadata file

-   Look for a file called `codemeta.json` in the
    root folder of the source code repository, or in the installation
    folder of the software itself. It will contain general metadata for
    the software, and you should be able to extract the useful data for
    citation.

### Other sources

-   Open the *About* dialog in the software itself, if it has a
    graphical user interface. It can usually be found in the main menu
    under *Help*, or in a *Help* section.
-   Look at the arguments for the software if it has a command line
    client. It may have an argument dedicated to citation (e.g.,
    `software --cite`) or a dedicated section in its
    help output (e.g., `software --help`).

References
----------

1.  Smith, Arfon M., Katz, Daniel S., Niemeyer, Kyle E., & FORCE11
    Software Citation Working Group. (2016). Software citation
    principles. *PeerJ Computer Science*, *2*, e86.
    <https://doi.org/10.7717/peerj-cs.86>.

[^1]: If you wonder more generally whether you *should* cite a specific
    software, please refer to
    [*shouldacite*](https://mr-c.github.io/shouldacite/index.html),
    which will provide you with the right
    answer!
    
[^2]: The following sections include exact quotes of the paper, which are,
    however, not marked as such, for reasons of readability. Please
    refer to the paper itself should you want to cite content from
    section [*How to cite software
    "correctly"*](#how-to-cite-software-correctly) to make sure that you
    are citing correctly.