An Anki deck for learning Spanish castellano as used in mainland Spain. The source language is British English. This is a continuously evolving deck.

# Requirements
This deck uses the [lela-anki-note](https://gitlab.com/evolverine/lela-Anki-note). If you have any issue related to the content, please open a ticket here. If it's about the functionality, it will be related to Lela.

To import this deck you will need [the CrowdAnki](https://ankiweb.net/shared/info/1788670778), and the [CookieMonster](https://ankiweb.net/shared/info/1501583548) addons.

# Collaboration
The main goal of this deck is to be continually improved by learners. For this to be possible, though, one currently needs a working understanding and knowledge of [the git versioning system](https://git-scm.com/). If that is the case, make sure you've installed it, and then install [CrowdAnki](https://ankiweb.net/shared/info/1788670778).

## Way of working

* make as small commits as possible. Ideally one commit for each changed note. (Admittedly I have yet to start following this rule, but once collaboration starts to happen it will be more important.)
* specify, whenever possible, the source of the changes in your commit messages - was it a native speaker (from which country / region?) who recommended it, was it a dictionary (which?), an online forum (which?), etc.

### Conventions

#### Tagging
* tag notes as specifically as possible
** \[verb\] for verbs, \[noun\] for nouns, \[adjective\] for adjectives, \[adverb\] for adverbs.
** for verbs one can be even more specific, with \[verb_infinitive\], \[verb_gerund\], \[verb_reflexive\], \[verb_imperative\], \[verb_subjunctive\]

#### Content
* all nouns come with their article ("the" in English, and "el/la" in Spanish)
* all verbs come with their article in English, ("to").
* nouns can be requested and learned in both their masculine and feminine forms, and, if desired, both in their singular and plural forms. This is useful when these forms are not standard in some way. When using the two genders, tag the note with "indication_2_genders_learned", and when representing both the singular and plural forms, use the tag "indication_singular_plural_learned".
* when it is unclear which meaning of the word / phrase you want remembered, you have two options:
  * **the gamut of "clarification_" tags**, which display a visual indication specifying that the word is an adjective, adverb, preposition, (transitive) verb, or a specific concept such as a color or a number. The last one is "clarification_expression", which indicates that a single word may exist, but that in this note one expects an expression instead.
  * using **contexts**: anything you put between brackets, for example \[context\] is by default hidden from the user until they decide to show it (by long-pressing on it). For example, "el piso \[🛏\]" ("the flat") vs. "el piso \[🏢\]" ("the floor").
* when the translation for a word or phrase is vague, prefer adding a full sentence instead. For example, "estribar" means "to lie in", such as a problem. Instead of having only the word and its translation, it's better to have a note of the form "the problem lies in..." to "el problema estriba en...", even if it doesn't exemplify all the possible ways it can be used.
* in the case of synonyms order them by frequency of use.
* prefer avoiding extraneous synonyms. For example, "la fatiga" translates into "the fatigue" and, based on the context, into other of its synonyms, such as "the tiredness". However, a better a-contextual translation for "the tiredness" is "el cansancio", so the latter should be its own separate note, and "la fatiga" should be translated only into "the fatigue".
* When there are specific notes for when to use one or the other of the versions in a note, explain this in the "usage note" field.
