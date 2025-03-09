# TVHPlayer User Guide

This guide will help you learn how to use [TVHplayer](https://github.com/mfat/tvhplayer).

## Overview

### What is TVHplayer?
TVHplayer is a user-friendly application designed for streaming and recording live TV content. It uses [Tvheadend](https://tvheadend.org/), a popular open-source TV streaming server, as its backend.

:warning: TVHplayer doesn't provide any built-in server. You must set up your own server to use this app. See below for how to set up a Tvheadend server. 

### What is Tvheadend?
Tvheadend is a TV streaming server that lets you watch and record live TV. In modern term, it helps you "stream" live TV from a tuner to the network and watch television on your devices. It works by receiving TV signals from a tuner (like a USB DVB device) or an M3U playlist (for IPTV), then streaming the channels to devices like TVHPlayer.

Please refer to [Official documentation for Tvheadend](https://docs.tvheadend.org/documentation) for more information.
There are various ways for setting up a Tvheadend server. 
You can easily set up a server with [Docker](https://hub.docker.com/r/linuxserver/tvheadend).


## Features

- Stream live TV channels
- View Electronic Program Guide (EPG)
- Schedule recordings
- Record locally on your computer
- User-friendly interface


## Getting Started

### Installation

To install TVHPlayer, download the app from the [official website](https://github.com/mfat/tvhplayer) or Flathub.

### Connecting to TVHeadend

To connect TVHPlayer to your TVHeadend server:

1. Open the TVHPlayer app.
2. Click the small cog icon above channel list to add your server
3. Enter the IP address and port number of your TVHeadend server (includibg http:// or https://)
4. Enter your TVHeadend username and password.
5. Save the settings and test the connection.

## Using TVHPlayer

### Streaming Live TV

Press the play button or double-click a channel on the channel list to start watching.

### View Program Guide (EPG)

TVHplayer has basic support for Electronic Program Guides (EPG). To view the program guide, right-click on the channel name and select "Show EPG". EPG needs to be provided by your TVheadend server. 

### Schedule recordings

1. To record a live program using Tvheaden's DVR function, click the record button below the player. You are asked to set duration for the recording. Recordings will be stored on the server. 
2. To schedule recording a show, right-click on the channel name and select "Show EPG". From the EPG window you can schedule recordings
3. To record live TV locally on your computer press the local record button (the downward arrow)

## Troubleshooting

If you encounter any issues while using TVHPlayer, try the following steps:

1. Ensure your TVHeadend server is running and accessible.
2. Check your network connection.
3. Verify that you have entered the correct IP address, port number, username, and password in the app settings.
4. Restart the TVHPlayer app and your device.

## Additional Resources

For more information and support, refer to the official TVHeadend documentation:

- [TVHeadend Official Documentation](https://docs.tvheadend.org/documentation)

Thank you for using TVHPlayer.