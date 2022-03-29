- **What is ATACseq?** ATAC-seq stands for **A**ssay for **T**ransposase-**A**ccessible **C**hromatin with high-throughput **seq**uencing and is a method that relies on next-generation sequencing (NGS) library construction using the hyperactive transposase Tn5 to insert Illumina sequencing adaptors into accessible chromatin regions and determine chromatin accessibility across the genome.

  Chromatin accessibility is the degree to which nuclear macromolecules are able to physically contact chromatinized DNA and is determined by the occupancy and topological organization of nucleosomes as well as other chromatin-binding factors that occlude access to DNA and it plays an essential role in establishing and maintaining cellular identity.
  
  The nucleosome — a core structural element of chromatin — consists of an octamer of histone proteins encircled by ~147 bp of DNA. The composition and post-translational modification of nucleosomes reflect distinct functional states and regulate chromatin accessibility through a variety of mechanisms, such as altering transcription factor (TF) binding through steric hindrance and modulating nucleosome affinity for active chromatin remodellers.
  
  Internucleosomal DNA is often bound by TFs, RNA polymerases or architectural proteins with linker histones, which facilitate higher-order chromatin organization and regulate access to DNA. This landscape of chromatin accessibility broadly reflects a network of permissible physical interactions through which enhancers, promoters, insulators and chromatin-binding factors cooperatively regulate gene expression- a critical determinant of chromatin organization and function. [1]( ATACseq_Explained/References/SKlemm_2019.pdf)
 
  The accessible genome comprises ~2–3% of total DNA sequence yet captures more than 90% of regions bound by TFs. With the exception of a few TFs that are enriched within either facultative or constitutive hetero chromatin, the overwhelming majority of TFs surveyed within the ENCODE project bind to open chromatin almost exclusively.[2]( ATACseq_Explained/References/RThurman_2012.pdf)
  
  For multicellular systems, TFs have a broad range of functional roles, providing dynamic regulation of transcription on short timescales and establishing and maintaining persistent epigenetic canalization of cell types that share a common genome. Consequently, chromatin accessibility reflects both aggregate TF binding and the regulatory potential of a genetic locus. This perspective establishes an analytical foundation for tracing changes in accessibility to differential binding of transcriptional regulators that determine cellular state.

*nucleosomes confer periodic hypersensitivity across the genome 36 . This periodicity was probed with Southern blot hybridization, showing a canonical 100–200 bp phasing pattern among DNase hypersensitivity sites (DHSs) that is conserved across genomic loci. This and subsequent work 37,38 provided the earliest direct evidence for stereotypical nucleosome phasing.

- **How old is this technique?** The ATAC-seq method was first published in 2013 in the journal [Nature Methods by Jason Buenrostro]( ATACseq_Explained/References/Buenrostro_2013.pdf) in the labs of Howard Chang and William Greenleaf at Stanford University. 

- **What are the main advantages?** Compared to other techniques, such as FAIRE-Seq or DNase-Seq that investigate similar chromatin features, ATACseq uses lower number of cells for the assay (~ 50,000 cells - between 25,000-75,000 cells recomended for the transposition step) and its a simple two-step experimental protocol.

- **How ATAC-seq can be interpreted?** 
It can be viewed as proxies for aggregate TF-binding signals. 

  Bound TFs protect DNA from enzymatic cleavage, and the level of protection is related to the occupancy of TF binding on the DNA. 
  
  Combining accessibility with transcriptional data: given a set of differentially accessible regions between cell types, developmental stages or other experimental conditions, TFs that are potentially involved in regulating the observed epigenetic differences can be identified by asking which TFs are differentially expressed and also putatively bind to differentially accessible DNA. These results underline the value of integrating chromatin accessibility data with functional and other epigenetic data analyses
  
  ** Whereas the majority of TFs bind to accessible
DNA 13 , pioneer factors arguably bind to nucleosomes
and mediate core histone displacement either inde­
pendently or by recruiting ATP-​dependent chromatin
remodeller
