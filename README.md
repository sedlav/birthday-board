# birthday board

A self-contained birthday and age tracker. Open `index.html` in a browser. Entries are saved in that browser; export the JSON data file to move the list to another device.

## deploy with cloudflare pages

1. Create a GitHub repository named `birthday-board` and push this folder to its `main` branch.
2. In Cloudflare, create a Pages project and connect the `birthday-board` repository.
3. Choose **None** as the framework preset, leave the build command blank, and set the build output directory to `.`.
4. Deploy. Cloudflare will publish `index.html` at the project's `pages.dev` address and rebuild on each push to `main`.
