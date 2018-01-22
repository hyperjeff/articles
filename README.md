# articles
Command-line article search and tracking

Just a handy, low-maintenance tool to search thru articles by title, authors or year (and content? i forget). You manage the files on your own, and run the script as you want, no need to alert anything about changes you've made to the files.

Some much more thoughtful, explanatory stuff should go here, with screenshots.

In the meantime, check out this blog article on it here: http://blog.hyperjeff.net/?p=178

## Installation

Type this in at the command line, from the directory containing this project.

(note: change "/usr/local/bin" to wherever you keep such execatuble scripts. In my case, it's ~/bin)

* mkdir -p ~/.config/articles
* echo "/path/to/your/articles" > ~/.config/articles/article_base
* chmod +x articles unread* openarticle markArticle
* cp articles unread* openarticle markArticle /usr/local/bin/


### Next Steps

Very rough state. Next things to fix:
* An install script / makefile
* Add screenshots in Readme
* Nice full explanation including file and folder naming conventions.

-Jeff
