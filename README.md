# On Jesus Reference Sheets

Reference sheets on the kingdom of heaven and the teaching of Jesus, drawn from the Gospels.

| Page | What it is |
|---|---|
| [`index.html`](index.html) | Home page listing the sheets |
| [`what-they-heard-in-galilee.html`](what-they-heard-in-galilee.html) | One-page handout: what Jesus taught on his Galilee preaching tours |
| [`seven-questions-about-the-kingdom.html`](seven-questions-about-the-kingdom.html) | Questions and answers: seven questions about the kingdom, answered from Matthew |
| [`gospel-of-the-kingdom-of-heaven.html`](gospel-of-the-kingdom-of-heaven.html) | Reference sheet: Matthew's five discourses and the life between them |
| [`the-faith-of-jesus.html`](the-faith-of-jesus.html) | Study page: the faith of Jesus in the Gospel of Matthew |

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

Edit the HTML file directly, or replace it with a newer version, then commit and push. Every page starts with the same row of tabs (the `site-tabs` block between the `<!-- site-tabs -->` comments). Keep it on any replacement page, and when adding a new page, add its tab to that block on every page.

## Scripture

Scripture quotations are from the ESV® Bible (The Holy Bible, English Standard Version®), © 2001 by Crossway, a publishing ministry of Good News Publishers. Used by permission. All rights reserved. Each page carries this notice. Reference links open the passage on BibleGateway in the ESV.
