---
author: Huw A. Ogilvie
level: Intermediate
title: StarBEAST2 v14 tutorial
subtitle: Estimating species trees using StarBEAST2
beastversion: 2.5.0
---


# Background

StarBEAST2 is a Bayesian implementation of the multispecies coalescent (MSC)
that jointly infers gene and species trees directly from multiple sequence alignments.
Trees inferred using this method contain not only topological relationships, but
also estimates of species divergences times and gene coalescence times. Such trees
are therefore often described as _time trees_.

This tutorial walks through through how to set up three kinds of species
tree analyses using StarBEAST2. The first is basic species tree reconstruction using
a strict nuclear clock rate.  The second is a relaxed clock analysis where a separate
molecular clock rate is estimated for each species branch. The third is a
_total evidence_ analysis where the times and rates and jointly estimated by integrating
fossil data into the model.