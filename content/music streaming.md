![[bugbox.png]]
# The Problem

| Service           | Notes                                                                                                    |
| ----------------- | -------------------------------------------------------------------------------------------------------- |
| Music Streaming   | monthly fee. don't own your media. poor compensation for artists                                         |
| Local files       | supports artists, but difficult to source and organize. tied to one device. expensive to start a library |
| Physical media??? | exists I guess                                                                                           |
# Enter, Jellyfin!
So, hear me out, what if we combined the worst parts of each of the above methods? All the organizational and financial issues of local media, with added maintenance costs🙃 All jokes aside self hosting a music server isn't for anyone, but if you're interested in owning your media and learning about server hosting this project may be for you! If you're looking for an in depth guide to setting up a linux server, check out [Hardware Haven](https://www.youtube.com/watch?v=eIHiRW4QH6I) on youtube. The [Jellyfin docs](https://jellyfin.org/docs/) are another great resource.
## Hardware
## Base
[Ubuntu Server](https://ubuntu.com/download/server)
[Docker](https://www.docker.com/)
## Finding music
- bandcamp
- patreon
- itunes
## Tagging
- [mp3tag](https://www.mp3tag.de/en/) - Simple metadata editor
- [MusicBrainz Picard](https://picard.musicbrainz.org/)  - Advanced tagger with the ability to lookup and identify music files
- [beets](https://beets.io/) - Command line library management
## Networking
[Wireguard](https://www.wireguard.com/)
[Duck DNS](https://www.duckdns.org/)