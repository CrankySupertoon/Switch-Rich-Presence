# Switch Rich Presence
A moderately okay solution to display what you're playing on Nintendo Switch on Discord. Thanks to [Da532](https://github.com/Da532) for doing 99% of the work on this. ✌️

## Introduction
"Switch Rich Presence" is a somewhat competent fork of ['NS-RPC' (Nintendo Switch Rich Presence)](https://github.com/Da532/NS-RPC), an Electron app for Windows and macOS that allows Switch users to display
the game they're currently playing as their Discord status with Rich Presence.

*This was my first time ever using JavaScript and I'm not great at it. I'm open to hearing how to improve*

![Switch Rich Presence Screenshot](https://i.imgur.com/uy7Pano.png)

### With Switch Rich Presence you can...
* Show off to non-Switch owners that you are a Nintendo Switch owner across all of Discord.
* Select from a currently-limited-by-discord list of games to show off.
* Set a custom status message to let everyone know exactly what you're doing in-game.
* Experience my absolutely disgusting attempt at re-designing a user interface.

### Missing a game?
Open an issue on this page and I'll add it as quickly as I can.

### Problems:
As of right now, I do not know of a way to have more than 150 art assets stored by Discord in order to display artwork for all of the games that are available on the Nintendo Switch. I have not added 150 games to the list yet, but I will attempt to find a way around this limitation in the meantime. The temporary solution is to keep the list updated with the 150 most popular/recent games.

Alternatively, the 150 game limit can be exceeded by using generic artwork for any game outside of the 150. The rich presence would then display the title and status of the game, just without the custom game artwork. I can foresee using the generic "Home" artwork in this case.

If you'd like to leave any suggestions or ideas about this problem, please open an issue on this repo.

I am also attempting to correct the UI errors.

## Prerequisites
All you need is a high tolerance for bad UI and the [Discord App](https://discordapp.com) installed to the same machine.

## Installation
If you're looking for convenience, you'll find already built copies of Switch Rich Presence for
both Windows and macOS [here](https://github.com/hobby-grade/Switch-Rich-Presence/releases).

## Building From source
Building from source is also possible if you don't value your time.

Required packages: [Node.js](https://nodejs.org/).

1. Once Node.js is installed, git clone or download and extract the source files to your chosen directory.
2. Open a terminal window, or command prompt in that directory.
3. To install the application's required dependencies, use the command `npm install`.
4. Finally, to execute the application you simply need to enter into terminal `npm start`.

## Need Help?
Open an issue on this page and I'll get back to you as soon as possible!
