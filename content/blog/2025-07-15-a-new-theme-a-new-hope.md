+++
title = "A new theme, a new hope"
date = "2025-07-15T11:34:54+01:00"
tags = ['hugo', 'git', 'netlify', 'bear']
+++

*"Git submodules? hmmm, sure ok, we'll figure it out.."*
 
*[Proceeds to break website and spend the rest of the day trying to get it back to some kind of working order]*
 
I've changed up my blog theme but woah..holy shit.. it's taken some hours. When building [Hugo](https://gohugo.io/) sites the suggested method to install themes is often to use Git submodules.. yeah?.. no?.. no idea. Git stuff stresses me out, I usually stumble through these kind of things following some online documentation. 
 
The idea was that I wanted to really strip down my website to look a lot more like these minimalist Bear blogs that I've been reading a lot of recently.
 
 Why not just use [Bear](https://bearblog.dev/) itself?.. well I did consider it. My main issue there is that you have to write posts in the browser window. For extra features you'll end up wanting, it becomes a paid subscription service. I like to have the control and to be able to customize every aspect of the site. I want to use my own offline editor to modify the code and write posts in my own writing environment. 
 
Thankfully there is a very nice implementation of the Bear theme by [janrassch](https://github.com/janraasch/hugo-bearblog). I followed instructions to get this set up for Hugo. I copied my pre-existing posts and images across and everything was seemingly up and running nicely.. for a short while at least.

I'm not even sure what happened honestly, but at some point I messed things up badly pushing stuff with git. Skill issue I'm sure, but I got to a point where the site wouldn't build and deploy through [Netlify](https://www.netlify.com/) and I had no idea how to fix it. It was something to do with tinkering on stuff in the submodule which I now had no idea how to remove.

I used this breakage as an opportunity to generate a fresh directory and Hugo site/Git repo. Turns out this was a good idea. My previous theme was somewhat out of date and would throw errors when you started the server on localhost. 

It wasn't too difficult to get something fresh up and running, push the repo, connect to Netlify and then link to my custom domain name. A lot of the settings were already in there from the previous build. I opted *not* to use the submodule approach this time and just straight clone the theme. I will have to keep track of any major changes but it's given me a good base to work on.

One nice perk to using this theme is that you should see it in light mode/dark mode depending on your system/browser settings. There's definitely some things to do that I'm chipping away at. I still don't know how these posts are going to appear in an RSS reader? I want it to show the full posts rather than summaries, pushing this will test that out. I'd like to use a custom font and I will be reviewing some past posts and cleaning up a bit. This feels like a fresh start. I'd like to do more off the top of the head writing, try to keep things reasonably short form and regular.


---

*Leave a comment by [email](mailto:bledley@posteo.com) or you can find me on the [Fediverse](https://mastodon.social/@bledley)*
