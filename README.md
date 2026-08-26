# Application policies

Privacy policies for published applications, served as static pages by GitHub
Pages. One directory per application.

| Application | Policy |
|---|---|
| Response Card | [response-card/](https://g2wf5c4sf2-jpg.github.io/application_policies/response-card/) |

Each page is self-contained: no scripts, no webfonts, no analytics, and no
request to any other host. A privacy policy that loads an asset from a third
party hands that third party the address of everyone who reads it, which is not
a thing a privacy policy should do.

`.nojekyll` is deliberate. It tells Pages to serve the committed bytes rather
than run a Jekyll build, so a page cannot pick up a theme or a remote reference
that was never reviewed here.
