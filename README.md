# Maxwell — root-hosted Zoho widgets

Served from the domain **root** (`https://trevor-maxwell-power.github.io/`) rather than a
project subpath. The Zoho widget SDK reports its own origin as `protocol//host/` and the
handshake is sensitive to being served from the root, which is how every working Zoho
widget we've seen is hosted.

Generated output — do not edit. Source: private `maxwell-tranche-widget` repo.
