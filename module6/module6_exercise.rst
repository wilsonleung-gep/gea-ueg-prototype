Module 6
============

.. role:: underline
     :class: underline


.. rubric:: Module 6: Alternative splicing
     :class: header1

:Author: Leocadia Paliulis (Bucknell University)
:Last Update: |today|
:Version: |version|



Investigation 1: Construct the gene model for tra-RB
----------------------------------------------------------------------

In this investigation, we will focus on tra-RB, the second
:term:`isoform` of the *tra* gene, and will explore how multiple
different mRNAs and polypeptides can be encoded by the same gene. The
story of tra-RB is an exciting story of sex,
:term:`alternative splicing`, and poison :term:`exons <exon>`!


1. To begin, open a web browser


2. Go to the UCSC Genome Browser Mirror site at
   http://gander.wustl.edu/ and follow the instructions given in
   :ref:`module1/module1_exercise:Module 1` to open ``contig1``
   of *Drosophila melanogaster*, using the ``July 2014
   (Gene)`` assembly rather than the "Aug. 2014 (BDGP Release 6 + ISO1
   MT/dm6)" assembly. Once you are on the Genome Browser page, set "Base
   Position" (under the "Mapping and Sequencing Tracks" bar) to
   ``full`` so that you will be able see the three possible reading
   :term:`frames <frame>` (remember that you will not see individual
   :term:`bases <base>` or :term:`amino acids <amino acid>` until you
   zoom in, though). Also set "FlyBase Genes" (under the "Genes and
   Gene Predictions" bar) to ``full``. Don't forget to click on one of
   the ``refresh`` buttons to see your changes.


3. Enter the following coordinates into the "enter position or
   search terms" text box: ``contig1:9,700-11,000`` and hit the
   ``go`` button to get a good view of the *tra* gene
   (:numref:`Figure %s <module6_figure_1>`).

.. figure:: /_static/images/module6/Figure1.png
   :alt: Genome Browser view of the *tra* gene
   :name: module6_figure_1

   Center the browser on the *tra* gene.


4. Let's consider what we know about tra-RA and learn more about tra-RB.


.. admonition:: Question 1
   :class: admonition-question

   Given that exons are shown by the black boxes, and introns are
   shown by thin lines with arrowheads in the FlyBase Genes track, what
   does this tell us about the first intron of tra-RB compared to that
   of tra-RA?


5. Now let's look at the patterns of :term:`transcription`. Scroll down
   to "RNA Seq Tracks", click on the ``RNA-Seq Coverage`` link. Change
   the track display settings as we did in
   :ref:`module2/module2_exercise:Module 2`:

   - Set the "Display mode" to ``full``

   - Set the "Data view scaling" field to ``use vertical viewing
     range setting``

   - Set the "max" field under "Vertical viewing range" to ``37``

   - Check both ``Adult Females`` and ``Adult Males`` under "List
     subtracks"

   - Hit the ``Submit`` button
     (:numref:`Figure %s <module6_figure_2>`)


.. figure:: /_static/images/module6/Figure2.png
   :alt: Configure the display settings for the RNA-Seq tracks
   :name: module6_figure_2

   Enter settings for RNA Seq tracks.


6. Back on the browser main page

   - Under "RNA Seq Tracks", change the display mode for the
     "Exon Junctions" track to ``full``, then hit ``refresh``.


.. tip::
   To review the use of RNA Seq data, watch the
   `RNA Seq and TopHat video <https://youtu.be/qepVXEsfLMM>`_


Now we can see the RNA-Seq data for males (red) and females (blue).
Recall that peaks in RNA-Seq Read Coverage tracks usually correspond to
the regions of the genome that are being transcribed. These two samples
generally show similar RNA-Seq read coverage along the entire span of
the *tra* gene. However, the adult female sample shows substantially
lower RNA-Seq read coverage at around 9,971-10,145 (red box in
:numref:`Figure %s <module6_figure_3>`). We can also see the RNA-Seq
Exon Junctions track, which shows the location of splice sites
supported by the RNA-Seq data (as you saw in
:ref:`Module 4 <module4/module4_exercise:Investigation
2\: Identifying splice sites>`). Recall that
the black boxes in the FlyBase Genes track are exons and the thin
lines with arrowheads show the locations of the :term:`introns <intron>`.
Notice that the diagrams for the first and second RNA-Seq Exon
Junctions tracks have the same :term:`5'` splice site but different
:term:`3'` splice sites. Let's see what we can find out about these
splice sites.

.. figure:: /_static/images/module6/Figure3.png
   :alt: Gene predictions and RNA-Seq data for *tra*
   :name: module6_figure_3

   Browser showing gene predictors, RNA-Seq tracks, and RNA-Seq
   exon junctions for male and female *Drosophila melanogaster*.


7. First, we need to establish the reading frame for the first exon. Zoom
   in on the 5' end of the transcript around position ``contig1:9850-9860``.

.. admonition:: Question 2
   :class: admonition-question

   Given what you know about the initiation of translation, which
   of the 3 possible reading frames is used for both the tra-RA and tra-RB
   products?


8. Now zoom in on the location of the 5' splice site at the end of the
   first exon in both tra-RA and tra-RB
   (:numref:`Figure %s <module6_figure_4>`). We will also be thinking
   about the concept of :term:`phase` here. To review :term:`splicing`
   and phase, watch the
   `Splicing and Phase video <https://youtu.be/JsvUfHy3eHE>`_.


.. figure:: /_static/images/module6/Figure4.png
   :alt: Splice donor site for intron 1
   :name: module6_figure_4

   Zoom in on the first 5' splice site.


.. admonition:: Question 3
   :class: admonition-question

   Give the coordinate for the last base of the first exon for tra-RA.


.. admonition:: Question 4
   :class: admonition-question

   Give the coordinate for the last base of the first exon for tra-RB.


.. admonition:: Question 5
   :class: admonition-question

   What is the consensus sequence for the 5' splice site (donor site)?


.. admonition:: Question 6
   :class: admonition-question

   What are the coordinates for the 5' splice site in tra-RA?


.. admonition:: Question 7
   :class: admonition-question

   What are the coordinates for the 5' splice site in tra-RB?


.. admonition:: Question 8
   :class: admonition-question

   What is the phase at this splice site?


9. Now zoom out and zoom in on the start of the second exon in tra-RB,
   just after the 3' splice site (:numref:`Figure %s <module6_figure_5>`).
   We can identify the second exon by the RNA-Seq data, in particular
   using the RNA-Seq Exon Junctions data.

.. figure:: /_static/images/module6/Figure5.png
   :alt: Splice acceptor site for intron 1 of tra-RB
   :name: module6_figure_5

   Zoom in on the start of second exon in tra-RB.


.. admonition:: Question 9
   :class: admonition-question

   What are the coordinates for the first base of the second exon
   in tra-RB?


.. admonition:: Question 10
   :class: admonition-question

   What is the consensus sequence for the 3' splice site?


.. admonition:: Question 11
   :class: admonition-question

   What are the coordinates for the 3' splice site in intron 1 of
   tra-RB?


.. admonition:: Question 12
   :class: admonition-question

   What phase do we anticipate?


.. admonition:: Question 13
   :class: admonition-question

   Given this, what is the reading frame for tra-RB exon2?


.. admonition:: Question 14
   :class: admonition-question

   Does this make sense, given the location of stop codons?


10. Now zoom out and zoom in on the 3' splice site for tra-RA.
    (:numref:`Figure %s <module6_figure_6>`). This can
    be identified from the RNA-Seq data, particularly the RNA-Seq Exon
    Junctions.

.. figure:: /_static/images/module6/Figure6.png
   :alt: Splice acceptor site for intron 1 of tra-RA
   :name: module6_figure_6

   Zoom in on start of second exon for tra-RA.


.. admonition:: Question 15
   :class: admonition-question

   What are the coordinates for the first base of the second exon
   in tra-RA?


.. admonition:: Question 16
   :class: admonition-question

   What is the consensus sequence for the 3' splice site?


.. admonition:: Question 17
   :class: admonition-question

   What are the coordinates for that sequence in intron 1 of tra-RA?


.. admonition:: Question 18
   :class: admonition-question

   Given the phase at the donor site, what phase are we looking
   for here?


.. admonition:: Question 19
   :class: admonition-question

   Given this, what is the reading frame for tra-RA exon 2?


.. admonition:: Question 20
   :class: admonition-question

   Does this make sense, given the location of stop codons?


The 3' acceptor site for the second intron in tra-RA is found inside the
second exon of tra-RB. This intron is
:term:`alternatively spliced <alternative splicing>`.
Alternative splicing is one way eukaryotes produce different proteins
from the same coding regions of DNA. Here the alternative decision is
made in a sex-specific manner; male fruit flies have targeted the
spliceosome to use the first 3' acceptor site identified by the RNA-Seq
Exon Junction data, while female fruit flies have targeted the
spliceosome to use the second 3' acceptor site identified. This change
in splicing has profound effects --- in fact, it drives the programming of
male and female characteristics in the developing fly. To review
alternative splicing, watch the
`Genes and Isoforms video <https://youtu.be/8jtTp_6vN4M>`_.


11. Reset your browser by entering ``contig1:9,700-11,000`` into the
    "enter position or search terms" text box and hit ``go``. Let's
    analyze the consequences of this alternative splicing on
    production of a protein product.


.. admonition:: Question 21
   :class: admonition-question

   From your analysis of the A isoform of *tra* in
   :ref:`Module 5 <module5/module5_exercise:Investigation 2: Construct the
   gene model for tra-RA>`, how many amino acids does the tra-RA
   protein product have?


Now look at the tra-RB isoform:

.. admonition:: Question 22
   :class: admonition-question

   Write down the coordinates for exon 1.


.. admonition:: Question 23
   :class: admonition-question

   Given the reading frame that you established for tra-RB, does
   translation continue through exon 2, or is it terminated by a stop
   codon?


.. admonition:: Question 24
   :class: admonition-question

   Write down the coordinates for the translated portion of exon 2.


.. admonition:: Question 25
   :class: admonition-question

   How many amino acids does the protein translated from the
   tra-RB isoform have?


.. admonition:: Question 26
   :class: admonition-question

   Is it likely that the protein translated from tra-RB could play
   the same functional role played by the protein translated from tra-RA?


.. note::

   The Tra protein has an important function in female *Drosophila*, and is
   itself a splicing factor that regulates splicing. Careful
   :term:`annotation` of genes, as we have done here, can provide many
   insights into biological control mechanisms.



Investigation 2: Polypeptides produced from each isoform of *tra*
----------------------------------------------------------------------

Now that we know that *tra* is alternatively spliced to make two
isoforms, tra-RA and tra-RB, and that males express one isoform while
females express the other, let's try to figure out how alternative
splicing affects the polypeptides produced from translating these mRNAs.
To do this, we need to produce a gene model for tra-RB and compare it to
the gene model for tra-RA that you constructed in
:ref:`module5/module5_exercise:Module 5`, showing
where the :term:`start codons <initiation codon (start codon)>` and
:term:`stop codons <stop codon (termination codon)>` appear in each
isoform.

Use what you learned in
:ref:`Module 5 <module5/module5_exercise:Investigation 2\:
Construct the gene model for tra-RA>` to construct a gene model for
tra-RB. Locate the start codon, splice sites, and the stop codon.
Construct the gene model below.


.. admonition:: Question 27
   :class: admonition-question

   :underline:`Gene model for tra-RB:`

   - Coordinate for start of translation: \_____________\_
   - Coordinate for last base of exon 1: \_____________\_
   - Coordinate for first base of exon 2: \_____________\_
   - Coordinate for last base of exon 2: \_____________\_
   - Coordinate for first base of exon 3: \_____________\_
   - Stop codon coordinates: \__________________________\_


Points for discussion
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- How does the polypeptide translated from the tra-RB isoform differ from
  the polypeptide translated from the tra-RA isoform? What are the
  consequences of these differences on protein function?

- Discuss how the bigger mRNA leads to creation of a smaller polypeptide!!

- Consider how alternative splicing could allow many different proteins to
  be encoded by the same gene.

- Based on the gene structure of the two isoforms of *tra* shown in the
  "FlyBase Genes" track, provide a hypothesis that could explain this
  difference in RNA-Seq read coverage between the adult males sample and
  adult females sample.
