<h1 align="center">Nepali Adblock Rules</h1>

<p align="center">Advertisement blocking rules for Nepali webpages.</p>

**Do not hesitate to contribute.** Even if you don't know how to write rules yourself, please do report certain ads in issues and get it removed.

<h2>Usage</h2>

Add `rules.txt` to your client by adding the following url:

```
https://github.com/justfoolingaround/adblock-rules-np/raw/master/rules.txt
```

These rules are supported over many adblockers. If you haven't installed one already, the most loved one is [uBlock Origin](https://ublockorigin.com/) (uBlock Origin works best in Firefox). 


<h2>Similar projects</h2>

Adblocking only grows stronger as the rules grow. Elitism is useless. More is good.

- [sndsabin/swaccha-adblock-filter](https://github.com/sndsabin/swaccha-adblock-filter)
- [canmando/adblock-nepal](https://github.com/canmando/adblock-nepal)

<h2>Contributing</h2>

If you need help, **ask.** If you see problems, point it out!

- Make sure your rules are as **aggressive** as possible.
    - `div#advertisement` is too specific and is consequently passive, use `#advertisement`.
- Avoid using *specific* urls unless the content cannot be blocked otherwise.
    - `a[href="https://www.jkl.com/abc/xyz.png"]` may be covered by a parent element like maybe `div[title^="Advertisement for"]`.
- If you add a section for a new site, please do mention if your rules apply to **all** of the advertisements on the site.

Creating these rules also increases your experience in `CSS-selectors`, `extended CSS-selectors`, `regular expressions`, `wildcards` and general pattern matching utilities.

<h2>Resources</h2>

Please take references from [this cheatsheet](https://adguard.com/kb/general/ad-filtering/create-own-filters/). It may seem long and tedious but it *is* elaborate.

You'll notice that there are extremely complicated, advanced and powerful adblocking rules in these cheatsheet. Please do keep in mind that you're free to use all of these mechanisms, no explanations needed so long as it keeps up with the contribution rules.
