# Tokenized CTSized Ancient Greek Texts

This repository contains the tokenized (graphic word) texts of the following two repositories (TSV format derived from the XML one in
https://github.com/gcelano/CTSAncientGreekXML; only the cts information of the text element is kept):
* https://github.com/PerseusDL/canonical-greekLit
* https://github.com/OpenGreekAndLatin/First1KGreek

The texts have been automatically generated from the original XML files which are well-formed and CTS-compliant (some may not). Some conversion errors are due to annotation inconsistencies in the original files, which I have not tried to solve). Each
file contains tab-separated values: 
* the first column lists the passage (the full cts urn derives from merging this value and the cts urn of the text shown in the # comment)
* the second column shows the running number id for each word (numeration starts again as the passage changes)
* the third column contains the word form
* the forth column specifies whether a punctuation mark should be attached to the preceding (b) or following (a) word.
* the fifth column shows some special elements which contained the word: more precisely, the add, del, unclear, surplus, supplied and seg elements, which can be 
of interest to identify editorial interventions

# License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
