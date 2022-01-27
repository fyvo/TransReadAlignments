# LIMSI sentence alignment corpus #
A collection of gold sentence alignments of literary bi-texts.

This resource has been produced in the course of the
[TransRead Project](https://transread.limsi.fr) funded
by the French National Research Agency under contract
ANR-12-CORD-0015.

Please cite the following paper if you use the resource in your research:

Yong Xu and François Yvon (2016). Novel annotation schemes for sentential 
and sub-sentential alignments of bi-texts. Proceedings of 10th Language 
Resources and Evaluation Conference (LREC 2016). Portorož (Slovenia).

## CONTENT/STRUCTURE ##

Bi-texts and alignment information are encoded in the [CES format](http://www.cs.vassar.edu/CES/).

For every book (except for Candide), only a fraction of the bi-text is aligned (usually the 
beginning chapters). See the following table for details. 

In each sub-directory, the documents whose name begin with "cut_" contain only the aligned fractions.
 
For some books, paragraph information is encoded. Thus 
the sentence ID "438.1" means the first sentence of the 438th paragraph.
For other ones, no paragraph information is available. The
sentence ID "1.495" means the 495th sentence in the whole text.


## Statistics ##
===========================================
Book                              $ Language pair $ Last aligned EN ID $ # Link $ # Source sent. $ # Target sent.
Alice's Adventures in Wonderland  $ EN-FR         $ 438.1              $ 746    $ 836            $ 941    
Candide                           $ EN-FR         $ 1024.1             $ 1,230  $ 1,524          $ 1,346
Candide                           $ EN-EL         $ 1024.1             $ 1,247  $ 1,524          $ 1,585
Candide                           $ EN-ES         $ 1024.1             $ 1,113  $ 1,524          $ 1,196
Du Côté de chez Swann             $ EN-FR         $ 1.495              $ 463    $ 495            $ 492
Emma                              $ EN-FR         $ 1.216              $ 164    $ 216            $ 160
Jane Eyre                         $ EN-FR         $ 1.205              $ 174    $ 205            $ 229
La Faute de l'Abbe Mouret         $ EN-FR         $ 1.226              $ 222    $ 226            $ 258
Les Confessions                   $ EN-FR         $ 1.236              $ 213    $ 236            $ 326
Les Travailleurs de la Mer        $ EN-FR         $ 1.389              $ 359    $ 389            $ 405
The Last of the Mohicans          $ EN-FR         $ 1.205              $ 197    $ 205            $ 232
Vingt Mille Lieues sous les Mers  $ EN-FR         $ 328.1              $ 778    $ 820            $ 781
Voyage au Centre de la Terre      $ EN-FR         $ 383.2              $ 714    $ 821            $ 754

Total         13 books            $               $                    $ 7,620  $ 9,021         $ 8,705
===========================================

## LICENCE ##

The annotations and database rights of this database are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

The underlying texts have been mostly collected from the [Gutenberg Project web site](http://www.gutenberg.org/) - see the Gutenberg project licence for restrictions and terms of use: http://www.gutenberg.org/wiki/Gutenberg:The_Project_Gutenberg_License

For the following books, the alignments are refined versions of the initial alignments of André Farkas 
© 2014 FarkasTranslations.com.
* Alice's Adventures in Wonderland
* Candide (EN-FR)
* Candide (EN-EL)
* Candide (EN-ES)
* Vingt Mille Lieues sous les Mers
* Voyage au Centre de la Terre

CONTAC’ INFORMATION

For more information, please contact {yong@limsi.fr, yvon@limsi}

