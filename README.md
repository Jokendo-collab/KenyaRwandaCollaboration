## Project workplan
This is the repository for Kenya and Rwanda collaboration for COVID-19 project.
We shall do the following:
- [x] Sample download
- [x] Sample annotation
- [x] Individual country analysis
- [x] Squence alignment using muscle aligner: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-5-113
- [x] Aliview program: https://ormbunkar.se/aliview/
- [x] We shall use BEAST analysis, from which we get an estimated substitution rate
- [x] BEAST Software - Bayesian Evolutionary Analysis Sampling: http://beast.community/

## Results
- Phylogenetic tree visualizations: 
## Rwanda samples
![rwandaOnlyData](https://github.com/javanOkendo/KenyaRwandaCollaboration/blob/main/Figures/RwandaOnlyData.png)
> ## Evolutionary relationships of taxa 
The evolutionary history was inferred using the Neighbor-Joining method [1]. The bootstrap consensus tree inferred from 1000 replicates [2] is taken to represent the evolutionary history of the taxa analyzed [2]. Branches corresponding to partitions reproduced in less than 50% bootstrap replicates are collapsed. The evolutionary distances were computed using the Maximum Composite Likelihood method [3] and are in the units of the number of base substitutions per site. This analysis involved 37 nucleotide sequences. Codon positions included were 1st+2nd+3rd. All ambiguous positions were removed for each sequence pair (pairwise deletion option). There were a total of 30084 positions in the final dataset. Evolutionary analyses were conducted in MEGA X [4]

1. Saitou N. and Nei M. (1987). The neighbor-joining method: A new method for reconstructing phylogenetic trees. Molecular Biology and Evolution 4:406-425.
2. Felsenstein J. (1985). Confidence limits on phylogenies: An approach using the bootstrap. Evolution 39:783-791.
3. Tamura K., Nei M., and Kumar S. (2004). Prospects for inferring very large phylogenies by using the neighbor-joining method. Proceedings of the National Academy of Sciences (USA) 101:11030-11035.
4. Kumar S., Stecher G., Li M., Knyaz C., and Tamura K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. Molecular Biology and Evolution 35:1547-1549.

![phylotree](https://github.com/javanOkendo/KenyaRwandaCollaboration/blob/main/Figures/boostrapTreeNewic.png)
> Phylogenetic tree comparing the four sample groups from Kenya, Rwanda, Uganda and Democratic republic of Congo

![phylo](https://github.com/javanOkendo/KenyaRwandaCollaboration/blob/main/Figures/boostrapTreeNewiccr.png)
![xx](https://github.com/javanOkendo/KenyaRwandaCollaboration/blob/main/Figures/boostrapTreeNewicseccircle.png)
Phylogenetic tree construction
> ## Table. Estimate of the Mean Evolutionary Diversity for the Entire Population
The number of base substitutions per site from mean diversity calculations for the entire population was 87.46 shown  [1]. Standard error estimate(s) (76.68) are shown in the second column and were obtained by a bootstrap procedure (1000 replicates). Analyses were conducted using the Maximum Composite Likelihood model [2]. This analysis involved 99 nucleotide sequences. Codon positions included were 1st+2nd+3rd. All ambiguous positions were removed for each sequence pair (pairwise deletion option). There were a total of 30232 positions in the final dataset. Evolutionary analyses were conducted in MEGA X [3]

1. Nei M. and Kumar S. (2000). Molecular Evolution and Phylogenetics. Oxford University Press, New York.
2. Tamura K., Nei M., and Kumar S. (2004). Prospects for inferring very large phylogenies by using the neighbor-joining method. Proceedings of the National Academy of Sciences (USA) 101:11030-11035.
3. Kumar S., Stecher G., Li M., Knyaz C., and Tamura K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. Molecular Biology and Evolution 35:1547-1549.

## Tajima's D neutrality test

Table. Results from Tajima's Neutrality Test [1]
Tajima's D was -0.499890. This analysis involved 37 nucleotide sequences. Codon positions included were 1st+2nd+3rd. All ambiguous positions were removed for each sequence pair (pairwise deletion option). There were a total of 30084 positions in the final dataset. Evolutionary analyses were conducted in MEGA X [2]. This data shows a recent selective sweep, population expansion after a recent bottleneck, linkage to a swept gene.

Abbreviations: m = number of sequences, n = total number of sites, S = Number of segregating sites, ps = S/n, Θ = ps/a1, π = nucleotide diversity, and D is the Tajima test statistic (see chapter 12 in ref. [3] for details).

1. Tajima F. (1989). Statistical methods to test for nucleotide mutation hypothesis by DNA polymorphism. Genetics 123:585-595.
2. Kumar S., Stecher G., Li M., Knyaz C., and Tamura K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. Molecular Biology and Evolution 35:1547-1549.
3. Nei M. and Kumar S. (2000). Molecular Evolution and Phylogenetics. Oxford University Press, New York.

