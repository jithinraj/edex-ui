# eDEX-UI

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/93b816722c4e4af2bdf401b8187b8a2d)](https://www.codacy.com/app/GitSquared/edex-ui?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=GitSquared/edex-ui&amp;utm_campaign=Badge_Grade)  [![Greenkeeper badge](https://badges.greenkeeper.io/GitSquared/edex-ui.svg)](https://greenkeeper.io/)   [![Build Status](https://travis-ci.org/GitSquared/edex-ui.svg?branch=master)](https://travis-ci.org/GitSquared/edex-ui)

[![Pre-release demo](https://github.com/GitSquared/edex-ui/raw/master/media/demo-preview.gif)](https://squared.codebrew.fr/edex-demo.mp4)

_(click to view full-size)_


eDEX-UI is a sci-fi interactive terminal interface heavily inspired from [DEX-UI](https://github.com/seenaburns/dex-ui) and the [TRON Legacy movie effects](https://web.archive.org/web/20170511000410/http://jtnimoy.com/blogs/projects/14881671), made cross-platform and easy to install with [Electron](https://github.com/electron/electron).

I had no ideas for a name so i took DEX-UI and added a "e" for Electron. Deal with it.

## FAQ
#### What OS can this thing run on?
Currently Windows and any linux distro that can run Chromium.
#### Is this a real terminal?
Yes. By default, eDEX runs bash on linux and Powershell on Windows, but you can change that to any command in the settings.json file.
#### Why is there a keyboard?
As DEX-UI's author said, it's there mostly because it looks cool, but in eDEX it's also a fully-capable tactile keyboard.
#### What's the difference between this and the original DEX-UI?
Seenaburns' DEX-UI was created _"as an experiment or an art piece, not distributable software"_.
My goal with eDEX is to create a similar experience, but easier to install, run, and use.
#### Will using this make me insanely badass?
[Yes.](https://78.media.tumblr.com/35d4ef4447e0112f776b629bffd99188/tumblr_mk4gf8zvyC1s567uwo1_500.gif)


## How to run it from source?
on *nix systems:
- clone the repository
- `npm run install-linux`
- `npm start`

on windows:
- start cmd or powershell **as administrator**
- clone the repository
- `npm run install-windows`
- `npm start`
