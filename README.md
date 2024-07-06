---
title: _C. glabrata_ _CTA1_ promoter dissection
author: Jinye Liang, Bin Z. He
---

Genes involved in development in multicellular eukaryotes often have multiple roles, or "pleiotropic effects". One of the sources for the pleiotropy is that genes are expressed at different times or different tissues. Such distinct expression patterns were found to be regulated primarily by physically separate enhancers, each of which appears to control one specific expression time/location.

In single celled organisms such as the yeast, there aren't multiple cell types in the same sense as in multicellular organisms. Nonetheless, genes can have pleiotropic functions. One example is stress response genes. Many stress response genes are known to be induced by more than one stressful conditions. Moreover, their regulation under these conditions appear to be non-identical (Gasch et al. 2000, PMID: 11102521). One such example is the catalase-encoding gene _CTA1_ and its paralog _CTT1_. In the opportunistic yeast pathogen, _C. glabrata_, we [previously found](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1011748) that _CTA1_ is induced under both the canonical oxidative stress (by > 1mM hydrogen peroxide) and phosphate limitation. Unpublished results show that it is also induced by the presence of oleic acid. Importantly, its induction kinetics, including the ramp up rate and plateau level, differ. So are the transcription factors (TFs) involved in its regulation, at least under the first two condition.

Given the above observation, our question in this study is: **how is the regulatory information for _CTA1_ induction under hydrogen peroxide and phosphate limitation encoded in its promoter region?**. We have two hypotheses:

1. Separate Cis-Regulatory Module (CRM) hypothesis, namely each condition controls _CTA1_ expression via a physically separate CRM located in the ~1000 bp upstream of _CTA1_ CDS.
1. Shsare CRM hypothesis: namely the regulatory information for both (and potentially other) conditions reside in a shared space, operating through the same set of TFs.

An important implication and difference between the two hypotheses has to do with pleiotropy. Under the first hypothesis, due to the physically separate CRM, we expect minimal pleiotropy for cis-regulatory mutations. And, for TFs not shared between the two conditions, trans-changes would also have specific effects on one but not the other condition. Under the second hypothesis, mutations are more likely to have pleiotropic effects.

To test these hypotheses, Jinye performed promoter bashing - she divided the 1kb upstream sequence into five regions, keeping the 0-200 bp proximal region unchanged and mutated the other four regions. She created three distinct series of promoter mutants for this purpose: 1) an internal deletion series (referred to as dP) where P1-P4 were individually removed and the two adjacent regions were fused; 2) a 5' truncation series (tP) where additional regions were sequentially removed from the 5' (or distal) end, starting from the furthest P4 (800-1000 upstream); 3) a 3' randomization series (rP), which is similar to the tP series except it started from the 3', or proximal end, and instead of removing, the regions were replaced by random sequences preserving the GC%, so as to keep the distance of the other regions to the Transcription Start Site (TSS) constant.

This repository contains the processed flow cytometry data and analysis code and results. This is Bin's reanalysis of Jinye's data. Her original analysis code is included as a submodule inside the `90-JY-code`
