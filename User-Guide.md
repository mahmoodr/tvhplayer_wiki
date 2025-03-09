# TVHPlayer User Guide

This guide will help you learn how to use [TVHPlayer](https://github.com/mfat/tvhplayer).  

## Overview

### What is TVHPlayer?
TVHPlayer is a user-friendly application designed for streaming and recording live TV content. It uses Tvheadend, a popular open-source TV streaming server, as its backend.

> ⚠️ TVHPlayer does not provide a built-in server. You must set up your own Tvheadend server to use this app. See below for setup instructions.

### What is Tvheadend?
Tvheadend is a TV streaming server that enables you to watch and record live TV. In modern terms, it allows you to "stream" live TV from a tuner to the network and watch television on your devices. It works by receiving TV signals from a tuner (such as an HDHomeRun or a USB DVB device) or an M3U playlist (for IPTV) and then streaming the channels to devices like TVHPlayer.

For more details, refer to the [official Tvheadend documentation](https://tvheadend.org/). There are multiple ways to set up a Tvheadend server, including an easy setup using Docker.

## Features
- Stream live TV channels
- View the Electronic Program Guide (EPG)
- Schedule recordings
- Record locally on your computer
- User-friendly interface
- **Free** and open-source
- **Cross-platform:** TVHPlayer works on Linux, macOS, and Windows

## Getting Started

### Installation
To install TVHPlayer, download the app from the [official website](https://example.com) or [Flathub](https://flathub.org/).

### Connecting to Tvheadend
To connect TVHPlayer to your Tvheadend server:

1. Open the TVHPlayer app.
2. Click the small cog icon above the channel list to add your server.
3. Enter the IP address and port number of your Tvheadend server (including `http://` or `https://`).
4. Enter your Tvheadend username and password.
5. Save the settings and test the connection.

## Using TVHPlayer

### Streaming Live TV
Press the **Play** button or double-click a channel in the channel list to start watching.

### Viewing the Program Guide (EPG)
TVHPlayer has basic support for Electronic Program Guides (EPG). To view the program guide:
1. Right-click on the channel name.
2. Select **Show EPG**.

> **Note:** The EPG data must be provided by your Tvheadend server.

### Scheduling Recordings
- **Recording a live program using Tvheadend's DVR function:**
  1. Click the **Record** button below the player.
  2. Set the duration for the recording.
  3. The recording will be stored on the server.

- **Scheduling a recording from the EPG:**
  1. Right-click on the channel name.
  2. Select **Show EPG**.
  3. In the EPG window, press the **Record** button next to your desired show.

- **Recording live TV locally on your computer:**
  - Press the **Local Record** button (the downward arrow).

## Troubleshooting
If you encounter any issues while using TVHPlayer, try the following steps:

- Ensure your Tvheadend server is running and accessible.
- Check your network connection.
- Verify that you have entered the correct IP address, port number, username, and password in the app settings.
- Restart the TVHPlayer app and your device.

## Additional Resources
For more information and support, refer to the [official Tvheadend documentation](https://tvheadend.org/).

---
Thank you for using TVHPlayer!