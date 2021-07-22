# ![nuclear](https://i.imgur.com/oT1006i.png) 
[![Maintainability](https://api.codeclimate.com/v1/badges/a15c4888a63c900f6cc1/maintainability)](https://codeclimate.com/github/nukeop/nuclear/maintainability) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/30750586202742279fa8958a12e519ed)](https://www.codacy.com/app/nukeop/nuclear?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nukeop/nuclear&amp;utm_campaign=Badge_Grade) [![nuclear](https://snapcraft.io//nuclear/badge.svg)](https://snapcraft.io/nuclear) [![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/JqPjKxE)

A music player for computers with free streaming.

![Showcase](https://i.imgur.com/8qHu66J.png)

# Links

[Official website](https://nuclear.js.org)

[Downloads](https://github.com/nukeop/nuclear/releases)

[Documentation](https://nukeop.gitbook.io/nuclear/)

[Mastodon](https://mstdn.io/@nuclear)

[Twitter](https://twitter.com/nuclear_player)

Support channel (Matrix): `#nuclear:matrix.org`

Discord chat: https://discord.gg/JqPjKxE

Readme translations: 

<kbd>[<img title="Deutsch" alt="Deutsch" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/de.svg" width="22">](docs/README-de.md)</kbd>
<kbd>[<img title="Português" alt="Português" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/br.svg" width="22">](docs/README-ptbr.md)</kbd>
<kbd>[<img title="Svenska" alt="Svenska" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/se.svg" width="22">](docs/README-se.md)</kbd>
<kbd>[<img title="English" alt="English" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/us.svg" width="22">](README.md)</kbd>
<kbd>[<img title="Hebrew" alt="Hebrew" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/il.svg" width="22">](docs/README-he.md)</kbd>
<kbd>[<img title="Italiano" alt="Italiano" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/it.svg" width="22">](docs/README-it.md)</kbd>
<kbd>[<img title="Türkçe" alt="Türkçe" src="https://cdn.staticaly.com/gh/hjnilsson/country-flags/master/svg/tr.svg" width="22">](docs/README-tr.md)</kbd>

## What exactly is nuclear?
nuclear is a free streaming service that takes its content from free sources on the Internet.

If [mps-youtube](https://github.com/mps-youtube/mps-youtube) sounds familiar to you, you can roughly imagine that nuclear is similar to this, but with the advantage that it has a graphical interface.
It can be said that it is like Spotify, but with a larger, and most importantly, free music library.

## What if I don't particularly like Electron?
See [this](docs/electron.md).

## Properties of nuclear

- Search and playback of music from YouTube (including integration of playlists and [SponsorBlock](https://sponsor.ajay.app/)), Jamendo, Audius and SoundCloud)
- Search for albums (supported by Last.fm and Discogs), album view, automatic song search based on artist and song name (in progress, can be a bit bumpy)
- Music queue that can be exported as a playlist if required
- Calling up saved playlists (saved as json file (s))
- Support of Last.fm scrobbling (including updating the 'playing now' status)
- Latest releases with reviews - songs and albums
- Search for Art
- Radio mode (automatic queuing of similar songs)
- Unlimited downloads (supported by Youtube)
- Playback of lyrics in real time
- Preview of current favorites
- List of favorite songs
- Play your own local library
- No accounts
- No ads
- No CoC (Code of Conduct)
- No CLA (Contributor Agreement)

## Development process

First of all, be sure to check out the [Contribution Guidelines](https://nukeop.gitbook.io/nuclear/contributing/contribution-guidelines).

The instructions for running Nuclear in development mode can be found in the [Development Process](https://nukeop.gitbook.io/nuclear/developer-resources/development-process) document.

## Community-maintained packages

Here is a list of third party packages for most operating systems. Most of them are maintained by the publishers. Thank you very much for providing these packages.

| Package type   | Link                                                               | Maintainer                                   | Installation Method                           |
|:--------------:|:------------------------------------------------------------------:|:--------------------------------------------:|:---------------------------------------------:|
| AUR (Arch)     | https://aur.archlinux.org/packages/nuclear-player-bin/             | [nukeop](https://github.com/nukeop)          | yay -s nuclear-player-bin                     |
| AUR (Arch)     | https://aur.archlinux.org/packages/nuclear-player-git              | [nukeop](https://github.com/nukeop)          | yay -s nuclear-player-git                     |
| Choco (Win)    | https://chocolatey.org/packages/nuclear/                           | [JourneyOver](https://github.com/JourneyOver)| choco install nuclear                         |
| GURU (Gentoo)  | https://github.com/gentoo/guru/tree/master/media-sound/nuclear-bin | [scardracs](https://github.com/scardracs)    | emerge nuclear-bin                            |
| Homebrew (Mac) | https://formulae.brew.sh/cask/nuclear                              | Homebrew                                     | brew install --cask nuclear                   |
| Snap           | https://snapcraft.io/nuclear                                       | [nukeop](https://github.com/nukeop)          | sudo snap install nuclear                     |
| Flatpak        | https://flathub.org/apps/details/org.js.nuclear.Nuclear            | [nukeop](https://github.com/nukeop)          | flatpak install flathub org.js.nuclear.Nuclear|


## Community translations
Nuclear has already been translated into many languages, but we are still looking for new contributors who want to add new languages or improve the quality of the content or something similar. Here is a list of currently available languages and their translators.

| Language             | Contributor                                                                                                 |
|:--------------------:|:-----------------------------------------------------------------------------------------------------------:|
| English              | N/A                                                                                                         |
| French               | [charjac](https://github.com/charjac), [Zalax](https://github.com/Zalaxx)                                   |
| Dutch                | [Vistaus](https://github.com/Vistaus)                                                                       |
| Danish               | [Hansen1992](https://github.com/Hansen1992)                                                                 |
| Spanish              | [mlucas94](https://github.com/mlucas94), [emlautarom1](https://github.com/emlautarom1)                      |
| Polish               | [kazimierczak-robert](https://github.com/kazimierczak-robert), [gradzka](https://github.com/gradzka)        |
| German               | [nuclear](https://github.com/nuclear), [schippas](https://github.com/schippas)                              |
| Russian              | [ramstore07](https://github.com/ramstore07), [dmtrshat](https://github.com/dmtrshat)                        |
| Brazilian Portuguese | [JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)                                                       |
| Turkish              | [3DShark](https://github.com/3DShark)                                                                       |
| Italian              | [gello94](https://github.com/gello94), [scardracs](https://github.com/scardracs)                            |
| Slovak               | [MartinT](https://github.com/MartinTuroci)                                                                  |
| Czech                | [PetrTodorov](https://github.com/PetrTodorov)                                                               |
| Tagalog              | [giftofgrub](https://github.com/giftofgrub)                                                                 |
| Traditional Chinese  | [oxygen-TW](https://github.com/oxygen-TW)                                                                   |
| Swedish              | [PalleKarlsson](https://github.com/PalleKarlsson), [nonew-star](https://github.com/nonew-star)                                                           |
| Greek                | [Shuin-San](https://github.com/Shuin-San)                                                                   |
| Vietnamese           | [HaiDang666](https://github.com/HaiDang666)                                                                 |
| Finnish              | [cjola002-xamk](https://github.com/cjola002-xamk)                                                           |
| Korean               | [dexterastin](https://github.com/dexterastin), [teamzamong](https://github.com/teamzamong/)                 |

## Screenshots
This will be updated as the program evolves.

![Album Search](https://i.imgur.com/idFVnAF.png)

![Album Display](https://i.imgur.com/Kvzo3q7.png)

![Artist View](https://i.imgur.com/imBLYl3.png)

![Dashboard Best New Music](https://i.imgur.com/bMDrR4M.png)

![Dashboard Genres](https://i.imgur.com/g0aCmKx.png)

![Playlist View](https://i.imgur.com/2VMXHDC.png)

![Lyrics View](https://i.imgur.com/7e3DJKJ.png)

![Equalizer View](https://i.imgur.com/WreRL0w.png)

## License

This program is under the "Free Software" license, which means that not only can the software be used and distributed free of charge, but the author is also obliged to disclose the source code. The licensee may then not only view this source code, but also change it and redistribute the changed source code and the software resulting from it.
