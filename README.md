# d3-graphs
A collection of sample graphs implemented in D3.

In this repo, I add d3-based visualisations that I've implemented, along with thorough comments, so that others can copy and learn. I am not a javascript or d3 expert - but hopefully that will just mean my explanations are suitable for other novices. The examples are written in regular javascript, though I do use some new features (like spread) from time to time. 
***

**How to run the examples**:

  Unless otherwise specified, you simply need to serve the html/js/css content within the project folder (e.g. barchart-msgcount) as-is, and open the index.html file in your browser. One way to do this is to install nodejs and the http-server module (npm install -g http-server), and then run the following commands:
```
  cd barchar-msgcount

  http-server
```

  That will start a simple http server that will serve content within the current folder. Simply open the URL listed in the command's output (e.g. http://127.0.0.1:8080/) and you should see the graph.
***

**Notes**:

  There is an order to the examples, but you don't need to follow them in order. Note though that I tend not to repeat explanations - so if something isn't explained in a later example, check an earlier one.

  Often, I just put everything into index.html if it is clean enough to do so. The exception to that is data, which generally will be served from a seperate local file (CSV or JSON).

  The examples should run in any modern browser.

  Internet access is required - since we need to access the d3 library, amongst other things. If that's a problem on your workstation, you can change the references to be local.
***

**Some useful resources**:

  http://www.d3noob.org/

  https://d3js.org/

  https://egghead.io/ (note that some content is behind a paywall)

