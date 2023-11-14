# ediarum.BASE.data-model

This repository contains the definition of the ediarum.BASE data model as ODD. It is based on the _Base format_ of the German Text Archive (DTABf). It is therefore also formally derived from this (using ODD chaining), i.e. the (compiled) DTABf ODD is specified as the source schema in the ODD.

The "dist" folder contains:
* the Relax NG file, which can be integrated as a schema in Oxygen XML Author and other XML-based software in order to validate XML files against it
* the compiled ODD file, which can be used as a starting point for creating ODD files for project-specific adaptations and additions of ediarum.BASE.

## References

DTABf. Deutsches Textarchiv – Basisformat (2011–2022), ed. by Berlin-Brandenburg Academy of Sciences and Humanities. <http://deutschestextarchiv.de/doku/basisformat>

Haaf, Susanne; Geyken, Alexander; Wiegand, Frank (2014/15): The DTA “Base Format”: A TEI Subset for the Compilation of a Large Reference Corpus of Printed Text from Multiple Sources. In: jTEI 8 (Selected Papers from the 2013 TEI Conference). <http://jtei.revues.org/1114>

Haaf, Susanne; Thomas, Christian (2016): Enabling the Encoding of Manuscripts within the DTABf: Extension and Modularization of the Format. In: jTEI 10 (Selected Papers from the 2015 TEI Conference). <https://journals.openedition.org/jtei/1650>