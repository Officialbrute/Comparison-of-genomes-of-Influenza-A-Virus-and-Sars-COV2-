# Comparison-of-genomes-of-Influenza-A-Virus-and-Sars-COV2-
This project aims to analyze and compare the genomes of Influenza A Virus and Sars COV 2 using
python and its libraries. Influenza virus A and Sars COV 2 were chosen as samples for this study
because both cause similar symptoms upon infection. This project aims to compare the sequences of
both these viruses and see if any similarities exist. The basis of comparison in this
study are :

  • A, U, C, and G content
  
  • GC content of the sequence
  
    ◦ The GC content is an important metric that corresponds to the stability of a sequence. A
      sequence with a higher GC percentage will have more stability as more hydrogen bonds
      are present.
      
    ◦ The melting point can also be predicted using the GC content as a sequence with a
      higher GC content has a higher melting point.
      
   • Skew
   
    ◦ Ideally, a sequence should have an equal number of adenines (A), guanines (G), cytosines
      (C), and thymines/uracils (T/U). However, this is not the case, as there is an
      overabundance of GC or AT residues. This overabundance of residues is called skew.
      
    ◦ Higher GC skew leads to higher stability in most cases.
    
    ◦ Uracil residues are considered in the AT skew as viruses’ RNA does not contain thymine.
    
  • Repeated patterns of length 20 (Kmers)
  
    ◦ Patterns of length 20 are found in the Influenza and Sars COV 2 sequences, and any matches are reported.
    
Another objective of this project is to locate open reading frames in both viruses' forward and reverse strands
. The open reading frames in the forward and reverse strands are located and then
translated. After obtaining the protein sequences, BLASTP is performed to identify similar
sequences in the NCBI database.
