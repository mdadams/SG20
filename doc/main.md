---
title: Guidelines for Teaching C++
author: SG20
geometry: margin=1in
output: pdf_document
---

__INCLUDE__(doc/obtaining_document.md)

__INCLUDE__(doc/disclaimer.md)

__INCLUDE__(doc/introduction.md)

# Summary of Modules/Areas and Topics

In the sections that follow, the various modules/areas and topics
are presented.
There is one section per module/area.
For each module/area, a table listing the various topics in that module/area
is provided.
The ID for a topic is linked to the detailed coverage of that
topic that comes later in the document.
If a topic has any learning outcomes at a given proficiency level, this is
indicated by a checkmark ("✔️").
If a topic has no learning outcomes
(simply because there
are not any, not because the information is missing),
this is indicated by an em dash ("—").
In the case that the information for a topic is completely
missing, a "❌" symbol is used.

[**NOTE**: These topics are taken mostly from the SG20 GitHub repository.
They are not intended to be complete in any sense.
In fact, by gathering together all topics in one place where they are
easily viewed, it is hoped that missing and unbalanced items will be more
obvious.]

__INCLUDE__(knowledge_areas_summary.md)

# Detailed Information for Modules/Areas and Topics

[//]: # ( ********** START OF DETAILED TOPIC DOCUMENTS ********** )

__INCLUDE__(doc/areas/object-model/copy-semantics.md)

__INCLUDE__(doc/areas/functions/user-defined-literals.md)

__INCLUDE__(doc/areas/functions/defaulted-parameters.md)

__INCLUDE__(doc/areas/compile-time-programming/requires-expressions.md)

__INCLUDE__(doc/areas/object-model/copy_elision.md)

[//]: # ( ********** END OF DETAILED TOPIC DOCUMENTS ********** )

__INCLUDE__(doc/course_examples.md)

# License {#license}

**[NOTE: This license is copied verbatim from the C++ Core Guidelines.]**
<pre>
__INCLUDE__(LICENSE.txt)
</pre>

# Contributors

For a complete list of contributors, please refer to the repository
containing this document on [GitHub](https://github.com/cplusplus/SG20).

__INCLUDE__(doc/contributing.md)

__INCLUDE__(doc/glossary.md)

__INCLUDE__(doc/references.md)