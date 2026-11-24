# Video Speed Controller Gecko

I use Video Speed Controller in Helium and wanted the same version in Zen, so I made this fork of [Ilya Grigorik's Video Speed Controller](https://github.com/igrigorik/videospeed). It's based on v0.11.2. I changed how Firefox loads the background script and how the controller passes settings back and forth.

## Try it

Run `npm ci` and `npm run package:firefox`. In Zen or Firefox 140 and newer, open `about:debugging#/runtime/this-firefox`, click **Load Temporary Add-on**, and pick the `.xpi` in `release/`. It stays loaded until you restart the browser.

I tested the overlay, shortcuts and remembered speed in Zen 1.24.3b and Firefox 160.0.1. See the [MIT licence](LICENSE).
