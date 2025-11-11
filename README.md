# Summary

UD Tswana-Popapolelo is a translation of the 20 Cairo Cicling sentences (https://github.com/UniversalDependencies/cairo) annotated with XPOS, UPOS and dependency relations.

# Introduction

There are 20 translated sentences with a total of 234 tokens.

The entire treebank is labeled as test set due to its size.
If it is used for training in future research, the users should employ ten-fold
cross-validation.

# Acknowledgments
Translations and initial annotations performed by Ansu Berg, Rigardt Pretorius, Kevin Mavalela, and Kaboentle
Maibi.

# References
The initial version of the treebank is described in detail in the following paper:

```
@inproceedings{gaustadetal2024udtreebank,
   author = {Gaustad, Tanja and Berg, Ansu and Eiselen, Roald and Pretorius, Rigardt},
   title = {The first Universal Dependency Treebank for Tswana: Tswana-Popapolelo},
   booktitle = {Proceedings of the fifth workshop on Resources for African Indigenous Languages (RAIL 2024)},
   publisher = {European Language Resources Association (ELRA)},
   pages = {N/A},
   type = {Conference Proceedings}
}
```

# POS Annotation
Automatic annotation was done with the NCHLT processing tools (https://hlt.nwu.ac.za/) and corrected manually. UPOS was automatically converted from the XPOS. The XPOS tags contain richer part-of-speech information for Tswana, e.g. class information, and are based on the NCHLT tag set (https://hdl.handle.net/20.500.12185/7).

# Changelog

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
Genre: grammar-examples
Lemmas: not available
UPOS: converted with corrections
XPOS: automatic with corrections
Features: automatic with corrections
Relations: manual native
Contributors: Berg, Ansu; Eiselen, Roald; Gaustad, Tanja; Pretorius, Rigardt
Contributing: here
Contact: tanja.gaustad@nwu.ac.za
===============================================================================
</pre>
