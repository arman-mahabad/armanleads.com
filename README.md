<!--
  Showcase README for the public repo arman-mahabad/armanleads.com.
  The code lives in two private repos (the site and the CRM). This repo holds only this page.
-->

<sub><a href="https://byarman.site">Made by Arman ↗</a></sub>

# ArmanLeads

**A marketing business for US dental practices. I built it and I run it: the website, the way it researches practices, and the CRM behind it.**

[Open armanleads.com ↗](https://armanleads.com) &nbsp;·&nbsp; Live &nbsp;·&nbsp; The code is private, in two repos: the site and the CRM.

<img src="assets/divider.svg" width="100%" alt="">

## The website

Links in emails go through one small Cloudflare function. It records which link was opened and sends the visitor on to the homepage in the same response. It holds only the public database key, and a database rule lets it add a click and nothing more. A leaked copy of the file couldn't read a single row.

## The research

Every fact about a practice gets saved with its source. Nothing goes out that can't be traced back.

## The CRM

A private web app that runs the whole pipeline.

- **Today** shows everything that needs a decision today, and nothing else.
- **The board** holds every practice as a card. Drag a card to change its stage. Overdue follow-ups and opened links show on the card.
- **A daily meter** counts the emails sent today against the day's goal.

No screenshots here, because the CRM holds real practices' data.

`HTML` `CSS` `Cloudflare Pages` `React` `Vite` `Tailwind` `Supabase` `Recharts`

<img src="assets/divider.svg" width="100%" alt="">

I can walk you through the code on a call: [arman@byarman.site](mailto:arman@byarman.site)

More of my work: [byarman.site](https://byarman.site) &nbsp;·&nbsp; [github.com/arman-mahabad](https://github.com/arman-mahabad)

<img src="assets/rosette.svg" width="18" alt="">
