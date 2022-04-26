# TuGeBiC -- A Turkish German Bilingual Code-Switching Corpus

This repository presents the TuGeBiC corpus that contains annotated transcriptions of spontaneous speech samples from Turkish-German bilinguals.

The recordings and their transcriptions date back to the first half of the 1990s. In 2022 we revisited the transciptions 
to make it available for the research community in a computer-readible, standardised format. The main improvements are manual
tokenisation and normalisation, and the replacement of all proper names (names of participants and places mentioned 
in the conversations) with pseudonyms. We also performed token-level automatic language identification, which made it possible 
to derive basic statistics on the corpus.
<br/><br/>

<table>
<tr><td> \# of tokens </td><td align='right'>   116688 </td></tr>
<tr><td> \# of monolingual sentences </td><td align='right'>  10141 </td></tr>
<tr><td> \# of bilingual sentences </td><td align='right'>  4510 </td></tr>
<tr><td> \# of CS points in bilingual sentences </td><td align='right'>    8180 </td></tr>
</table>

<br/><br/>


There are 25 files in total in the corpus, presented in two different versions:

- **plain/tugebic_XX.txt**		files in plain text. 
- **langID/tugebic_XX.conllu**	files in CoNLL-U format. The `MISC` column contains predicted language IDs.

where XX is the file ID between 00 and 25.
