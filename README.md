# Bookmark Server

This is a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

This server supports Threading so processes run simultaneously and non-blocking

See [BookmarkServer.py](./BookmarkServer.py] for starter code and instructions on how it was built.

See [Procfile](./Procfile) for declared environment

This server is hosted on [heroku](https://www.heroku.com/home)