
blogroll-roller
===============

This PHP script helps you grab all the RSS feeds from a list of blogs, so you can quickly subscribe to them, without having to do a lot of looky-looky clicky-clicky.

The script will output all the RSS feeds it finds into one OPML file, which you can import into your favorite feed reader to add all the blogs to your favorite feed reader.

Some examples of well-designed, modern RSS reader apps include [inoReader](https://www.inoreader.com/blog/2014/05/opml-subscriptions.html) and [Readwise Reader](https://docs.readwise.io/reader/docs/faqs/adding-new-content#how-do-i-upload-an-opml-file-to-import-all-my-rss-feeds-from-my-existing-rss-feed-reader-such-as-feedly-inoreader-reeder-etc), both of which can import an OPML list of feeds to subscribe to.


Instructions for Use
--------------------------------------------------------------------------------

1. make a text file named `URLlist.txt`
2. fill the text file the the URLS of blogs you'd like to follow, one URL per line. for example:
```
https://example.com
https://example.net
https://example.org
```
3. put `URLlist.txt` and `index.php` in the same directory on your server (i.s. `~/blogroll-roller/`)
4. `cd` to that directory and run the command `php index.php` to make it go.
5. profit!

If you have any questions about this, please use the Github Issues and I'll try to help you out. I'm not the original author of this, but I'll do my best.


License
-------------------------------------------------------------------------------

You may freely use, modify, and distribute this code, provided that any derivative works also comply with the [GNU General Public License v3.0](http://www.gnu.org/copyleft/gpl.html). For more details, see the [LICENSE](LICENSE) file.

This project is forked from [@skinofstars](https://github.com/skinofstars) work: [PHP Script for RSS auto-discovery and OPML file generation](https://web.archive.org/web/20200802141531/http://skinofstars.com/2010/03/php-script-rss-auto-discovery-opml-file).
