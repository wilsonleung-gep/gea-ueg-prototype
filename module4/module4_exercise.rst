Module 4
============

.. role:: underline
     :class: underline


.. rubric:: Module 4: Removal of introns from pre-mRNA by splicing
     :class: header1

:Author: Meg Laakso (Eastern University)
:Last Update: |today|
:Version: |version|


Investigation 1: Examining RNA-Seq data
----------------------------------------------------------------------

We will continue to focus on :term:`isoform` A of *transformer*
(referred to as tra-RA). Here we will focus on data from experiments
that assess the RNA population in cells. This data can be used to help
us identify :term:`exons <exon>` and :term:`introns <intron>` for the
gene under study.

All RNAs in the cell are collectively known as the "transcriptome," as
almost all RNA is produced by :term:`transcription` from a DNA
template. (In some cases, RNA is made from an RNA template.) The
transcriptome includes messenger RNAs, ribosomal RNAs, transfer RNAs,
and other RNAs that have specialized functions in the cell.

RNA can be harvested from cells or a whole organism like *Drosophila*
and converted to DNA, then sequenced to produce RNA-Seq (RNA Sequencing)
data. First, extracted mRNA that has been fully spliced is copied back
to DNA with the enzyme called **reverse transcriptase**. Short fragments
of the copied or complementary DNA are sequenced, and then these
segments are mapped back to the genome. By analyzing the mapping data,
it is possible to know which and how many messenger RNAs have been
synthesized.

This is a powerful technique that allows us to see when and where
different genes are expressed. This kind of information can help
researchers and clinicians know which genes are expressed in different
types of cancer, for example. Here and in the next modules we are going
to use RNA-Seq data to explore how the *transformer (tra)* gene is
expressed in male vs. female *Drosophila*.

RNA-Seq data can indicate where transcription occurs, to the exact
nucleotide. The number of RNA-Seq fragments that map to a given site
also tells us how many copies of the RNA are present in the sample.
Remember from :ref:`module3/module3_exercise:Module 3` that the
initial RNA transcripts are quickly processed to remove the introns.
Hence in total RNA from a cell, sequences from exons will be much more
abundant than sequences from introns. We will use RNA-Seq data to help
us find the exon-intron boundaries for tra-RA, the isoform of the
*tra* gene that is expressed in female fruit flies.

1. Open a web browser on your computer. Internet Explorer, Mozilla
   Firefox, Safari, or Chrome will work for this investigation. Go to
   the GEP Mirror of the UCSC Genome Browser at http://gander.wustl.edu.
   Follow the instructions given in
   :ref:`module1/module1_exercise:Module 1` to navigate to the contig1
   project in the *D. melanogaster* ``July 2014 (Gene)`` assembly.

.. note::
   **Reminder:** Configure the Genome Browser Gateway page as follows:

   .. cssclass:: compact-list

   1. Select ``D. melanogaster`` under "REPRESENTED SPECIES"

   2. Select ``July 2014 (Gene)`` under "*D. melanogaster* Assembly"

   3. Enter ``contig1`` into the "Position/Search Term" text box

   4. Click on the ``GO`` button


As you will remember, this section of DNA is 11,000
:term:`base pairs <base pair (base pairing)>` long
(:numref:`Figure %s <module4_figure_1>`) and is part of the left arm
of chromosome 3, which is about 28,100,000 bp long. If your Browser
window is showing other evidence tracks, reset by clicking on
``default tracks``.

.. figure:: /_static/images/module4/Figure1.png
   :alt: Genome browser view of contig1
   :name: module4_figure_1

   A screen shot of the "contig1" project.


2. Let's start by setting the evidence tracks we want to see. Click on
   the ``hide all`` button. Then open only the tracks that will provide
   data for this investigation.

3. Change the display mode for the "RNA-Seq Coverage" track to ``full``.
   Click on one of the ``refresh`` buttons.


You will see blue and red histograms representing RNA-Seq data generated
using RNA samples from adult females and adult males, respectively. This
allows us to infer the pattern of RNA synthesis, and to look for
similarities and differences between the sexes. Both similarities and
differences are apparent!


4. Zoom in to view only the *tra* gene by entering
   ``contig1:9,800-10,900`` in the "enter position or search terms"
   text box (:numref:`Figure %s <module4_figure_2>`).

.. figure:: /_static/images/module4/Figure2.png
   :alt: RNA-Seq read coverage for the tra gene
   :name: module4_figure_2

   Histograms representing RNA-Seq data in *transformer* (*tra*).


5. We are now looking at the region of chromosome 3 where the *tra* gene
   is located. Compare the blue and red histograms for Adult Females and
   Adult Males. Note that there are numbers on the y-axis that show how
   many RNA reads (sequences from transcripts) map to that position.


.. admonition:: Question 1
   :class: admonition-question

   List two ways in which the histograms are similar.


.. admonition:: Question 2
   :class: admonition-question

   List one way that the histograms differ (other than color).


To recap: The blue histogram represents the sequenced messenger RNA from
female fruit flies, and represents the form of the *tra* gene referred
to as isoform A (tra-RA). The red histogram represents the RNA-Seq data
from male fruit flies. The mRNA in males is different from that in
females, and this second isoform of the *tra* gene is called isoform B
(tra-RB).

.. admonition:: Question 3
   :class: admonition-question

   Recall that our other evidence (see
   :ref:`module3/module3_exercise:Module 3`) indicates that tra-RA
   extends from 9,851 to 10,846. How many gaps do you see in the
   histograms in this interval?


Each gap corresponds to an intron --- there is very little RNA-Seq
signal for that part of the gene because the intronic RNA was spliced
out before the mRNA was collected and sequenced.


.. admonition:: Question 4
   :class: admonition-question

   How many exons do you see?


Remember that the exon is the "expressed" part of the gene and there
will be either a sharp, or broad, peak in the RNA-Seq histogram.


.. admonition:: Question 5
   :class: admonition-question

   Do females or males make more *transformer* mRNA or do they express
   it at about the same level?


6. Now that you've examined the evidence yourself, let's go back and
   review.

   **Gaps (introns)**
       :numref:`Figure %s <module4_figure_3>` is a screen shot of the
       genome browser with gaps circled. Note that there are 2 gaps in
       females, and 2 gaps in males. The first gap in females looks a
       little strange because it doesn't have clean boundaries, suggesting
       a mixed population of processed transcripts.

   **Exons**
       Brackets have been drawn underneath the RNA-Seq data for
       Adult Female flies, corresponding to the three exons that are
       expressed.

   **Isoforms**
       Note that isoform A and isoform B of the *tra* gene
       are the result of :term:`alternative splicing`. For other
       genes, isoforms may have **different transcription start
       sites**. Isoforms of a gene always have different mRNA
       sequences, but they may have the same protein sequence. To
       learn more about isoforms and genes, watch the
       `Genes and Isoforms video <https://youtu.be/8jtTp_6vN4M>`_.


.. figure:: /_static/images/module4/Figure3.png
   :alt: Interpret RNA-Seq read coverage in the two samples
   :name: module4_figure_3

   In this screen shot of the *tra* gene, introns have been circled
   and exons have brackets underneath them.


.. admonition:: Question 6
   :class: admonition-question

   Using the information you've gathered so far, make a diagram of the
   tra-RA (female specific) isoform with 3 exons and 2 introns.
   Represent exons as rectangular boxes and introns as lines
   connecting the boxes. Number each exon and intron (start from left
   with "exon 1").


.. admonition:: Question 7
   :class: admonition-question

   Where is the promoter in relation to the exons and introns? Mark
   the putative Transcription Start Site in your diagram with a bent
   arrow pointing in the direction of transcription.



Investigation 2: Identifying splice sites
----------------------------------------------------------------------

We will again focus on tra-RA to identify splice sites, that is, the
exact nucleotides where :term:`splicing` occurs to remove introns from
the :term:`pre-mRNA`.

Background
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Two software programs, called TopHat and Bowtie, use the RNA-Seq data to
graphically represent the exon junctions. The resulting graphic on the
genome browser coincidentally looks something like a little bowtie (two
small boxes connected by a thin line)
(:numref:`Figure %s <module4_figure_4>`). The boxes represent
the sequenced mRNA (the exons), and the line represents a gap (the
intron). The exon junction can be inferred when the first part of a
sequenced fragment from the RNA population matches (for example) DNA
positions 50-100 and the second part of the same fragment matches DNA
positions 200-250; the RNA from positions 101-199 must have been taken
out of the middle!

Short sequences are present at the beginning and end of each intron
that allow the spliceosome --- the molecular machinery that cuts out
introns --- to precisely remove the intron, leaving only the exon
sequences in the :term:`mature mRNA`. The first two nucleotides of the
intron are the :term:`splice donor site` and almost always the
nucleotides "GT". The last two nucleotides of the intron are the
:term:`splice acceptor site` and almost always the nucleotides "AG".
(Recall your observations in
:ref:`Module 3 <module3/module3_exercise:Removal of introns through
splicing>`.) For more information on RNA-Seq and the search
for :term:`splice junctions <splice junction>`, watch the
`RNA-Seq and TopHat video <https://youtu.be/qepVXEsfLMM>`_

.. figure:: /_static/images/module4/Figure4.png
   :alt: Illustration of an intron-exon junction
   :name: module4_figure_4

   A diagram of intron-exon junctions.


Use the Genome Browser to identify splice sites
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Using the same Genome Browser page, reset the Browser by clicking on
   ``hide all``. Then open the tracks that will provide the information we
   want for Investigation 2. (See the beginning of :ref:`Investigation 1
   <module4/module4_exercise:Investigation 1: Examining RNA-Seq data>`
   for a reminder on how to get the Genome Browser page.)


2. Change the display mode for the "Base Position" track to ``dense``,
   and then click on ``refresh``. (Note that you will not be able to
   see the DNA sequence until you "zoom in".)


3. Change the display mode for the "RNA-Seq Coverage" track to ``full``,
   and then click on ``refresh``.


4. You will again see blue and red histograms representing the RNA-Seq
   data (indicating the amount of mRNA synthesized) in females and males,
   respectively. We will focus on the blue histogram (Adult Females)
   again. As we did in :ref:`module3/module3_exercise:Module 3`, let's
   customize the RNA-Seq track by setting the "Data view scaling" field
   to ``use vertical viewing range setting`` and the "max" field under
   "Vertical Viewing range" to ``37``. Remember that you gain access to
   these settings by clicking on the ``RNA-Seq Coverage`` link under the
   RNA-Seq Tracks green bar.


5. Change the display mode for the "Exon Junctions" track to ``full``,
   and then click on ``refresh``. These rectangular boxes joined by a
   thin black line will help you identify the exon-intron boundaries.


Our graphical output viewer will look like the screen shot below
(:numref:`Figure %s <module4_figure_5>`).

.. figure:: /_static/images/module4/Figure5.png
   :alt: View of the *tra* RNA-Seq data
   :name: module4_figure_5

   View of the *tra* RNA-Seq data with the splice donor site in intron
   1 circled.


6. Zoom in to the area that is circled --- click and drag the cursor just
   above the numbers, or use zoom buttons.


7. Set the screen so that you can see about 15--20 nucleotides, as shown
   in the example below (:numref:`Figure %s <module4_figure_6>`).

.. figure:: /_static/images/module4/Figure6.png
   :alt: TopHat junctions near the splice donor site of exon 1
   :name: module4_figure_6

   TopHat data (in black) for adult males and adult females indicating
   an exon junction.


The blue histogram stops at the end of exon 1. The last three
nucleotides of exon 1 are "G-A-G".


.. admonition:: Question 8
   :class: admonition-question

   What is the coordinate of the last nucleotide in exon 1?


.. admonition:: Question 9
   :class: admonition-question

   What are the first two nucleotides of intron 1?


This is called the :term:`5'` splice site or "splice donor site."


8. Zoom out so that you can see all of the *tra* gene. Let's use TopHat
   to help us find the :term:`3'` end of the intron. Examine the Exon
   Junctions track. The first intron-exon junction predicted by TopHat
   (black) seems to align with the red histogram data from males; the
   second junction aligns better with the blue histogram data from
   females (:numref:`Figure %s <module4_figure_7>`).

.. figure:: /_static/images/module4/Figure7.png
   :alt: Compare TopHat and RNA-Seq data for adult males and females
   :name: module4_figure_7

   TopHat and RNA-Seq data for males and females.


9. Let's examine the 3' end of intron 1 more closely. Change the "enter
   position or search terms" field to ``contig1:10,140`` and then click
   ``go``. Zoom out 10x and then 3x (:numref:`Figure %s <module4_figure_8>`).

.. figure:: /_static/images/module4/Figure8.png
   :alt: Genome Browser view of the beginning of exon 2 of tra-RA
   :name: module4_figure_8

   Graphical viewer centered on the junction between intron 1 and exon
   2 of the tra-RA (female specific) isoform.


.. admonition:: Question 10
   :class: admonition-question

   What are the last two nucleotides of the female tra-RA intron 1?


This is called the 3' splice site or "splice acceptor site".


.. admonition:: Question 11
   :class: admonition-question

   What is the coordinate of the first nucleotide in the female
   tra-RA exon 2?



Investigation 3: Identify the splice sites for intron 2
----------------------------------------------------------------------

We can use the same approach to map the exon-intron boundaries of the
second intron.

Review steps #2--5 in Investigation 2. Then repeat the process to answer
the following questions about the 5' splice donor and 3' splice acceptor
sites for the tra-RA (female specific) intron 2.

1. Zoom into the sequence surrounding the 5' splice donor for the
tra-RA (female specific) intron 2.

.. admonition:: Question 12
   :class: admonition-question

   What are the last three nucleotides of the female tra-RA exon 2?


.. admonition:: Question 13
   :class: admonition-question

   What is the coordinate of the last nucleotide in the female tra-RA
   exon 2?


.. admonition:: Question 14
   :class: admonition-question

   What are the first two nucleotides of the female tra-RA intron 2?


2. Zoom out as needed so that you can see all of intron 2. Use the
   TopHat evidence track to find the 3' end of intron 2.


3. Click and drag so that the end of intron 2 is centered in the
   viewer. Then zoom in so that you can see the nucleotide sequence.


.. admonition:: Question 15
   :class: admonition-question

   What are the last two nucleotides of the female tra-RA intron 2?


.. admonition:: Question 16
   :class: admonition-question

   What is the coordinate of the first nucleotide in the female tra-RA
   exon 3?

.. admonition:: Question 17
   :class: admonition-question

   Using the information you've gathered so far, make a graphical
   picture of the tra-RA (female specific) isoform with 3 exons
   and 2 introns. Number each exon and intron at the corresponding
   DNA coordinates. Add the coordinates for first and last
   nucleotide of the exons that you have found so far. Add the
   sequences of the splice donor and splice acceptor sites at the
   appropriate locations.


.. admonition:: Question 18
   :class: admonition-question

   Where do you think the promoter is located in relation to your gene
   model? What evidence do you have to support your idea, using the
   evidence tracks we have displayed (Base Position, RNA-Seq
   Coverage, Exon Junctions)?


.. admonition:: Question 19
   :class: admonition-question

   **Bonus question!** Support your hypothesis by gathering additional
   data. Recall our explorations in :ref:`module2/module2_exercise:Module 2`
   and :ref:`3 <module3/module3_exercise:Module 3>`. You might want
   to open the tracks "D. mel. cDNAs," and "TSS Annotations," both
   in ``full``. What type of evidence is shown by each of these
   tracks (refer to :ref:`module2/module2_exercise:Module 2`)?
   Finally, to see tra-RA as currently annotated in FlyBase, open the
   "tra Isoform" track on ``full``, or to see both isoforms open the
   "FlyBase Genes" track in ``pack``. Do these results support your
   model? Do any ambiguities remain?


Homework: Determining splice sites for the *spd-2* gene
----------------------------------------------------------------------

1. Open a web browser on your laptop. Internet Explorer, Mozilla Firefox,
   Safari, or Chrome will work for this investigation. Go to the GEP
   Mirror of the UCSC Genome Browser at http://gander.wustl.edu. Follow
   the instructions given in :ref:`module1/module1_exercise:Module 1` to
   navigate to the contig1 project in the *D. melanogaster* ``July 2014
   (Gene)`` assembly.

.. note::
   **Reminder:** Configure the Genome Browser Gateway page as follows:

   .. cssclass:: compact-list

   1. Select ``D. melanogaster`` under "REPRESENTED SPECIES"

   2. Select ``July 2014 (Gene)`` under "*D. melanogaster* Assembly"

   3. Enter ``contig1`` into the "Position/Search Term" text box

   4. Click on the ``GO`` button

As you will remember, this section of DNA is 11,000 base pairs long
(:numref:`Figure %s <module4_hw_figure_1>`) and is part of the left arm
of chromosome 3, which is about 28,100,000 bp long. If your Browser
window is showing other evidence tracks, reset by clicking on
``default tracks``.

.. figure:: /_static/images/module4/Figure1.png
   :alt: Genome Browser view of contig1
   :name: module4_hw_figure_1

   A screen shot of the "contig1" project.


2. Let's start by setting the evidence tracks we want to see. Click on
   the ``hide all`` button, then open only the tracks that will provide
   data for this investigation:

   - Base Position: ``dense``

     - Note that you will not be able to see the DNA sequence until
       you zoom in. If the Base Position is changed to ``full``, you
       can see the :term:`amino acid` tracks also.


   - RNA-Seq Coverage: ``full``

     - You will see blue and red histograms representing RNA-Seq data generated
       using RNA samples from adult females and adult males, respectively.


   - Exon Junctions: ``full``

     - The exon junctions will help you to find the splice donor and
       splice acceptor sites.


   - D\. mel\. cDNAs: ``full``

     - This track was used extensively in previous modules, and is
       useful for confirming the sequence of the mature mRNA.
       Remember that a :term:`cDNA` is a DNA copy of an mRNA.


3. Zoom in to view only the *spd-2* gene by entering ``contig1:5,750-9,800``
in the "enter position or search terms" text box.

We are now looking at the region of chromosome 3 where the *spd-2* gene
is located.


.. admonition:: Question 1
   :class: admonition-question

   How many exons does *spd-2* have?


.. admonition:: Question 2
   :class: admonition-question

   How many introns does *spd-2* have?



Part 1: Identifying splice sites for Intron 1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You remember from class that short sequences are present at the
beginning and end of each :underline:`intron` that allow the spliceosome to
precisely remove each intron, leaving only the exon
sequences in the mature mRNA. The first two nucleotides of the intron
are "GT" and the last two nucleotides are "AG"
(:numref:`Figure %s <module4_hw_figure_2>`).


.. figure:: /_static/images/module4/Figure4.png
   :alt: Diagram of an intron
   :name: module4_hw_figure_2

   A bowtie diagram


4. Zoom in to the end of exon 1. Set the screen so that you can see about
   15--20 nucleotides.


.. admonition:: Question 3
   :class: admonition-question

   What are the last three nucleotides of exon 1? What is the
   coordinate of the last nucleotide in exon 1?


.. admonition:: Question 4
   :class: admonition-question

   What are the first two nucleotides of intron 1?


5. Zoom out so that you can see all of intron 1, and use TopHat to
   help find the end of the intron. Examine the Exon Junctions track.
   Then zoom in so that you can see the nucleotide sequence.

.. admonition:: Question 5
   :class: admonition-question

   What are the last two nucleotides of intron 1?


.. admonition:: Question 6
   :class: admonition-question

   What is the coordinate of the first nucleotide in exon 2?



Part 2: Identifying splice sites for Intron 2
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's use the same approach to map the exon-intron boundaries for intron
2. Review the steps you used in Part 1, then repeat the process to answer
the following questions about the 5' splice donor and 3' splice acceptor
sites for intron 2.


6. Zoom in to the sequence surrounding the 5' splice donor for intron 2.


.. admonition:: Question 7
   :class: admonition-question

   What are the last three nucleotides of exon 2?


.. admonition:: Question 8
   :class: admonition-question

   What is the coordinate of the last nucleotide in exon 2?


.. admonition:: Question 9
   :class: admonition-question

   What are the first two nucleotides of intron 2?


7. Zoom out as needed so that you can see all of intron 2. Use TopHat
   to find the end of intron 2.

8. Click and drag so that the end of intron 2 is centered in the
   viewer. Then zoom in so that you can see the nucleotide sequence.


.. admonition:: Question 10
   :class: admonition-question

   What are the last two nucleotides of intron 2?


.. admonition:: Question 11
   :class: admonition-question

   What is the coordinate of the first nucleotide in exon 3?


.. admonition:: Question 12
   :class: admonition-question

   Using the information you've gathered so far, make a graphical
   picture of the *spd-2* gene with 3 exons and 2 introns. Number
   each exon and intron. Add the coordinates for first and last
   nucleotide of the exons that you have found so far. Add the
   sequences of the splice donor and splice acceptor sites at the
   appropriate locations. Finally, add a bent arrow for the
   transcription start site.
