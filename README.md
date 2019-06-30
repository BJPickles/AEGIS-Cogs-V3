<h1 align="center">
  <br>
  <a href="https://github.com/Cog-Creators/Red-DiscordBot/tree/V3/develop"><img src="http://pluspng.com/img-png/png-hd-gears-cogs-07-54-11-march-2017-600.png" alt="AEGIS Cogs"></a>
  <br>
  AEGIS bot V3 - COGS
  <br>
</h1>

<h4 align="center">Music, Moderation, Trivia, Stream Alerts and Fully Modular.</h4>

<p align="center">
  <a href="https://discord.gg/smvhW9t">
    <img src="https://discordapp.com/api/guilds/301811233827454986/widget.png?style=shield" alt="Discord Server">
  </a>
  <a href="https://www.patreon.com/Red_Devs">
    <img src="https://img.shields.io/badge/Support-Red!-yellow.svg" alt="Support AEGIS on Patreon!">
  </a>
  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Made%20With-Python%203.7-blue.svg?style=for-the-badge" alt="Made with Python 3.7">
  </a>
  <a href="https://crowdin.com/project/red-discordbot">
    <img src="https://d322cqt584bo4o.cloudfront.net/red-discordbot/localized.svg" alt="Localized with Crowdin">
  </a>
  <a href="https://github.com/Rapptz/discord.py/tree/rewrite">
      <img src="https://img.shields.io/badge/discord-py-blue.svg" alt="discord.py">
  </a>
</p>
<p align="center">
  <a href="https://travis-ci.com/Cog-Creators/Red-DiscordBot">
    <img src="https://api.travis-ci.com/Cog-Creators/Red-DiscordBot.svg?branch=V3/develop" alt="Travis CI">
  </a>
  <a href="http://red-discordbot.readthedocs.io/en/v3-develop/?badge=v3-develop">
    <img src="https://readthedocs.org/projects/red-discordbot/badge/?version=v3-develop" alt="Red on readthedocs.org">
  </a>
  <a href="https://github.com/ambv/black">
    <img src="https://img.shields.io/badge/code%20style-black-000000.svg" alt="Code Style: Black">
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
  </a>
</p>

<p align="center">
  <a href="#overview">Overview</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="http://red-discordbot.readthedocs.io/en/v3-develop/index.html">Documentation</a>
  •
  <a href="#plugins">Plugins</a>
  •
  <a href="#join-the-community">Community</a>
  •
  <a href="#license">License</a>
</p>

# Overview

These are cogs for Red, which have been made for AEGIS, but are publicly released. See deployment(#deployment) for further instructions.

[Installation](#installation) is easy, and you do **NOT** need to know anything about coding! Aside
from installation and updating, every part of the bot can be controlled from within Discord.

**The default set of modules includes and is not limited to:**

- Moderation features (kick/ban/softban/hackban, mod-log, filter, chat cleanup)
- Trivia (lists are included and can be easily added)
- Music features (YouTube, SoundCloud, local files, playlists, queues)
- Stream alerts (Twitch, Youtube, Mixer, Hitbox, Picarto)
- Bank (slot machine, user credits)
- Custom commands
- Imgur/gif search
- Admin automation (self-role assignment, cross-server announcements, mod-mail reports)
- Customisable command permissions

**Additionally, other [plugins](#plugins) (cogs) can be easily found and added from our growing
community of cog repositories.**

# Installation

**The following platforms are officially supported:** 

- [Windows](https://red-discordbot.readthedocs.io/en/v3-develop/install_windows.html)
- [MacOS](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)
- [Ubuntu](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)
- [Debian Stretch](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)
- [CentOS 7](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)
- [Arch Linux](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)
- [Raspbian Stretch](https://red-discordbot.readthedocs.io/en/v3-develop/install_linux_mac.html)


If after reading the guide you are still experiencing issues, feel free to join the
[Official Discord Server](https://discord.gg/red) and ask in the **#support** channel for help.

# Plugins

Red is fully modular, allowing you to load and unload plugins of your choice, and install 3rd party
plugins directly from Discord! A few examples are:

- Cleverbot integration (talk to Red and she talks back)
- Ban sync
- Welcome messages
- Casino
- Reaction roles
- Slow Mode
- Anilist
- And much, much more!

Feel free to take a [peek](https://github.com/BJPickles/AEGIS-Cogs) at a list of
available 3rd party cogs!

# Join the community!

**AEGIS** is in continuous development, and it’s supported by an active community which produces new
content (cogs/plugins) for everyone to enjoy. New features are constantly added. 
Our community loves to play games together, why don't you join us!
If you can’t [find](https://github.com/BJPickles/AEGIS-Cogs) one of our cogs that you’re looking for,
consult Red's [guide](https://red-discordbot.readthedocs.io/en/v3-develop/guide_cog_creation.html) on
building your own!

Join us on our [Official Discord Server](https://discord.gg/smvhW9t)!

# License

Released under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.

Red is named after the main character of "Transistor", a video game by
[Super Giant Games](https://www.supergiantgames.com/games/transistor/).

Artwork created by [Sinlaire](https://sinlaire.deviantart.com/) on Deviant Art for the Red Discord
Bot Project.


# Deployment

Use the following to get our released AEGIS cogs:

```
[p]cog repo add AEGIS-Cogs https://github.com/BJPickles/AEGIS-Cogs
```
```
Example:

[p]cog install AEGIS-Cogs modmail
```

# Built With

* [Python](Link) - The framework used
* [Discord RED](Link) - Dependency Management
* [GitHub](Link) - Used to generate host

# Contributing

Please read [CONTRIBUTING.md](Link) for details on our code of conduct, and the process for submitting pull requests to us.

# Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

# Authors

* **BJPickles** - *Initial work* - [BJPickles](https://github.com/BJPickles)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

# Acknowledgments

* Hat tip to anyone whose code was used.
* There are a lot of amazing authors here.
* It's important to note this is a huge collaboration of authors who have spent hundreds of hours pouring their time into this project.
* AEGIS is humbled that we are able to use this code and extend it to our own aims.
* Big thank you to everyone for your hard work.
