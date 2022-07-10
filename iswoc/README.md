The ISWOC Treebank
==================

The _ISWOC Treebank_ is a dependency treebank with morphosyntactic and
information-structure annotation. It includes texts in several older
Indo-European languages and is freely available under a [Creative Commons
Attribution-NonCommercial-ShareAlike 3.0 License](
http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

Please cite as

> Bech, Kristin and Kristine Eide. 2014. The ISWOC corpus. Department of Literature, Area Studies and European Languages, University of Oslo. http://iswoc.github.com.

Releases of the ISWOC Treebank are hosted on
[Github](https://github.com/iswoc/iswoc-treebank).

Contents
--------

The following texts are included in this release of the treebank:

  Text                                                | Language            | Filename    | Size
  ----                                                | --------            | --------    | ----
  Ælfric's Lives of Saints                            | Old English         | æls         | 3137 tokens
  Apollonius of Tyre                                  | Old English         | apt         | 5541 tokens
  Anglo-Saxon Chronicles                              | Old English         | chrona      | 5939 tokens
  Orosius                                             | Old English         | or          | 1728 tokens
  West-Saxon Gospels                                  | Old English         | wscp        | 13061 tokens
  La Vie Saint Eustace                                | Old French          | eustace     | 2340 tokens
  Crónica Geral de Espanha 2-12                       | Portuguese          | cge1        | 12074 tokens
  Crónica Geral de Espanha 155-167                    | Portuguese          | cge2        | 10547 tokens
  Décadas Livro 5, VIII, 9-14                         | Portuguese          | coutdec-v-8 | 13794 tokens
  Crónica de Alfonso XI                               | Spanish             | alfonso-xi  | 7942 tokens
  Crónica de España                                   | Spanish             | ce          | 4627 tokens
  El Conde Lucanor                                    | Spanish             | cdeluc      | 17551 tokens
  Estoria de Espanna I                                | Spanish             | ee1         | 9488 tokens
  General Estoria parte IV Daniel                     | Spanish             | ge4         | 9233 tokens
  Libro delos claros varones                          | Spanish             | varones     | 5820 tokens


(The 'size' column in the table above shows the number of annotated tokens in
a text. The number of tokens will be slightly larger than the number of words
in the original printed edition as some words have been split into multiple
tokens and some tokens have been inserted during annotation.)

Please see the XML files for detailed metadata and a full list of contributors.

Data formats
------------

The texts are available on two formats:

1. PROIEL XML: These files are the authoritative source files and the only ones
that contain all available annotation. They contain the complete morphological,
syntactic and information-structure annotation, as well as the complete text,
including punctuation, section headers etc. The schema is defined in
[`proiel.xsd`](https://github.com/proiel/proiel-treebank/blob/master/proiel.xsd).

2. [CoNLL-X format](http://nextens.uvt.nl/depparse-wiki/DataFormat)
