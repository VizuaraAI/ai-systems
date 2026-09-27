# Vizuara AI Systems Guest Series

Teach what you’re working on. A guest series on inference engineering, GPU kernels, chip design, and parallelism, explained from first principles.

This repository contains only the public landing page. Booking is handled by the three live Calendly event types. Speaker research and contact data are not part of this repository.

## Hosting

Free GitHub Pages, main branch, repository root. Intended URL: https://vizuaraai.github.io/ai-systems/

Local preview: `python3 -m http.server 4174 --bind 127.0.0.1`

The HTML and CSS are build-free. Assets use relative paths, so the page works both under a GitHub Pages project path and on a future custom domain. Update canonical and Open Graph URLs when moving domains.

## Future custom domain

Suggested address: speakers.vizuara.ai. Configure the domain in GitHub Pages and add the corresponding DNS record only once the domain administrator can make and verify those changes. There is deliberately no CNAME file before DNS is ready.

## Domain connection when DNS access is restored

1. In this repository’s Pages settings, set the custom domain to `speakers.vizuara.ai`.
2. In the DNS provider, add a CNAME record named `speakers`, with target `vizuaraai.github.io` (no repository path). Use DNS-only mode initially if Cloudflare is the provider.
3. Verify the domain as directed by GitHub, wait for its DNS check and certificate, then enforce HTTPS.
4. Update canonical/Open Graph URLs and the invitation link to the custom domain after it resolves successfully.

These domain steps have not been applied. The free GitHub Pages URL remains the launch URL.
