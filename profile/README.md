# byandell-sysgen Organization

These repositories study methods for
[Systems Genetics](https://www.nature.com/articles/nrg3575),
[Systems Genomics](https://www.nature.com/articles/s41598-020-75400-2)
and 
[Omics](https://www.ncbi.nlm.nih.gov/books/NBK202165/).
I have been involved in this work for over 25 years.
The vast majority concern gene mapping, or QTLs.
They are organized by subject under dropdown menus.

<details>
<summary>QTL Repos</summary>
<br>

QTL stands for
[quantitative trait loci](https://www.nature.com/scitable/topicpage/quantitative-trait-locus-qtl-analysis-53904/),
which is also known as gene mapping.
Recent work builds on Karl Broman's
[R/qtl2](https://kbroman.org/qtl2/)
package,
offering [ggplot2](https://ggplot2.tidyverse.org/) functionality as well as deeper dives into 
[SNP](https://www.genome.gov/genetics-glossary/Single-Nucleotide-Polymorphisms)
patterns.
The `qtl2shiny` package provides a friendly interface to investigate local QTL behavior.
It draws on mediation repos found in another dropdown menu.
Earlier work builds on Broman's
[R/qtl](https://rqtl.org/)
package, and includes some useful features (notably hotspot analysis) not yet fully migrated to `R/qtl2`.
  
| repo | title | type |
| ---- | ----- | ----- |
| [`qtl2`](https://github.com/byandell-sysgen/qtl2) |QTL analysis software for high-dimensional data and complex cross designs | [Broman R/qtl2](https://kbroman.org/qtl2/) |
| [`qtl2ggplot`](https://github.com/byandell-sysgen/qtl2ggplot) | Extension of R/qtl2plot to ggplot2 | R graphics |
| [`qtl2pattern`](https://github.com/byandell-sysgen/qtl2pattern) | Pattern support for R/qtl2 | R analysis |
| [`qtl2shiny`](https://github.com/byandell-sysgen/qtl2shiny) | Shiny app for R/qtl2 | R shiny |
| [`qtl2hot`](https://github.com/byandell-sysgen/qtl2hot) | Hot Spot Analysis with Qtl2 | R analysis in devel |
|||
| [`qtl`](https://github.com/byandell-sysgen/qtl) | Branch of Karl Broman's R/qtl | [Broman R/qtl](https://rqtl.org/) |
| [`qtlbim`](https://github.com/byandell-sysgen/qtlbim) | QTL Bayesian Interval Mapping | R analysis |
| [`qtlnet`](https://github.com/byandell-sysgen/qtlnet) | Infer QTL genetic architecture and causal network for set of correlated traits | R analysis |
| [`qtlhot`](https://github.com/byandell-sysgen/qtlhot) | QTL hotspot inference | R analysis |
| [`qtlbcsft`](https://github.com/byandell-sysgen/qtlbcsft) | Tools for testing QTL BCsFt calculations | R analysis |
| [`qtlyeast`](https://github.com/byandell-sysgen/qtlyeast) | QTL Analysis of Brem Kruglyak Yeast Data | R data |
  
</details>
<details>
<summary>Mediation Repos</summary>
<br>

Mediation repos build on the excellent work of
[Elias Chaibub Neto](https://www.linkedin.com/in/elias-chaibub-neto-a469913b/)
on causal model selection tests.
This is incorporated into the `qtl2shiny` app cited in the QTL dropdown menu.
  
| repo | title | type |
| ---- | ----- | ----- |
| [`intermediate`](https://github.com/byandell-sysgen/intermediate) | small R utility for mediation analysis | [Churchill Lab](https://github.com/churchill-lab/intermediate) |
| [`qtl2mediate`](https://github.com/byandell-sysgen/qtl2mediate) | Mediation using package qtl2 | R analysis |
| [`Tmem68`](https://github.com/byandell-sysgen/Tmem68) | Tmem68 mRNA Data example from Chick et al. 2016 | [Churchill Lab](https://github.com/churchill-lab/intermediate) |
| [`qtlcmst`](https://github.com/byandell-sysgen/qtlcmst) | QTL Causal Model Selection Tests | R analysis |
| [`CausalMST`](https://github.com/byandell-sysgen/CausalMST) | Causal Model Selection Hypothesis Tests | see `intermediate` and `qtl2mediate` |
| [`qdg`](https://github.com/byandell-sysgen/qdg) | QTL Directed Graphs | R analysis defunct? |
  
</details>
<details>
<summary>Founder Repos</summary>
<br>

These repos study the
[Collaborative Cross (CC)](https://www.nature.com/articles/ng1104-1133)
mouse founder lines.
See `foundr` for information about deployed shiny apps.
  
| repo | title | type |
| ---- | ----- | ----- |
| [`foundr`](https://github.com/byandell-sysgen/foundr) | Multiparent Founder Study Tools | R analysis |
| [`foundrShiny`](https://github.com/byandell-sysgen/foundrShiny) | Shiny app tools for foundr package | R shiny |
| [`foundrHarmony`](https://github.com/byandell-sysgen/foundrHarmony) | Harmonize data for foundr analysis and visualization | R tidy data |
| [`metabr`](https://github.com/byandell-sysgen/metabr) | Metabolite Data Processing | R analysis |
| [`modulr`](https://github.com/byandell-sysgen/modulr) | Trait Module Creation and Analysis | R analysis |
  
</details>
<details>
<summary>Attie Lab Repos</summary>
<br>

These repos are specific to collaboration with the
[Alan Attie Lab](https://attielab.biochem.wisc.edu/)
at UW-Madison Biochemistry.
This is part of a long-term collaboration (>25 years) that has inspired much of my work.
  
| repo | title | type |
| ---- | ----- | ----- |
| [`FounderDietStudy`](https://github.com/byandell-sysgen/FounderDietStudy) | Founder Diet Study Application | [Attie Lab](https://github.com/AttieLab-Systems-Genetics) |
| [`FounderCalciumStudy`](https://github.com/byandell-sysgen/FounderCalciumStudy) | Founder Calcium Study Application | [Attie Lab](https://github.com/AttieLab-Systems-Genetics) |
| [`DO_Diet`](https://github.com/byandell-sysgen/DO_Diet) | DO Diet Study Application | [Attie Lab](https://github.com/AttieLab-Systems-Genetics) |
| [`AttieDOv2`](https://github.com/byandell-sysgen/AttieDOv2) | Attie DO 500 Study Application | R tidy data |
  
</details>
<details>
<summary>Other Repos</summary>
<br>

These other repos include a workshop in Thailand in 2017 and various projects that have not moved forward.
  
| repo | title | type |
| ---- | ----- | ----- |
| [`PlantSysGen`](https://github.com/byandell-sysgen/PlantSysGen) | Thailand Plant Systems Genetics Workshop 2017 | R analysis |
| [`thailand`](https://github.com/byandell-sysgen/thailand) | Thailand Plant Systems Genetics Workshop 2017 | HTML presentation |
|||
| [`qtl2rmd`](https://github.com/byandell-sysgen/qtl2rmd) | Rmarkdown for qtl2 analyses | R analysis defunct? |
| [`qtl2feather`](https://github.com/byandell-sysgen/qtl2feather) | R/qtl2 package using feather to store genotype probabilities | R analysis defunct? |
| [`CCSanger`](https://github.com/byandell-sysgen/CCSanger) | Pull Sanger features for CC founder strains | R analysis defunct? |
| [`qtl2biome`](https://github.com/byandell-sysgen/qtl2biome) | R/qtl2 package for microbiome data analysis | R early stages |
| [`Rbiodalliance`](https://github.com/byandell-sysgen/Rbiodalliance) | R wrapper for biodalliance.org | R analysis defunct? |
| `qtlview`](https://github.com/byandell-sysgen/qtlview) | Utilities to view QTL results on the Web | R graphics defunct? |
