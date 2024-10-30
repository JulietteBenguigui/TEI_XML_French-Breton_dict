# Encoding a French-Breton Dictionary with TEI XML

## Context

This project, developed as part of an academic program, encodes a French-Breton dictionary, specifically focusing on the Vannes dialect, using TEI (Text Encoding Initiative) Guidelines. Sample materials, including unprocessed PDFs and JPEGs, are provided alongside an XML template and a custom DTD based on TEI. 

## Source Description

This project encodes a historical *Dictionnaire breton-français du dialecte de Vannes* by *Pierre de Châlons* (1641-1718), a French lexicographer specialised in the Vannes dialect. The dictionnary was revised in 1895 by *Joseph Loth* (1847-1934), a prominent Celtic linguist. Published by J. Plihon and L. Hervé in Rennes, this dictionary is a part of the *Bibliothèque bretonne armoricaine* collection. The edition provides an in-depth lexicon of the Vannes dialect, with French translations and supplementary references in other Celtic languages, such as Welsh or other Breton dialects. The digital source file used in this project is held by the *National Library of France, Literature and Art Department* and is available online, catalogued under the identifier [ark:/12148/bpt6k113565r](http://catalogue.bnf.fr/ark:/12148/cb308355735).

## Purpose and Methodology

The encoding framework implemented in this project follows the TEI Guidelines, with customizations made to support comparative linguistics studies. It aims to facilitate structured data extraction, linguistic comparison, and analysis of dialectal variations within the Celtic language family, with a particular emphasis on the Breton Vannes dialect. This XML encoding lays a foundation for future, more extensive work that will enable structured and accessible insights into the linguistic and historical richness of the source. The encoding of the main body of the text follows the guidelines of the *Dictionnary* module of TEI. To emphasize the multilingustic nature of the source, it was decided to use the <cit> element with the @type attribute "translation". The idea was to make it accessible to researchers to extract specific entries in different languages. 

## License

This project is under the MIT License. Please check the LICENSE file in the repository for more information.
