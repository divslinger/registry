# Deno Module Registry

[![Build Status](https://travis-ci.com/denoland/registry.svg?branch=master)](https://travis-ci.com/denoland/registry)

This is the webserver and database for the [https://deno.land/x/](https://deno.land/x/) service.

This service allows people to create pretty URLs which redirect to github (or
other content). For example:

```sh
deno -A https://deno.land/x/std@v0.2.7/http/file_server.ts
```

To run the dev server (you shouldn’t need to do this to add a package to the registry):

```sh
cd src
npm install
npm start
```

the registry will launch at [http://localhost:4000/x/](http://localhost:4000/x/)
