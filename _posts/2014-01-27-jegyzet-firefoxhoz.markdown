---
layout: post
title:  "Jegyzet firefoxhoz"
date:   2014-01-27 16:00:00
categories: 'technikum'
tags: ['firefox', 'sultum']
---

Ezt a postot eredetileg csak magamnak irtam, de kiteszem ide is, hatha valakinek a hasznara valik.

Miota elkurtak az operat, bugrokat hasznalok. Megvannak a maga elonyei es hatranyai, de <em>ahhoz, hogy hasznalhato legyen, szukseg van addonokra.</em> (Majd ha lesz az explorerhez hasznalhato adblocker. akkor. szoljatok.)<br>
Attol fuggoen, hogy akarok-e honapokig kattintgatnti, es finomitani a whitelisteket, vagy csak kenyelmesen bongeszni akarok (ez a ritkabb eset) 2 setupban hasznalom oket: van a full autistic paranoia osszeallitas (lsd tablazat) vagy csak felteszem az adblocker melle a ghostery-t.

<table class="pure-table pure-table-horizontal">
    <thead>
        <tr>
            <th>must have addonok</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td><a href="https://addons.mozilla.org/en-us/firefox/addon/adblock-edge/">Adblock Edge</a><br>
                Gyors, nem megalkuvo (tiltja a google hiredeteseit is) es amint beallitottad, el is felejtheted.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-us/firefox/addon/noscript/">NoScript</a><br>
                A leghatasosabb placebo javascript ellen.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-us/firefox/addon/requestpolicy/">RequestPolicy</a><br>
                Cross-site request whitelister. Ezzel is sok szopas van eleinte.</td>
        </tr>

        <tr>
            <td><a href="https://www.eff.org/https-everywhere">https-Everywhere</a><br>
                Https-re valt, ahol csak tud.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-US/firefox/addon/betterprivacy/">BetterPrivacy</a><br>
                A firefox bezarasa utan torli a flash-cookie-kat.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/En-us/firefox/addon/self-destructing-cookies/">SelfDestructingCookies</a><br>
                Torli a nem whitelistelt cookie-kat.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/En-us/firefox/addon/refcontrol/">RefControl</a><br>
                Elrejti a referrereket. Micsi nem kedveli ezt.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/">Greasemonkey</a><br>
                <a>4chanX</a>-hez es <a>Youtube Center</a>-hez kell.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-US/firefox/addon/textarea-cache/">Textarea Cache</a><br>
                Menti/visszaallitja a beviteli mezok tartalmat.</td>
        </tr>

        <tr>
            <td><a href="https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/">FoxyProxy</a><br>
                Konyvtari es egyetemi halohoz.</td>
        </tr>
    </tbody>
</table>

Ha ezek fent vannak, johet az about:config taknyolas:

<code>geo.enabled => false</code> Geolok kikapcsolasa.

<code>New > string: general.useragent.override => "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:20.0) Gecko/20100101 Firefox/20.0"</code> Useragent csere valami altalanosabbra. 
