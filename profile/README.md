# ABBYY Compreno Semantics

<a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/static/v1?label=license&message=CC-BY-NC-4.0&color=green"/></a>

Here we present the materials for the semantic analysis of texts in natural languages based on the ABBYY Compreno linguistic technologies. 

ABBYY decided to publish this technology for the needs of the scientific society in the area of corpus linguistics under terms of the CC-BY-NC 4.0 License. 

The ABBYY Compreno model consists of morphological, syntactic and semantic patterns and includes the syntactic and semantic parser built on them.
The core of the model is the ABBYY Compreno Semantic Hierarchy - the thesaurus-like semantic tree, which consists of the semantic classes (SCs). SCs correspond to semantic fields universal for all languages included in the hierarchy and denote semantic senses common for all languages. The SCs are filled with lexical contents (lexical classes, or LCs) special for each language of the hierarchy.

The ABBYY Compreno Semantic Hierarchy is a part of the ABBYY Compreno markup format. The semantic part of the markup includes the boundaries of the constituents, the SC for every token and the semantic relations between all the constituents (semantic roles, or, deep slots). Additionally, the markup can also be provided with surface, or syntactic, roles, coreference, non-tree links, and some other information.

In the current repository, we suggest the following data:

- First, we open the [shortened version of the hierarchy](https://github.com/compreno-semantics/semantic-hierarchy), where one can see only the hyperonym SCs.

The hierarchy is presented in the form a .csv table which contains the information needed to visually re-create the Semantic Hierarchy as a tree for exploration. We also provide a [link](https://drive.google.com/file/d/13StDOV0t6MR7R9lAMBCUhrGT9d8yj9Ga/view?usp=drive_link) to the GUI program for browsing the hierarchy (Windows only).

- Second, we open the [simplified version of the semantic slot list](https://github.com/compreno-semantics/semantic-slots) with examples in English and Russian.


# Compreno semantics references

KV Anisimovich, K Yu Druzhkin, KA Zuev, FR Minlos, MA Petrova, and VP Selegei. 2012. Syntactic and
semantic parser based on ABBYY Compreno linguistic technologies. // Proc Dialogue, Russian International
Conference on Computational Linguistics, P 91–103.

MA Petrova. 2014. The compreno semantic model: the universality problem. International Journal of Lexicography, 27(2):105–129.

Ekaterina Manicheva, Maria Petrova, Elena
Kozlova, and Tatiana Popova. 2012. The compreno semantic model as integral framework for
multilingual lexical database. In Proceedings of
the 3rd Workshop on Cognitive Aspects of the
Lexicon, pages 215–230.

Yudina M. V., Garaschuk R. V., Petrova M. A., Druzhkina A. A. 2018. Semi-Automatic Integration Of A New Language Into A Multilingual NLP Model: The Case Of Japanese // Computational Linguistics and Intellectual Technologies.


J Detkova, V Novitskiy, M Petrova, and V Selegey. 2020. Differential semantic sketches for russian internet corpora. // Computational Linguistics and Intellectual Technologies, P 211–227.
