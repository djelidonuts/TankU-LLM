# TankU-LLM
A large language model specifically trained for low-resource languages


Notes for the user:

Contained herein is a neural network tool which through linguistic analysis serves bolster low-resource languages by generating and translating media. Training data for each language is gathered through word association games and grammar questionaires which is then processed to provide reading and learning materials. 
this tool can then be used to quickly establish a base of reading materials for languages typically excluded from scientific and technical discourse.


classes: family, language, passage, phrase, word



language instance attributes:



name:

family: Niger Congo, Indo European, Afro-Asiatic, Sino-Tibetan, Austronesian, Trans New Guinea

sub_family: Franco-Carib, Romance, Dravidic, Semitic, etc.

sister languages:

avg word length:

word order ratio: (SOV, SVO, OSV, OVS, VSO, VOS)

phoneme inventory:

phoneme associations (bound v unbound):

sentence length (words):

sentence length (phonemes):

paragraph length (words)

paragraph length (phonemes)

paragraph length (sentence)

agglutination/affix dependence:



passage instance attributes:



semantic:



word length

word position

sentence length (words)

sentence length (phonemes)

paragraph length (words)

paragraph length (phonemes)

orthographic changes (spelling)



contextual:



author name (if available):

year of publication:

city, country:

intended listener(s):

purpose of the writing: informative, entertainment, persuasive

topic classes/related subclasses: science, art, math, sports, popular culture, history, news,

presentation type: novel, epic, poetry, free association, informative essay, scientific literature, screenplay, skit, short story, song, etc.



family class attributes:



every topic should have an associated glossary set of probable words and co-topics

Step 1 
Parse passages by word length and choice

find all spaces
extract strings from between spaces to get words

compare strings to glossary
possibly add corrections for mispellings

t


step 2

relate word choice to distance in passage
compare new data with a bank of translated training data
send translations to language team for vetting
Add vetted translation to training data and calculate the error rate.

generating passages
if data is known about relationships between languages, closest family structures and cognates will be substituted in times of uncertainty


run passages through a noise function, replacing random words/phonemes, deleting them, etc.
send data to vetters for intelligibility review
search for common points of "just noticeable difference" which represented maximum points of integrated information for a given moment(like p/b/v, s/f)


