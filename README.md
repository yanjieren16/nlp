# nlp
Natural language processing programming assignment

The Hyphenator function in this program is based on pyphenate.py by Ned Bachelder, which was placed in the public domain in July 2007. The hyphenator algorithm is based on Frank Liang’s hyphenation algorithm.

This program was inplemented to reformat a text document by justifying (i.e., both left alignment and right alignment) the document to a different width for printing/displaying (e.g., adjust margins of the same size paper, change orientation of paper between portrait and landscape, change paper size, etc.) To make your task easier, assume all characters (letters, digits, punctuations, spaces, etc.) have the same size. In order to justify, the program uses multiple spaces roughly evenly between words. However, too many spaces between words make the document unpleasant to read, so this program splits the word with hyphens at line breaks. This program also handles indentations for bullets, numberings, multi-list, etc.
This program reads the input either pre-justified or not-justified text and divide it into words (by removing consecutive spaces), merge splitting-words (by removing hyphens or “\n”) and reformat and output to different width with justification and splitting.

Example Input:
40
Your program should scan the input pre-justified
text and divide it into words, merge splittingwords
(by removing hyphens or “\n”) and reformat
to different width with justification and splitting.

Example Output:
Your program should scan the input prejustified
text and divide into words,
merge splitting-words (by removing hy
