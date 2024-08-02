[![Ada Search logo](img/ada_search.svg)](https://mgrojo.github.io/adasearch/)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/ada-lang/Lobby)
[![Mentioned in Awesome Ada](https://awesome.re/mentioned-badge.svg)](https://github.com/ohenley/awesome-ada)

This repository is dedicated to Ada Search: a custom Google search
engine for the Ada/SPARK programming language, and other search
engines customized for Ada. It contains:

* [`index.html`](index.html) - The HTML/JavaScript page ready to be
  deployed to a website.
* [`google/`](google/) -
  [Configuration](https://developers.google.com/custom-search/docs/basics)
  of the [Google Programmable Search
  Engine](https://programmablesearchengine.google.com/about/).  It
  includes Ada and SPARK from the [Google Knowledge
  Graph](https://en.wikipedia.org/wiki/Knowledge_Graph), some synonyms
  and custom autocompletions based on the Ada 2022 RM index.
* [`plugins/`](plugins/) - [OpenSearch description
  files](https://developer.mozilla.org/en-US/docs/Web/OpenSearch) for
  all the search engines. That means that you can add them as
  alternative search plugins to your browser.

The main reason why this project exists is that we, Ada programmers,
are tired of filtering standard search results from information about
diabetes, dentist and generally name of Ada. List of excluded keywords
can grow almost every day and don't help too much.

Also, this project can help others create and maintain their own
version of a custom search engine :)

**INFO:** This project is a maintained fork of the former
thindil/adasearch project.
