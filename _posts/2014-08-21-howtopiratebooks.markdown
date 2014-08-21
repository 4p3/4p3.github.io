---
layout: post
title:  "How to viking books through irc"
date:   2014-08-21 21:45:11
categories: 'howto'
tags: ['book','pirate','irc']
---

My buddies used to joke about how some music album/movie/game is so bad that instead of pirating it deserves to vikinged, meaning that we should raid the house of the authors, loot everything valuable (compensation for wasting our time) rape their wives (compensation for the lack of fun) and kill their children (proactive measurement for the future generations).

My opinion is that very few products (from the entertainment industry) deserves the benefit of the doubt. Considering the educating nature of books and the fact that public libraries exist, I don't think that downloading an e-book is something that should be prosecuted. Anyway I didn't wanted to rant about ethics.

In your favorite IRC client:

<code>
	/server eu.undernet.org:6667
	/join #bookz
	/msg #bookz @search (author) (book title)
</code>

For example if you wanted the 2014 Hugo award winner Ancillary Justice by Ann Leckie:

<code>
	<viking23> @search Ancillary Justice Ann Leckie
	<bot> I have found 1 file(s) for your query: Ancillary Justice Ann Leckie. Displaying 1:
	<bot> !fojteach Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar ::INFO:: 866.44 KiB
	<viking23>  !fojteach Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar
	<bot> I have added Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar as 3 in my queue. This is file 1 of 75 allowed in your queue. The send will be initiated as soon as possible.
	<bot> After waiting 0 min(s), Ann Leckie - [Imperial Radch 01] - Ancillary Justice.rar is on the way.
</code>

And that's it, the bot sends you the book through dcc.