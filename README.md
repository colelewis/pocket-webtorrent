# pocket-webtorrent

Minimal JS web torrent client built with [WebTorrent](webtorrent.io)

## Notes
To use:
* `git clone https://github.com/colelewis/pocket-webtorrent.git`
* Navigate to downloaded directory
* Serve `index.html` using a local web server.
  * Recommended method: `python3 -m http.server 8000`
  * Navigate to `localhost:8000` in your web browser.


The pocket-webtorrent client can download or stream files from magnet link/torrent file. The client can also create new torrents and seed them from file(s) you provide. Supports the [HTML5 Drag and Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API). 

The pocket-webtorrent client only supports WebRTC seeded torrents or torrents with a valid WebTorrent webseed.

Here's a sample magnet link to Sintel, a free, Creative Commons movie:

> magnet:?xt=urn:btih:08ada5a7a6183aae1e09d831df6748d566095a10&dn=Sintel&tr=udp%3A%2F%2Fexplodie.org%3A6969&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.empire-js.us%3A1337&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337&tr=wss%3A%2F%2Ftracker.btorrent.xyz&tr=wss%3A%2F%2Ftracker.fastcast.nz&tr=wss%3A%2F%2Ftracker.openwebtorrent.com&ws=https%3A%2F%2Fwebtorrent.io%2Ftorrents%2F&xs=https%3A%2F%2Fwebtorrent.io%2Ftorrents%2Fsintel.torrent

## Demonstration

Try pocket-webtorrent out [here](https://menthol.cloud/pocket-webtorrent)
