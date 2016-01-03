![Rocket.Chat logo](https://rocket.chat/images/logo/logo-dark.svg?v3)

The Ultimate Open Source WebChat Platform

* [Live Demo](#live-demo)
* [Mobile apps](#mobile-apps)
* [Desktop apps](#desktop-apps)
* [Deployment](#deployment)
  * [Heroku](#heroku)
  * [Scalingo](#scalingo)
  * [Sandstorm.io](#sandstormio)
  * [Sloppy.io](#sloppyio)
  * [Docker](#docker)
  * [FreeBSD](#freebsd)
  * [Ansible](#ansible)
  * [Ubuntu VPS](#ubuntu-vps)
  * [Ubuntu Software Center](#ubuntu-software-center)
* [About Rocket.Chat](#about-rocketchat)
  * [On the News](#on-the-news)
  * [Features](#features)
  * [Roadmap](#roadmap)
  * [Issues](#issues)
  * [Integrations](#integrations)
  * [Documentation](#documentation)
  * [License](#license)
* [Development](#development)
 * [Installation](#installation)
  * [Branching Model](#branching-model)
  * [Translations](#translations)
  * [Community](#community)
  * [How to Contribute](#how-to-contribute)
* [Credits](#credits)
* [Donate](#donate)


# Live Demo
Checkout the latest version at [https://demo.rocket.chat](https://demo.rocket.chat)


# Desktop Apps
Download the Native Cross-Platform Desktop Application at [Rocket.Chat.Electron](https://github.com/RocketChat/Rocket.Chat.Electron/releases)


# Mobile Apps
### Available from the AppStore
[![Rocket.Chat on Apple AppStore](http://linkmaker.itunes.apple.com/images/badges/en-us/badge_appstore-lrg.svg)](https://itunes.apple.com/us/app/rocket.chat/id1028869439?mt=8)

### Available from the Google Play
[![Rocket.Chat on Google Play](https://developer.android.com/images/brand/en_app_rgb_wo_45.png)](https://play.google.com/store/apps/details?id=com.konecty.rocket.chat)

Now compatible with all Android devices as old as version 4.0.x - [download here](https://github.com/RocketChat/Rocket.Chat/wiki/Build-the-Android-Cordova-Web-App-and-connect-to-your-own-Rocket.Chat-Server), even on BlackBerry Passport!

### Also available as FirefoxOS app
[![Firefox OS app now available](https://raw.githubusercontent.com/Sing-Li/bbug/master/images/firefoxos.png)](https://github.com/RocketChat/Rocket.Chat/wiki/Native-Firefox-OS-app-%28hosted-webapp%29)


# Deployment
`Host your own Rocket.Chat server in four seconds flat`


## Heroku
Host your own Rocket.Chat server for **FREE** with [One-Click Deploy](https://heroku.com/deploy?template=https://github.com/RocketChat/Rocket.Chat/tree/master)

Branch **master** (Latest stable version):

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/RocketChat/Rocket.Chat/tree/master)

Branch **develop** (Newer but unstable):

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/RocketChat/Rocket.Chat/tree/develop)

## Scalingo
Deploy your own Rocket.Chat server instantly on [Scalingo](https://scalingo.com)

Branch **master** (Latest stable version):

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy?source=https://github.com/pavelsuba/Rocket.Chat#master)

Branch **develop** (Newer but unstable):

[![Deploy on Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy?source=https://github.com/pavelsuba/Rocket.Chat#develop)





# About Rocket.Chat


## Features

- BYOS (bring your own server)
- Multiple Rooms
- Direct Messages
- Private Groups
- Public Channels
- Desktop Notifications
- Mentions
- Avatars
- Markdown
- Emojis
- Media Embeds
- Link Previews
- Sent Message Edit and Deletion
- Transcripts / History
- File Upload / Sharing
- Full text search
- Live chat / Messaging call center
- LDAP Authentication
- Support for Okta SSO through SAML v2
- I18n - Supports 22 Languages
- Hubot Friendly
- Face to Face Video Conferencing (aka WebRTC)
- Multi-users Video Group Chat
- Audio calls
- Multi-users Audio Conference
- Screensharing
- REST APIs
- Remote Locations Video Monitoring
- Chat-ops powered by Hubot: scalable horizontal app integration (early access)
- Massively scalable hosting and provisioning (beta testing now)
- Native Cross-Platform Desktop Application [Windows, Mac OSX, or Linux](https://rocket.chat/)
- Mobile app for iPhone, iPad, and iPod touch [Download on AppStore!](https://geo.itunes.apple.com/us/app/rocket.chat/id1028869439?mt=8)
- Mobile app for Android phone, tablet, and TV stick [Available now on Google Play!](https://play.google.com/store/apps/details?id=com.konecty.rocket.chat)
- Native Firefox OS Application (also for Desktop Firefox and Firefox for Android!) - [Check the wiki page for install instructions](https://github.com/RocketChat/Rocket.Chat/wiki/Native-Firefox-OS-app-%28hosted-webapp%29)
- Sandstorm.io instant Rocket.Chat server [Now on Sandstorm App Store](https://apps.sandstorm.io/app/vfnwptfn02ty21w715snyyczw0nqxkv3jvawcah10c6z7hj1hnu0)


## Roadmap

#### In Progress
- Support multiple teams on the same instance / same VPS infrastructure: [Issue #658](https://github.com/RocketChat/Rocket.Chat/issues/658), [Issue #630](https://github.com/RocketChat/Rocket.Chat/issues/630)
- Support for PostgreSQL: [Issue #533](https://github.com/RocketChat/Rocket.Chat/issues/533), [Issue #822](https://github.com/RocketChat/Rocket.Chat/pull/822)
- Native iOS Application [Issue #270](https://github.com/RocketChat/Rocket.Chat/issues/270), [Rocket.Chat.iOS - HELP WANTED](https://github.com/RocketChat/Rocket.Chat.iOS)
- Native Android Application [Issue #271 - HELP WANTED](https://github.com/RocketChat/Rocket.Chat/issues/271)
- Off-the-Record (OTR) Messaging [Issue #36](https://github.com/RocketChat/Rocket.Chat/issues/36), [Issue #268 - HELP WANTED](https://github.com/RocketChat/Rocket.Chat/issues/268)
- API-enabled methods: [Issue #202](https://github.com/RocketChat/Rocket.Chat/issues/202), [Issue #454](https://github.com/RocketChat/Rocket.Chat/issues/454), [Issue #455](https://github.com/RocketChat/Rocket.Chat/issues/455), [Issue #759](https://github.com/RocketChat/Rocket.Chat/issues/759)
- Scalable WebRTC broadcaster / media-server integration, [Issue #1118 - HELP WANTED](https://github.com/RocketChat/Rocket.Chat/issues/1118)

## Issues

[Github Issues](https://github.com/RocketChat/Rocket.Chat/issues) are used to track todos, bugs, feature requests, and more.

## Integrations

#### Hubot

The docker image is ready.
Everyone can start hacking the adapter code, or launch his/her own bot within a few minutes now.
Please head over to the [Hubot Integration Project](https://github.com/RocketChat/hubot-rocketchat) for more information.


## Documentation

Checkout [Github Wiki](https://github.com/RocketChat/Rocket.Chat/wiki)


# Development

## Installation
Prerequisites:

* [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Meteor](https://www.meteor.com/install)

Now just clone and start the app:

```sh
git clone https://github.com/RocketChat/Rocket.Chat.git
cd Rocket.Chat
meteor
```

## Branching Model

See [Branches and Releases](https://github.com/RocketChat/Rocket.Chat/wiki/Branches-and-Releases).

It is based on [Gitflow Workflow](http://nvie.com/posts/a-successful-git-branching-model/), reference section below is derived from Vincent Driessen at nvie.

See also this [Git Workflows Comparison](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) for more details.