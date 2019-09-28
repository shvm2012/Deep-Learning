1) You will find three language pairs : English-Bengali, English-Hindi, English-Telugu. Please choose one pair each
2) For each language pair, you will have two datasets - Facebook data and Twitter data. Use them for training, validation and testing.
3) Apart from the two language tags, you will encounter additional tags - UNIV (Universal.. represents universal expressions like numbers, symbols, etc. ),
NE(Named Entities), ACRO(Acronyms), UNDEF(Undefined.. where none of the tags make sense for the word)
4) Finally, you have POS tag information which can prove useful to train the model. Following is the description of the tags - 

N_NN 		Common Noun
N_NNV 		Verbal Noun
N_NNP 		Proper Noun
PR_PRP		Personal
PR_PRL		Relative
PR_PRF		Reflexive
PR_PRC		Reciprocal
PR_PRQ		Wh-Word
V_VM 		Main
V_VAUX 		Auxiliary
JJ 		Adjective
RB_ALC 		Locative Adverb
RB_AMN 		Adverb of Manner
DM_DMD 		Absolute
DM_DMI 		Indefinite
DM_DMQ 		Wh-word
DM_DMR 		Relative
QT_QTF 		General
QT_QTC 		Cardinal
QT_QTO 		Ordinal
RP_RPD 		Default
RP_NEG 		Negation
RP_INTF 	Intensifier
RP_INJ 		Interjection
RD_RDF 		Foreign Word
RD_SYM 		Symbol
RD_PUNC 	Punctuation
RD_UNK 		Unknown
RD_ECH 		Echo Word
CC 		Conjunction
PSP 		Pre-/Postposition
& 		Numeral
DT 		Determiner
@ 		At-mention
˜ 		Re-Tweet/discourse
E 		Emoticon
U 		URL or email
# 		Hashtag