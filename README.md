# Plant-LysM-Domain-HMM
Here we provide HMM profiles for the identification of LysM domains in plants that were used by our group for the identification and classification by ligand specificity of plant LysM containing Receptor Like Kinases (RLKs) and Receptor Like Proteins (RLPs).
## Description
Different HMM profiles were built with different objectives in mind.
1. LysM-ST: HMM profile for LysM domains built based on the structural alignment of LysM domains from different sources including PDB and AlphaFoldDB. A curated multiple structural alignment of 273 LysM domains was used.
2. LysM-3B: HMM profile for the triple LysM bundles commonly found in plant RLK/Ps. This HMM profile was built from the structural alignment of 48 RLK/Ps extracellular domains (ECD), and 26 sequences added to that alignment with mafft --add option.
3. LysM1, LysM2, LysM3 and LysM1-3: These HMM profiles were built from the LysM_i extracted from the LysM-3B structural alignment.
4. CO, LCO and PGN profiles: These profiles were built from the LysM-3B sub-alignments of RLK/Ps with experimentally determined ligand specificity. All the combinations of HMM were built. LysM-3B X [CO,LCO,PGN]; [LysM1,LysM2,LysM3] X [CO,LCO,PGN]; and [LysM1,LysM2,LysM3] X [Region II, Region IV ]X [CO,LCO,PGN]

## Supplementary files
The supplementary material can be found [Here](https://github.com/maurijlozano/Plant-LysM-Domain-HMM/tree/main/Supplemetary%20files).

## Cite
If you use these profiles please cite: 
1. Improved detection and phylogenetic analysis of plant proteins containing LysM domains. 2023. Dardo Dallachiesa, O. Mario Aguilar, Mauricio J Lozano. bioRxiv 2023.06.21.545963; doi: ttps://doi.org/10.1101/2023.06.21.545963
