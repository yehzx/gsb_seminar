## Native centromeres are enriched for the heterochromatic mark H3K9me2 in *C. deuterogattii*

In centromeric regions:  

* *C. neoformans* are enriched for active transposable elements, small-RNAs, 5mC DNA methylation, and heterochromatin.

* *C. deuterogattii* has lost the RNAi pathway and the centromeres lack active transposable elements and contain only truncated remnants.

> Hypothesis:  
> It is possible that transposable element silencing pathways, in addition to RNAi, such as heterochromatin and DNA methylation, could also be redundant and might have been lost or evolved differently in this species.

### Methods

#### Results 1-3
To test if heterochromatin is still functional in *C. deuterogattii*,
ChIP followed by ChIP-seq is performed with an antibody specific to **H3K9me2 (heterochromatic modification)**.


#### Results 4
In addition to analysis of the heterochromatic mark, they performed ChIP-seq with an antibody against the **euchromatic histone mark H3K4me2**.

### Results

1. The native centromeres were found to be enriched for H3K9me2 and this chromatin mark spanned the entire ORF-free region. ([Fig 1A](./images/1_F1A.png){:target="_blank"}, [Fig 1B](./images/1_F1B.png){:target="_blank"}, [Fig 1C](./images/1_F1C.png){:target="_blank"})

2. CENP-A-bound region was embedded within the H3K9me2-enriched region and displayed a similar pattern as was previously shown in *C. neoformans*. ([Fig S1](./images/1_S1.png){:target="_blank"})

3. Telomeres, sub-telomeric, and several short chromosomal regions (non-telomeric and non-centromeric regions) were also found to be enriched for H3K9me2. Compared to the centromeres, the level of H3K9me2 enrichment was at least five-fold lower in these regions.

4. H3K4me2 colocalizes with actively expressed genes and was mostly absent from centromeres. ([Fig 1A](./images/1_F1A.png){:target="_blank"}, [Fig 1B](./images/1_F1B.png){:target="_blank"}, [Fig 1C](./images/1_F1C.png){:target="_blank"})

### Conclusion
Centromeres in *C. deuterogattii* are heterochromatic in nature despite the loss of RNAi and the absence of full-length, active transposons.

### Discussion

#### Native centromeres, but not neocentromeres, are heterochromatic in **C. deuterogattii**

TODO



## Correlation between 5mC DNA methylation and H3K9me2 across centromeres

DNA methyltransferase gene DMT5 was truncated in the *C. deuterogattii* R265 reference genome, and 5mC methylation was thought to be entirely absent based on PCR-based assays with methylation-sensitive restriction enzymes. ([ref](https://www.pnas.org/doi/full/10.1073/pnas.1713725115){:target="_blank"})

*DMT5* gene was previously mis-annotated and it could encode a putative fully functional protein. ([Fig S2](./images/1_S2.png){:target="_blank"})

*Note for Fig S2:  
The C. deuterogattii DMT5 gene encoding Dnmt5 is intact and expressed similarly to the C. neoformans ortholog.
(B) Detailed view of C. deuterogattii introns and exons of the DMT5 gene is supported by RNA-seq reads, which are shown to support the gene structure.*

### Methods
To analyze the function of 5mC DNA methylation, the *DMT5* gene was deleted by **homologous recombination** and **bisulfite sequencing** was performed with DNA isolated from the wild-type strain and a *dmt5Δ* deletion mutant. ([Fig S3A](./images/1_S3.png){:target="_blank"})

### Results

1. Two independent DNA methylation analysis methods, **bisulfite sequencing**, and **DNA methylation enrichment from nanopore sequencing** showed that centromeres are enriched for 5mC in *C. deuterogattii*. However, methylation levels were significantly reduced compared to the *C. neoformans* wild-type reference strain H99. ([Fig 1A](./images/1_F1A.png){:target="_blank"}, [Fig 1B](./images/1_F1B.png){:target="_blank"}, [Fig 1C](./images/1_F1C.png){:target="_blank"}, [Fig S1](./images/1_S1.png){:target="_blank"})

2. 5mC was observed only in a subset of centromeres and localized to specific regions instead of pan-centromere, unlike *C. neoformans*. ([Fig 1A](./images/1_F1A.png){:target="_blank"}, [Fig 1B](./images/1_F1B.png){:target="_blank"}, [Fig 1C](./images/1_F1C.png){:target="_blank"})


3. As expected, 5mC levels were abolished in the R265 *dmt5Δ* mutant strain. The bisulfite sequencing analysis also confirmed that 5mC was lacking in the R265 genomic regions.

4. 5mC DNA methylation in *C. neoformans* co-localized with H3K9me2 and DNA methylation was found to be dependent on the presence of H3K9me2 ([ref](https://www.cell.com/cell/fulltext/S0092-8674(19)31374-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867419313741%3Fshowall%3Dtrue){:target="_blank"}). In contrast, the results show that H3K9me2 and 5mC are not well-correlated with each other in C. deuterogattii. For example, the two longest members of the retro-transposable elements family, Tcn3 (~5 kb), located in *CEN3* and *CEN5*, lack both CENP-A and H3K9me2 enrichment but are among the most abundant 5mC-enriched regions in the *C. deuterogattii* genome.([Fig 1B](./images/1_F1B.png){:target="_blank"})

5. The remaining four shorter Tcn3 elements (~0.4 to 2.2 kb) are enriched for H3K9me2 and CENP-A but not significantly enriched for 5mC. Transposable elements Tcn4 and Tcn6 are also enriched with both 5mC and H3K9me2 suggesting that the two modifications can occur at the same locus.

6. *CEN4*, *CEN6*, and *CEN7* completely lack 5mC enrichment but are significantly enriched for H3K9me2. ([Fig S1](./images/1_S1.png){:target="_blank"})


### Conclusion

Even though 5mC methylation is present in *C. deuterogattii*, the overall level is significantly reduced compared to *C. neoformans*. In addition, two heterochromatic marks, 5mC and H3K9me2, differ significantly in terms of their binding pattern between the two species.

### Discussion

#### The heterochromatin machinery differs between closely related species C. deuterogattii and C. neoformans

TODO

## Neocentromeres are not enriched for the heterochromatic mark H3K9me2 or 5mC

Previously, we deleted native *CEN10* and obtained multiple isolates in which neocentromeres were formed. These neocentromeres span actively-expressed genes and the majority of the neocentromeres are located in close proximity to the deleted, native centromere ([ref](https://elifesciences.org/articles/56026){:target="_blank"}).

### Methods

#### Results 1
To test if there is a correlation between histone marks and the chromosomal location of neocentromeres, they analyzed the chromatin of wild-type chromosome 10 ([Fig 2A](./images/1_F2A.PNG){:target="_blank"}).

#### Results 2-4

To test if cen10Δ neocentromeres are enriched for H3K4me2 and H3K9me2, ChIP-seq with antibodies specific for either H3K4me2 or H3K9me2 were performed for three cen10Δ strains containing neocentromeres ([Fig 2A](./images/1_F2A.PNG){:target="_blank"}, [Fig 2B](./images/1_F2B.PNG){:target="_blank"}). 

Isolate cen10Δ-A has two CENP-A-enriched regions of which one is the primary peak and the second is a less abundantly enriched peak. Isolate cen10Δ-E has a neocentromere directly flanking the left telomere and isolate cen10Δ-F has a neocentromere proximal to the deleted native centromere. ([ref](https://elifesciences.org/articles/56026){:target="_blank"}) 

#### Results 5-
They also tested for 5mC methylation at the neocentromere locations and performed Oxford Nanopore sequencing for four *cen10Δ* mutants. ([Fig 2A](./images/1_F2A.PNG){:target="_blank"}, [Fig 2B](./images/1_F2B.PNG){:target="_blank"}, [Fig S4](./images/1_S4.png){:target="_blank"})


### Results

1. As expected, euchromatin (H3K4me2) is spread along the length of the chromosome and co-localizes with the genes, contrasting with the heterochromatin mark (H3K9me2) that is enriched at the subtelomeric regions and the centromere. ([Fig 2A](./images/1_F2A.PNG){:target="_blank"})

2. The neocentromeres of *cen10Δ-A* and *cen10Δ-F* lacked H3K9me2 enrichment. The subtelomeric regions of all 14 chromosomes as well as the native centromeres of the other 13 chromosomes were all still enriched for H3K9me2, as expected. ([Fig 2A](./images/1_F2A.PNG){:target="_blank"})

3. As the neocentromere of *cen10Δ-E* is telocentric, it was enriched with H3K9me2. However, because the sub-telomeric regions are already modestly enriched for H3K9me2 in the wild type, we think that the enrichment in this isolate simply reflects that the neocentromere is located in a sub-telomeric region that was already modified.

4. All *cen10Δ* neocentromeres were found to be enriched for H3K4me2, and the enrichment levels for the neocentromeric chromosomal locations are similar in *cen10Δ* mutants and wild-type.

5. All of the neocentromere regions analyzed lacked any enrichment for 5mC DNA methylation in the wild-type and as well as in neocentromere-harboring strains ([Fig S4](./images/1_S4.png){:target="_blank"}). This is not surprising provided that all pathogenic Cryptococcus species were shown to harbor only the maintenance DNA methyltransferase Dnmt5 and have lost the de novo DNA methyltransferase enzyme ([ref](https://www.cell.com/cell/fulltext/S0092-8674(19)31374-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867419313741%3Fshowall%3Dtrue){:target="_blank"}).

### Conclusion

1. H3K9me2 is not required for neocentromere function in *C. deuterogattii*.

2. Neocentromere locations are not modified with respect to their H3K9me2 or H3K4me2 marks.

3. Native centromeres are located in a large ORF-free region, enriched for truncated transposable elements, H3K9me2, and 5mC, whereas neocentromeres are smaller, span actively expressed genes, and lack enrichment for H3K9me2 or 5mC. ([Fig S5](./images/1_S5.png){:target="_blank"})

### Discussion


## Inactive neocentromeres lack epigenetic memory

## Chromosome fusion leads to centromere inactivation instead of a dicentric chromosome

## Integration of a URA5 transgene into CEN2 results in neocentromere formation

## CENP-A binding drifts within the ORF free region of CEN5 and CEN14