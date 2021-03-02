---
title: "Research software citation for software developers"
permalink: "/developers/"
toc: true
sidebar:
  nav: developers
---

Making your software citable is actually a lot easier than you may
think: Provide the relevant metadata pertaining to your software, and
let the user know how you would like to software to be cited.

How to provide citation metadata for your software
--------------------------------------------------

The best way to provide this metadata is in a metadata file, either a
`CITATION` file, or in a
`codemeta.json` file, or both.

The files should be placed in the root directory of your public source
code repository.

Additionally you may want to package them with the distributed version
of your software.

How to create a CITATION file
-----------------------------

The easiest way to create a CITATION file is by creating a
`CITATION.cff` file in the [Citation File
Format](http://citation-file-format.github.io/) (CFF). These files are
plain-text.

A minimal `CITATION.cff` file -- following best
practices -- would look something like the following (you can actually
copy and paste it and replace the example data with your own).

    cff-version: 1.1.0
    message: If you use this software, please cite it as below.
    authors:
    - family-names: Druskat
        given-names: Stephan
        orcid: https://orcid.org/0000-0003-4925-7248
    title: "My Research Software"
    version: 2.0.4
    doi: 10.5281/zenodo.1234
    date-released: 2017-12-18

This example includes only a minimal set of fields. CFF provides many
more fields for software citation metadata.

You can also add further references to the citation metadata -- e.g., a
paper describing your software -- and give them a scope describing under
what circumstances that secondary reference should also be cited.

For more details and a complete list of available fields, please refer
to the [CFF format
specifications](https://github.com/citation-file-format/citation-file-format/blob/master/README.md)
[(Druskat et al., 2017)](#cff).

You can also [validate](https://github.com/citation-file-format/schema)
your file against the schema.

CFF is compatible with CodeMeta, so you can also create a
`codemeta.json` file from the metadata in your
`CITATION.cff` file.

How to create `codemeta.json`
-------------------------------------------------

[CodeMeta](https://codemeta.github.io/) [(Jones et al.,
2017)](#codemeta2) files provide software metadata, expressed in JSON's
linked data (JSON-LD) notation. To use it, create a
`codemeta.json` file.

A minimal file -- following best practices -- would look something like
the following (you can actually copy and paste it and replace the
example data with your own).

    {
        "@context": "https://doi.org/10.5063/schema/codemeta-2.0",
        "@type": "SoftwareSourceCode",
        "author": [{
            "@type": "Person",
            "givenName": "Stephan",
            "familyName": "Druskat",
            "@id": "http://orcid.org/0000-0003-4925-7248"
        }],
        "name": "My Research Tool",
        "softwareVersion": "2.0",
        "identifier": "https://doi.org/10.5281/zenodo.1234",
        "datePublished": "2017-12-18",
        "codeRepository": "https://github.com/research-software/my-research-tool"
    }

This example includes only a minimal set of fields. CodeMeta provides
many more fields for software metadata.

You can also add further references to the citation metadata -- e.g., a
paper describing your software.

For more details and a complete list of available fields, please refer
to the [CodeMeta terms page](https://codemeta.github.io/terms/).

You can also validate your file against the schema using a JSON schema
linter, of which there are different ones available online.

References
----------

1.  <a name="cff"/>Druskat, Stephan, Spaaks, Jurriaan H., Chue Hong, Neil, Haines, Robert, Baker, James. (2017, December).
    Citation File Format (CFF) - Specifications. <https://doi.org/10.5281/zenodo.3515946>.
2.  <a name="codemeta2"/>Jones, Matthew B., Boettiger, Carl, Mayes, Abby Cabunoc, Smith,
    Arfon, Slaughter, Peter, Niemeyer, Kyle, ... Goble, Carole. (2017).
    CodeMeta: an exchange schema for software metadata. Version 2.0. KNB
    Data Repository.
    <https://doi.org/10.5063/schema/codemeta-2.0>.

