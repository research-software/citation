---
title: "Research Software Citation:<br/>Cite and Make Citable"
permalink: "/"
sidebar:
  nav: index
layout: splash
header:
  overlay_color: "#642c8f"
  overlay_filter: "0.5"
  overlay_image: /assets/images/citable.jpg
  caption: "Photo: [**K. Förstner**](https://www.flickr.com/photos/konradfoerstner/40914663482/)"
excerpt: >- # this means to ignore newlines until "intro:"
  **Software is an important research product.**  

  It should be **cited** like all other scientific products.
intro: 
  - excerpt: >- #
      Version 1.0 -- 2018-02-16  

      Contributors: [Stephan Druskat](https://orcid.org/0000-0003-4925-7248), [Michael R. Crusoe](https://orcid.org/0000-0002-2961-9670)
feature_row:
  - image_path: /assets/images/intro-img.jpg
    alt: "Photo of an empty blackboard next to a light bulb"
    title: "Citation of research software: An introduction"
    excerpt: "What is the state of research software citation, and what solutions are out there?"
    url: "/introduction/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/res-img.jpg
    alt: "Photo of a magnifying glass showing over a text showing the words science and technology"
    title: "Research software citation for researchers"
    excerpt: "Find out how to cite software correctly in your publication."
    url: "/researchers/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/dev-img.jpg
    alt: "Photo of binary numbers on a screen"
    title: "Research software citation for software developers"
    excerpt: "Find out how to make sure that your software can be cited, and cited correctly."
    url: "/developers/"
    btn_label: "Read More"
    btn_class: "btn--primary"
sidebar:
  nav: index
---

{% include feature_row id="intro" type="center" %}

**Software is an important research product.**  
It should be **cited** like all other scientific products.

The following guides help researchers understand present issues and cite
research software correctly in their publications. They also present
authors of research software with tools that can help ensure their
software can be cited in a way that follows best practices.

Researchers and software developers aren't the only stakeholders in
research software citation, and thus the list below will be extended to
include others as well, such as repositories, funders, indexers, etc. If
you're keen to see guides for these parties sooner rather than later,
please consider [contributing them](#contributions).



Guides
------

{% include feature_row %}

Further resources
-----------------

### Communities working on research software citation solutions

-   The [FORCE11 Software Citation Implementation Working
    Group](https://www.force11.org/group/software-citation-implementation-working-group)
    -- successor of the [FORCE11 Software Citation Working
    Group](https://www.force11.org/group/software-citation-working-group)
    -- works on implementations of software citation workflows.
-   The [WSSSPE community](http://wssspe.researchcomputing.org.uk/)
    (*Working Towards Sustainable Software for Science: Practice and
    Experiences*) is working on research software sustainability, and
    software citation is an important part of it.

### Projects

-   The [Citation File Format](https://citation-file-format.github.io/)
    is a machine- and human-readable and -writable format for software
    citation metadata files.
-   The [CodeMeta](https://codemeta.github.io/) project provides
    compatibility information across software metadata formats via a
    crosswalk table, and a minimal schema for software metadata,
    complete with an implementation in JSON-LD.
-   The [Zenodo](https://zenodo.org/) repository accepts research
    products of all kinds -- including software -- and provides DOIs for
    artifacts, making research products sustainable.
-   The [figshare](https://figshare.com/) repository also accepts source
    code and binaries and provides DOIs for them.
-   [CiteAs](https://citeas.org/) retrieves citation information for
    different types of research products, including software.
-   [shouldacite](https://mr-c.github.io/shouldacite/) offers guidance
    on whether a specific software should be cited and provides further
    pointers as to how to cite and get cited.

### Publications

-   Smith, Arfon M., Katz, Daniel S., Niemeyer, Kyle E., & FORCE11
    Software Citation Working Group. (2016). Software citation
    principles. *PeerJ Computer Science*, *2*, e86.
    <https://doi.org/10.7717/peerj-cs.86>.
-   Druskat, Stephan, Spaaks, Jurriaan H., Chue Hong, Neil, Haines, Robert, Baker, James. (2017, December).
    Citation File Format (CFF) - Specifications. <https://doi.org/10.5281/zenodo.3515946>.
-   Jones, Matthew B., Boettiger, Carl, Mayes, Abby Cabunoc, Smith,
    Arfon, Slaughter, Peter, Niemeyer, Kyle, ... Goble, Carole. (2017).
    CodeMeta: an exchange schema for software metadata. Version 2.0. KNB
    Data Repository.
    <https://doi.org/10.5063/schema/codemeta-2.0>.

### Blog posts

-   Katz, Daniel S. (2018, February). Compact identifiers for software:
    The last missing link in user-oriented software citation? Blog.
    Retrieved from
    <https://danielskatzblog.wordpress.com/2018/02/06/compact-identifiers-for-software-the-last-missing-link-in-user-oriented-software-citation/>.
-   Druskat, Stephan, Bast, Radovan, Chue Hong, Neil, Konovalov,
    Alexander, Rowley, Andrew, & Silva, Raniere. (2017, December). A
    standard format for CITATION files. *Software and research: The
    Software Sustainability Institute's Blog*. Blog. Retrieved from
    <https://www.software.ac.uk/index.php/blog/2017-12-12-standard-format-citation-files>.
-   Katz, Daniel S. (2017, September). Software Heritage and repository
    metadata: a software citation solution. Blog. Retrieved from
    <https://danielskatzblog.wordpress.com/2017/09/25/software-heritage-and-repository-metadata-a-software-citation-solution/>.
-   Katz, Daniel S. (2017, February). Creation, publication, and
    citation: Issues in software citation versus paper and data
    citation. Blog. Retrieved from
    <https://danielskatzblog.wordpress.com/2017/02/22/creation-publication-and-citation-issues-in-software-citation-versus-paper-and-data-citation/>.
-   Wilson, Robin. (2013). Encouraging citation of software -
    introducing CITATION files. *Software and research: The Software
    Sustainability Institute's Blog*. Blog. Retrieved from
    <http://bit.ly/2ECSdEQ>.
-   Jackson, Mike. How to cite and describe software. *Software and
    research: The Software Sustainability Institute's Blog*. Blog.
    Retrieved from
    <https://www.software.ac.uk/how-cite-and-describe-software>.

Contributions
-------------

Community contributions to this site are welcome! Please file issues and
create pull requests on the project's GitHub site at
<https://github.com/research-software/citation>.
