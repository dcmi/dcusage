---
title: DCMI Usage Board Review of Application Profiles
date: 2002-07-06
description: This document defines the term "Application                      Profile"
  in the context of the Dublin Core                     Metadata Initiative and outlines
  the criteria                     by which the DCMI Usage Board can review an                     Application
  Profile and assign to it a status.
draft: false
creators:
- Thomas Baker
contributors: []
publisher: Dublin Core Metadata Initiative
tags: []
aliases:
- "/usage/documents/2002/07/06/profiles/index.shtml"
notes: 
annotation: 
---

<!--#include virtual="/ssi/header.shtml" --><pre>
Title: DCMI Usage Board Review of Application Profiles
Creator: Thomas Baker
Identifier: <a href="/usage/documents/2002/07/06/profiles/">http://dublincore.org/usage/documents/2002/07/06/profiles/</a>
Latest version: <a href="/usage/documents/profiles/">http://dublincore.org/usage/documents/profiles/</a>
Date modified: 2002-07-06
Description: This document defines the term "Application 
                     Profile" in the context of the Dublin Core
                     Metadata Initiative and outlines the criteria
                     by which the DCMI Usage Board can review an
                     Application Profile and assign to it a status.

1. "Application Profile" defined

For the purposes of DCMI Usage Board review, an Application
Profile (AP) is a declaration of which metadata terms an
organization, information resource, application, or user
community uses in its metadata. Moreover:

-- By definition, an AP cannot "declare" new metadata
    terms and definitions; it only "reuses" terms from existing
    element sets [HEERY].

-- The ideal element set will use URIs to uniquely identify
    its terms within XML namespaces [DCMI-NAMESPACE]. As of
    2002, however, this cannot be required.

-- By definition, any new term coined for use in an AP
    must first be declared in a form citable in the AP.

-- An AP may also provide additional documentation
    on how the terms used are constrained, encoded, or
    interpreted for particular purposes.

As of 2002, APs are seen primarily as a form of documentation,
the purpose of which is to help implementor communities
harmonize their metadata practice. It is hoped that in the
longer term, machine-processable versions of such APs based
on data models such as RDF will provide a basis for automating
metadata interoperability functions such as semantic crosswalks
and format conversions.

2. Documentation requirements for Application Profiles

Application Profiles may be presented to the Usage Board by
any DCMI working group.  

For the purposes of review by the Usage Board:

-- APs must provide, for each term, an identifier
    of the element set where it is defined, ideally in
    the form of URIs for individual terms.

-- If the terms in an AP describe anything other
    than generic "resources" (the typical domain of
    Dublin Core), the AP must make this clear. This is
    particularly important if an AP is based on a data
    model that describes multiple classes of resources,
    such as agents or collections.

-- It is recommended that APs be prepared using
    previously reviewed APs as models for their layout,
    appearance, and content. Aside from the required term
    and element set identifiers, there are no particular
    constraints on the types of documentation -- local
    definitions, comments, constraints, or technical notes --
    that may be associated with a term.

-- Each AP must provide, or point to, a short text that
    describes:

    -- The context and purposes in which the AP is used
       or is likely to be used.

    -- The organizations or individuals involved in its
       development and a capsule history thereof.
       
    -- Any arrangements, policies, or intentions regarding the 
       future development and maintenance of the AP.

3. Review of Application Profiles by the Usage Board

-- The Usage Board is interested in reviewing APs that make
    substantial use of Dublin Core elements. The review of
    APs by the Usage Board serves to:

    -- analyze the usage of Dublin Core within significant 
       implementations;
    -- assign a DCMI stamp of approval;
    -- promote the sharing of APs between communities; and
    -- identify new terms as candidates for inclusion in
       DCMI namespaces.

-- An AP is "well-formed" if it is presented in accordance 
    with the broad and flexible requirements outlined above.
    These presentation requirements may become more specific as
    "good practice" emerges over time.

-- Usage Board review focuses on the use of terms related to
    Dublin Core terms and on any data models that provide a
    context for those terms. The Usage Board is agnostic
    about the use of terms not directly related to Dublin
    Core; strictly speaking such terms are outside the scope
    of Usage Board review.

-- The use of terms related to Dublin Core (such as qualifiers
    of Dublin Core elements, or Dublin Core elements that
    have been constrained for particular contexts) will be
    evaluated from the standpoint of grammatical principle
    (eg, "dumb-down"), clarity, and good practice.

4. Publication and use of Usage Board reviews

-- For APs that "pass" review, the Usage Board
    will publish a Review on a Web page for APs.

-- Each Review will include, at a minimum:

    -- Any comments from the Usage Board on the AP.
    -- Pointers to locally archived copies of the AP
        as originally submitted and (if necessary) as 
        subsequently amended in light of Usage Board 
        comments.
    -- A pointer to the "latest version" of an AP
        held by its maintainers.

-- Review represents a form of recognition, and its
    URL will be persistent for purposes of citation.

-- The official status of reviewed APs will be
    that of "Reviewed".

References

[HEERY] Rachel Heery and Manjula Patel, Application profiles:
mixing and matching metadata schemas, Ariadne 25, September
2000, <a href="http://www.ariadne.ac.uk/issue25/app-profiles/intro.html">http://www.ariadne.ac.uk/issue25/app-profiles/intro.html</a>.

[DCMI-NAMESPACE] Andy Powell, Harry Wagner, Stuart Weibel, Tom
Baker, Tod Matola, Eric Miller, Namespace policy for the Dublin
Core Metadata Initiative,
<a href="/documents/dcmi-namespace/">http://dublincore.org/documents/dcmi-namespace/</a>.

</pre><!--#include virtual="/ssi/footer.shtml" -->
