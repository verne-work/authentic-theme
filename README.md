## Contents
* [Changelog](https://github.com/webmin/authentic-theme/blob/master/CHANGELOG.md)
* [Download![](https://authentic-theme.com/media/icons/download-23x14.png)](https://github.com/webmin/authentic-theme/releases)
* [About](#about)
* [FAQ](#faq)
* [Development](#development)
* [Donate![](https://authentic-theme.com/media/icons/heart-23x15.png)](https://github.com/webmin/authentic-theme#donate)
* [License](#license)

## About
**Authentic Theme** is modern, ultrafast single-page application for [Webmin/](https://github.com/webmin/webmin)[Usermin](https://github.com/webmin/usermin) that is made with _love_. Managing servers, operating systems and applications has never been so easy.

[![Quick UI overview 2021](https://user-images.githubusercontent.com/4426533/114315375-61a1c480-9b07-11eb-9aaf-4aa949a39ab7.png)](https://www.youtube.com/watch?v=daYG6O4AsEw&feature=emb_logo)
![](https://user-images.githubusercontent.com/4426533/114394315-bc88f980-9ba3-11eb-8025-ccac774ea460.png)

### Features
* Configurable theme options using _Webmin_/_Usermin_ UI, with ability to embed user logos and custom styles
* Code highlight when viewing and editing files
* Drop-down terminal interface for _Command Shell_ module
* Hotkeys and favorites for quicker access
* Notification slider for instant access to pushed system messages
* Extended support for _File Manager_ and _ConfigServer Security & Firewall_ modules

### Requirements
* Webmin _1.995+_ (required), Usermin _1.855+_ (optional), Virtualmin _7.0+_ (optional), Cloudmin _9.6+_ (optional)

### Recommended modules
* Installed _Net::SSLeay_ module, to make automatic update notifications work

## FAQ

### How to update _Authentic_ Theme manually?
Go to theme configuration and hit _Force update theme_ button to install either _stable_ or _development_ version of the theme.

### How to update _Authentic_ Theme automatically?
The theme has built-in feature to notify administrative users to install updates. To enable this feature, turn on _Check for Authentic Theme updates_ in theme configuration.

### How to show beta updates notifications for the theme?
Go to theme configuration folder under Webmin, create/find _config_ file, open it and add/change the value from _0_ to _1_ for _beta_updates_ option.

### How do I customize the theme?
Theme has configurable options. There, as well, you can upload custom _logos_ and code custom _styles.css_, _scripts.js_ and _scripts.pl_.

### How do I execute shell command using search field?
Type `!` in search, followed by your command. Example: `!ls /root`. It's required to have _Command Shell_ module available.


## Extended support for bundled/third-party modules

### _File Manager_
Theme has great support for this module, by adding numerous must-have features, which enables you to use _File Manager_ just as normal desktop browser.

### _ConfigServer Security & Firewall_
Theme only re-renders this module and adds support for code highlight, when editing files manually.

## Development
### Lead developer
* [Ilia Rostovtsev](https://authentic-theme.com)  [![](https://authentic-theme.com/media/icons/stackoverflow-18x17.jpg)](https://stackoverflow.com/users/1455661/ilia)

### Contributions

#### Code
* [Jamie Cameron](https://github.com/jcameron)
* [Joe Cooper](https://github.com/swelljoe)

#### Translations
* [Pierre Wozniak](https://github.com/pwozniak89) (French)
* [Maicol Battistini](https://github.com/maicol07) (Italian)
* [Richard van Laak](https://github.com/Rvanlaak) (Dutch)
* [Michał Pawlik](https://github.com/majk-p) (Polish)
* [Kay Marquardt](https://github.com/gnadelwartz), [Michael Keck](https://github.com/mkkeck) (German)
* [Silviu-Ionut Radu](https://github.com/sealview) (Romanian)
* [David Canalias](https://github.com/diathesaron) (Catalan)
* [Sopor](https://github.com/Sopor-) (Swedish)
* [7stars](https://github.com/7starsone) (Spanish, French, Portuguese)
* [miyorineko](https://github.com/miyorineko), [dreista](https://github.com/Dreista) (Chinese)
* [jlndk](https://github.com/jlndk) (Danish)
* [stuchy3](https://github.com/stuchy3) (Czech)
* [Samsul Ma'arif](https://github.com/samsulmaarif) (Indonesian)
* [Adalen Vladi](https://github.com/adalenv) (Albanian)
* Stein-Aksel Basma, [Kjetil Elde](https://github.com/w00p) (Norwegian)
* [Kosugikun](https://github.com/kosugikun) (Japanese)

## Donate
 It takes countless hours to develop and maintain this project. Donations show appreciation. Your donation would help me to pay my bills and _excite future development_.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&lc=us&business=pay%40ilia%2eengineer&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest">![](http://authentic-theme.com/media/icons/paypal-175x45.png)</a>

![](https://authentic-theme.com/media/icons/bitcoin-175-207.png)
<br>
*bc1q5jk7wf6urdj4w9hm9de52xvf8strzc0unyt3cu*

![](https://authentic-theme.com/media/icons/ethereum-175-42.png)
<br>
*0x598d0549aF24aD80e5b868297D44C479Cc2Dab6F*

![](https://authentic-theme.com/media/icons/litecoin-175-42.png)
<br>
*ltc1qdc5x5ucah9u6x6rl9ttw29wcejtt0h62rx2t2z*

## License

**Authentic Theme** is released under the [MIT License](https://github.com/webmin/authentic-theme/blob/master/LICENSE).
