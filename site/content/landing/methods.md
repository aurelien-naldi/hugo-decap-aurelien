---
title: "Methodological work"
hidetitle: true
weight: 1
style: hg3
date: 2019/07/18 12:58
---


I proposed a method for the identification of **stable states** (fixed points) by
transforming the logical functions associated to all model components into stability
conditions. The intersection of these conditions then provides the list of all possible
stable states. Note that while this method only provides a list of all possible stable
states, it does not imply anything about their reachability properties.

My initial implementation used handcrafted decision diagrams, newer implementations use
generic constraint solvers such as the [clingo ASP solver](https://potassco.org/).
This approach has been generalized by others for the identification of **stable motifs**
which provide a good approximation of complex attractors.


{{< ref  Naldi2007 >}}

---

I also proposed a **model reduction** method, allowing to remove some manually-selected
components while preserving important dynamical properties. We could show in particular
that this reduction preserves stable states as well as minimal stable motifs and gives
an under-approximation of reachability properties.

The trajectories obtained with the reduced model correspond to trajectories of the complete
model in which the reduced components are always updated before the remaining ones. The
reduced model can thus also be interpreted as a kinetic refinement of the full model with
a simplification similar to the quasi-steady-state approximation for continuous systems.

{{< ref  Naldi2011 >}}

---

I am currently interrested in the definition of multi-scale models of cell populations,
starting with the stochastic approximation of their behaviours.

I currently work on the caracterisation of reachability properties which can be derived
from stable motifs. I then aim to use this work to derive efficient abstractions of cell 
populations based on the analysis of isolated cells.

{{< ref  Stoll2020 >}}


