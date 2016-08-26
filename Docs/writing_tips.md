# Writing tips

## General tips

* Don’t use more words than you need - some poor soul has to read them all.

* You get no extra credit for using long or obscure words - use little ol’ English.

* Don’t let your sentences run away from you - keep them short and simple.

* If you have a sense of humour - use it. In a pinch, [link](http://xkcd.com/1348/) [to](http://xkcd.com/195/) [xkcd](http://xkcd.com/386/).

* Technical writing should convey facts, not scatter confetti. If a sentence doesn't include at least one fact, it's probably a waste of the reader's time. Unless it's a joke, because giving people a break and a reason to smile helps them deal with text.

## Technobabble

Look, you deal with hardware, so maybe you'll find a good reason to reverse the polarity of the neutron flow. But until you do, please could you speak English?

You have to notice when you’re throwing out odd bits of vocabulary as if they’re common knowledge. Some may very well be; others will not. Usually the problem is that within the context of a sentence, you don’t stop and think about all of the words you’re using and how many of them don't make sense to anyone who doesn't already know the material. You certainly don't think about the possibility that a google search will bring 100 irrelevant results, so at least do google it for the reader.

On first use, give the meaning of initials, then the initials in parentheses. For example, it’s Bluetooth Low Energy (BLE), not BLE (Bluetooth Low Energy). Don’t bother doing this with things that are more commonly known by their initials, like BBC. You can put the full term in italics if you like: *Bluetooth Low Energy* (BLE).

## Writing an instruction

If you're giving a one-step instruction, you just write "x to y". So:

> "Select Compile > Update Docs to regenerate the program documentation".

Or "for y, do x":

> "To regenerate the program documentation, select Compile > Update Docs".

If you have more than one step, start with the expected result, then the steps as a numbered list ("for y, do x"). So it's:

> "To create a new program:

> 1. Select New > New Program to open the Create New Program window.

> 2. Another action.

> 3. You get the point."

Fun fact (it's not a fact, just a preference): we use bullets if a list can come in any order and numbers if the list can only come in the order in which it's presented. Instructions will therefore tend to be numbered.

It's better to tell people what they should do, not what they shouldn't do. If you're worried about damage to hardware: add a warning, then be as negative as you want. Note that warnings are not a step in the instructions; they're a formatted paragraph before all steps or before the relevant step. The formatting should stand out from the list, but not be too jarring.

__Naming things__

When giving keyboard shortcuts:

* Use “press” for a physical button or key (like the power button on the boards, or keyboard keys).

* Give the short form with a capital letter: Del, Cmd.

* If more than one key is required, use + without spaces: Ctrl+Alt+Del.

When talking about on-screen buttons:

* Use “click” for something in a GUI (like the compile button).

* If the button has a name (written on it) you can refer to it directly with a capital letter, and you can also use bold font if you want: “click **Compile**”. But if there’s just an icon, it’s best to use a few more words: “click the search button” (no capital, and using an article, because there’s no name for the button).

## Additional material

Additional material can be problem solving, FAQ, links to other resources and anything that you couldn't shove into the main body of the text. You don't have to include it, but if you do it's important you don't treat it as a catch-all; you should put stuff within the main body if at all possible, resorting to the additional material section only for things that cannot possibly fit anywhere else. 

FAQs are often a repetition of the main body. In a sense they're highlights, rather than new information. That's fine. They're also often a dumping ground for things you don't want to say in the main body because you're mildly embarrassed. That, too, is fine.

## Writing an introduction

An introduction has two main jobs: tell me what your tool does, and tell me why I should use it (instead of some other tool). To do all that, an introduction will usually cover:

1. What the tool is supposed to do.

2. How it manages to do it.

3. Perhaps a couple of features, to highlight the tool's awesome capabilities.

4. Sometimes version differences (see next section).

## Version differences

If this isn't the first version of the tool, it's polite to highlight the differences between the current version and the previous one:

* If it's only a couple of new things, put them in the introduction.

* If there are many differences, put them in their own section right after the introduction. 

Wherever you put the differences, it's helpful to readers if you flag them with "what's new in version x" or something similar. Readers who are already familiar with your tool are fishing for the version differences - they don't need the full guide.

## Cross referencing

It's helpful to cross reference - with links. 

Introduce information in the order in which you expect the reader to learn it; readers shouldn't have to jump between sections to put the story together. Cross-references should therefore link back (to things the reader has already read), not forward. However, there are times when you should forward reference:

* In an introduction, where it allows people to skip to the interesting bits (it functions like a table of contents). This is true for all introductions - for the whole doc, for a chapter, for a section or set of instructions - anything.

* When you're telling people "if you're already familiar with x, skip to y", giving knowledgeable readers a handy bypass of the beginners' stuff.

* When saying "this is all you need for now, but we'll go further into this at a later section". Here the purpose of the reference is to allow curious readers to see ahead, not to provide essential information.

* If you're sending readers to an appendix.

* If you're pointing to a figure in the next page.

A couple of notes:

* Don't say "below" or "above" or anything like that unless you're one paragraph away from where you're pointing to. You're making the user guess, and anyway you may reorder the text. Give the name of the section and a link. 

* It's good to introduce (at least as a list) all the sections of a guide in the introduction. Link to them.

## A final word of warning

Do not leave your own notes in the text when you publish it, especially if you tend to be less than entirely polite when talking to yourself (and your collaborators). Always preface them with the same bit of text, like TBD or WTH, and do a search on it before publishing.
