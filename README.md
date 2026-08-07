**PROJECT OVERVIEW**

Phylogenetic analysis is a method used to determine the evolutionary relationships among organisms by comparing their genetic characteristics and identifying patterns of common ancestry. In this study, mitochondrial cytochrome c oxidase subunit I (COI or COX1) sequences are utilized because this gene is widely applied in DNA barcoding and evolutionary studies due to its high abundance in cells, maternal inheritance, and ability to provide sufficient genetic variation for distinguishing closely related species.
The family Bovidae was chosen because it contains a diverse group of mammals, including cattle, buffaloes, goats, sheep, and antelopes, which display varying degrees of genetic relatedness and are suitable for examining evolutionary relationships through molecular analysis.
The inclusion of _Cervus elaphus_ as an outgroup provides a reference for comparing genetic differences and determining the evolutionary placement of the selected species.
Therefore, this activity aims to construct and analyze a phylogenetic relationship among selected members of the family Bovidae using mitochondrial COI (COX1) gene sequences obtained from the NCBI database. 



**TAXONOMIC GROUP**

The in-group consists of species belonging to the family Bovidae, taxonomically classified under Kingdom Animalia, Phylum Chordata, Class Mammalia, and Order Artiodactyla.
This group is represented by _Bos indicus_, _Bison bison_, _Antilope cervicapra_, _Syncerus caffer_, _Capra hircus_,_ Ovis aries_, and _Bos taurus_. As bovids, these species share defining physical traits suited for herbivorous diets, such as permanent, unbranched horns and multi-chambered ruminant stomachs.
The out-group is the family Cervidae, represented by the Red Deer (_Cervus elaphus_).
While Cervidae shares the identical higher taxonomic hierarchy—Kingdom Animalia, Phylum Chordata, Class Mammalia, and Order Artiodactyla—it branches into a distinct family.
Because _Cervus elaphus_ shares a common artiodactyl origin with bovids but diverged before the bovid family evolved its specialized features, distinct cervid traits such as shed antlers serve as a baseline.



**METHODS**

Mitochondrial cytochrome c oxidase subunit I (COI) sequences for selected Bovidae species and the outgroup Cervus elaphus were retrieved from the NCBI Nucleotide database using target keywords ("COI", "COX1", "mitochondrion") to ensure coverage of the same gene region and comparable sequence lengths.
The downloaded FASTA files were uploaded to Galaxy, renamed with short species labels, and merged into a single multi-FASTA file.
Multiple sequence alignment was performed using MAFFT under default settings to generate uniform, co-linear alignment sequences with gaps denoted by dashes.
To summarize common nucleotide patterns and assess conserved and variable sites, a consensus sequence was generated using the Galaxy consensus sequence tool for sequence analysis only.
Finally, the aligned dataset was used to construct a Newick-formatted phylogenetic tree via FastTree, which was visualized using the Galaxy tree viewer and rooted with _C. elaphus_ to analyze sister taxa, major clades, and branch lengths against published Bovidae phylogenies within the complete Galaxy workflow.


**FIGURES**

<img width="468" height="225" alt="Figure 1" src="https://github.com/user-attachments/assets/677ed447-d7b9-4780-a4c4-a3b11fbd0cc5" />

**Figure 1.** MAFFT alignment screenshot: Gaps were replaced with dash (-) to make every sequence the exact same length. This transforms the raw, unaligned sequences into uniform, co-linear alignment sequences. 


<img width="468" height="217" alt="Figure 2" src="https://github.com/user-attachments/assets/dae090b9-05eb-4c14-b57d-6c32f866b07f" />

**Figure 2.** Galaxy analysis history overview for Group_3_Bovidae showing the complete workflow. The panel displays the user account, history title, uploaded multi-FASTA files, and the successive outputs generated from MAFFT alignment, FastTree phylogenetic tree construction, and consensus sequence generation.


<img width="468" height="90" alt="Figure 3" src="https://github.com/user-attachments/assets/530f3407-bc51-4aa2-900c-065bd1615804" />

**Figure 3.** A screenshot of Representative MAFFT alignment. 


<img width="490" height="369" alt="Figure 4" src="https://github.com/user-attachments/assets/8ecc025b-c323-4e1c-abc9-2efcb1cba0b2" />

**Figure 3.** Phylogenetic tree of selected Bovidae species based on mitochondrial COI sequences. 

The phylogenetic tree constructed from mitochondrial cytochrome c oxidase subunit I (COI) sequences shows the evolutionary relationships among selected members of the family Bovidae, with _Cervus elaphus_ (family Cervidae) serving as the outgroup.
The outgroup branches separately from all Bovidae, confirming that it is more distantly related and providing a reference for rooting the tree. Within the Bovidae, two major clades are evident.
The first includes _Syncerus caffer_, _Bison bison_, _Bos taurus_, and _Bos indicus_, while the second consists of _Antilope cervicapra_, _Capra hircus_, and _Ovis aries_.
The closest sister taxa are _Bos taurus_ and _Bos indicus_, reflecting their recent common ancestry within the genus Bos.
Likewise, _Capra hircus_ and _Ovis aries_ form another pair of closely related sister taxa within the subfamily Caprinae.
_Bison bison_ is closely related to the Bos species, whereas _Syncerus caffer_ diverges earlier within the cattle lineage.
The branch lengths indicate the amount of genetic divergence among the COI sequences, with shorter branches representing closer genetic relationships.
Overall, the tree is consistent with the accepted taxonomy of Bovidae.
However, because it is based on a single mitochondrial gene, it should not be regarded as the definitive species phylogeny, as more comprehensive analyses generally incorporate multiple mitochondrial and nuclear genes to better resolve evolutionary relationships. 



**DISCUSSION**

Our COI phylogenetic tree is largely consistent with the molecular phylogeny reported by Hassanin et al. (2012).
First, both trees recover _Bos taurus_ and _Bos indicus_ as sister taxa, reflecting their close evolutionary relationship within the genus Bos (Hassanin et al., 2012).
Second, _Capra hircus_ and _Ovis aries_ are also grouped together as sister taxa in both phylogenies, supporting their shared ancestry within the subfamily Caprinae (Hassanin et al., 2012). 
Our results also agree with the phylogenetic analysis of Bibi (2013). Similar to our tree, Bibi recovered the tribe Bovidae including Bos, Bison, and Syncerus, as a distinct evolutionary lineage within Bovidae. In both trees, _Bison bison_ is more closely related to the Bos species than to goats or sheep, and _Syncerus caffer_ belongs to the same broader cattle lineage (Bibi, 2013). 

One difference between our phylogeny and the published studies is the branching position of _Syncerus caffer_ within the tribe Bovidae.
Although our tree recovered _Syncerus caffer_ as part of the Bovidae lineage, its exact branching position differs slightly from those reported by Bibi (2013) and Hassanin et al. (2012).
These differences are likely due to the use of a single mitochondrial marker (COI) and a smaller number of taxa in our analysis, whereas the published studies included multiple mitochondrial and nuclear genes, larger taxon sampling, and different phylogenetic reconstruction methods.



**REFERENCES:**

Antilope cervicapra voucher BB-BRC5 cytochrome c oxidase subunit I (CO) - Nucleotide - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/nuccore/MT251370.1?report=fasta 

Bibi, F. (2013). A multi-calibrated mitochondrial phylogeny of extant Bovidae (Artiodactyla, Ruminantia) and the importance of the fossil record to systematics. BMC Evolutionary Biology, 13(1), 166. https://doi.org/10.1186/1471-2148-13-166 

Bison bison voucher HBL008230 cytochrome oxidase subunit 1 (COI) gene - Nucleotide - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/nuccore/JF443195.1?report=fasta 

Bos taurus isolate Nanyang_cattle7-B-COI-9.seq cytochrome c oxidase subunit I - Nucleotide - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/nuccore/MZ099227.1?report=genbank 

Capra hircus voucher T2186 cytochrome oxidase subunit 1 (COX1) gene - Nucleotide - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/nuccore/OK184394.1?report=fasta 

Cervus elaphus voucher 14-528 cytochrome oxidase subunit 1 (COI) gene - Nucleotide - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/nuccore/MZ402619.1?report=fasta 

COX1 cytochrome c oxidase subunit I [Ovis aries (sheep)] - Gene - NCBI. (n.d.). https://www.ncbi.nlm.nih.gov/gene/808251 

Galaxy. (n.d.). https://usegalaxy.org/ 

Hassanin, A., Delsuc, F., Ropiquet, A., Hammer, C., van Vuuren, B. J., Matthee, C., Ruiz-Garcia, M., Catzeflis, F., Areskoug, V., Nguyen, T. T., & Couloux, A. (2012). Pattern and timing of diversification of Cetartiodactyla (Mammalia, Laurasiatheria), as revealed by a comprehensive analysis of mitochondrial genomes. Comptes Rendus Biologies, 335(1), 32–50. https://www.sciencedirect.com/science/article/abs/pii/S1055790312004344 

National Center for Biotechnology Information (NCBI). (n.d.). GenBank overview. U.S. National Library of Medicine. https://www.ncbi.nlm.nih.gov/nuccore


