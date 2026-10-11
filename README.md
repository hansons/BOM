# On Jesus Reference Sheets

Reference sheets on the kingdom of heaven and the teaching of Jesus, drawn from the Gospels.

| Page | What it is |
|---|---|
| [`index.html`](index.html) | Home page listing the sheets |
| [`what-they-heard-in-galilee.html`](what-they-heard-in-galilee.html) | One-page handout: what Jesus taught on his Galilee preaching tours |
| [`kingdom-of-heaven-in-matthew.html`](kingdom-of-heaven-in-matthew.html) | Study page: the kingdom of heaven in the Gospel of Matthew |
| [`gospel-of-the-kingdom-of-heaven.html`](gospel-of-the-kingdom-of-heaven.html) | Reference sheet: Matthew's five discourses and the life between them |

Every page is a single self-contained HTML file. Nothing needs to be built or installed; open any file in a browser to view it.

## Publishing with Cloudflare Pages

In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git**, choose this repository, and use:

| Setting | Value |
|---|---|
| Production branch | `main` |
| Framework preset | None |
| Build command | *(empty)* |
| Build output directory | `/` |
| Root directory | *(empty)* |

Every push to `main` redeploys the site.

The empty `.nojekyll` file is only needed if the site is ever served with GitHub Pages instead; it tells GitHub Pages to serve the files as they are.

## Updating a page

Edit the HTML file directly, or replace it with a newer version, then commit and push. Keep the `← All reference sheets` link near the top of each page so readers can get back to the home page.

## Scripture

Scripture quotations are from the ESV® Bible (The Holy Bible, English Standard Version®), © 2001 by Crossway, a publishing ministry of Good News Publishers. Used by permission. All rights reserved. Each page carries this notice. Reference links open the passage on BibleGateway in the ESV.
