---
layout: post
title: My Attempt at a No-Coding Scraper
---

Last Summer, while working with Dr. Mel Stanfill to revise a grant proposal, I was asked if I could find them a scraper to pull information from a web-page. On doing so, I thought it might be a good opportunity to expand this small side project into something that might be useful for my colleagues; a resource which would walk the user through reading HTML tree, and scraping, in a step-by-step "no-coding-required" manner. Of course, I'm a python amateur, and a scraping amateur as well, but, I figured that making a resources for *others* would make me better at both!

The notebook uses BeautifulSoup to attempt to guide the user through scraping in a step-by-step manner, while teaching the basics of how to read HTML and navigate along the way. [I rely heavily on "quotes.toscrape.com" throughout the notebook](https://quotes.toscrape.com/), in order to introduce users to a sample site first, which, ideally, will then let theme apply the notebooks to a site with more complicated HTML.

In the terms of a the Blades in the Dark RPG: I'd qualify my efforts as a *mixed success*. It certainly scrapes most websites well enough, and guides the user through the process of scraping. However, there are some websites that just don't work as of writing: attempting ot bull the titles of an ace attorney fan blog for a colleague, for example, was far beyond the capabilities of my simple scraper; I think I need to fix something about how it iterates over the blog posts, which I suppose is something I will update this blog post about, if/when I get around to fixing it.

