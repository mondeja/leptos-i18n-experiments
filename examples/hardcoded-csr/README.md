# hardcoded-csr

This is the most naive implementation of internationalization in a client side rendered Leptos app. It was my first starting point investigating how to build a i18n solution for Leptos.

To run it, just issue the `trunk serve --open` command in the example root. This will build the app, run it, and open a new browser to serve it.

> If you don't have `trunk` installed, [click here for install instructions](https://trunkrs.dev/).

## Details

It uses [strum](https://docs.rs/strum/latest/strum/) to easily manage the `Language` enum inside the component.

## Run tests

```bash
trunk serve

# in another terminal
cd end2end
npx install playwright
playwright test
```
