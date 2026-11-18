# birthday board

A self-contained birthday and age tracker. The page reads the shared list from `people.json`.

To update the family list, edit `people.json` and push the change to GitHub. Cloudflare Pages will redeploy, and everyone will see the updated list. Each entry has an `id`, `name`, and birthday `date` in `YYYY-MM-DD` format.

## deploy with cloudflare pages

1. Connect the `birthday-board` GitHub repository to Cloudflare Pages.
2. Choose **None** for the framework preset, leave the build command blank, and set the build output directory to `.`.
3. Cloudflare publishes `index.html` and `people.json`. Push changes to the `main` branch to update the shared page and list.
