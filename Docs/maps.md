# Document maps - writing v reading

Here is an important distinction: where you start writing and where the user starts reading are not the same place. The user will start at the beginning. You will not. This means you'll need to know:

1. [What you're going to write](#the-writing-map).

2. [How to organize it for the reader](#the-reading-map).

We'll create a map or list for each document (or section in a long document) before we start working. If we just improvise as we go along we'll get lost, forget things, double-up and generally take three times as long as we need to.

## The writing map

Before you start writing you should know what you'll need to cover. So make a map:

1. You start at the most important point. It's like marking the X, then drawing the treasure map around it. With software, this will normally be all available features and their options, for example all of the options of a command-line tool.

1. List what you need to install your tool - including all dependencies. 

1. Think of all the technical background required to understand steps 1 and 2.

1. Steps 1 to 3 have mapped out all of the technical ground you need to cover. Start [fleshing it out bit by bit](fleshing_out.md).

1. Think of some [examples](fleshing_out.md#giving-examples) showing how to use your tool and some of its best features.

1. If there's [additional material](writing_tips.md#additional-material) you want, like FAQs and a problem solving section, now's the time to outline them. 

1. Write a summary. This should tell me what I've accomplished by following your instructions, and what other resources are available if I want to learn more.

1. Finally, write [an introduction](writing_tips.md#writing-an-introduction). This should explain what your tool does and why I should bother using it. If you're writing for a new version of the tool, you'll address version differences either in the introduction or in the [section after the introduction](writing_tips.md#version-differences).

## The reading map

When you're done writing, please don't forget to put the text in reading order. For example, it makes very little sense to give a full explanation of all commands before bothering to explain what the general purpose of the tool is. 

The standard structure is:

1. The introduction. 

1. The version highlights, if you wrote them outside of the introduction. 

1. The installation instructions (start with a list of dependencies). 

1. How to use the tool, feature by feature, with the technical background each one requires. Please think carefully about the order of features. Start with the most basic, in the order in which people are most likely to use them. For example, if you've created a painting program, teach me how to paint before teaching me how to print.

1. Examples can be stand-alone, or you can mix them in with the previous step by giving an example for each feature.

1. Summary.

1. Additional materials.