# How to flesh out your document map

## The plan

Now you have a map of features and their sub-functions or options. Assuming it's not enough (don't assume - for [some things it may well do](#Scalability)), how do you turn that map into a text? You measure every feature on your list against a checklist.

### Checklists

Every feature your tool offers (probably) has the following:

1. A purpose.

2. A mechanism.

3. Options and sub-functions.

4. One or more results.

5. One or more failure scenarios and ways of handling them.

You can flesh things out by going over each item in your list and checking it off as [you explain it](#fleshexplain). For some items, you'll have to do quite a bit of writing (this is why you listed all sub-functions earlier - so that you don't forget any now).

You may have noticed by now that I'm a huge fan of working to a list. You should list every section's content before you start writing it. If you think of something as you write, add it to the list rather than divert yourself by writing it (or forgetting about it). So, for example, make a list of failure scenarios, and a list of solutions for each one. Then write into that list.

You'll sometimes find that you want to mix things up a bit, like putting failure scenarios with the sub-functions that generate them. This isn't necessarily a bad idea, but it isn't necessarily a good one, either. If you mix things up too much you create something that's hard to follow. Pulp Fiction isn't a good outline for a user's guide.

### Organizing the features for reading

Please think carefully about the order in which you present features. There are two considerations here, and they often conflict:

1. You can't start people off at the most complex features. The basis of Hello World is that we start people at the simple things and then work our way up. 

2. It's instinctive to start people off at the most interesting bits: the most useful features or the features we want to show off the most. 

Sometimes the most interesting features are quite simple and it's a win-win. Sometimes they're very complex and require a lot of knowledge that the reader might not have; by deciding to start off with these you'll create either a very complicated - even exhausting - guide, or one that leaves out most of the information the reader needs.

This is a balancing act, but if you look at programming guides you'll notice that they go for gradual build of complexity rather than being useful right off the bat. This means they're boring as all hell to start with, so many developers shy away from writing that way. But it's a good model to keep in mind when you write.

### Scalability

The nice thing about this method is that it's equally valid for all sizes of text. Sometimes you'll find that the map is enough (you'll just have to put it in reading order and add a short introduction). Sometimes you'll find that it takes pages and pages to explain every single feature. Either way, you follow the same method from start to finish. 

It's also valid for different kinds of text, although it might at times lack elegance. So even if you're explaining a general concept like debugging, security or connectivity, you can think of every concept you're trying to get across as a feature or tool and work from there.

How do you know how detailed your docs should be? Some of it is gut feeling, some of it is common sense (it's a fine line between the two). Either way: write it out, give it to someone, and ask them if they understood and managed to follow it and use the tool. If they didn't, it was either too short or too messy (or both). There is a third option, but then it's your fault for picking that person as your doc's tester, so either way you learned a lesson.

## Explaining things

You can start [here](http://arkinwriting.com/2014/02/21/dont-dumb-it-down-layer-it-up-writing-tips-for-engineers/).

### Connecting the dots

There is one thing I keep seeing in developers’ writing: all the dots, without a single line to connect them. You need to do three things: list your ideas, put them in a readable order, and specify whether they are linked by causation, contrast or continuation. So don’t write “A, B, C, D, E” (and certainly not "E, C, A2, A3, B, A1, D"). Write “A and B, therefore C. Oh, and D, therefore not E”.

There are two easy ways of spotting the dots:

* The Why/So What method: my name for the Inductive Order approach. This is similar to the way Sherlock Holmes speaks: give a conclusion, then the facts proving it, one by one. You do this by asking yourself “what’s the bottom line”, then “why”. Keep asking “why” until you’ve reached the basic concepts we all agree on. Invert that list, and you have a fully structured argument. Then ask “so what” so that you remember to do something with all the information you just gave me - like connect it to the next dot.

* The Need/Meet method: everything is either something you need or a way to meet that need (I’m sorry if I sound like Ayn Rand). If you pair these out, you’ll end up understanding what everything in the story does.

Then there are several ways of organizing the dots:

* Inductive order: you used this earlier to spot dots. Now you can use it to organize them. How handy!

* Increasing difficulty: start at the basics and move on. This works equally well in a single paragraph and in a full-fledged book. The Why/So What method builds this for you per dot, and sometimes even connects dots for you.

* Problem and solution: this matches the need/meet method, which provides a list of problems. You'll just have to put them in a logical order. What "logical" means changes depending on what you're writing.

* Inverted pyramid: the way a newspaper article works. You start with a summary of the whole idea, and then you give out the facts in descending order of importance.

Don’t mix and match ideas, explaining bits and pieces of each in a random order; explain one thing fully, then explain another thing fully, then tie them together. It’s very easy to follow a zigzag pattern when you already know the conclusion, but your reader will have to deconstruct it and put the ideas in order for you.

Last, please remember to clearly link the dots: causation, contrast or continuation.

## Guessing at prior knowledge

How much prior knowledge can you assume when writing? The easiest way to figure it out is to pretend you’re writing a chapter for a book. Where in the book will the chapter come? If it’s the very first chapter, you can’t assume any prior knowledge. If it’s in the middle, everything that would have come before can be assumed to be prior knowledge. 

Of course, guessing how much your readers know is the easy bit (I mean, it's a guess - it's going to be wrong). Sticking to it when you write is much harder. Developers tend not to understand how little an agreed readership actually knows (if they knew this much, they wouldn't be reading), how unintuitive some of the developers' intuitive leaps are, and how dense some of their "simple introductions" are. When writing, it's better to aim lower; readers can skim and skip much more easily than they can fill in the gaps.

## Giving examples

Our basic assumption is that readers should be able to perform the examples themselves, so we should provide a full process, not just a pretty result. From this assumption we reach the following wild conclusions:

* Don't start in the middle or skip steps; if they were obvious, we wouldn't be writing a guide to begin with. For example, it might make sense to you that your command-line tool requires you navigate to the relevant directory, but some users assume tools are global and will have a "work with this directory command". So tell me that you opened the CMD and navigated to a particular directory.

* Tell me how you do everything, not just that you did it. What command did you use? How did you reach it?

* Tell me why you do everything. Why is this the next step? Why did you choose that particular sub-option?

* Tell me about things like long processing times (or I'll think I did something wrong) and questions I'll need to answer (and what each possible answer means).

* Don't dump some new tool on me at step 17. Tell me before you start the example what I'll need installed.

* If you find that you're giving me a lot of background information in one of the steps, it probably means your original explanation omitted too much.

* Don't cover too much material in any example. Show one or two big things, and another couple of small things. Move on to a fresh example to show other things.

* A single step should include only one sequential action, or all simultaneous actions. Do not group sequential actions or separate simultaneous actions.

* Don't forget [the screen caps](http://arkinwriting.com/2014/02/26/screen-cap-tips-for-beginners/).
