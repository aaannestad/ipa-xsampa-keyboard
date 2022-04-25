# ipa-xsampa-keyboard

This is an IPA keyboard I built for myself back in 2013 using MSKLC, where the conventions for inputting complex characters are based on X-SAMPA rather than being a dé nóvó set of conventions like many other IPA keyboards use. This means two things:

- If you have some familiarity with X-SAMPA (as I did at the time), you can translate that knowledge directly into using this keyboard
- If you can't remember or don't know the X-SAMPA representation of an IPA letter, you can look it up on Wikipedia rather than having to hunt down your keyboard's documentation

Additionally, X-SAMPA's conversion conventions are relatively straightforward and IMO easier to remember than what I've seen of other keyboard layouts' conventions, so I suspect this keyboard might be easier to learn even if you don't know X-SAMPA.

The key differences between X-SAMPA and this keyboard's input conventions are the following:

- X-SAMPA's postposed modifier symbols (e.g. the <\\> in <p\\>; X-SAMPA's representation of IPA <ɸ>) are converted into *pre*posed dead keys (so <ɸ> is typed as <\\> + \<p> in that order)
- X-SAMPA's underscore for diacritics (e.g. <u_0> for IPA <u̥>) is converted into a dash, to save on input keystrokes (so <u̥> is input as \<u> + <-> + <0>)
- Cases where X-SAMPA uses two modifier symbols (e.g. <r\\\`> for <ɻ>) use <|> (the pipe) as their dead key (so <ɻ> is typed as <|> + \<r>).

There are a few cases where this keyboard and X-SAMPA differ; full documentation can be found in the spreadsheet included in the top-level directory. Most of these are cases where either X-SAMPA has no code at all for an IPA symbol (e.g. this keyboard has <-> + \<g> for <ʱ>), or X-SAMPA uses two modifier symbols when one is unambiguous (e.g. <J\\<> for <ʄ>, where this keyboard just uses <<> + \<J>). If a key combination doesn't do what you expect, poking around and trying similar options may be faster than actually looking in the documentation.

Currently this keyboard is only available in a Windows option. To install it, download the latest release, unzip it, and run `setup.exe`. The keyboard language is set to English, so you'll need to add it as an English-language keyboard option.
