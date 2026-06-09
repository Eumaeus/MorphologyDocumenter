# Documenting the POS-Tag

## Overview
 
A "part-of-speech tag" ("postag) captures a morphological analysis for the word.  

It is a string 9 characters long, and corresponds to the following morphological features:
 
### 1: 	part of speech
 	
- n	noun
- v	verb
- t	participle
- a	adjective
- l	article
- d	adverb
- c	conjunction
- r	preposition
- p	pronoun
- m	numeral
- i	interjection
- e	exclamation
- u	punctuation
 	
### 2: 	person
 	
- 1	first person
- 2	second person
- 3	third person
 	
### 3: 	number
 	
- s	singular
- d	dual
- p	plural
 	
### 4: 	tense
 	
- p   present
- i   imperfect
- r   perfect
- l   pluperfect
- t   future perfect
- f   future
- a   aorist
 	
### 5: 	mood
			
- i	indicative
- s	subjunctive
- o	optative
- n	infinitive
- m	imperative
- p	participle
 	
### 6: 	voice
 	
- a	active
- p	passive
- m	middle
- e	medio-passive
 	
### 7:	gender
 	
- m	masculine
- f	feminine
- n	neuter
 	
### 8: 	case
 	
- n	nominative
- g	genitive
- d	dative
- a	accusative
- b	ablative
- v	vocative
- l	locative
 	
### 9: 	degree
 	
- c	comparative
- s	superlative
 	
## Examples 

n


describe_pos("ᾗ", "ὅς", "p-s---fd-")
describe_pos("ἐμπρῆσαί", "ἐμπίμπρημι", "v--ana---")
describe_pos("φέροντας", "φέρω", "v-pppama-")
describe_pos("ἠγάπησε", "ἀγαπάω", "v3saia---")
describe_pos("ἡσυχίας", "ἡσυχία", "n-s---fg-")
describe_pos("ἑαυτὸν", "ἑαυτοῦ", "p-s---ma-")
describe_pos("περιόψεται", "περιοράω", "v3sfim---")
describe_pos("Λακεδαιμονίους", "Λακεδαιμόνιος", "n-p---ma-")
describe_pos("γὰρ", "γάρ", "d--------")
describe_pos("ἐπεμείγνυντο", "ἐπιμίγνυμι", "v3piie---")
describe_pos("ἐπεμείγνυντο", "ἐπιμίγνυμι", "v3piie---")
describe_pos("γιγνόμενα", "γίγνομαι", "v-pppenn-")
describe_pos("γιγνόμενα", "γίγνομαι", "v-pppenn-")
describe_pos("πρόφασις", "πρόφασις", "n-s---fn-")
