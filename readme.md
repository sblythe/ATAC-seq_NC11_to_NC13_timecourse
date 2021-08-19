#readme.md

This repository contains BigWig formatted coverage data for *Drosophila* ATAC-seq "open" regions (< 100 bp fragments) of a 3-minute timecourse spanning the three nuclear cycles preceding NC14/ZGA/MBT.
The data are associated with a prior publication: [Blythe and Wieschaus, eLife 2016](https://elifesciences.org/articles/20148).
The data are average normalized (z-scored counts-per-million-reads) counts per 10 bp window as mapped to the *Drosophila* genome, version **dm6**. Please see the cited work for additional details of how the samples were generated. Raw data is available through GEO/SRA at accession number [GSE83851](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE83851)

The available timepoints for wild-type are:

1. NC11 @ 3, 6, and 9 minutes
2. NC12 @ 3, 6, 9, and 12 minutes
3. NC13 @ 3, 6, 9, 12, 15, and 18 minutes

(13 total samples)

The final timepoints per nuclear cycle are in mitosis. The zero time reference for each nuclear cycle is anaphase of the cycle prior.

The "UCSC_display_links..." files are used for display of the bigwig files on the UCSC genome browser.
