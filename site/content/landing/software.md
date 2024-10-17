---
title: "Software tools and standards"
weight: 3
style: hg1
date: 2019/07/18 12:58
---


Since 2006, I am the main developer of the [GINsim](http://www.ginsim.org) software,
which has been used for the definition and analysis of a many logical models.
This tool provides a graphical interface for model design and a number of analytical tools.


{{< ref  Naldi2018a >}}

---

The number of software tools for qualitative models grew over the years, each of them
using its own file format. To overcome the multiplication of formats and enable
interoperability between complementary tools, I participated in the definition of the
[SBML qual extension](http://sbml.org/Community/Wiki/SBML_Level_3_Proposals/Qualitative_Models),
an exchange format for qualitative models.

This effort led to the creation of the [CoLoMoTo](http://www.colomoto.org) consortium.

{{< ref  Chaouiya2013 >}}
{{< ref  Naldi2015 >}}


---


The [bioLQM toolbox](https://github.com/colomoto/bioLQM) provides command line and
programmatic interfaces for the core data structures and algorithms available in GINsim,
as well as import/export filters to improve interoperability beyond the tools supporting
the SBML qual format directly.

These tools along with many others are integrated in the
[CoLoMoTo notebook](http://www.colomoto.org/notebook).
This modelling platform focuses on reproducible results through the use of Docker images
(providing frozen snapshots of a complex software environment) and Jupyter notebooks to
build and share complex analysis workflows.

{{< ref  Naldi2018c >}}
{{< ref  Naldi2018b >}}

