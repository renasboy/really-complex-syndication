really-complex-syndication
==========================

This is the README file.
For installation just download the rcs file and make it executable.

git clone https://github.com/renasboy/really-complex-syndication
cd really-complex-syndication
chmod 755 rcs
./rcs

The idea behind the really complex syndication is to extract links to create
news feeds for sources websites that do not provide a RSS (really simple 
syndication) solution.

There is a DEMO website using really complex syndication to display linux and
geek news under [linuxforme.com/news](http://www.linuxforme.com/news).

In order to create your own really complex syndication script all is required
is the URL of the page and a smart REGEX to match link and title of the news.

In the example provided we use the (hacker news)[http://news.ycombinator.com] from ycombinator.

Dependencies are bash, wget, grep and sed, basically any GNU/Linux should do it.
