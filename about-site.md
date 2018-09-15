---
layout: page
title: This site
permalink: /about/site/
---

# How this site is built

This site is built in [Jekyll](https://jekyllrb.com) ([jekyll on GitHub](https://github.com/jekyll/jekyll)) and deployed using a script I knocked up that pulls the Jekyll [source tree](https://github.com/thelovebug/davelee.uk-jekyll/) from GitHub to one of my VPSes, builds the static site, and then pushes the site via FTP to where you're looking at it now.

The script I've put together will eventually end up in my GitHub account at some point, once it looks slightly less like a mouldy dogs' dinner.

# Why Jekyll?

I had a notion, after having a conversation with a fellow geek about static websites, to have a go at setting up Jekyll on this domain.  I 
wasn't doing anything with this domain at the time, so it was an excellent candidate.

And, of course, being a static site it should be really quite speedy to load the pages!

# Is the deployment script working?

At the moment, the site is deployed every 15 minutes, regardless of any changes.  The datestamp below will show whether it's working or not! 
:-)

**Site last deployed:** {{ site.time }}
