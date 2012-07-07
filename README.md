really-complex-syndication
==========================

This is the README file.<br/>
For installation just download the rcs file and make it executable.<br/>

<pre>
<code>
$ git clone https://github.com/renasboy/really-complex-syndication
$ cd really-complex-syndication
$ chmod 755 rcs
$ ./rcs
</code>
</pre>

The idea behind the really complex syndication is to extract links from source
websites that do not provide a RSS feed (really simple syndication).<br/>

There is a [DEMO](http://www.linuxforme.com/news) website using really complex syndication to display linux and
geek news under [linuxforme.com/news](http://www.linuxforme.com/news).<br/>

In order to create your own really complex syndication script all that is required
is the URL of the source page and a smart REGEX to match link and title of the news.<br/>

In the example provided we use the [hacker news](http://news.ycombinator.com) from ycombinator.<br/>

Dependencies are bash, wget, grep and sed, basically any GNU/Linux should do it.
