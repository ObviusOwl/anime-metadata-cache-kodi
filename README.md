# Kodi Scraper Addon for Anime Metadata Cache

This is the Kodi metadata scraper addon for the anime metadata cache server. 
All scraping, caching and XML formatting is done server side. This addon is only
the client side interface for kodi.

To install this addon, place the files into your Kodi addon directory, i.e. this
readme file would have the path `~/.kodi/addons/metadata.anidb.cache/README.md`.
Note that the URL of this repository differs from the addon name, meaning that
you will need to rename the directory or specify the empty directory for git-clone.

You must configure the URL to the metadata server before using the scraper. 
This can be done on the addon settings page. An example URL would be 
`http://localhost:8080/kodi.php`. Note that `kodi.php` is part of the URL and
part of the server application. However, if the webserver has URL rewriting, 
the URL may be completely different.