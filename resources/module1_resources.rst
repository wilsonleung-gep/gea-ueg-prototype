Module 1 Instructor Resources
===============================

Lesson Plan
-------------------------------

Title
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Introduction to the Genome Browser: What is a Gene?


Objectives
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Demonstrate basic skills in using the UCSC Genome Browser to navigate
  to a genomic region and to control the display settings for different
  evidence tracks.

- Explain the relationships among DNA, pre-mRNA, mRNA, and protein.


Pre-requisites: knowledge of...
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- DNA structure (base composition, anti-parallel double-stranded helix,
  base-pairing properties)

- Chromosome structure (a chromosome is a continuous DNA molecule, basic
  understanding of chromosome arms)

- Protein structure (proteins are made up of amino acids)


Order
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Warm Up

- Investigation

- Exit


Homework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Discuss the question:  What is a gene?  (Discuss with a partner,
  then as a class.) Emphasize the *function* of a gene; consider how
  the structure of the gene is related to its function.

- Work through the genome browser investigation, with pauses to
  discuss the answers to the questions.

- Conclude with an emphasis on the main points:

- Genes may run in either direction on a chromosome;

- Genes are represented on the genome browser as blocks connected by lines;

- Eukaryotic genes are made up of protein-coding exons (the blocks)
  connected by introns;

- Proteins usually begin with a Methionine (M) and end at a stop codon (*)


Associated Videos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- `Genome Browser video <https://youtu.be/suMC7wmP7tA>`_

- `Tracks video <https://youtu.be/BwwP7cOqr0Y>`_


Module 1 Resources
-------------------------------

The evidence tracks in the Genome Browser are grouped into three
categories:

- Mapping and Sequencing Tracks
     Basically these contain the information obtained from sequencing
     that region of the chromosome. These tracks show the As, Ts, Cs,
     and Gs (``Base Position``) and matches to particular sequences of
     interest (``Short Match``) or to the cleavage sites for different
     "Restriction Enzymes".

- Genes and Gene Prediction Tracks
     These tracks show the genes as they are reported in the Drosophila
     Database (``FlyBase Genes``), and as predicted by a couple of computer
     programs (``Genscan Genes``, ``N-SCAN Genes``). It also contains the
     transcription start site (TSS) annotations (``TSS Annotations``) and *D.
     melanogaster* cDNAs that have been mapped to contig1.

- RNA Seq Tracks
     These tracks show the results of sequencing mRNAs derived from a
     particular tissue and developmental time point. Most of the RNA-Seq
     reads are derived from processed mRNAs (where the introns have been
     removed). The mRNAs are broken into smaller fragments (e.g. via
     nebulization) prior to sequencing (usually using the Illumina HiSeq
     platform). The short reads (~100--125bp) are then mapped against the
     *D. melanogaster* genome. The y-axis of the ``RNA-Seq Coverage`` track
     shows the number of reads that has been mapped to each position of the
     contig (x-axis); this provides an estimate of the expression level.
     The ``Exon Junctions`` track shows the predicted locations of the
     introns. This track is derived from the subset of RNA-Seq reads that
     map partially to each of two adjacent exons (i.e. spliced RNA-Seq
     reads).


.. tip::
     For manipulating tracks, students may need to be reminded to read
     carefully what is immediately under the displayed tracks: Click on a
     feature for detail. Click sidebars for track options. Drag side bars
     or labels up or down to reorder tracks. Drag tracks left or right to a
     new position.
