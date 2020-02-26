[WordNet®] is a large lexical database of English. This package includes
data describing all parts-of-speech in [English WordNet] for use with
[WordNet container].

> Refer to [WordNet container] for usage examples.<br>
> All data has been transformed from [WordNet 3.1].

```javascript
const ENGLISH = require('extra-wordnet.english');
// -> {
//   table: {name, type, synset, pointers, frames},
//   blob: {senses, pointers, frames}
// }
```

### reference

| Method                  | Action
|-------------------------|-------
| [DATA]                  | Data describing all parts-of-speech in English WordNet for use with WordNet container.
| [ADJECTIVES]            | Adjective data of English WordNet as Map.
| [ADJECTIVE_WORDS]       | Adjective words of English WordNet as Array.
| [ADJECTIVE_EXCEPTIONS]  | Adjective exceptions of English WordNet as Map.
| [ADVERBS]               | Adverb data of English WordNet as Map.
| [ADVERB_WORDS]          | Adverb words of English WordNet as Array.
| [ADVERB_EXCEPTIONS]     | Adverb exceptions of English WordNet as Map.
| [NOUNS]                 | Noun data of English WordNet as Map.
| [NOUN_WORDS]            | Noun words of English WordNet as Array.
| [NOUN_EXCEPTIONS]       | Noun exceptions of English WordNet as Map.
| [VERBS]                 | Verb data of English WordNet as Map.
| [VERB_WORDS]            | Verb words of English WordNet as Array.
| [VERB_EXCEPTIONS]       | Verb exceptions of English WordNet as Map.
| [VERB_SENTENCES]        | Verb usage sentence list of English WordNet as Map.
| [VERB_FRAMES]           | Verb frames text of English WordNet as Array (from number).

### references

- Princeton University "About WordNet." [WordNet]. Princeton University. 2010.

<br>

[![nodef](https://merferry.glitch.me/card/extra-wordnet.english.svg)](https://nodef.github.io)

> Browserified, minified version of this package is [extra-wordnet.english.min].

[DATA]: https://github.com/nodef/extra-wordnet.english/wiki/DATA
[ADJECTIVES]: https://github.com/nodef/extra-wordnet.english/wiki/ADJECTIVES
[ADJECTIVE_WORDS]: https://github.com/nodef/extra-wordnet.english/wiki/ADJECTIVE_WORDS
[ADJECTIVE_EXCEPTIONS]: https://github.com/nodef/extra-wordnet.english/wiki/ADJECTIVE_EXCEPTIONS
[ADVERBS]: https://github.com/nodef/extra-wordnet.english/wiki/ADVERBS
[ADVERB_WORDS]: https://github.com/nodef/extra-wordnet.english/wiki/ADVERB_WORDS
[ADVERB_EXCEPTIONS]: https://github.com/nodef/extra-wordnet.english/wiki/ADVERB_EXCEPTIONS
[NOUNS]: https://github.com/nodef/extra-wordnet.english/wiki/NOUNS
[NOUN_WORDS]: https://github.com/nodef/extra-wordnet.english/wiki/NOUN_WORDS
[NOUN_EXCEPTIONS]: https://github.com/nodef/extra-wordnet.english/wiki/NOUN_EXCEPTIONS
[VERBS]: https://github.com/nodef/extra-wordnet.english/wiki/VERBS
[VERB_WORDS]: https://github.com/nodef/extra-wordnet.english/wiki/VERB_WORDS
[VERB_EXCEPTIONS]: https://github.com/nodef/extra-wordnet.english/wiki/VERB_EXCEPTIONS
[VERB_SENTENCES]: https://github.com/nodef/extra-wordnet.english/wiki/VERB_SENTENCES
[VERB_FRAMES]: https://github.com/nodef/extra-wordnet.english/wiki/VERB_FRAMES
[WordNet]: https://wordnet.princeton.edu/wordnet/
[WordNet®]: https://wordnet.princeton.edu/wordnet/
[English WordNet]: https://wordnet.princeton.edu/wordnet/
[WordNet 3.1]: http://wordnetweb.princeton.edu/perl/webwn
[WordNet container]: https://www.npmjs.com/package/extra-wordnet
[extra-wordnet.english.min]: https://www.npmjs.com/package/extra-wordnet.english.min
