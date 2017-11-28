This is my repository for home server and home theater PC building. It contains script for docker-composer, configurations, and some other useful scripts

My plan is building a home server where I can store my animes, music, manga, and other files so I can access them from everywhere.

## Hardware Build
- To be decided

## Software Build
- Media Server
  - Plex Media Server with Plex Pass (_originize all media and serves them, support transcode video for all devices_ )
  - PlexPy - monitor Plex server's statitics
- Media Downloaders
  - Sonarr (_shows, video downloader using usenet by monitor RSS feed_)
  - Radarr (_a fork of Sonarr which focus on movie_)
  - Headphones (_automatically music downloader_)
  - Jackett (_proxy server for Sonarr and Radarr, helps to communicate with more torrent server_)
- Torrent Server
  - Deluge (_the best torrent client exist in this world!_) with its WebUI plugin (_pirate anime o((*^▽^*))o_)
- Usenet Server / Downloader
  - To be decided, Usenet services are paid services. Need to see how things are going first.
- Cloud Service
  - Next Cloud - store other files
- Web Server
  - nginx - act as reversed proxy server
