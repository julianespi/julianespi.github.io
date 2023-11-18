# Background

A static site generator (SSG) is a tool that generates a full static HTML website based on raw data and a set of templates. Essentially, a static site generator automates the task of coding individual HTML pages and gets those pages ready to serve to users ahead of time. Because these HTML pages are pre-built, they can load very quickly in users' browsers.

SSG describes the process of compiling and rendering a website or app at build time. The output is a bunch of static files, including the HTML file itself and assets like JavaScript and CSS to be served entirely on the first load. These files can additionally be cached on a CDN (Content Delivery Network) for even faster retrieval.

# Getting started

Install and start the [Eleventy static site generator][1]:

```shell-session
npm install
npm start
```

Open the [newly generated site][2].

[1]: https://www.11ty.dev/
[2]: http://localhost:8080/

# Data

The data (\_data) supplied here for templating come from Pexels. Stock photos are widely used as visual elements in advertising and website design and Pexels is a website offering freely-usable stock photos through its curated collections of photos. If you want to generate your own Pexel photos, you'll need an API key in the `.env` file.
