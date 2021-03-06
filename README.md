# No Coin
No coin is a tiny browser extension aiming to block coin miners such as Coinhive.

![v0.3 demo](https://ker.af/content/images/2017/09/nocoin-v0.3.gif)

You can grab the extension from: 
* [Chrome Web Store](https://chrome.google.com/webstore/detail/no-coin/gojamcfopckidlocpkbelmpjcgmbgjcl)
* [FireFox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/no-coin/)

### Why?
Even though I think using coin mining in browser to monetize content is a great idea, abusing it is not. Some websites are running it during the entire browsing session which results in high consumption of your computers resources. I do believe that using it occasionally such as for the proof of work of a captcha is OK. But for an entire browsing session, the user should have the choice to opt-in which is the aim of this extension.

### Why not just block the URLs in an adblocker?
The idea was to keep it separate from adblocking. Coin mining in the browser is a different issue. Where ads are tracking you and visually interfering with your browsing experience, coin mining, if abused, is eating your computer ressources resulting in slow downs (from high CPU usage) and excessive power consumption. You might be OK with that and not with ads, or vice versa. Or you might just want to keep ads blocked entirely and just enable the coin mining script for a minute to pass a Captcha. That's why I believe having a separate extension is useful.

### How does it work?
The extension is simply blocking a list of blacklisted domains in *blacklist.txt*. Clicking on the icon will display you a button to pause/unpause No Coin. If you are aware of any scripts or services that provide coin mining the browser, please submit a PR.

## Contribute
Contributions are welcome! Don't hesitate to submit bug fixes, improvements and new features. 

Regarding new features, please have a look at the issues first. If a feature you whish to work on is not listed in here, you might want to add an issue first before starting to work on a PR.


*Made by Rafael Keramidas (keraf [at] protonmail [dot] com - [@iamkeraf](https://www.twitter.com/iamkeraf) - [ker.af](https://ker.af/)). Image used for logo by [Sandro Pereira](https://www.iconfinder.com/icons/33757/coin_question_icon).*
