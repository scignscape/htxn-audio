# htxn-audio

This page links to a dataset and code library accompanying the article "Age-related hearing loss, speech understanding and cognitive
technologies" by Joseph Lehmann, et. al., to be published in the _International Journal of Speech Technology_. This link will be activated in early March, corresponding to the article publication in print. Thank you for your interest in the article, dataset, and code library.

---
**UPDATE**

The data set and code base are still under development, but a link is now provided to the repository and branch where the current work-in-progress is being hosted. Specifically, interested readers may browse or check out the https://github.com/scignscape/ntxh repository on the "ctg" branch: https://github.com/scignscape/ntxh/tree/ctg.

---
The data set includes a collection of language samples (mostly sentences) drawn from a variety of sources, including some invented to illustrate or examine claims in the context of cognitive grammar. Other samples are selected from writings of linguists such as Ronald Langacker, Geoffrey Nunberg, and Julia Hirsh, and from a recent Conference on Natural Language Learning corpus. In addition to the written sentences, a collection of audio samples used for speech quality measurement is republished from the IJST article _Subjective Speech Quality Measurement With and Without Parallel Task: Laboratory test results comparison_ by Hakob Avetisyan and Jan Holub. Collectively the sentences/samples are annotated with different kinds of parses, prosodic descriptions, or other analytic structures with the goal of exploring cognitive processing and how the cognitive dimensions of understanding can be related to other aspects of languages, such as speech and prosody, as well as prelinguistic situational awareness. The data set includes code and special software for viewing the samples, together with prototypes for novel document-generation formats, database management tools, and other programming concerns which could potentially be integrated into a cognitive-linguistics software platform. 

The sample annotations use several formats including 

1) S-Expressions to indicate parse structures
2) CONLLU dependency graphs
3) Prosodic Annotations using ToBI (Tones and Break Indices) or other markup to suggest intonation boundaries, stress patterns, and so forth.
4) Proposed variations on dependency graphs using De Bruijn indices, or in another context word-pairing sequences to decompose dependency parsers into particular head/dependency relations

Most of the samples are also printed inline in one of three accompanying documents discussing various linguistic and philosophical issues relevant to Cognitive Grammar. Dataset users may, if desired, read or skim over those documents to see the samples in the context of arguments discussing/analyzing them, as well as browsing the samples as a collection via the software applications whose code is provided with the data set. If built with PDF support, users can switch between the dataset application and the PDF documents by right-clicking on any of the samples; one context menu option provides a feature for launching a PDF viewer and reading the sample in the document context. 


This data set and code library will be published with the hope of helping to seed or inspire a broader software project in cognitive linguistics and particularly cognitive grammar, which could include features such as supporting different parse and analytic representations of language artifacts (e.g. sentences) annotated from a cognitive-grammar perspective, generating and visualizing parse-graphs and diagrams illustrating cognitive-grammar principles, integrating cognitive grammar with prosody and other linguistic concerns as well as cognitive science more generally, and so forth. The goal of collecting samples from existing linguistics literature -- such as those in the current data set from the Blackwell Handbook of Pragmatics -- could also easily be expanded to other sources, creating a larger corpus of samples which have been used in the literature to illustrate cognitive-linguistic claims.
  
