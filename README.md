This repository is dedicated to the Ada Search - custom Google search engine
for the Ada/SPARK programming language. It contains:

* [index.html](index.html) - Ready to deploy the HTML/JavaScript page which can
  be added to a webpage.
* [configuration.md](configuration.html) - The short description of Google
  Programmable Search Engine configuration to create it

If you have any questions, problems or ideas about the Ada Search feel free to
open [issue](https://github.com/thindil/adasearch/issues/new).

Main reason why this project exists is that I was tired of filtering standard
search results from information about diabetes, dentist and generally name of
Ada. List of excluded keywords growth almost with every day and don't helped
too much.

Also, this project exists to help others create and maintain they own version
of custom search engine :)

The whole search engine is based on [Google Knowledge Graph](https://en.wikipedia.org/wiki/Knowledge_Graph).

### Installation

#### As a separate webpage

Just download file `index.html` and (if you need) rename it and put on the
server. Feel free to modify the default look of the webpage.

#### Search entry only

If you want to embed the search engine on your page, put in the place where you
want to add it (in HTML):

    <script async src="https://cse.google.com/cse.js?cx=009829025445605706198:-dt42nxzgi8"></script>
    <div class="gcse-searchbox-only"></div>

### License

Everything here is released under [CC0 license](LICENSE).

----

That's all for now, as usual, probably I forgot about something important ;)

Bartek thindil Jasicki
