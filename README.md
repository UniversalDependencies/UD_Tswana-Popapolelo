# Summary

UD Tswana-Popapolelo is a treebank for Tswana containing translation of the 20 Cairo Cicling sentences (https://github.com/UniversalDependencies/cairo) as well as 30 sentences containing examples of verbs with causative, applicative and reciprocal verbal extensions sourced from the SetswanaWaC v2 corpus (via SketchEngine), both annotated with XPOS, UPOS and dependency relations.

# Introduction

There are 50 sentences with a total of 600 tokens.

The first 20 sentences (sentence IDs starting with CC followed by a number) are Tswana translations of the Cairo Cicling sentences.

The other 30 sentences (sentence IDs starting with A (applicative verbs), C (causative verbs) or R (reciprocal verbs) followed by a number) are part of a study done for an MA thesis in Setswana carried out by Kevin Mavalela at the North-West University, South Africa, with the title "The influence of Setswana causative, applicative and reciprocal verbal extensions on argument structure". The focus of the study is on the applicative, causative and reciprocal verbal extensions to determine their influence on the argument structure in sentences. This includes determining the transitivity of the inflected verbs as well as investigating if the valency of these verbs are increased, decreased (reduced) or otherwise changed. The data has been extracted from the SetswanaWaC v2 corpus via SketchEngine (https://www.sketchengine.eu/).

The entire treebank is labeled as test set due to its size.
If it is used for training in future research, the users should employ ten-fold
cross-validation.

# Acknowledgments
Translations and initial annotations performed by Ansu Berg, Rigardt Pretorius, Kevin Mavalela, and Kaboentle Maibi.

# POS Annotation
Automatic annotation was done with the NCHLT processing tools (https://hlt.nwu.ac.za/) and corrected manually. UPOS was automatically converted from the XPOS and corrected manually. The XPOS tags contain richer part-of-speech information for Tswana, e.g. class information, and are based on the NCHLT tag set (https://hdl.handle.net/20.500.12185/7).

# Changelog

* 2026-11-15 v2.19
  * Added 30 sentences with CAR verbs
  * Added features Poss and PronType
  * Added dep rel advcl-relcl
  * Updated copulas and auxiliaries
  * Added lemmas and Poss/PronType features for 20 Cairo Cicling sentences
* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.


# Contact

Tanja Gaustad (Tanja.Gaustad@nwu.ac.za)

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Parallel: cairo
Genre: grammar-examples web
Lemmas: manual native
UPOS: converted with corrections
XPOS: automatic with corrections
Features: manual native
Relations: manual native
Contributors: Berg, Ansu; Eiselen, Roald; Gaustad, Tanja; Mavalela, Kevin; Pretorius, Rigardt
Contributing: here
Contact: tanja.gaustad@nwu.ac.za
===============================================================================
</pre>
