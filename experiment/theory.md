Part-of-speech tagging (POS tagging) is the process of marking up a word in a text as corresponding to a particular part of speech, based on both its definition, as well as its context. POS-taggers play an increasingly important role in speech recognition, natural language parsing and information retrieval.

In traditional grammars there were generally only a few parts of speech (Refer to Experiment 5). However, there is a need for further distinction within these categories. For example these tagsets distinguish between possessive pronouns (my, your, his, her, its) and personal pronouns (I, you, he, me). Knowing whether a word is a possessive pronoun or a personal pronoun can tell us what words are likely to occur in its vicinity.
For Example , possessive pronouns are likely to be followed by a noun, personal pronouns by a verb.
- his(Possessive) pen(Noun)
- he(Personal_Pronoun) went(Verb)


Therefore, each of the traditional part of speech can be made more fine-grained so that can convey additional information. Such a tagset (adapted from the Penn tagset) is shown below:

<p style="text-align:center; font-size:24px"><b>PENN tagset</b></p>

|POS Tag|Deacription|Example|
|---|---|---|
|CC |Coordinating Conjunction|and, but, or|
|CD |Cardinal Number|1, one, third|
|DT |Determiner|the, some|
|EX |Existential There|there is|
|IN |Preposition/Subordinating conjunction|in, of, like, that|
|JJ |Adjective|green, good|
|JJR|Adjective, Comparative|greener, better|
|JJS|Adjective, Superlative|greenest, best|
|MD |Modal|could, will|
|NN |Noun, Singular or Mass|table|
|NNS|Noun Plural|tables|
|NNP|Proper Noun, Singular|John, Google|
|NNPS|Proper Noun, Plural|Vikings, Bachchans|
|PDT|Predeterminer|both the boys|
|POS|Possessive Ending|friend's|
|PRP|Personal Pronoun|I, he, it|
|PRP&#36;|Possessive Pronoun|my, his|
|RB |Adverb|however, usually, naturally, here, very|
|RBR|Adverb, Comparative|more|
|RBS|Adverb, Superlative|most|
|RP|Particle|give up|
|TO |To |to go, to him|
|UH |Interjection|uhhuhhuhh|
|VB |Verb, base form|take|
|VBD|Verb, Past|Took|
|VBG|Verb, Gerund/Present Participle|Taking|
|VBN|Verb, Past Participle|Taken|
|VBP|Verb, Singular, Present, non-3rd person|Take|
|VBZ|Verb, Singular, Present, 3rd person|Takes|
|WDT|Wh-determiner|which|
|WP |Wh-pronoun|who, what|
|WP&#36;|Possessive Wh-pronoun|whose|
|WRB|Wh-abverb|where,when|



For eg :<br/>
**A child in the play liked to place the green bill on the red flower, and used to wonder which of them was beautiful.**<br/>
A/DT child/NN in/IN the/DT play/NN liked/VBD to/TO place/VB the/DT green/JJ bill/NN on/IN the/DT red/JJ flower/NN and/CC used/VBD to/TO wonder/VB which/WDT of/IN them/PRP was/VBD beautiful/JJ




|   |   |   |   |   |
|---|---|---|---|---|
|   |   |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |
