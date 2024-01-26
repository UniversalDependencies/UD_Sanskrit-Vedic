# Summary

The Treebank of Vedic Sanskrit contains 4,000 sentences with 27,000 words chosen from metrical and prose passages of the Ṛgveda (RV), the Śaunaka recension of the Atharvaveda (ŚS), the Maitrāyaṇīsaṃhitā (MS), and the Aitareya- (AB) and Śatapatha-Brāhmaṇas (ŚB).

Lexical and morpho-syntactic information has been generated using a tagging software and manually validated.
POS tags have been induced automatically from the morpho-sytactic information of each word.


# Introduction



Vedic Sanskrit is an ancient Indo-Aryan language,
one of the oldest transmitted Indo-European languages and
the precursor of Classical Sanskrit. The relatively large corpus of Vedic poetry and prose is critical for the reconstruction of the early linguistic history of Indo-European and important as a source for socio-cultural developments in South Asia during the second and first millenia BCE.

The composition of the Vedic treebank is motivated by the need for a resource that can be used for data-driven, quantitatively robust diachronic and synchronic investigations of linguistic
phenomena in, and starting with, the oldest layers of Vedic Sanskrit. 

## References
Annotation and composition of this treebank are described in detail in the following paper:

```
@inproceedings{hellwig-vtb-lrec-2020,
	author = {Hellwig, Oliver and Scarlata, Salvatore and Ackermann, Elia and Widmer, Paul},
	title = {The Treebank of {Vedic Sanskrit}},
	booktitle = {Proceedings of the LREC},
	year = {2020}
}
```

An updated overview of the annotation procedure and coverage can be found here:

```
@article{vedic-parser,
    title = {Data-driven Dependency Parsing of {V}edic {S}anskrit},
    author = {Hellwig, Oliver and Nehrdich, Sebastian and Sellmer, Sven},
    journal = {Language Resources \& Evaluation},
	volume = {57},
	pages = {1173--1206},
    year = {2023}
}
```

## Train-test split

Following the UD recommendations, documents are kept together when generating the train, test and dev splits.
For the Vedic data, the term "document" means a hymn (metrical texts) or a chapter (prose texts).
Some of these documents are not complete, meaning that not the whole chapter or hymn was annotated. This happens quite often with the Rigveda.


# Acknowledgments

The annotation has been performed by Salvatore Scarlata, Oliver Hellwig, Elia Ackermann, Erica Biagetti, and Sven Sellmer.

# Changelog

* 2020-04-26 v1.0
  * First release in UD
* 2024-01-26 v2.0
  * Second release in UD
  
<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.6
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction
Lemmas: converted from manual
UPOS: automatic with corrections
XPOS: converted from manual
Features: converted from manual
Relations: manual native
Contributors: Scarlata, Salvatore; Ackermann, Elia; Hellwig, Oliver; Biagetti, Erica; Widmer, Paul; Sellmer, Sven
Contributing: elsewhere
Contact: hellwig7@gmx.de
===============================================================================
</pre>