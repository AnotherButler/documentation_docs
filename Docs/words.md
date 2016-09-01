# Words, voices and grammar 

## Spelling

### In general 

* Put all your text into something that can check your spelling. Do not trust yourself.

* Do not trust the spellchecker.

* Okay, that was a bit unfair. If you’re not sure you’ve got the correct spelling, you can do two things: google the spelling you have and see what the dictionary says, or google both forms (“x or y?”) and see if anyone explains the difference. If the only difference is that one is British and one is American, please use American.

* Do not use all-caps unless that is the legal form of a name (so it's ARM, not Arm).

* There is a difference between the verb and noun forms of many words in software. For example, "login" is the noun, "log in" is the verb. So the window is "Login", but the button is "Log In" (yes, buttons are verbs). Other pairs: setup/set up; startup/start up; takeoff/take off.

* On first use, give the meaning of initials, then the initials in parentheses. For example, it’s Bluetooth Low Energy (BLE), not BLE (Bluetooth Low Energy). Don’t bother doing this with things that are more commonly known by their initials, like BBC. You can put the full term in italics if you like: *Bluetooth Low Energy* (BLE).


### A word about American v British English

ARM uses the [Chicago Manual of Style](http://www.chicagomanualofstyle.org/16/contents) and [Merriam-Webster's Collegiate Dictionary](http://www.merriam-webster.com/). Both of these are in American English (or International English, which follows the American spelling). 

To pick a spelling for a word with two or more commonly used options, go to Merriam-Webster and use the spelling listed first. 

The ARM style guide has a summary of the most consistent differences between British and International English:

* Past and continuous tense of words ending in -l do not use -ll. For example: 
	* Cancelled is canceled. 
	* Cancelling is canceling. 
	* Labelled is labeled. 
	* Labelling is labeling. 

* Words ending in -ise end in -ize. For example:
	* Initialise is initialize. 
	* Customise is customize. 

* Words ending in -yse end in -yze. For example: 
	* Analyse is analyze. 

* Words ending in -our end in -or. For example: 
	* Colour is color. 
	* Behaviour is behavior. 

* Past and past participle tense of words ending in -t end in -ed. For example: 
	* Learnt is learned. 
	* Spelt is spelled. 

* Words ending in -ogue end in -og. 
	* For example: — Dialogue is dialog

### Some words you often get wrong

* It's "any more", not "anymore".

* Bottleneck (one word).

* "Cannot" is a single word. It's separated into two (can not) when you want to stress one of the words or when giving the option not to do something. This often makes you sound like a parent arguing with their child, so be careful.

* Command-line (two words with a hyphen).

* Foolproof is one word, and a fantasy.

* The [Guardian says](http://www.theguardian.com/guardian-observer-style-guide-g) "Google" is the correct form of the verb; I write "google". Pick one and stick with it (hint: the Guardian knows more than I do).

* Identical with (not to).

* You give someone a *licence* (noun), but you *license* (verb) an item.

* Log into (two words, not three).

* Nevertheless, nonetheless (one word).

* Onto is usually one word.

* Oriented (not orientated) and disoriented (not disorientated).

* Password (one word).

* Pixelated (but pixilated means drunk, so you may well be using it correctly).

* You invite someone to the *practice* room (noun), where you *practise* (verb).

* Under way (two words).

* Usable, not useable.

* User-generated content.

* v, not vs.

### It's its IT's ITs list

I never thought it would come to this, but I'm going to explain the difference between it's and its:

* It's: short of "it is". 

* Its: possessive form of "it".

* IT's: possessive form of the IT department.

* ITs: many people from the IT department.

And while we're at it:

* You're: short for "you are".

* Your: possessive form of "you".

* Yous: plural form of you in some dialects; please don't use it, because it's non-standard to a degree that will confuse non-native speakers.

* You is: singular form of you in some dialects. Again, confusing for non-native speakers.

### A or an?

For a/an before H or abbreviations, I'll just [quote the Guardian](http://www.theguardian.com/guardian-observer-style-guide-a): "Use *an* before a silent H: an heir, an hour, an honest politician, an honorary consul; use *a* before an aspirated H: a hero, a hotel, a historian (but don't change a direct quote if the speaker says, for example, "an historic"). With abbreviations, be guided by pronunciation: eg an LSE student." 

This is one of the many ways in which it's impossible to learn English until you know English.

## Passive and active voices

The objection to passive constructions is not as mental as you think. A passive sentence can make perfectly reasonable developers think they don't have control of the process, when in fact you were trying to tell them exactly the opposite. 

Consider a situation where you're writing an application that allows your device to talk to some third-party device, and each device has control over part of the relationship. If your API documentation says "x can be controlled", that doesn't give a good idea of which device controls it. Can you control it - or can the other device reject your attempt at control?

So use active rather than passive constructions. "You can x", not "x can be". But use the passive when:

* The active sounds like it's shouting at the reader.

* There is no specific entity performing the action, so you don't have a pronoun around which to construct an active sentence.

* If there's no way to control something, it's better to use the passive voice rather than mislead the reader. For example, don't create an illusion that something is under the user's control when it's actually hardcoded.

## Grammar (and similar considerations)

* Feel free to ignore Latin grammar that’s been shoved down English’s throat (to boldly split where no infinitive was split before, as they say).

* The rule that you can’t use a noun as a verb is only here to give snobs something to snob about (see what I did there?). Of course you can - an estimated 20% of English verbs are nouns doing double-duty.

* Don't use &, /, # and so on. There's enough room for the words and you don't know how someone might understand the symbol. Remember the lesson of "I don't have a key called Any". Besides, it’s ugly and I hate it - and I edit your texts.

* I distinguish “which” and “that”, though some might say it’s fussy of me:
    * “Which” comes after a comma, and denotes a non-essential bit of information (from the point of view of the sentence, not the universe). For example, if you say "Hamsters, which have no table manners, are eaten by zombies", you mean that zombies eat hamsters, and also that hamsters have no table manners. If you remove "which have no table manners", the sentence remains true, just slightly less informative.
    * “That” comes without a comma and the information following it should be vital to the sentence. If you say "Zombies eat hamsters that have no table manners" you mean that zombies eat only those hamsters that don't have table manners (which seems like a harsh punishment). If you remove "that have no table manners", you make the sentence a lie by saying that zombies eat all hamsters.

* Double negatives are not grammatically wrong, but they’re often very confusing. This isn’t because people can’t read, it’s because double negatives are used differently in different languages and English dialects - they can either cancel each other out or intensify each other - and you have an international audience; best to stick to single negatives or develop a positive mindset. Good luck with that.

* I don’t have many pet peeves, but the “and/or” construction drives me nuts (using just / drives me even crazier). In 99.99% of the cases (no, I didn’t count) one of them is enough. If not, English has been kind enough to give you plenty of nice ways to indicate choices and constraints. The point is that people should know for certain whether you meant "or", "and" or "one or both", and the stroke leaves too much room for error.

* Plurals: use [common sense](http://www.theguardian.com/media/mind-your-language/2015/jul/17/two-whoppers-junior-please-with-hashes-brown-on-the-side).

## Vocabulary

Here is the correct form of several terms you shouldn’t be using: I couldn’t care less (unless you could); gobbledegook (not gobbledygook); groundbreaking (don’t flatter yourself); hovercraft (although if you find a legitimate reason to use this in mbed documentation, I’m sure we’ll all appreciate it); knowhow (it’s not two words, just an ugly one); morris dancing (as in “technical writing is the morris dancing of the writing world”); ongoing (not two words; not a word, either - it’s jargon, so don’t use it); Tardis (but see the note about hovercrafts).

### In general

* Don't give the same thing two different names. This is not a cryptic puzzle.

* Don’t give two different things the same name. That’s just mean.

* Do not make up words. If there is no un- or in- form for your word, it's not up to you to create it. If I google your word, I want to find it.

* Latin's nice and all, but if you can find an English equivalent, please use it. Normally “a” would do for “per”: “200 users a year”, not “200 users per annum”. This also applies to ie, eg and etc, which many of you sprinkle over your texts like chocolate buttons over a cake.

* Make sure your sentence doesn't include the same word more than once, hiding behind different forms. A common mistake is to use two words that mean “and a few others like this”. If you write “Such as x, y, z and more”, then “and more” and “such as” are doing the same job. “Including a, b, c etc”: “including” and “etc” are doing the same job.

* Don’t use slang or regional English unless it’s very well known, and even then remember that it can make your text sound flippant - best to use it when you’re trying to get your audience to loosen up. Remember that you have an international audience, so what constitutes “well known” is anyone’s guess.

* On first use, give the meaning of initials, then the initials in parentheses. For example, it’s "Bluetooth Low Energy (BLE)", not "BLE (Bluetooth Low Energy)". Don’t bother doing this with things that are more commonly known by their initials, like BBC. You can put the full term in italics if you like: *Bluetooth Low Energy* (BLE).

### Counting things

* If you can count it, it's “fewer”. If you can't count it, it's “less”. This often doesn’t matter to readers, but sometimes choosing the wrong word makes a mess of your sentence. For example, you may modify a noun to be weaker (less) rather than smaller in number (fewer): “you’ll need less powerful boards” (weaker boards are enough) or “you’ll need fewer powerful boards” (if you use powerful boards, you won’t need as many).

* In a sentence, it’s:
	
	* One to ten and first to tenth.

	* 10-999,999 and 10th to 999,999th.

	* Then 1m, 5bn, millionth etc, unless you’re counting users, then it’s always million or billion (spelled-out).

	* If you're mixing numbers below and above ten, go with numerals: 4, 9 and 17 (not four, nine and 17).

	* If you're using a unit of measure, use a numeral. I often don't (I tend to write "four KB" rather than "4KB"), but I'm wrong about it.

	* If the number is the first word of a sentence, it’s always spelled out. If you don’t want to spell it out - change your sentence.

	* When you're referencing steps, it's in numerals, not words (step 2, step 14).
	
* Thanks to the Economist, we know that ["last year" means 2015](http://www.economist.com/styleguide/l#node-21534682). If you mean the 12 months up to now, you mean "past year". This applies to month and week, too. Generally, it’s easier to give an exact date (or range of dates), so that your dates don’t become outdated.

## Now I'm really nitpicking

* Please remember that "alright" and "all right" mean different things.

* So do "as" (causal) and "since" (temporal). I almost never obey this rule. But also note that using "as" when you mean "because" can confuse non-native speakers, so it's best to avoid it.

* [Centered *on*, not around or in](http://www.economist.com/styleguide/c#node-21532488). Also: [in the circumstances](http://www.economist.com/styleguide/c#node-21532496), not under them (for British English; if you’re American you can use either. So basically, you can use either).

* Always google “comprise”, “consist”, “compose” and “constitute” if you want to use them correctly. Or just [wait for someone to edit your texts](http://www.theguardian.com/commentisfree/2015/feb/05/why-wikipedias-grammar-vigilante-is-wrong).

* The Guardian says: [Continual: repeatedly, but not constantly. Continuous: unbroken sequence](http://www.theguardian.com/guardian-observer-style-guide-c).

* Data is plural. Feel free to ignore that, because most Latin plurals have long-since become singular and data will not be an exception for long.

* Safest to say “different from”, not “different to”. Never say “different than” or “differs to”.

* If, whether, whether or not: [Grammar Girl has it](http://www.quickanddirtytips.com/education/grammar/if-versus-whether).

* Mass nouns (water, furniture) are followed by the singular form of the verb. So the verb following "data" is "is", which is another reason you don't need to remember that it's a plural in Latin. The easiest way to know if something is a mass noun is to try to count it: if you have to add a unit of measurement, it's a mass noun. Going back to water, it'll have to be in litres or glasses to be counted.

* The Economist has a nice explanation of when ["may" might mean "might"](http://www.economist.com/style-guide/may-might).

* Generally, “starting with” is for when the order doesn’t actually matter, we just pick a starting point at random. “Starting from” implies that there is a logical order. So with versions, we might expect it to be “starting from”.

* Substitute *by*, *with* and *for* are different ideas.

* Systematic: methodical. Systemic: relating to a system](http://www.theguardian.com/guardian-observer-style-guide-s).

* You're supposed to use "therefore" at the start of a sentence and "so" in the middle of it. I almost always use "so". And when I do get round to using "therefore", I tend to stick it in the middle of a sentence (but between two commas; I'm not a total slob).

* Try to, not try and.

* You may think that "whom" is dead and good riddance to it, but it has its uses: in some sentences it’s the only way to clarify who did what to whom. There’s an [easy way to remember the difference](https://www.youtube.com/watch?v=zBZgZ4e36IU#t=38). And a slightly more helpful one over at [The Oatmeal](http://theoatmeal.com/comics/who_vs_whom). Too lazy? Then rewrite your sentence so that it's clear without "whom".


## Proper nouns

Quick flashback to school (stop screaming, it will be over soon!): there are two kinds of nouns, proper and common. A proper noun points to a unique thing, and it therefore takes no article (unless the article is part of the name, like the Rolling Stones). A common noun, on the other hand, points to a class or a non-specific instance of a class, and therefore takes an article.

When you're referring to specific APIs, functions, services and so on, the structure of the sentence is how you'll know if they're proper or common. "We use BLE_API" - this is a specific API. It's a proper noun, and therefore takes no article. "We use the BLE, not Wi-Fi, API" - you're talking about two kinds of API, and the focus is on the API. The two kinds - BLE and Wi-Fi - are treated as common nouns, and they take the article "the". You'll note that we didn't use their proper names (BLE_API has an underscore, "the BLE API" doesn't).

The difference is more obvious in the following two sentences: "we call waitForEvent()" and "we call the waitForEvent() function". The reason you needed the article "the" in the second sentence is that you used the word "function", rather than just the name of a specific function

This is not 100% consistent. Nothing in English is, though, so I’m not too worried.

## Using jargon

[Don’t](http://www.amazon.co.uk/Who-Touched-Base-Thought-Shower/dp/1444781847).

Never confuse field-specific vocabulary with jargon. The first is necessary to all fields and specific to each one, the second is useless and identical in all fields (although the self help people are driving a goals-oriented approach to markedly distinguish the essence of their individual personalities by meticulously crafting a holistic communication experience that is both unique and networking-supportive). Use the simplest word that accurately describes what you’re trying to say, and don’t use more words than you need.

Every style guide you’ll read will, at this point, quote [Bill Bryson](http://www.theguardian.com/guardian-observer-style-guide-j): “[Jargon is] the practice of never calling a spade a spade when you might instead call it a manual earth-restructuring implement”.

Imagine a stranger saying what you just wrote; would you think they're knowledgable professionals, or would you roll your eyes and stop listening? This is the process your reader goes through when reading your text. 

## Technobabble

Look, you deal with hardware, so maybe you'll find a good reason to reverse the polarity of the neutron flow. But until you do, please could you speak English?

You have to notice when you’re throwing out odd bits of vocabulary as if they’re common knowledge. Some may very well be; others will not. Usually the problem is that within the context of a sentence, you don’t stop and think about all of the words you’re using and how many of them don't make sense to anyone who doesn't already know the material. You certainly don't think about the possibility that a google search will bring 100 irrelevant results, so at least do google it for the reader.

