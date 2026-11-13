<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/hero-banner-dark.svg"><img src="assets/hero-banner-light.svg" alt="Soma18: a daily 18-minute mind-body practice. Website, hosting and online store, built and maintained by Taha Saiyed." width="100%"></picture>
</p>

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/rotating-tagline-dark.svg"><img src="assets/rotating-tagline-light.svg" alt="An 18-minute daily mind-body practice. Four brain and eight body exercises. Free book, video series, secure member login. Built and maintained by one developer." width="100%"></picture>
</p>

<p align="center">
  <a href="https://soma18.ca"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/status-pill-dark.svg"><img src="assets/status-pill-light.svg" alt="Live at soma18.ca" width="232"></picture></a>
</p>

# Soma18

Soma18 is a daily 18-minute mind-body practice of four brain and eight body exercises, created by its founder, Hans Anderssen. The website offers his free book by email sign-up, a paid video series, and a secure member login for people who have bought it. I built and maintain the website, hosting and online store for Soma18.

**Live site:** [soma18.ca](https://soma18.ca)

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/section-divider-dark.svg"><img src="assets/section-divider-light.svg" alt="" width="100%"></picture>

## How it fits together

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/architecture-telemetry-dark.svg"><img src="assets/architecture-telemetry-light.svg" alt="A visitor reaches the site on Cloudflare. From there four services branch out: Clerk for login, Stripe for payments, Stream for videos and D1 for the database." width="100%"></picture>
</p>

A visitor reaches the site on Cloudflare. Clerk handles login, Stripe handles payments, Stream plays the videos and D1 is the database.

## From visitor to viewer

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/purchase-flow-state-machine-dark.svg"><img src="assets/purchase-flow-state-machine-light.svg" alt="Five steps in order: Browse, Sign in, Pay, Unlock, Watch." width="100%"></picture>
</p>

Browse the site, sign in, pay once, and the video series unlocks for that account.

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/section-divider-dark.svg"><img src="assets/section-divider-light.svg" alt="" width="100%"></picture>

## See it

<table>
  <tr>
    <td width="68%" valign="top" align="center">
      <img src="assets/live-scroll-tour.webp" alt="A smooth scroll down the public Soma18 home page: the hero photo of Hans Anderssen, the practice and its twelve exercises, what people say, Hans's story, the free book form and the footer." width="100%"><br>
      <sub>The public home page, scrolled top to bottom</sub>
    </td>
    <td width="32%" valign="top" align="center">
      <picture><source media="(prefers-color-scheme: dark)" srcset="assets/mobile-viewport-frame-dark.svg"><img src="assets/mobile-viewport-frame-light.svg" alt="The public Soma18 home page at phone width, 390 by 844, inside a plain phone outline." width="100%"></picture><br>
      <sub>The same page at phone width</sub>
    </td>
  </tr>
</table>

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/section-divider-dark.svg"><img src="assets/section-divider-light.svg" alt="" width="100%"></picture>

## Details

<details>
<summary><b>What I built</b></summary>

<br>

- The public website: one home page that explains the practice, shows the twelve exercises, and introduces Hans.
- The free book: an email sign-up with a consent tick box, followed by an instant download.
- The online store: a one-time purchase of the video series, with payment handled by Stripe.
- A secure member login for people who have bought the series.
- The hosting and the domain setup for soma18.ca.
- Built for older readers: large type, plain wording, and full keyboard support.
- The basics that help people find and trust a site: a clear page title and description, a sitemap, a proper "page not found" page, and self-hosted fonts.

</details>

<details>
<summary><b>Security approach</b></summary>

<br>

Kept general on purpose.

- Every member page checks a verified login.
- Videos play through signed links that expire.
- A payment only counts once the payment provider confirms it to the server. The browser is never trusted for this.
- Secrets live outside the code.
- The code repository is private.

</details>

<details>
<summary><b>What I learned</b></summary>

<br>

- Check paid access as three different people: logged out, logged in without a purchase, and logged in with one.
- Decide what a refund should do before the first sale, not after it.
- When a release changes the database, the database change goes first.
- Writing for older readers made the whole site clearer: bigger text, fewer words, and error messages that say what to do next.
- Keep notes a non-technical client can read. It saves everyone time.

</details>

## Built with

<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="assets/tech-stack-constellation-dark.svg"><img src="assets/tech-stack-constellation-light.svg" alt="Cloudflare Workers, Hono, TypeScript, D1, R2, Stream, Clerk and Stripe." width="100%"></picture>
</p>

Cloudflare Workers · Hono · TypeScript · D1 · R2 · Stream · Clerk · Stripe

Built with [Claude Code](https://claude.com/claude-code).

<picture><source media="(prefers-color-scheme: dark)" srcset="assets/section-divider-dark.svg"><img src="assets/section-divider-light.svg" alt="" width="100%"></picture>

## Contact

[LinkedIn](https://www.linkedin.com/in/taha-saiyed/) · [GitHub](https://github.com/TahaSaiyed08)

<sub>Code is private to protect the client. Every graphic on this page is a file in this repository: plain SVG and WebP, no scripts and no outside services. See <a href="assets/DESIGN.md">assets/DESIGN.md</a>.</sub>
