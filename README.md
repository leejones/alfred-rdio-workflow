# Rdio Alfred Workflow

Control Rdio.app from Alfred including:

* add/remove the currently playing track from your collection
* play/pause
* next/previous

Includes output to Notification Center.

![Rdio Alfred Workflow in Notification Center](docs/notification.png)

## Usage

![Rdio Alfred Workflow Usage](docs/usage.png)

	rd [command]

If no command is given, the workflow will launch Rdio.app (or bring it to the foreground if it is already launched).

## Commands

* `add` - add the currently playing track to your collection
* `remove` - remove the currently playing track from your collection and advance to the next track
* `play` - play the current track
* `pause` - pause the current track
* `next` - advance to the next track
* `previous` - return to the previous track

## Requirements

* [Alfred v2](http://www.alfredapp.com)
* [Rdio.app](http://www.rdio.com/apps/)

## Installation

From the terminal:

1. clone this repo `git clone https://github.com/leejones/alfred-rdio-workflow.git`
2. cd into the repo `cd alfred-rdio-workflow`
2. install with `bin/install`
