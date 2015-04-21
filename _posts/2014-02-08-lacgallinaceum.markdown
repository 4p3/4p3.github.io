---
layout: post
title:  "Lac gallinaceum"
date:   2014-02-08 22:45:00
categories: 'technikum'
tags: ['blog', 'sultum', 'ego']
---

Nem mintha fontos, vagy erdekes tema lenne, de igy sabbath este ehhez van kedvem: par szo az oldalrol.

Amikor ugy dontottem, hogy utat engedek <del>narcisztikus egomnak</del> annak a tompa, nyomo erzesnek a nyakszirtemen, amely jelzi szamomra, hogy blogot kell irni, csak egy dolgot tudtam: nem lesz benne javascrip, php, *sql. Nem azert, mert ezeket tartom a modern webfejlesztes megrontoinak (de) vagy aggodnek a skalazhatosag miatt - egyszeruen elegansabb egy ilyen kis <del>szar</del> blogot html-ben vezetni.

Viszont egyre duzzado file-okat egy leiro nyelvben szerekesztgetni igen kevesse kivanatos, sot hosszu tavon erzelmileg majdnem olyan terhelo, mint naponta gentoot telepiteni. Kellett valami, ami okosan legeneralja az oldalakat, valami, ami fut a lehetseges operacios rendszerek legjobbiakan (windows), elbir vele egy gyenge laptop es gyorsan testreszabhato. A <a href="https://duckduckgo.com/">ddg</a> szerint ilyen a <a href="http://jekyllrb.com/">jekyll</a>.

Eloneye, hogy van hozza egy kupac plugin, nincs rakfene <a href="http://hup.hu/node/70236#comment-760064">licence</a> es <a href="http://purecss.io/">PURE</a>-val is viszonylag konnyen ossze lehet hozni.
Mivel a domain melle kapott tarhely nem csak keves, de keves es keves, ezert a blogot a <a href="http://pages.github.com/">github</a> hostolja. Egesz kenyelmes. 

<code>
	jekyll build

	cd _site\
	
	git add -A
	git commit -m "uj post. fascinatign"
	git push
</code>
