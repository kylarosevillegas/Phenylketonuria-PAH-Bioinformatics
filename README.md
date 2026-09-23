# Exploring the PAH Gene Using UCSC Genome Browser and NCBI ClinVar

**Name:** Kyla Rose D. Villegas  

**Assigned Gene:** PAH  

**Associated Disease:** Phenylketonuria (PKU)  

**Activity:** Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar

## 2. UCSC Gene Location

I opened the UCSC Genome Browser and selected the Human GRCh38/hg38 genome assembly. I searched for the PAH gene and opened the official human PAH gene locus.

- **Official gene symbol:** PAH
- **Full gene name:** Phenylalanine hydroxylase
- **Chromosome:** 12
- **Genome assembly:** GRCh38/hg38
- **Genomic coordinates:** chr12:102,836,889-102,958,410
- **DNA strand:** Minus (-) strand
- **Approximate gene size:** 121,522 bp (~121.5 kb)

### Screenshot 1 - PAH Gene Location

![PAH Gene Location](images/01_gene_location.png)

## 3. Exons, Introns, and Transcripts

- **Selected transcript:** NM_000277.3
- **Number of exons:** 13
- **Multiple transcripts/isoforms visible:** Yes

An exon is a region of a gene that remains in the mature RNA after splicing, while an intron is a region that is removed during RNA processing.

In the PAH gene, the introns generally appear much longer than the exons because the exon boxes are relatively short and are separated by long connecting intron regions.

## 4. UCSC Annotation Tracks

For the gene annotation, I used the **NCBI RefSeq** track. I also displayed the **ClinVar Variants** track and the **UCSC 100 Vertebrates** conservation track.

- **Gene annotation track used:** NCBI RefSeq
- **ClinVar-related variants visible:** Yes. Many ClinVar variant marks were visible within and near the PAH gene.
- **Were some regions more conserved than others?** Yes. The conservation signal varied across the PAH region, with some areas showing stronger conservation than others.
- **Where were the conserved regions located?** Stronger conservation was mainly seen around several exon-associated regions, although some conservation signal was also present outside the exons.

Strong conservation suggests that a DNA region has remained similar across different species over evolutionary time. This can indicate that the sequence has an important biological function because major changes in important regions may be less likely to be tolerated.

### Screenshot 3 - ClinVar and Conservation Tracks

![PAH UCSC Tracks](images/03_tracks.png)

## 5. Selected ClinVar Variant

- **Gene:** PAH
- **Variant/HGVS:** NM_000277.3(PAH):c.1222C>T (p.Arg408Trp)
- **ClinVar Variation ID:** 577
- **VCV accession:** VCV000000577.151
- **rsID:** rs5030858
- **Chromosome and genomic position (GRCh38):** chr12:102,840,493
- **Cytogenetic location:** 12q23.2
- **Associated condition:** Phenylketonuria
- **Clinical significance:** Pathogenic
- **Review status:** Reviewed by expert panel
- **ClinVar URL:** https://www.ncbi.nlm.nih.gov/clinvar/variation/577/

### Screenshot 4 - Selected ClinVar Variant

![ClinVar PAH Variant](images/04_clinvar_variant.png)
