# A collection of manual sentence and word aligned bitexts #

This repository contains manually aligned parallel texts developped in the course of the ANR funded [TransRead](https://transread.limsi.fr) project on bilingual reading devices.

## Data format ##
The `doc/` directory contains the definition of the formalisms to be used for resource annotation and exchange (in French). The following associated files are distributed in the `dat/dtd/` directory

* transread_v1-2.xsd: the XML scheme. This is the definition of the annotation formalism.
* transread_v1-2.dtd: the DTD of the annotation scheme. This file introduces the structure of the annotation scheme.

We also provide a text annotated according to this scheme. This sample is based on an excerpt of the novel "The Last of the Mohicans" by F. Cooper and is composed of three files:

* sample_Mohicans_en.xhtml: the first two chapters of the English version of the novel, taken from the Gutenberg Project.
* sample_Mohicans_fr.xhtml: the first two chapters of the French version of the novel, taken from Gutenberg Project.
* sample_Mohicans_annot.xml: the annotation file linking the previous two documents. The file contains alignments at various levels, morpho-syntactic annotations, word sense disambiguation information, etc.

These files can be downloaded in the `dat/samples/` directory.

## Parallel Corpora ##

This section lists the parallel corpora created and manually annotated during the TransRead project. These corpora are distributed under the CC-BY licence. If you use it for your research, please cite:

	@InProceedings{Xu16novel,
	author = 	 {Xu, Yong and Yvon, François},
	title = 	 {Novel annotation schemes for sentential and sub-sentential alignments of bi-texts},
	booktitle = {Proceedings of 10th Language Resources and Evaluation Conference},
	year = 	 2016,
	series = 	 {LREC'16},
	url = {https://aclanthology.org/L16-1099/},
	address = 	 {Portorož (Slovenia)}
	}

The data collection includes:

* A collection of gold sentence alignments for 13 novels (mostly en/fr) - see `dat/novels`
* A collection of confidence annotations of sentence alignment links - see  `dat/sconf`
* A collection of confidence annotations of word alignment links, in 5 language pairs. - see `dat/wconf`

Thanks to a supplementary funding of the French Ministère de la Culture / Direction Générale à la Langue Française et aux Langues de France, additionnal subsentential manual alignments for 5 French/English short stories were collected using a "divisive" alignment scheme, and were also automatically annotated with a rich syntactic annotation, totalling about 12K bilingual segments. These are available on a companion [Web Site](https://github.com/fyvo/AlibiWordAlignments).
