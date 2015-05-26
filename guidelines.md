---
title: Guidelines for submissions
layout: page
---


## Diplomatic textual edition ##

While editors may submit editions in a format of their choosing (accompanied by explanatory documentation), they are encouraged to consult with the ODE editorial board prior to submitting an edition for review if they are uncertain about the acceptability of their editorial format, or if it departs signficantly from the [template material available from ODE](../templates).  Before the ODE editorial board sends a submission out for review, they will ensure that it satisfies the following critiera:

1. The editors must have chosen one of the following two licenses for publication:
    2. CC-BY-SA
    3. CC-BY-SA-NC
1. The edition must follow a documented structure. Usually, this will be some form of XML, but that is not strictly required.  All editions should include some form of syntactic validation (such as a Relax NG or XML Schema for an XML edition).  Documentation of the structure should be descriptive prose formatted in [lean markdown](../markdown).
2. The edition must have an appropriate canonical citation system, and the documentation of the structure must specify how citation values are identified in the edition.
3. In addition to its structural validation, the edition must specify some form of content validation.



## Full facsimile-level edition##

Full facsimile-level editions must satisfy all the requirements for a diplomatic textual edition.  In addition, a facsimile edition must include:


1. an ordered list of one or more text-bearing surfaces (e.g., columns of a papyrus, surfaces of an inscription or pages of a codex)
2. a reference image for each text-bearing surface.   The simplest format for this pairing is a table pairing canonical identifiers for text-bearing surfaces with canonical identifiers for images.
1. citation of visual data sources for each citable node of the textual edition.  The simplest format for this mapping is a table pairing textual references (in the form of CTS URNs) with image citations (in the form of CITE Object URNs.)


## Work in progress  ##


Partial editions satisfying all the criteria for either a diplomatic textual edition or a full facsimile edition may be submitted for a preliminary review, and included in ODE's `inprogress` content.  This can be a valuable way to "release early/release often," and ensure that a project's editorial practice satisfies the requirements of inclusion in ODE.   Only editions of complete texts are included in published releases of ODE, however.