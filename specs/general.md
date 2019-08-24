# General specs
This webui shall come as an extension for [`natnat-mc/imglib`](https://github.com/natnat-mc/imglib). It shall only setup a router on either `/` or another specified path that serves static files, its own config file, its stylesheet and any required extensions.

## Interface style
The interface shall be built using [Materialize](https://materializecss.com/) and communicate with the main software using its API. The colors shall be customizable.

## Technologies used
- [Sass](https://sass-lang.com/), compiled to CSS for the stylesheets
- [Typescript](https://www.typescriptlang.org/), compiled to JS for handling the client logic
- [Moonscript](https://moonscript.org/), compiled to Lua for the server logic
