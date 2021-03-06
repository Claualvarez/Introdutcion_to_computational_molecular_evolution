# Sequence similarity searching

## Homology

![Homology](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/BelonBirdSkel.jpg/300px-BelonBirdSkel.jpg)

“If the amino acid sequences of two proteins are set side by side in one-to-one correspondence, there may occur an abnormally large number of pairs containing the same amino acid [...] When such a large similarity is found, the proteins are said to be homologous and are considered to possess a common ancestral gene.”
> Walter Fitch. J Mol Biol. 1966


## BLAST


**BLAST algorithm**

![Query word](https://github.com/Claualvarez/Introdutcion_to_computational_molecular_evolution/blob/master/slides/Query_word.jpg)

**BLOSUM62 Substitution matrix**

![BLOSUM62 Substitution matrix](https://github.com/Claualvarez/Introdutcion_to_computational_molecular_evolution/blob/master/slides/BLOSUM62.png)



**PAM250 Substitution matrix**

![PAM250 Substitution matrix](https://github.com/Claualvarez/Introdutcion_to_computational_molecular_evolution/blob/master/slides/PAM250.png)



**Extreme-value distribution.**

![Extreme-value distribution](https://github.com/Claualvarez/Introdutcion_to_computational_molecular_evolution/blob/master/slides/nihms519883f1.jpg)

The human dual specificity protein phosphatase 12 (DUS12_HUMAN) was compared to 38,114 human RefSeq proteins using the SSEARCH program. The distribution of bit-scores for all 38,114 alignments is shown (squares, □) as well as the mathematically expected distribution of normalized similarity scores (z-scores, or standard deviations above and below the mean 0) based on the size of the database, using the extreme-value distribution. The close agreement between the observed and expected distribution of scores reflects the observation that the distribution of unrelated sequence scores is indistinguishable from random (mathematically generated) scores, so sequences with significant sequence similarity can be inferred to be not-unrelated, or homologous.
> Pearson. Curr Protoc Bioinformatics. 2013



**Position specific scoring matrices**
- Protein divergence is not uniform over a protein –some parts are more conserved than others.
- Position specific scoring matrices can capture specific paterns of conservation at different sites in a protein.


**Activity: sequence similarity searching**

1. Sequence vs. sequence database
   
   [NCBI](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
   
   [UniProt](https://www.uniprot.org/blast/)
   
   [KEGG](https://www.genome.jp/tools/blast/)
   
   [PDB](https://www.rcsb.org/pdb/search/advSearch.do?st=SequenceQuery)


2. Profile vs. sequence database AND Sequence vs. profile database 

    [NCBI](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
    
    [HMMER3](https://www.ebi.ac.uk/Tools/hmmer/)
   
3. Profile vs. profile database
 
    [HH-suite](https://toolkit.tuebingen.mpg.de/)

