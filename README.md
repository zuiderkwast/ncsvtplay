ncsvtplay
=========

NCurses client for downloading programmes from SVT Play

How to use
----------

Copy the file `ncsvtplay` to `/usr/local/bin/`. You need Python 3 and svtplay-dl installed.

Svtplay-dl can be installed using `sudo apt-get install svtplay-dl` in Debian och downloaded from https://svtplay-dl.se/.

Run the program `ncsvtplay` in a terminal. Programmes you select for download will be downloaded in the current directory. If the program is terminated, any incomplete download is deleted.

Note
----

If `svtplay.se` changes the HTML code on the website, the program might stop working. Regular expressions are used to scrape the website.

Features
--------

* all programmes view
* genre view(s)
* download
* download queue (invisible)
* back-forward view navigation
* keyboard help in status bar

Todo
----

* view download queue
* download(ed/ing) indicator on each episode (bold/color/symbol)
* open file in vlc or other player (experimental implementation exists)
* config file
* store local files hierarchically, by programme
* url-to-file mapping database (local file in ~/.ncsvtplay, etc.)
* help page
* search/grep
* unit test and integration with Travis CI
