# TankU-LLM
A large language model specifically trained for low-resource languages



variables:

language profile:

language name:
language family: Niger Congo, Indo European, Afro-Asiatic, Sino-Tibetan, Austronesian, Trans New Guinea
sub_family: Franco-Carib, Romance, Dravidic, Semitic, etc  
avg word length
word order ratio: (SOV, SVO, OSV, etc)
phoneme inventory
phoneme associations (bound v unbound)
sentence length (words)
sentence length (phonemes)
paragraph length (words)
paragraph length (phonemes)
paragraph length (sentence)
agglutination

per piece:

word length
word position
sentence length (words)
sentence length (phonemes)
paragraph length (words)
paragraph length (phonemes)
orthographic changes (spelling)

contextual:

year of publication:
demographics of speaker and intended listener(s)
purpose of the writing: informative, entertainment, persuasive
topic classes relaated subclasses:
presentation type: novel, epic, poetry, free association, informative essay, scientific literature, screenplay, skit, short story, song, etc.


every topic should have an associated glossary set of probable words and co-topics

Step 1 
Parse passages by word length and choice

find all spaces
extract strings from between spaces to get words

compare strings to glossary
possibly add corrections for mispellings

t


step 2
parse by phonemes and groups thereof
take IPA phoneme inventory and rewrite the article so one sound gets one symbol, inserting IPA figures to patch over ambiguities



relate word choice to distance in passage
compare new data with a bank of translated training data
send translations to language team for vetting
Add vetted translation to training data and calculate the error rate.
