# Gaming Twitch Bot

A personal Twitch chat bot that serves live Valorant stats during streams.

## Description

A Twitch chat bot for the Miznatnasah channel. Responds to `!rank` (current rank + peak rank) and `!record` (this-stream RR change, this-stream W/L/D, current rank/RR) with live Valorant stats for whichever Val account the streamer is currently playing on. Automatically detects account switches via match-history timestamps, and tracks per-stream stats by watching the channel's Twitch live state.

## Getting Started

### Dependencies

* Python 3.x (Windows / macOS / Linux)
* Twitch developer application credentials (client ID + secret) for the chat connection and Helix API access
* Henrik API access for Valorant stats
* Specific Python libraries: *TBD as the project develops*

### Installing

*To be filled in as v1 progresses — currently no install method exists.*

### Executing program

*To be filled in once a working entry point exists. Will cover: configuring your Val account list, setting up Twitch credentials, and starting the bot before going live.*

## Help

*To be filled in as common issues surface during development.*

## Authors

Tanzim Hasan — [@Miznatnasah](https://github.com/Miznatnasah)

## Version History

* 0.0 — Planning and scope locked
    * v1 scope: `!rank` and `!record` commands, multi-account auto-detect, go-live session tracking, Valorant only
    * Out of scope for v1: LoL stats, persistent session history, automated rank-up announcements

## License

*TBD — pick a license before the repo gets serious traffic. MIT is common for personal projects; see [choosealicense.com](https://choosealicense.com) if unsure.*

## Acknowledgments

* README template adapted from [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
