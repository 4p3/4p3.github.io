---
layout: post
title:  "How to viking books through irc"
date:   2014-08-21 21:45:11
categories: 'howto'
tags: ['book','pirate','irc']
---

My buddies used to joke about how some music album/movie/game is so bad that instead of pirating, it deserves to be vikinged, meaning that we should raid the house of the authors, loot everything valuable (compensation for wasting our time) rape their wives (compensation for the lack of fun) and kill their children (proactive measurement for the future generations).

My opinion is that <mark>very few products (from the entertainment industry) deserve the benefit of the doubt</mark>. Considering the educating nature of books and the fact that public libraries exist, I don't think that downloading an e-book is something that should be prosecuted. Anyway I didn't wanted to rant about ethics.

In your favorite <a href="https://en.wikipedia.org/wiki/IRC_client">IRC client</a>:

<code>
	/server eu.undernet.org:6667<br>
	/join #bookz<br>
	/msg #bookz @search (author) (book title)<br>
</code>

For example if you wanted the 2014 Hugo award winner Ancillary Justice by Ann Leckie:

<code>
	<b>(viking23)</b> @search Ancillary Justice Ann Leckie<br>
	<b>(bot)</b> I have found 1 file(s) for your query: Ancillary Justice Ann Leckie. Displaying 1:<br>
	<b>(bot)</b> !bot Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar ::INFO:: 866.44 KiB<br>
	<b>(viking23)</b>  !bot Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar<br>
	<b>(bot)</b> I have added Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar as 3 in my queue. This is file 1 of 75 allowed in your queue. The send will be initiated as soon as possible.<br>
	<b>(bot)</b> After waiting 0 min(s), Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar is on the way.<br>
</code>

And that's it, the bot sends you the book through dcc.