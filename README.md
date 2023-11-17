# Fox_Luisa_PhD_Study

I'm a PhD candidate at the University of Copenhagenm, Center for Evolutionary Hologenomics. My PhD is atm entitled "The bugs and behaviours of animals – Hologenomics as a tool for studying the role of the gut microbiota in mammalian behaviour". The main aim of PhD thesis is to investigate how/if the gut microbiome influences animal behaviour using a hologenomic approach. I have two research studies in my PhD to assess this and they are called:
1. Fox study (alias: behavioural fox study, fox project)
2. Mice study (alias: BeHo study, BeHo project, behavioural hologenomics mice study)

Here I share the computational work (codes and results) of the Fox project. The text below origins from this document:
https://docs.google.com/document/d/13SOUi5Yxq_MihZQy8W0XrG5qL448_isNdrylyaxvvPo/edit?usp=sharing

## Project description
Much evidence suggests that the gut microbiome influences animal behaviour, but many behavioural traits have still not been studied, especially those unassociated with disease. In this study, we compare two distinct behaviours in foxes that are either tame or aggressive to unveil if their gut microbiomes affect these behaviours, and if there are any microbial differences between them. At the Institute for Cytology and Genetics in Novosibirsk, Russia, a population of silver foxes (Vulpes vulpes) have been selected for over 50 generations to be either tame or aggressive, resulting in two genetically different groups. However, the role of their gut microbiomes has not been examined, we are therefore investigating it here using a hologenomic approach involving metatranscriptomic and metagenomic sequencing techniques. Moreover, a third, unselected, group of foxes exists as well. These foxes are nor tame or aggressive, and thus, they serve an ideal comparison group to, for example, explore the origin of the microbial patterns found in the tame and aggressive foxes.

## Objctives
The objectives may need to be updated. But here goes:
1. Generate MAGs based on two fox metagenomic data sets. One derives from the gut (my samples) and the other from feces (samples from a prior PhD student of Tom). Once the MAGs are generated, I am to compare these with each other - how similar or dissimilar are they.
2. Generate RNA transcripts and compare these to the gut derived MAGs to see which gut microbes are active, at which sites (ileum and/or colon) and within which gut sample types (gut tissue and/or gut content)
3. Determine the RNA gene expressions (the activity) of the gut microbiome in the tame and aggressive foxes
4. Evaluate the potential compositional and functional differences between the gut microbiomes of tame and aggressive foxes. Compare these findings with the unselected group of foxes.
5. Disentangle if/how the gut microbes affect the foxes' brain (hence behaviours) via the microbiota-gut-brain (MGB) axis by looking into which MGB genes are expressed, hence active

## Hypotheses
The main hypothesis of my PhD thesis is:

Null hypothesis: The gut microbiomes of the mice have no effect on dominance

Alternative hypothesis: The gut microbiomes of the mice have an effect on dominance

I have subhypotheses as well, but they are not shared here.

## Sample collection
We collected samples from three behavioural cohorts of foxes: 
* Tame
* Unselected (nor tame or aggressive)
* Aggressive
The planned number of fox individuals per cohort was five. Thus, in total: 15 individuals (= 5 individuals x 3 cohorts). This was however not possible, as we could not find more than two proper labelled unselected individuals. So the number of fox individuals per cohort in the metagenomic data set is two. In total: 6 individuals (= 2 individuals x 3 cohorts), and the number of fox individuals per cohort in the metatranscriptomic data set is: 2 unselected foxes, 5 tame foxes and 5 aggressive foxes.
We have samples from two sites in the gut: 1) Ileum and 2) Colon (see image)
We have two sample types per site: 1) Gut tissue and 2) Gut content

The number of samples in total in the metagenomic data set is 24 (= 2 individuals x 3 cohorts x 2 gut sites x 2 sample types) 
The number of samples in total in the metatranscriptomic data set is 48 (= 10 tame and aggressive foxes x 2 gut sites x 2 sample types + 2 unselected foxes x 2 gut sites x 2 sample types). However, two samples failed during lab work and were not sequenced (write specifically which samples).

!! add image of gut!! Coming soon.

## Experimental setup
More info coming soon

## Sequencing techniques applied
We have two sequencing techniques applied in BeHo:
* Metagenomics (short-read 150bp DNA sequencing)
* Metatranscriptomics (short-read 150bp DNA sequencing)

## Datassets
Thus, we have two datasets in the Fox project:
1. Metagenomic sequencing data
2. Metatranscriptomic sequencing data

The metagenomic sequencing data derives from in total 24 gut samples (from 6 foxes) 
The metatranscriptomic sequencing data originates from in total 46 fox gut sampes (from 12 foxes). It is the same individual animals as the metagenomic data, but six more are in this datasat. 

## Lab work
The DNA and RNA samples were extracted simultaneously from the same subsample under controlled conditions in our molecular lab. Shortly after the extraction, the DNA and RNA concentrations were measured of each extract. The RNA extracts were kept cold during concentration measurements and immediately after frozen to -70C. Novogene UK did the library preparation and sequencing of the metascriptomics samples based on raw RNA extracts sent to Novogene, whereas the metagenomics samples were prepared in-house, and thus, only sequenced by Novogene UK.

## Other relevant info
A PhD student of Tom (Lara Puetz) has already generated MAGs showing that the tame and aggressive foxes do differ in their gut microbiome (in prep). However, these MAGs originate from another sample source (feces) and sample collection years (2015 and 2017) compared to my sample source and year. My sample sources are gut tissue and content (no feces) from two sites in the gut (ileum and colon), and the collection year is 2018. 
Furthermore, our collaborators at the Institute for Cytology and Genetics in Novosibirsk, Russia, have already analysed and published the host genome of the tame and aggressive foxes showing that they differ. Hence, the genome of the tame foxes differs from the aggressive. You can find the papers below:

!! add links to papers !!


Lastest update: Friday 17th of November 2023

