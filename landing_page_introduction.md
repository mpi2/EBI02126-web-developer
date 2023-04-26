Introduction to IMPC Embryo Data
--------------------------------

Up to one third of homozygous knockout lines are lethal, which means no homozygous mice or less than expected are observed past the weaning stage (IMPC [Viability Primary Screen procedure](//www.mousephenotype.org/impress/ProcedureInfo?action=list&procID=703&pipeID=7)). Early death may occur during embryonic development or soon after birth, during the pre-weaning stage. For this reason, the IMPC established a [systematic embryonic phenotyping pipeline](//www.mousephenotype.org/impress) to morphologically evaluate mutant embryos to ascertain the primary perturbations that cause early death and thus gain insight into gene function.

As determined in IMPReSS (see interactive diagram [here](//www.mousephenotype.org/impress)), all embryonic lethal lines undergo gross morphology assessment at E12.5 (embryonic day 12.5) to determine whether defects occur earlier or later during embryonic development. A comprehensive imaging platform is then used to assess dysmorphology. Embryo gross morphology, as well as 2D and 3D imaging are actively being implemented by the IMPC for lethal lines.

Read more in our paper on [High-throughput discovery of novel developmental phenotypes, Nature 2016.](https://europepmc.org/article/PMC/5295821)

Accessing Embryo Phenotype Data
-------------------------------

Embryo phenotype data can be accessed in multiple ways:

*   [Embryo Images: interactive heatmap](/data/embryo_imaging) A compilation of all our Embryo Images, organised by gene and life stage, with access to the Interactive Embryo Viewer, where you can compare mutants and wild types side by side and rotate 2D and 3D images; we also provide access to our external partners' embryo images.
*   [Embryo Vignettes](/data/embryo/vignettes) Showcase of best embryo images with detailed explanations.
*   [From the FTP site, latest release](ftp://ftp.ebi.ac.uk/pub/databases/impc/all-data-releases/latest/results/) All our results. Reports need to be filtered by a dedicated column, Life Stage (E9.5, E12.5, E15.5 and E18.5). Please check the README file or see documentation [here](https://www.mousephenotype.org/help/non-programmatic-data-access/).
*   Using the REST API (see documentation [here](https://www.mousephenotype.org/help/programmatic-data-access/))

Determining Lethal Lines
------------------------

The IMPC assesses each gene knockout line for viability (Viability Primary Screen [IMPC\_VIA\_001](//www.mousephenotype.org/impress/ProcedureInfo?action=list&procID=703&pipeID=7)). In this procedure, the proportion of homozygous pups is determined soon after birth, during the preweaning stage, in litters produced from mating heterozygous animals. A line is declared lethal if no homozygous pups for the null allele are detected at weaning age, and subviable if pups homozygous for the null allele constitute less than 12.5% of the litter.

Lethal strains are further phenotyped in the [embryonic phenotyping pipeline](//www.mousephenotype.org/impress). For embryonic lethal and subviable strains, heterozygotes are phenotyped in the IMPC [adult phenotyping pipeline](//www.mousephenotype.org/impress).