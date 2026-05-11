---
title: Germline Gene Prediction
layout: default
nav_order: 3
---

# Tools for finding Adaptive Immune Receptor germline gene sequences in a genome assembly
(or other large contiguous germline sequence)

## [IgDetective](https://github.com/Immunotools/IgDetective)
RSS-based approach for finding divergent genes. Well-tested in mammals.
**Flagship paper.** Sirupurapu V, Safonova Y, Pevzner PA. Gene prediction in the immunoglobulin loci. Genome Res. 2022 Jun;32(6):1152-1169. doi: 10.1101/gr.276676.122. Epub 2022 May 11. PMID: 35545447; PMCID: PMC9248892.

## [Digger](https://williamdlees.github.io/digger/_build/html/index.html)
Great for providing annotations of all gene features in a BLASTn hit. Overly sensitive in my experience, but great for procuring candidate gene lists.
**Flagship paper.** Lees, W. D., Saha, S., Yaari, G., & Watson, C. T. (2024). Digger: directed annotation of immunoglobulin and T cell receptor V, D, and J gene sequences and assemblies. Bioinformatics (Oxford, England), 40(3), btae144. https://doi.org/10.1093/bioinformatics/btae144

## [LIGMotif](https://www.imgt.org/ligmotif/)
Only available in-browser, not as command line tool. Must first find target locus; cannot predict from sequences beyond a somewhat small maximum size of 2.5 Mb.
**Flagship paper.** Lane, J., Lefranc, M.-P., & Duroux, P. (2007). IMGT/LIGMotif: A tool to annotate V-, D- and J-GENE of immunoglobulin and T cell receptor of vertebrates. In C. Brun & G. Didier (Eds.), Actes des Journées Ouvertes Biologie, Informatique et Mathématiques (JOBIM 2007) (pp. 339–340). Université Montpellier II. https://www.imgt.org/PDF/Coms/com417.pdf
