# kairosai.xyz

The website for Kairos AI: a single static page showcasing [Kairos](https://github.com/nihilistau/Kairos), [kairos-engine](https://github.com/nihilistau/kairos-engine), [The Clockwork Dark](https://github.com/nihilistau/clockwork-dark) and [Primer](https://github.com/nihilistau/Primer).

- Plain HTML and CSS in `index.html`. No build step and no dependencies.
- Screenshots are in `assets/img/`, resized to WebP from each project's repo.
- Hosted on GitHub Pages. `CNAME` points it at `kairosai.xyz`.

## Adding a project
Copy one `<section class="project">` block in `index.html`, add a card to `.index`, and drop its screenshots in `assets/img/`.

## DNS (at GoDaddy)
| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | nihilistau.github.io |

Leave every other record alone. MX, TXT, autodiscover, the DKIM selectors, `_dmarc`, lyncdiscover and the SIP SRV belong to Microsoft 365 email.
