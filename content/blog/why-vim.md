+++
title = "Why Vim?"
date = 2025-07-27
template = "page.html"
+++

When fellow developers see me using Vim (or, more specifically, [Neovim](https://neovim.io/)), the most common question I get is, "Why?"

<!-- more -->

Why use this antiquated text editor, a notorious pain to learn and use, when you could opt for much more sensible IDEs? They come with great default features out of the box, are easy to learn, and are tried and tested by countless developers, think [VSCode](https://code.visualstudio.com/), [JetBrains](https://www.jetbrains.com/?var=2) products, or lately, [Cursor](https://cursor.com/).

I should preface my answer by saying that there is nothing wrong with these editors. Often, after I explain my choice, the follow-up question is, "So what's wrong with VSCode?" In fact, VSCode is a great choice; it gets the job done, it's fast enough on modern hardware, and it has a rich ecosystem of plugins for almost any need.

To choose Vim over VSCode (or other GUI editors) is a matter of personal preference, but it's a very important choice nevertheless. The text editor is the most important piece of software a developer will use in their lifetime. A full-time developer spends a considerable amount of their waking life interacting with this single piece of software. The idea of not caring about it as long as "it gets the job done" is an answer I find puzzling.

The benefits of Vim come in three parts. The first is the keybindings, which are not exclusive to the Vim editor, as almost all modern text editors support them. The keybindings are developed with the idea that a developer's primary job is not writing text but editing it. The second benefit comes from eliminating the mouse and the GUI. The main advantage here is not just that it makes you faster (although it does), but that it removes the abstractions that a GUI provides, thereby enhancing the developer's knowledge and understanding of any given system. This ties into my third point: Vim lives inside the second most important piece of software in a developer's life, the terminal.

The beauty of Vim keybindings is that they split development into distinct modes: writing (INSERT mode) and editing (NORMAL and VISUAL modes). In a regular text editor, the keyboard is reserved for typing. However, by limiting writing to a single mode, Vim frees the entire keyboard for the main act of programming: editing. The keys that you use to type become actions (d for delete, hjkl for navigation, w for jumping to the next word, etc.). Since you're not restricted to function keys or modifier combos like Ctrl and Shift, the number of actions you can express becomes infinitely larger. In fact, editing becomes its own language. The biggest benefit here is not speed; it's pleasure. The moment you internalize the keybindings and can execute the edit in your mind almost instantly without thinking or reaching for the mouse, returning to the old way of using the keyboard for a single purpose feels painfully frustrating. It might take a week or so of pain to learn Vim motions, but once you're comfortable with them, there's no going back.

Before I explain the second benefit, I'd like to correct the common misconception that Vim cannot have the same feature set as VSCode or other commonly used GUI editors. This is 90% false. I have yet to see a VSCode feature for which I couldn't find a plugin for my Neovim configuration. The only area where Vim concedes to full-fledged IDEs like Visual Studio or JetBrains Rider/IntelliJ is debugger support. The Neovim debugger is the one plugin I have yet to set up properly and I often find myself opening another IDE just to use its debugger. Skill issue, potentially ;).

Though plugins are available for almost every feature VSCode has, setting them up takes significantly more effort for Neovim, and even more so for Vim. As contradictory as it sounds, the extra setup time has benefits. First, it makes you a better programmer, as you gain a deeper grasp of your tools. For students or those new to programming, setting up a Neovim configuration yourself is a much closer experience to actual software development than you'll find in any intro to computer science course. Most of software engineering is about understanding a large piece of software, deciphering unfamiliar APIs, and figuring out how to implement the required change within that ecosystem. This process will teach you more than any number of generic to-do apps, although those are useful for other reasons.

The third benefit comes from the fact that Vim lives in the terminal. The power of the terminal lies in the minimal abstraction between the program and the programmer. Many options can be expressed with a single flag or a few words. It's much easier to extend a terminal-based application than a GUI one, and for that reason, terminal apps often provide a level of control that most GUI apps cannot. For example, GUI apps for Git are very common, but anytime a complex Git action needs to be performed, users often find themselves back in the terminal. The only caveat is that it takes significantly more time to get familiar with a terminal app than a GUI app. Though, similar to my previous reasoning, this is not always a bad thing, as it increases the developer's understanding of any application they're using.

So far, I've mostly compared Vim with VSCode and other traditional GUI editors, but what about Cursor? Surely Vim doesn't provide the benefits of an IDE designed for AI. To that end, I believe the best medium for AI is the one in which Vim operates: the terminal. Since both LLMs and the terminal are fundamentally text-based, many terminal applications are already great tools for an LLM to leverage. Recently, I've been switching between [Warp](https://www.warp.dev/) and [Claude Code](https://www.anthropic.com/claude-code) as my main AI programming aid, and I haven't seen many benefits Cursor offers that I can't get from these terminal-based AI tools, though I admit I have yet to give Cursor a solid try.

If you're interested, here's are a few resources to get started with Vim:

- [No Boilerplate YouTube video on Vim](https://youtu.be/sqm4-B07LsE?feature=shared): Best presentation of the argument for Vim motions I've seen. 

- [VSCode Vim Extenstion](https://github.com/VSCodeVim/Vim): Switching to Vim/NeoVim without getting familiar with the motions might be too much to handle, I think VS Code extension for Vim is a great place to start, that's how I started as well.

- [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim): Simple NeoVim configuration that provides most of the functionality that you'd need from an ide, it's a great starting point. My own config is still 80% based on this.

- [The Primeagen](https://www.youtube.com/@ThePrimeTimeagen): Funny ex-Netflix engineer that talks about Vim sometimes, has great takes usually



