+++
title = "Flirting With Obsidian"
date = "2025-08-06T10:33:42+01:00"
tags = ['obsidian', 'writing', 'emacs']
+++

![Image 1](/2025-08-06-flirting-with-obsidian/screenshot-default.png)

## Firstly, I'm still using Emacs
Let me start by stating that Emacs is my main. It's how I interact with my computer for the most part, the client is always running and it's certainly not going anywhere. As much as I like Org mode, I also have a bit of a soft spot for markdown. I just get this occasional temptation to use pure markdown with a very minimal and distraction free writing environment. Yes, I do use *Writeroom mode* in Emacs and have a nice clean setup for writing, and *could* use markdown there, but a program with a sole purpose can be useful for just focusing on the act of writing. My daily notes, tasks, agenda, and pretty much everything else (file manager, terminal, email, calendar, code, git, RSS reader etc.) is in Emacs but that also means there's a lot of distractions available within just a few keystrokes. Sometimes restrictions or limitations can help give you a creative boost. I go through phases of installing and reinstalling Obsidian on my system. I've converted a load of notes from '.org' to '.md' a few times. I usually have a little play around then ultimately end up back in Emacs.

This time, what started as a light flirtation quickly developed into - *"OK.. I'm going to keep my Zettelkasten and blog writing in Obsidian"*. This latest approach is focused around *just writing*. I'm not using daily notes - I find they just clutter up the vault. Not implementing extensive GTD systems or anything related to projects and agendas. I think Org mode and Org Agenda are better tools for that kind of thinking. Org Roam is totally fine by the way for Zettelkasten and note writing but a pain point can be quick mobile access on the go. I'm not really a massive fan of any of the org apps on Android and fully fledged Emacs on mobile is not exactly intuitive. Obsidian is designed in a way that makes keeping a Zettelkasten style vault very simple and easily operated on across devices.

## Folder structure
The vault's name is *'writing'* as that is what it's supposed to encourage. This is my current folder structure and they don't go any deeper than that. I've experimented with having a flat folder structure before but having these note types separated still feels reasonably minimal and does actually feel useful.

Drafts/

Reference/

zArticles/

zAssets/

zk/

All new notes go in to *'Drafts'*. I used to call this *'Fleeting'* and have previously called it *'Inbox'*. It aligns with the Zettelkasten (or [How To Take Smart Notes](https://www.soenkeahrens.de/en/takesmartnotes)) principle of *'Fleeting notes'*. It's the initial capture/dumping ground for everything. My current thinking is that calling it *'Drafts'* might encourage more fleshed out writing for blog posts and articles. 

*'Reference'* could also be called *'Literature notes'* in the [Zettelkasten methodology](https://zettelkasten.de/introduction/) or *'Source'* notes. This is for anything captured from an external source that's not in my own words but useful to keep and refer to. If I started taking notes from a book or a video it would live here. I also keep technical notes and other snippets of gathered knowledge in *'Reference'*. I think of this section like a personal wiki of information.

*'zArticles'* the z prefix is purely to change the order of display in the sidebar. The articles folder is almost an *'outbox'*. This folder is for creating output. If I am writing something for my blog and it's ready to publish it goes in articles. I have previously called it *'Published'*.

*'zAssets'* is just for templates and file attachments.

*'zk'* This is the main Zettelkasten *'slipbox'*. These are short *'atomic notes'* or *'zettels'* in my own words. They are ideas or statements. They should be concise, interlinked and can continue to be developed over time.

![Image 2](/2025-08-06-flirting-with-obsidian/screenshot-sidebars.png)

## Install some nice fonts
Let's get into the visuals. I'm having an interesting issue where Obsidian doesn't seem to be recognising my local fonts on Linux. From a little research, I think it's a bug. I had to use an external plugin called '[Custom Font Loader](https://github.com/pourmand1376/obsidian-custom-font)' to load in the '[IA Writer Quattro](https://ia.net/topics/a-typographic-christmas)' font. One unexpected bonus to this method is that it keeps the font in a folder inside your vault and it'll carry over to the mobile app where installing system fonts is usually more difficult.

## Minimal theme/Style settings and Hider
The [Minimal Theme](https://stephango.com/about) by [Kepano](https://stephango.com/about) alone might feel like enough to get you a simpler UI but there are other plugins like *'Hider'* and *'Style Settings'* which can help you hide many other UI elements. For example, I like to disable the vertical app ribbon, scroll bars, and some other buttons I never use. *'Style settings'* can help you really customise every element and colour within your light and dark theme to get things looking just as you want.

## I don't like the look of properties
I don't like the look of the properties in Obsidian at the top of the file and not into having extensive metadata in my notes. A lot of people rave about *'data view'* and all that kind of stuff but.. nah - I'm not into it. I want a minimal, clean slate every time. I disable *'properties'* and showing back links at the bottom of a note and just use a couple of tags to aid with search.

## Click clack sound effects
The plugin [Click clack](https://github.com/Acylation/obsidian-click-clack) gives you typewriter style sound effects. It's totally unnecessary but I find there's something quite therapeutic about having some sound feedback. This plugin works well and I find it subtle enough to not be too annoying. It's easily toggled on or off.

## Typewriter scroll/Zen mode
This plugin keeps the line you are working on stable and centred like a typewriter would. I combine this with *'Zen mode'* which gives you a distraction free writing experience. You can have text fade out apart from the current line you are working on and other interface elements like tabs and sidebars get right out the way with just a key press.

![Image 3](/2025-08-06-flirting-with-obsidian/screenshot-dark-zen.png)

## Keep the Rhythm 
[Keep the Rhythm](https://github.com/benjaminezequiel/keep-the-rhythm) displays a GitHub style writing habit tracker in your sidebar. There are useful little widgets for daily, weekly word count etc. You can set a word count goal per day and also see how many words you've added to certain files.

## Reading time 
If you are writing content or blog posts you may find it handy to have this little status bar indicator. It displays alongside the word count at the bottom and gives a rough estimate for how long a file will take to read e.g *'2 min read'*.

## Emacs key binds
This is a personal one.. it doesn't work perfectly and you will probably have to rethink a few of your existing key binds to fully implement this. I just need *some* Emacs like bindings for consistency when editing and navigating text. I don't even use all of them, just a few binds like copy/yank with 'C-w', 'C-y' etc. can help to reduce the friction when switching applications.

## Other community plugins
I'm staying reasonably light on other community plugins for now, but do have; *'Templater'*, *'Tag Wrangler'*, *'Settings Search'* and *'Emoji short codes'* installed. 🙂 👍

![Image 4](/2025-08-06-flirting-with-obsidian/screenshot-graph-dark.png)

## Closing thoughts 
Whether I'm working on my markdown files in Obsidian, Emacs or any other editor it's the content of the text that matters most. I made the vault in Obsidian but you can easily just open the directory or one of your markdown files in your default editor and do some more extensive editing there.

As a visual person, I like and use Obsidian's graph view a lot. I find it really helpful for making links between ideas and identifying areas of interest. [Org Roam UI](https://github.com/org-roam/org-roam-ui) provides a *similar* graph with Emacs but that's something you have to display in a separate browser window and on desktop only. Obsidian's is a bit more slick and easily accessed. 

Being able to switch light to dark theme with just a key bind or based on your system settings is also really nice. This would be much more complicated process in Emacs for me as I have loads of custom faces set on top of my light theme.

To conclude, I'm not exclusive to any one application. I think the basics of my system would be the same whichever program I use. The most important note taking concepts can also be implemented just with pen and paper. I find that sometimes the things you learn in one tool can be brought across to another. I see this latest experiment with Obsidian more like using a different kind of pen or notebook for a bit. If it gets you writing more, revisiting notes and progressively making them more useful it's got to be a positive right?


---

*Leave a comment by [email](mailto:bledley@posteo.com) or you can find me on the [Fediverse](https://mastodon.social/@bledley)*
