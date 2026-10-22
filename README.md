# Movie Portal — TizenBrew module

A TV-remote-friendly launcher for **https://movies.do/home**.

## Features

- A large Movies.do tile opens `https://movies.do/home`.
- A setting named **Open Movies.do automatically** lets you choose between showing the launcher or opening the website on later launches.
- The automatic-open preference is saved in browser local storage.
- The launcher displays the current time and date when supported.
- No other website shortcuts are included.

## Files

- `package.json` — TizenBrew app module metadata
- `app/index.html` — launcher interface and navigation
- `service.js` — minimal service entrypoint

## Upload to GitHub

Create a repository named `movie-portal` and upload the contents of this folder, keeping `package.json`, `README.md`, and `service.js` at the repository root and `index.html` inside `app/`.

Then add the repository through the Add Module flow in your installed TizenBrew version. Its required repository format may vary by version.

## Notes

- The first launch shows the launcher by default.
- If **Open Movies.do automatically** is switched on, later launches navigate directly to Movies.do.
- The preference depends on local storage being retained by the TizenBrew webview.
- This module does not replace Samsung's system Home screen or launch installed native TV apps.
