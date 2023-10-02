## Clr4-Mediated Histone H3 Lysine 9 Methylation Is an Essential Regulatory Mechanism in Mucorales

The Mucorales express 
a diverse repertoire of RNAi components that are involved in
distinct repressive, regulatory pathways relying on sRNA-directed 
degradation of complementary mRNAs that results in PTGS.

These sRNAs also serve as initiators of chromatin 
modifications leading to transcriptional gene silencing (TGS) in 
other eukaryotic organisms.

**While many of these modifications have been characterized in the Dikarya, their conservation and role in early-diverging fungi was unexplored. Therefore, the presence of chromatin modifications was first surveyed in early-diverging 
fungal genomes, focusing on the Mucorales** ([phylogeny](./images/2_intro_early_fungi.jpeg){:target="_blank"}). As in most eukaryotes, Mucoralean histone proteins H3 and H4 are highly conserved.  The M. lusitanicus genome encodes four histone H3 and 
three histone H4 copies (SI Appendix, Fig. S1 A and B), and the 
KMT-lysine substrates and neighboring regions are also conserved.  Thus, these proteins could harbor chromatin modifications 
catalyzed by KMT enzymes or other histone lysine modifiers.

### Methods

#### Results 1-6
To identify RNAi components, and KMT and DNMT homologs 
in the Mucorales, **86 fungal proteomes were analyzed including 
at least one representative of most fungal phyla, focusing on the  Mucoromycota phylum and major fungal pathogens**. 
Out of these proteomes, 43 were selected as representatives to 
capture the presence or absence of different epigenetic modifying enzymes. ([Fig 1](./images/2_F1.jpg){:target="_blank"})

*TODO: add method details*

#### Results 7-
To gain a better understanding of Clr4 function in Mucorales, 
we attempted to delete clr4 through **CRISPR-Cas9** and **homologous recombination** in *M. lusitanicus*.

Mucorales have nonseptate hyphae and multinucleated asexual spores. As such, genetic transformation often results in initially heterokaryotic mutants, producing spores that harbor both wild-type (WT) and mutant nuclei. Mutant allele segregation by sexual reproduction is not possible because *M. lusitanicus* is not able to undergo a complete sexual cycle under laboratory conditions. To render these mutants 
homokaryotic, i.e., harboring mutant nuclei exclusively, **transformants must be passaged through several vegetative growth cycles in a medium that positively selects the mutant allele**.



### Results 

1.  We identified homologs of the three major RNAi 
enzymes—RdRP, Dicer, and Ago—across all fungal phyla and 
particularly, in every Mucoromycota species, though not in some 
isolated Dikarya species or clades, e.g., *Saccharomyces cerevisiae*, *Candida auris*, *Ustilago maydis*, and *Malassezia pachydermatis*.

2. In *S. pombe*, CTGS leading to constitutive heterochromatin initiates in regions producing complementary sRNA that are loaded into the RITS complex by the Argonaute siRNA chaperones (ARC), Arb1 and Arb2. These two proteins are mostly conserved in the Mucorales, ascomycetes that have retained RNAi, and some early diverging fungi.

3. However, RITS-exclusive components—Chp1 and Tas3—are found only in *S. pombe*, indicating that any possible interplay among RNAi and heterochromatin formation might require novel components.

4. KMT homologs and accessory proteins in the methyltransferase complexes were identified. Clr4/KMT1, KMT6, and KMT5 catalyze methylation of H3K9, H3K27, and H4K20, respectively, resulting in transcriptional repression ([Fig S1](./images/2_S1.png){:target="_blank"}). Clr4 and associated proteins, Rik1 and the ubiquitin ligase Cul4, are highly conserved in fungi, particularly in the Mucorales. ([Fig 1](./images/2_F1.jpg){:target="_blank"})

5.  In *S. pombe*, the Clr4 complex (CLRC) has 
been shown to interact with Ago1 through Stc1, which connects 
both pathways to establish H3K9me via RNAi ([ref](https://link.springer.com/article/10.1007/s00294-007-0165-7){:target="_blank"}). Interestingly, 
Stc1 homologs are present in the Mucoromycota despite the lack 
of other RITS components. The HP1 complex (Swi6/Chp2 
homologs) is also conserved among the Mucoromycota, and all 
early-diverging fungi that have retained RNAi. KMT6 was lost in every Mucoromycota species, yet is conserved in some other early-diverging fungal phyla. It was also lost in some 
Ascomycota and many Basidiomycota, suggesting that **H3K27me and Polycomb silencing was lost in many independent events during fungal evolution**.

6. We searched for DNMT enzymes, specifically 
those capable of producing transcription-repressive 5mC DNA 
methylation. ...

    *TODO: add the other miscellaneous explanation mentioned in paper about Fig 1.*

7. Surprisingly, every transformation experiment aiming at clr4 deletion resulted in heterokaryotic mutants that were unable to achieve complete mutant homokaryosis, and after 20 vegetative passages they still harbored WT nuclei ([Fig S3](./images/2_S3.png){:target="_blank"}). We tested if Clr4 activity could be essential for viability by genotyping the asexual 
progeny of a heterokaryotic mutant, reasoning an equal rate of 
WT or mutant homokaryons in the spore population is expected 
for a nondeleterious mutation. To do so, 40 spores from a heterokaryotic mutant were dissected and plated on a nonselective medium and after incubation, 30 spores were able to germinate. Next, we analyzed the germinated spores and found either WT homokaryotic or heterokaryotic colonies (with WT and *clr4Δ* nuclei), yet no *clr4Δ* homokaryons were observed ([Fig S3](./images/2_S3.png){:target="_blank"}). These results indicate that **homokaryotic *clr4Δ* spores are not able to survive implying Clr4 is essential and suggesting that a functionalH3K9me-mediated heterochromatin formation mechanism is required for cell viability in *M. lusitanicus*.**



## Regions Targeted by H3K9 Methylation Are Transcriptional  Deserts Enriched with Repeats

### Methods

#### Results 1
Chromatin immunoprecipitation followed by Illumina sequencing (ChIP-seq) using alpha-H3K9 di- (H3K9me2) or tri-methylated (H3K9me3) antibodies was performed to characterize H3K9me in *M. lusitanicus*.

Reads were mapped to the publicly available *M. lusitanicus* MU402 v1.0 genome, and H3K9me2 and -me3 enriched peaks were identified across the genome.

#### Results 2-4
To determine whether H3K9me-mediated heterochromatin results in TGS, ChIP-seq against RNA polymerase II (RNA polII) and ribosomal RNA (rRNA)-depleted strand-specific RNA sequencing (RNA-seq) were performed.

#### Results 5-6
Because previous studies have shown that *M. lusitanicus*
Dicer-dependent, canonical sRNAs are able to target repeated 
and transposon sequences and most of the H3K9me 
islands are localized to repeats, the sRNA distribution across 
the whole genome was analyzed by conducting sRNA-enriched 
RNA purification and sequencing (sRNA-seq). 

#### Results 7
In many eukaryotic genomes, repeated regions represent copies 
of transposable elements (TEs) whose transposition gave rise to 
fine-tuned regulatory mechanisms that shaped their genome evolution. To determine the extent of TEs regulated by either 
or both H3K9me and RNAi, we conducted a comprehensive TE 
identification analysis in the *Mucor* species complex.

Briefly,

1. Open reading frames (ORFs) were predicted in every repeat type identified in our previous analysis.

2. And searched for protein domains frequently associated with TE activity.

3. The presence and relative position of these domains within each sequence was used to manually curate TE predictions, identifying six different TE families: 
DNA or class II elements Tc1/Mariner, PIF/Harbinger, and RC/
Helitron; and RNA or class I elements non-LTR GremLINE1 
and other LINE, and LTR Ty3/Gypsy. ([Fig 2E](./images/2_F2.jpg){:target="_blank"})

4. After generating this curated TE library, the whole genome 
and annotated TE sequences were screened using restrictive 
parameters, ensuring only highly similar and full-length elements were included.

5. Then, TE distribution across the genome was 
examined to detect conspicuous clustering patterns. ([Fig 2F](./images/2_F2.jpg){:target="_blank"})

### Results

1. Genome-wide observations revealed a striking overlapping 
pattern between H3K9me2 and -me3, which was confirmed by 
linear correlation measurements of every enriched peak detected. ([Fig 2A, 2B](./images/2_F2.jpg){:target="_blank"})

2. H3K9me peaks emerge as heterochromatin islands in transcriptional deserts, which are devoid of mRNA and RNA pol II occupancy ([Fig 2A](./images/2_F2.jpg){:target="_blank"}). Genes are absent from most of these heterochromatic regions, suggesting H3K9me is targeting other genomic elements.

3. A denovo repeat identification analysis was conducted across the genome of *M. lusitanicus*, resulting in an estimate of 22.3% genome-wide repeated DNA content, 53.9% gene sequences, and the remaining percent intergenic sequences.

4. An in-depth, base pair-resolution analysis confirmed the genome-wide observations, showing that ~19.7% of the genome is bound by H3K9me chromatin, which is mainly directed at repeats (15.3%, [Fig 2C](./images/2_F2.jpg){:target="_blank"}). In contrast, only 1.2% of the genome is targeted by H3K9me across coding sequences, suggesting that **H3K9me is mostly controlling repeats rather than regulating gene expression**.

5. The sRNA content analyzed exhibits key features of canonical sRNAs: 1) a discrete length ranging from 21 to 24 nt and 2) a strong preference for uracil at the 5′-end. ([Fig 2D](./images/2_F2.jpg){:target="_blank"})

6. These canonical sRNAs coincide extensively with H3K9me at silenced repeated regions ([Fig 2A](./images/2_F2.jpg){:target="_blank"}), indicating a **dual regulation by posttranscriptional and transcriptional silencing mechanisms**.

7. Only the GremLINE1 elements occupy a specific genomic region, 
defining the pericentric regions of M. lusitanicus, which are transcriptionally silent regions devoid of genes. Conversely, the remaining TE families have a cosmopolitan distribution across the genome. Telomeric regions containing the repeated sequence 5′-TTAGGG-3′ were identified at the 3′-end of scaffolds 2, 3, 8, 9, and 10 (indicated as asterisks in [Fig 2F](./images/2_F2.jpg){:target="_blank"}).

8. These telomeric and subtelomeric (~50 kb) regions were not enriched in TE of any family, although several structural repeats and H3K9me marks were found at these regions.([Fig S5A](./images/2_S5.png){:target="_blank"}) 

9. Sex determination in Mucorales is controlled by the sex locus, comprising an allelic high-mobility group transcription factor—sexP and sexM alleles—flanked by triose phosphate transporter (tptA) and RNA helicase (rnhA)-encoding genes. Despite its epigenetic regulation in other fungal models, the M. lusitanicus mating-type locus did not show any specific silencing mark. ([Fig S5B](./images/2_S5.png){:target="_blank"}) 

### Conclusion

These findings reveal an intimate overlap between H3K9me2 and -me3 islands primarily forming in repeated regions subject to transcriptional silencing.

Most of these genomic regions are also targeted by sRNAs, indicating **a possible interconnection between RNAi and heterochromatin formation pathways to control transposition that was explored further**.

## RNAi Is Dispensable for Heterochromatin Maintenance at TEs

### Methods

RNAi relies on sRNAs to induce posttranscriptioal silencing of complementary transcripts but in addition, these sRNAs may participate in CTGS by interacting with other repressive epigenetic mechanisms to initiate and maintain heterochromatin formation.

#### Results 1-5
To explore the interaction between the principal epigenetic repressive mechanisms in *M. lusitanicus*, RNAi and H3K9me levels were compared in the TEs.

An RNA intermediate could be more readily targeted by RNAi and consequently, the analysis was focused on RNA transposons.

#### Results 6-11

To investigate that H3K9me or sRNAs may be acting independently,
an extensive mutant collection comprised of every key RNAi enzyme identified in *M. lusitanicus* was studied.

To confirm their involvement in RNAi, sRNA content was sequenced and compared with previous studies. ([Fig S6A](./images/2_S6.png){:target="_blank"})

These results recapitulate that sRNAs are 
almost depleted in *dcl1Δ* *dcl2Δ*, a double mutant lacking any 
Dicer activity; and in *ago1Δ*, lacking the main Argonaute enzyme, confirming that both activities are essential for sRNA biogenesis and canonical RNAi. ([Fig S6B](./images/2_S6.png){:target="_blank"})

These canonical sRNAs are mostly produced from exons and repeated sequences ([Fig S6C](./images/2_S6.png){:target="_blank"}), **suggesting gene and transposon regulation are their primary targets**. Therefore, **we focused our analysis on canonical (dcl1Δ dcl2Δ, ago1Δ, and rdrp2Δ) and alternative (rdrp1Δ and r3b2Δ) RNAi pathway mutants**. ([Fig 3](./images/2_F3.jpg){:target="_blank"})

Other RNAi paralog mutants (*dcl1Δ*, *dcl2Δ*, *ago2Δ*, *ago3Δ*, and *rdrp3Δ*) are covered in supplementary material because their function is not essential for *M. lusitanicus* RNAi. ([Fig S7](./images/2_S7.png){:target="_blank"})

ChIP and RNA-seq analyses were conducted to identify H3K9me2 and 
-me3 enrichment, as well as transcription across the genome.

#### Results 12-
*S. pombe* Rdp1 and the RNA-directed RNA polymerase complex (RDRC) are essential to initiate CTGS at pericentric repeats 
. In contrast, M. lusitanicus encodes three subspecialized RdRP 
enzymes, suggesting more complex regulatory dynamics. 

To address this, sRNA production and transcript expression across TE sequences were studied in the RdRP and alternative RNAi pathway mutants.

#### Results 15-
To confirm the extent of GremLINE1 unique regulation, the 
remaining DNA TEs (Tc1/Mariner, PIF/Harbinger, and RC/
Helitron) were examined ([Fig S9A](./images/2_S9A.png){:target="_blank"}). Most copies of 
DNA transposons show H3K9me across the coding sequence. Despite 
relying on a DNA intermediate for transposition, sRNAs are produced from Mariner and Harbinger copies as well as several Helitron subfamilies through canonical and alternative RNAi pathways. Only

### Results

1. H3K9me binds to most copies of GremLINE1 and Gypsy, and several copies of LINE in the *M. lusitanicus* WT strain. ([Fig 3](./images/2_F3.jpg){:target="_blank"})

2. In these elements, H3K9me is deposited across the entire sequence, with the highest enrichment at the start and end positions.

3. As expected, sRNAs are abundantly produced from these regions but interesting, they target more TE copies than H3K9me. For instance, some LINE subfamilies generate sRNAs, but H3K9me is completely absent. 

4. Nevertheless, none of these elements are being actively 
transcribed, not even those lacking H3K9me, as evidenced by the 
transcriptomic and RNA pol II occupancy data. ([Fig 3](./images/2_F3.jpg){:target="_blank"})

5. Because **several TE copies are differentially targeted by H3K9me or sRNAs, these mechanisms may be acting independently to regulate these elements**.

6. Strikingly, not a single RNAi-defective mutant showed a 
significant decrease in H3K9me3 at any TE analyzed ([Fig 3](./images/2_F3.jpg){:target="_blank"}, [Fig S7](./images/2_S7.png){:target="_blank"}), and no differences in H3K9me2 and -me3 
content were observed in any genomic region ([Fig S8](./images/2_S8.png){:target="_blank"}). **These findings indicate that RNAi is neither sufficient nor necessary to maintain histone methylation across TEs.**

7. Despite not showing alternations in H3K9me, both mRNA expression and sRNA accumulation were substantially affected in the mutants. The production of sRNAs targeting most of these regions decreased dramatically in *dcl1Δ* *dcl2Δ*, and to a lesser extent in *ago1Δ*, as expected of Dicer- and Ago-dependent, canonical sRNAs.

8. More importantly, the absence of Dicer or Ago activity increased transcript levels in many TE despite being embedded in H3K9me chromatin, especially but not restricted to GremLINE1 elements.

9. Conversely, some TE subfamilies showed a marked decrease in 
canonical sRNA production in RNAi-defective mutants but 
remained transcriptionally silent or inactive, suggesting H3K9me 
and RNAi may operate independently to repress TE expression. 

10. RNA pol II occupancy remained stable in all of the 
RNAi mutants, indicating that increased transcript accumulation 
was a result of lacking PTGS instead of increased transcription. 

11. These results confirm that M. lusitanicus RNAi pathways act exclusively via PTGS.

12. Obvious differences were observed 
in centromeric GremLINE1 retrotransposons compared with other 
elements. ([Fig 3](./images/2_F3.jpg){:target="_blank"})

13. Rdrp1 and R3B2—the main components of the 
alternative pathway are important to produce sRNAs from LINE 
and Gypsy retrotransposons and to regulate their expression, suggesting an interaction between canonical and alternative RNAi 
pathways to control these elements. In contrast, posttranscriptional silencing of GremLINE1 elements is completely dependent on the canonical pathway because sRNA and transcript levels remain unchanged in mutants of the alternative RNAi pathway.

14. These differences in TE regulation suggest that centromeric GremLINE1s are controlled by a unique RNAi-based mechanism, possibly as a consequence of their role in centromere identity.

15. Only Mariner and Helitron subfamilies 1 ([Fig S8A](./images/2_S8.png){:target="_blank"}, green in both Mariner and Helitron) depend on RNAi to repress their expression as dcl1Δ dcl2Δ and ago1Δ exhibit increased transcript levels, similar to Gypsy and LINE RNA transposons. On the other hand, the remaining DNA element copies are transcriptionally silenced, possibly as a result of H3K9me.

16. Due to the presence of full-length 
elements and the necessary protein products for autonomous transposition, we reasoned that **transcripts encoding transposase protein domains might be targeted by RNAi**. Indeed, sRNAs are specifically directed to the transposase-encoding transcript, suggesting **RNAi is silencing transposase transcripts to prevent DNA transposition events as a genome defense mechanism** ([Fig S9B](./images/2_S9B.png){:target="_blank"})

17.  Intriguingly, H3K9me3 is more broadly distributed, extending to neighboring structural repeats, reinforcing that histone methylation is maintained in regions not targeted by RNAi and that both epigenetic mechanisms may recognize and target repeats differently.

## RNAi Prevents Genome Instability by Repressing GremLINE1 Transposition to Noncentromeric Regions

GremLINE1 elements represent a LINE L1-like subfamily of RNA TEs exclusively located in pericentric regions and they are conserved in Mucoromycota species that lost the centromere protein A (CENP-A), suggesting an important role in centromere–kinetochore dynamics.
### Methods

#### Results 1-

We investigated the regulatory mechanisms controlling GremLINE1 expression, analyzing H3K9me and sRNA accumulation at the centromeres.

#### Results 3-

Because all other TEs rely on Rdrp1 to generate sRNAs, we determined which RdRPs were triggering RNAi to target the GremLINE1s by searching for differences in natural antisense transcription and thus, dsRNA, across the GremLINE1 retrotransposons.

#### Results 5

Our data confirm that GremLINE1 regulation is unique compared with other repeated elements outside of the centromeres, 
therefore we hypothesized that loss of RNAi could incite their 
transposition and lead to genome instability.

To test this hypothesis, an artificial evolution experiment was conducted by culturing 
RNAi-defective and WT strains for 20 asexual passages in minimal 
medium [Fig 4C](./images/2_F4.jpg){:target="_blank"}. 

#### Results 6-
To further characterize these transposition events, the strains 
were cultured under positive selection exerted by FK506, an 
antifungal drug that binds FKBP12, generating a protein–drug 
complex that inhibits calcineurin and enforces yeast-like growth. Mycelium-growing colonies were selected to capture 
GremLINE1s in the FKBP12-encoding locus fkbA and thus cause FKBP12 loss-of-function and FK506 resistance [Fig 4C](./images/2_F4.jpg){:target="_blank"}.

After passage on the selective medium, 36 spontaneous FK506-
resistant colonies were isolated: 10 in *dcl1Δ dcl2Δ*, 5 in *ago1Δ*, 1 in *rdrp2Δ*, 10 in *rdrp1Δ*, and 10 in the WT strains. Mutation types in each of these isolates were characterized by analyzing fkbA fragment size and whole-locus Sanger-sequencing, classifying these as insertions, point mutations or deletions, or epimutations when no genetic alteration was found.

### Results

1. H3K9me delimits the pericentric regions, extending further from the GremLINE1s and their complementary sRNAs into other repeated sequences, but sparing neighboring genes. ([Fig 4A](./images/2_F4.jpg){:target="_blank"})

2. Notably, H3K9me is absent at the kinetochore-binding region, possibly to maintain an open chromatin state that allows kinetochore binding. Additionally, RNAi exerts fine-tuned, posttranscriptional silencing of GremLINE1 elements ([Fig 3](./images/2_F3.jpg){:target="_blank"}) independently of Rdrp1—the main RdRP associated with silencing initiation in *M. lusitanicus*.

3. Many GremLINE1 copies exhibited a significant decrease of antisense transcripts in rdrp2Δ compared with the WT and rdrp1Δ ([Fig 4B](./images/2_F4.jpg){:target="_blank"}, False Discovery Rate (FDR) ≤ 0.05), indicating that Rdrp2 may generate dsRNA from these elements and induce RNAi. Rdrp2 is the only RdRP that harbors an RNA-recognition motif in its N terminus (Dataset S2, RdRP), and its activity is essential to maintain silencing through an sRNA-amplifying positive feedback loop. 

4. We propose that both activities, generating antisense transcription resulting in dsRNA and amplifying silencing, are important to initiate and maintain PTGS directed at the GremLINE1s, and could explain the slight increase of GremLINE1 transcript levels in *rdrp2Δ*. ([Fig 3](./images/2_F3.jpg){:target="_blank"})

5. We estimated GremLINE1 copy number variation across these strains as the fold change compared with a single-copy gene by qPCR, resulting in a significant copy number increase in dcl1Δ dcl2Δ and ago1Δ—key components of PTGS ([Fig 4D](./images/2_F4.jpg){:target="_blank"}). Interestingly, transcript levels seem to correlate with the increase in copy number in each given mutant, particularly in *dcl1Δ dcl2Δ* and *ago1Δ*, but also in *dcl2Δ* and *rdrp2Δ*, though their increase in copy numbers followed a trend that was not statistically significant ([Fig 3](./images/2_F3.jpg){:target="_blank"}, [Fig 4D](./images/2_F4.jpg){:target="_blank"}).

6. Six insertions disrupting the fkbA locus were detected in only *dcl1Δ dcl2Δ* and *ago1Δ* resistant isolates. 
Four independent insertion events were fully characterized: one 
full-length and one truncated GremLINE1 copies in each of the 
*dcl1Δ dcl2Δ* and *ago1Δ* mutants ([Fig 4E](./images/2_F4.jpg){:target="_blank"}).

7. In addition, two double GremLINE1 insertions were detected in *dcl1Δ dcl2Δ*, confirmed by PCR with a 
specific fkbA and GremLINE1 primer pair. Every insertion analyzed revealed exclusively a GremLINE1 copy, and the remaining resistant isolates in other mutant or WT strains did not harbor any insertions. The presence of A/T-5′-end target site duplications and truncated insertions reflect the LINE L1 canonical transposition mechanism, involving element-encoded endonuclease and reverse transcriptase activities. ([Fig 2](./images/2_F2.jpg){:target="_blank"})

8. Briefly, the endonuclease nicks genomic DNA in AT-rich regions generating an exposed 3′-OH end that primes a reverse transcription reaction of the A-rich 3′-end of the element ([Fig 5](./images/2_F5.jpg){:target="_blank"}). Abrupt termination of the reverse transcription step frequently leads to incomplete insertions, explaining truncated copies.

9. These findings strongly support that RNAi is preventing GremLINE1 transposition from H3K9-methylated pericentromeres to other genomic regions, limiting disruption of genes encoding antifungal drug targets.

> Note: Alternative RNAi  
> Source: [A Non-canonical RNA Silencing Pathway Promotes mRNA Degradation in Basal Fungi](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1005168)
> Source: [A non-canonical RNA degradation pathway suppresses RNAi-dependent epimutations in the human fungal pathogen Mucor circinelloides](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5384783/)
> we have identified a new rdrp-dependent dicer-independent esRNA class. These esRNAs are produced by a degradation pathway in which the RdRP proteins signal specific transcripts that will be degraded by a newly identified RNase.
>  Depending on the proteins of the RNAi machinery required for their biogenesis, these ex-siRNAs can be classified into four different classes, all of which are dicer-dependent, since they require one of the M. circinelloides Dicer-like (Dcl) proteins for their biogenesis. The main class of the dicer-dependent ex-siRNAs (class II) requires Dcl-2 [12] and RdRP-1 [13], an RNA-dependent RNA polymerase essential for activation of silencing with single stranded RNA molecules by producing antisense RNA transcripts. Only a small group of dcl-2-dependent ex-siRNAs (class I) does not require RdRP-1 for their biogenesis, but most of them require RdRP-2 [13], which is involved in the amplification process that produce secondary siRNAs. These two classes are specifically bound to Ago-1, one of the three M. circinelloides Argonaute proteins [14] and are accumulated at a reduced extent in the ago-1- mutants, suggesting that they require Ago-1 for their biogenesis/stability. Class III corresponds to ex-siRNAs that can be generated by either Dcl-1 or Dcl-2 and require both RdRP-1 and RdRP-2, and class IV is a tiny group of ex-siRNAs that depends on dcl-1 [15] but not on dcl-2 [11].