# LIMSI sentence alignment confidence annotation corpus #

A collection of confidence annotations for sentence alignments. 

This resource has been produced in the course of the [TransRead Project](https://transread.limsi.fr) funded by the French National Research Agency under contract ANR-12-CORD-0015.

Please cite the following paper if you use the resource in your research:

Yong Xu and François Yvon (2016). Novel annotation schemes for sentential
and sub-sentential alignments of bi-texts. Proceedings of 10th Language
Resources and Evaluation Conference (LREC 2016). Portorož (Slovenia).

## CONTENT/STRUCTURE ##

Five confidence annotation tags have been used:
1. "sure": the pair of sentences are (near) perfect mutual translations;
2. "partial": one side contains some parts that are not translated on the other side;
3. "unperfect": the pair constitutes a loose full mutual translation, or a translation only in specific contexts;
4. "not corresponding": the pair has no correspondence relation at all;
5. "undecidable": none of the previous four cases, mainly for pairs which are highly context-dependent and cannot be annotated in isolation.

Three annotators have annotated 1,800 pairs of English-French sentences.
Each pair is annotated twice, by two different annotators.
One pair takes 5 lines in the annotation document:
* sentence pair ID;
* source sentence;
* target sentence;
* first annotation (with untranslated word indices if the tag is "partial");
* second annotation (with untranslated word indices if the tag is "partial").

For each sentence, the word indice begins at 0.

The distribution of work among the three annotators :
* 3000-3599.txt : Annotator 1, Annotator 2
* 3600-4199.txt : Annotator 1, Annotator 3
* 4200-4799.txt : Annotator 2, Annotator 3

## LICENCE ##

The annotations and database rights of this database are licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

The sentence pairs were extracted from the OpenSubtitle corpus, which is freely downloadable from http://opus.lingfil.uu.se/.

## CONTACT INFORMATION ##

For more information, please contact {yong@limsi.fr, yvon@limsi}
