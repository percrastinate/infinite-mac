# Transparent Mac

TODO

## Development

Common tasks, all done via `npm run`:

-   `start`: Run local dev server (will be running at http://localhost:3127)
-   `import-basilisk-ii`: Copy generated WebAssembly and data files from a https://github.com/mihaip/macemu checkout (assumed to be in a sibling directory to this repo)
-   `build`: Rebuild for either local use (in the `build/` directory) or for Cloudflare Worker use
-   `worker-preview`: Preview built assets in a Cloudflare Worker (requires a separate `build` invocation)
-   `worker-deploy`: Deploy built assets to the live version of the Cloudflare Worker (requires a separate `build` invocation)