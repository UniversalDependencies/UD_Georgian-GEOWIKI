# Summary

**UD\_Georgian-GEOWIKI** is a Universal Dependencies corpus for the Georgian language, derived from randomly selected texts from the Georgian Wikipedia. The corpus currently contains 385 sentences, which were automatically tokenized and morphologically tagged using a TreeTagger model trained on a separate Georgian dataset. You can find the TreeTagger resource [here](https://github.com/SophikoComp/TreeTagger-for-Georgian).

The output was semi-automatically converted into the UD format through custom Python scripts, followed by extensive manual correction to ensure conformity with UD guidelines and improve annotation quality. Morphological annotations are complete and validated; syntactic annotations are currently in progress.

This corpus contributes to the growing set of low-resource language resources and provides a foundation for future syntactic, morphological, and cross-linguistic research in Georgian NLP.

# Introduction

The **UD\_Georgian-GEOWIKI** corpus was developed as part of a master's thesis focused on enriching the landscape of NLP resources for underrepresented languages. Georgian, a South Caucasian (Kartvelian) language, poses unique challenges due to its complex morphosyntactic structure, agglutinative morphology, and limited digital resources. Despite being spoken by over 4 million people, Georgian remains largely underserved in computational linguistics.

This project aimed to create a Universal Dependencies (UD)-formatted treebank using texts sourced from Georgian Wikipedia. The goal was to produce a morphosyntactically annotated corpus that adheres to UD guidelines, facilitating future multilingual NLP research and tool development.

The corpus was initially tagged using a TreeTagger model trained on a separate Georgian dataset (Daraselia, 2019). Custom Python scripts were developed to convert the output to UD-compatible part-of-speech tags and features, followed by thorough manual corrections. Currently, the corpus includes around 8,000 tokens with completed morphological and lexical annotations. Syntactic annotations are in progress, after which the corpus will be fully eligible for inclusion in the official UD release cycle.

This initiative supports the broader goal of bridging the resource gap for low-resource languages by contributing high-quality annotated data and by documenting linguistic features that challenge standard annotation frameworks.

# Acknowledgments

Acknowledgments to the prior work that made this project possible, including the doctoral research that provided the TreeTagger model for Georgian, and the Universal Dependencies community for their standards, tools, and support. Special thanks to my thesis supervisors, Delphine Bernhard and Hélène Gérardin, for their guidance, support, and expertise throughout the development of this project.

# References

* Shanidze, A. (1980). *Les bases de la grammaire géorgienne*. Tbilisi, Georgia. [http://archive.org/details/shanidze](http://archive.org/details/shanidze)
* Daraselia, S. (2019). *Computational Analysis of Morphosyntactic Categories in Georgian* (PhD thesis). University of Leeds. [https://etheses.whiterose.ac.uk/25313/](https://etheses.whiterose.ac.uk/25313/)
* Gérardin, H. (2016). *Les verbes intransitifs primaires et dérivés en géorgien*. Doctoral thesis. Sorbonne Paris Cité. [https://www.theses.fr/2016USPCF025](https://www.theses.fr/2016USPCF025)
* Finlayson, M., & Erjavec, T. (2016). Overview of Annotation Creation: Processes & Tools. In *Handbook of Linguistic Annotation* (pp. 167–191). Springer. [Link](https://www.researchgate.net/publication/301847215)
* Kapanadze, O. et al. (2020). *Building Resources for Georgian Treebanking-based NLP*. TbiLLC Proceedings. [Link](https://www.researchgate.net/publication/341821701)
* Lobzhanidze, I. (2013). *Morphological Analyzer and Generator of Modern Georgian Language*. Tbilisi. [http://eprints.iliauni.edu.ge/642/](http://eprints.iliauni.edu.ge/642/)
* Schmid, H. (n.d.). TreeTagger. [https://www.cis.uni-muenchen.de/\~schmid/tools/TreeTagger/](https://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)
* Ruder, S. (2020). *Why You Should Do NLP Beyond English*. [https://ruder.io/nlp-beyond-english/](https://ruder.io/nlp-beyond-english/)

(*Additional references available in the thesis documentation*)


# Changelog

* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Genre: wiki
Lemmas: automatic with corrections
UPOS: automatic with corrections
XPOS: not available
Features: automatic with corrections
Relations: automatic with corrections
Contributors: Didebashvili, Mate
Contributing: here
Contact: matedideba@gmail.com
===============================================================================
</pre>
