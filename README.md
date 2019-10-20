# autohostbot-rust ![GNU AGPLv3][agpl-logo]
An autohosting bot for Twitch supporting smaller streamers

This is a simple autohosting bot that should imitate the behaviour of Mixers ChannelOne. It will automatically host a list of given channels, sorted by priorities that are based on the channels viewer numbers. This should make sure that smaller channels get some attention and should take away the burden from bigger channels to decide which channel they give their host. It will keep hosting a channel for a certain time period or until it goes offline and then re-hosts a new channel afterwards. If there are no channels left on the hosting list it will pull in new channels from a search result and give them also priorities based on viewer numbers and continues to host them.

### Version 0.1.0:
- Initial release.

# License
GNU AGPL-3.0-or-later; see [copying.md](copying.md) and [legal/AGPL-v3](legal/AGPL-v3).

[agpl-logo]: https://www.gnu.org/graphics/agplv3-88x31.png