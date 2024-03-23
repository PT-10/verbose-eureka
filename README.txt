ADE Corpus Charactersitics


The ADE corpus is distributed within two files i.e. DRUG-AE.rel and DRUG-DOSE.rel. DRUG-AE.rel describes relations between drugs and adverse effects whereas DRUG-DOSE.rel describes relations between drugs and dosages. 

The format of DRUG-AE.rel is as follows with pipe delimiters:

Column-1: PubMed-ID
Column-2: Sentence 
Column-3: Adverse-Effect
Column-4: Begin offset of Adverse-Effect at 'document level'
Column-5: End offset of Adverse-Effect at 'document level'
Column-6: Drug
Column-7: Begin offset of Drug at 'document level'
Column-8: End offset of Drug at 'document level'


The format of DRUG-DOSE.rel is as follows with pipe delimiters:

Column-1: PubMed-ID
Column-2: Sentence 
Column-3: Dose
Column-4: Begin offset of Dose at 'document level'
Column-5: End offset of Dose at 'document level'
Column-6: Drug
Column-7: Begin offset of Drug at 'document level'
Column-8: End offset of Drug at 'document level'


During annotation, documents were used in the following format:
PubMed-ID\n\nTitle\n\nAbstract

Due to licensing and distribution issues associated with PubMed, only those sentences that contain annotated information are provided.


If you use this corpus for any publication purposes, you are requested to cite the source article:

Gurulingappa et al., Benchmark Corpus to Support Information Extraction for Adverse Drug Effects, JBI, 2012.
http://www.sciencedirect.com/science/article/pii/S1532046412000615



