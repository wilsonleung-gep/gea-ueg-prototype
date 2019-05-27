Module 5
============

.. role:: underline
     :class: underline

.. role:: underline-italics
     :class: underline-italics


.. rubric:: Module 5: Translation: The need for an Open Reading Frame
     :class: header1

.. |br| raw:: html

   <br/>


.. GitHub does not support the include directive. Extracted symbols
.. from isonum.txt in Docutils <http://docutils.sourceforge.net>

.. |rarr| unicode:: U+02192 .. RIGHTWARDS ARROW


:Authors: Carina Endres Howell (Lock Haven University of Pennsylvania)
          and |br|
          Leocadia Paliulis (Bucknell University)

:Last Update: |today|
:Version: |version|


Investigation 1: Examining Open Reading Frames in *tra*
----------------------------------------------------------------------


Introduction: review of reading frames
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In this exploration, we will continue to focus on the *transformer*
gene (referred to as tra-RA or just *tra*), and will learn about how
the *tra* mRNA is translated into a string of
:term:`amino acids <amino acid>`.

Given that DNA is double-stranded, and that the genetic code is based
on triplets (3 consecutive bases), there are six possible reading
:term:`frames <frame>`. One can determine a reading frame by dividing
the sequence of nucleotides in DNA or RNA into a set of consecutive,
non-overlapping triplets. There are three possible reading frames
(read :term:`5'` |rarr| :term:`3'`) in the forward direction on the top
strand of DNA, and three (read 5' |rarr| 3') in the reverse direction
on the complementary bottom strand of the same DNA molecule. Hence,
there are six possible reading frames for each gene (see illustration
in :ref:`Module 1<module1/module1_exercise:Coding exons are translated
in a single reading frame>`).

Once it is determined in which direction a particular gene is
transcribed (for review see :ref:`module2/module2_exercise:Module 2`
and :ref:`3 <module3/module3_exercise:Module 3>` on transcription),
there remain three choices for the reading frame. To determine which
of these reading frames is used during :term:`translation`, evidence
such as the presence of an
:term:`initiation codon <initiation codon (start codon)>` and the
absence of :term:`stop codons <stop codon (termination codon)>` is
used. As you learned in :ref:`module1/module1_exercise:Module 1`, the
initiation codon is ATG in the coding DNA strand (AUG in the mRNA) and
specifies the amino acid methionine. Additional triplets code for the
other 19 amino acids, and three triplets are stop codons, causing
termination of translation. These stop codons are TAA, TAG and TGA in
DNA, or UAA, UAG and UGA when found in mRNA). An Open Reading Frame is
a string of consecutive codons that is uninterrupted by stop codons.
Every mRNA contains one :term:`ORF` that is translated by the ribosome
from start codon to stop codon.


Investigate reading frames for the *tra* gene
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Go to the UCSC Genome Brower Mirror site at
   http://gander.wustl.edu/ and follow the instructions given in
   :ref:`module1/module1_exercise:Module 1` to open ``contig1`` of
   *Drosophila melanogaster* using the ``July 2014 (Gene)`` assembly.


2. The screen below will appear (:numref:`Figure %s <module5_figure_1>`).
   As you will remember, this section of DNA is 11,000
   :term:`base pairs <base pair (base pairing)>` long and is a small
   part of the left arm of chromosome 3, which is about 28,100,000 bp
   long.

.. figure:: /_static/images/module5/Figure1.png
   :alt: Genomic region surrounding the *tra* gene
   :name: module5_figure_1

   View of the region of the *tra* gene on Chromosome 3.


3. Zoom in to view only the first :term:`exon` of the tra-RA gene
   by entering ``contig1:9,840-9,920`` in the "enter position or
   search terms" text box and hitting the ``go`` button.


4. Open only the tracks that will provide information for this
   investigation. Set the Base Position track to ``full``. Now we can
   see the amino acid tracks as well, giving the results from conceptual
   translation.


5. There are three possible reading frames for this transcript in the
   forward direction, here indicated by the numbers 1, 2 and 3 (red
   arrow) (:numref:`Figure %s <module5_figure_2>`).

.. figure:: /_static/images/module5/Figure2.png
   :alt: Three possible reading frames on the plus strand
   :name: module5_figure_2

   Three possible reading frames for the *tra* gene in the forward direction.


6.  Three reading frames are possible in the forward direction, as one
    could start translating with the first :term:`base`, the second
    base or the third base. (Starting with the fourth base is
    equivalent to starting with the first base, only missing one
    :term:`codon`.) The DNA "top strand" is read from left to right
    (indicated by the arrow in the browser, right under the word
    "contig1" that looks like this ``--->``). If you click on that
    arrow, the three reading frames in the reverse direction will appear,
    as the "bottom strand" is read from right to left. As you learned in
    :ref:`Module 1 <module1/module1_exercise:Genes have directionality>`,
    genes have directionality. The *tra* gene is read from the "top
    strand" (left to right).


7.  Notice that the third reading frame has a green M codon (methionine)
    at the location where the thick black rectangle indicates the
    first :term:`coding exon` or :term:`CDS` (Coding DNA Sequence) of
    tra-RA mRNA. Remember that the codon for methionine (ATG in DNA)
    is the start signal, the first codon used in translation.
    :underline:`This gives us our first piece of evidence that reading
    frame 3 is the one used in translation of the first CDS of the \ `
    :underline-italics:`tra \ ` :underline:`gene`. For simplicity
    let's call this first CDS "CDS1" to distinguish it from
    other CDS's in the *tra* gene. Note that there is a stretch of RNA
    transcript upstream (to the left) of the ATG; this is the
    5'\ :term:`UTR` (5' untranslated region), found at the 5' end of
    all eukaryotic mRNAs.


8.  Next carefully examine reading frame 2. Notice that in this reading
    frame there is no codon for methionine (no start codon) in the
    region that maps to the first exon. This gives us evidence that
    reading frame 2 is probably not being used during translation of
    CDS1 of the *tra* gene.


9.  Finally, look at reading frame 1. Notice that there is a stop codon
    at the beginning of that reading frame (indicated by a red box with
    an asterisk in it). This evidence indicates that reading frame 1
    probably is not being used during translation of CDS1 of the *tra*
    gene.


10. Let's move on to looking at the reading frames for exon 2 of tra-RA.
    Zoom in to view only the second exon of the *tra* gene by jumping to
    ``contig1:10,120-10,570`` using the "enter position or search terms"
    text box. Remember that both the RNA-Seq data and the :term:`cDNA`
    data have been used to map the positions of exons.


.. admonition:: Question 1
   :class: admonition-question

   First examine reading frame 1. Are there any stop codons in the
   reported exon? If there are early stop codons, do you think
   this is the reading frame used during translation?


.. admonition:: Question 2
   :class: admonition-question

   Examine reading frame 2. Are there any stop codons in this reading
   frame within the exon?


.. admonition:: Question 3
   :class: admonition-question

   Examine reading frame 3. Are there any stop codons in the reported
   exon?


.. admonition:: Question 4
   :class: admonition-question

   Using the evidence above, which reading frame maintains an Open
   Reading Frame (ORF) across exon2 of tra-RA? Is this the same
   reading frame as that used for exon 1?

11. Finally, take a look at exon three (``contig1:10,600-10,850``). We
    anticipate that since this is the last CDS there will be one or more
    stop codons; one of which will mark the site of translation
    termination. The 3'UTR (3' untranslated region) extends downstream
    from this point to the site of poly(A) addition where the last exon
    ends (see
    :ref:`Module 3 <module3/module3_exercise:Addition of a 3' poly(A) tail>`).
    Here all three reading frames have a significant ORF
    followed by one or more stop codons in the exon.

.. note::

   How can we figure out which reading frame is correct? We will
   investigate this in the next section by looking specifically at the
   :term:`splice junction`.


Investigation 2: Construct the gene model for tra-RA
----------------------------------------------------------------------

We can combine what we know about reading frames with what we know about
:term:`splicing` to learn exactly how tra-RA is put together. We'll
note where the start codon, splice sites, and stop codon are so we can
construct a gene model. Then, in :ref:`module6/module6_exercise:Module 6`,
we'll use these same types of information to solve some mysteries
about tra-RB.


1. Using the same Genome Browser page, reset the Browser by clicking on
   ``hide all``. Then open the tracks that will provide the information we
   want for Investigation 2:

   - Base Position: ``full``

     - Note that you will not be able to see the DNA sequence or amino acid
       tracks until you zoom in.

   - FlyBase Genes: ``pack``

   - RNA-Seq Coverage: ``full``

     - You will see blue and red histograms representing the RNA-Seq
       data (indicating the amount of mRNA synthesized) in females and
       males, respectively.

     - We will focus on the blue histogram (Adult Females)
       again. As we did in :ref:`module3/module3_exercise:Module 3`,
       let's customize the RNA-Seq track:

       - Click on the ``RNA-Seq Coverage`` label under the RNA-Seq
         Tracks green bar found in the bottom section of the page.

       - Set the "Data view scaling" field to
         ``use vertical viewing range setting``

       - Set the "max" "Vertical Viewing range" to ``37``

       - Under the "List sub-tracks" section, unselect the
         ``Adult Males`` track

   - Exon junctions: ``full``

     - These rectangular boxes joined by a thin black line will help us
       identify the exon-intron boundaries.



Identify the start codon
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2. Let's find the start codon for tra-RA. Zoom in on where the FlyBase
   Genes track shows that the translation starts (where the tracked
   black box gets thicker for the tra-RA :term:`isoform`) as seen in
   (:numref:`Figure %s <module5_figure_3>`)

.. figure:: /_static/images/module5/Figure3.png
   :alt: Region near the translation start site for tra-RA
   :name: module5_figure_3

   Translation start region of the *tra* gene.


.. admonition:: Question 5
   :class: admonition-question

   Give the coordinates for the entire start codon for tra-RA (start
   codon coordinates should be three consecutive numbers, for example:
   nucleotides 212--214).


.. admonition:: Question 6
   :class: admonition-question

   Which reading frame should we follow along to see the predicted amino
   acid sequence of tra-RA?


.. admonition:: Question 7
   :class: admonition-question

   Zoom out to see the entire exon. Are there any stop codons in this
   reading frame in the first exon?



Identify the splice sites for intron 1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3. Now zoom in and find the last base of the first exon for tra-RA
   using your RNA-Seq data and Exon Junctions data
   (:numref:`Figure %s <module5_figure_4>`).

.. figure:: /_static/images/module5/Figure4.png
   :alt: Splice donor site for Exon 1 of tra-RA
   :name: module5_figure_4

   Region at the end of Exon 1 of the *tra* gene.


.. admonition:: Question 8
   :class: admonition-question

   Give the coordinates for the very last base of the first exon.


So that we can follow the polypeptide through until we identify the stop
codon, we need to figure out which reading frame we should follow in the
second exon. This is not as easy as you might think, because eukaryotes
don't always read in the same reading frame when looking at the genome.
You saw an example of this previously in
:ref:`Module 1 <module1/module1_exercise:Coding exons are translated
in a single reading frame>`. Sometimes we can infer the correct
reading frame given the pattern of start and stop codons within the
region of the exon, identified by RNA-Seq data. But that sort of
information does not always give a definitive answer --- there may be
more than one possible reading frame for a given exon. To figure out
which reading frame is being translated at exon 2, we need to check
the end of the first exon to see how many bases of the last codon are
present before the 5' splice site consensus sequence. To do this, look
closely at reading frame 3, just before the splice site
(:numref:`Figure %s <module5_figure_5>`).


.. figure:: /_static/images/module5/Figure5.png
   :alt: Determining the phase of the donor site
   :name: module5_figure_5

   An extra nucleotide between the last complete codon and the
   splice donor site for Exon 1 of the *tra* gene.

Note that the splice site cuts off the last codon of the first exon
after just one base (\ **as indicated by the red box in**
:numref:`Figure %s <module5_figure_5>`). Therefore, we would say this
exon has a **"phase 1" end because there is a partial codon at the end
of the exon that is 1 base long.**


.. note::

   If there were a fully completed codon before the splice site, it
   would be in **phase 0**, and if there were two bases before the
   splice site, it would be in **phase 2**.


For this exon with a :term:`phase` 1 end we will need two more bases from the
next exon to complete the codon. Knowing this we can identify the
reading frame that will be used in the second exon. Navigate to the 3'
splice site of :term:`intron` 1 (i.e., the location where the first
intron ends and the second exon begins;
:numref:`Figure %s <module5_figure_6>`).
To review splicing and the concept of phase, watch the
`Splicing and Phase video <https://youtu.be/JsvUfHy3eHE>`_.

.. figure:: /_static/images/module5/Figure6.png
   :alt: Splice acceptor site for Exon 2 of the *tra* gene
   :name: module5_figure_6

   Region at the beginning of Exon 2 of the *tra* gene


.. admonition:: Question 9
   :class: admonition-question

   Knowing that exon 1 ends with a partial codon of 1 base, what
   reading frame is being used in the second exon?


.. admonition:: Question 10
   :class: admonition-question

   Based on the evidence you see in the browser, give the coordinates
   for the first base of the second exon of tra-RA.


.. admonition:: Question 11
   :class: admonition-question

   Do you observe an appropriate splice acceptor site just upstream
   within the intron?


Now we will be using reading frame 2, because, after the splice site,
there are two bases left in the codon. These two bases plus the one base
left from the first exon make a complete codon.

4. Next, zoom out and look at reading frame 2 for all of exon 2 of
   tra-RA. You can see that there are no stop codons in this reading
   frame, which lends support to our conclusion that this is the proper
   reading frame.



Identify the splice sites for intron 2
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5. Now, let's do the same for the 5' splice site of intron 2 for
   tra-RA. Zoom in on that splice site
   (:numref:`Figure %s <module5_figure_7>`).

.. figure:: /_static/images/module5/Figure7.png
   :alt: Splice donor site for Exon 2 of the *tra* gene
   :name: module5_figure_7

   Region at the end of Exon 2 of the *tra* gene.


.. admonition:: Question 12
   :class: admonition-question

   Give the coordinate of the base prior to the 5' splice site of
   intron 2.


.. admonition:: Question 13
   :class: admonition-question

   How many bases are left in the codon before the splice site, i.e. is
   this phase 0, phase 1, or phase 2?


6. Now navigate to the start of the final exon
(:numref:`Figure %s <module5_figure_8>`).

.. figure:: /_static/images/module5/Figure8.png
   :alt: Splice acceptor site for Exon 3 of the *tra* gene
   :name: module5_figure_8

   Region at the beginning of Exon 3 of the *tra* gene.


.. admonition:: Question 14
   :class: admonition-question

   Locate the 3' splice site of Intron 2. Give the coordinate of the
   first base in exon 3 for tra-RA.


.. admonition:: Question 15
   :class: admonition-question

   Which reading frame is being translated in the final exon?



Identify the stop codon
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7. Now locate the first stop codon in the translated reading frame.
   Stop codons are shown as red boxes with asterisks (red arrows) as
   shown in :numref:`Figure %s <module5_figure_9>`.

.. figure:: /_static/images/module5/Figure9.png
   :alt: Genome Browser view of the region near the end of Exon 3
   :name: module5_figure_9

   Region at the end of Exon 3 of the *tra* gene.


.. admonition:: Question 16
   :class: admonition-question

   Give the coordinates for the bases in the stop codon.


Construct the complete gene model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Let's consolidate all the data we found above in one place:

.. admonition:: Question 17
   :class: admonition-question

   :underline:`Gene model for tra-RA:`

   - Coordinate for start of translation: \_____________\_
   - Coordinate for last base of exon 1: \_____________\_
   - Coordinate for first base of exon 2: \_____________\_
   - Coordinate for last base of exon 2: \_____________\_
   - Coordinate for first base of exon 3: \_____________\_
   - Stop codon coordinates: \__________________________\_


   Take the coordinate information above to draw a map of tra-RA using
   rectangles to represent exons and connecting lines to represent introns.
   Label the ends of the exons with the appropriate coordinates and
   indicate the transcription start site for the tra-RA initial transcript.
   Below this map, provide a map of the processed mRNA after intron
   removal. Below this map, indicate the regions that are translated into a
   protein. Give precise coordinates. Color coding may be helpful.

In :ref:`module6/module6_exercise:Module 6`, we will compare this
model of tra-RA with a model of tra-RB.


.. admonition:: Question 18
   :class: admonition-question

   To cement your knowledge of gene structure, you could construct a
   similar map of the *spd-2* gene. How many exons does this gene
   have? How many introns? How many isoforms? Use the same approach to
   determine the coordinates for the exons, and the coordinates for
   the coding region (another name for the region that is translated).
