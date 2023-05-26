## Supplementary Table 1 (supp-table-1-taxonomy.tsv)
* Taxonomic annotations for all n=442 ASVs used in the differential abundance analysis. 
* Species annotations were inferred using the `dada2::addSpecies()` function with `allowMultiple=F`, in order to exclude identification of ASVs where a species-level consensus was not reached. 
* For the binned differential abundance analysis, the column “bin” was used to sum ASV rows

## Supplementary Table 2 ( coming )

## Supplementary Table 3 (supp-table-3-master.tsv)
* Clinical and demographic characteristics are prefixed with 'clin.'
* Microbial features are prefixed with 'tax.'
    * ASV and higher taxa (binned) relative abundances
    * Summary taxonomic features (Shannon, Observed, PB_ratio for Shannon diversity, taxonomic richness, and _Prevotella_-to-_Bacteroides_ ratio)
* Serum metabolites are prefixed with 'metab.', followed by the experiment (SCFA_ or TRP_)
