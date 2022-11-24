# notion-cloudflare
Power a website with Notion + Cloudflare

Inspired by https://fruitionsite.com/

Had to rework it because it did not work properly (anymore).

What do have in mind for Cloudflare config:
1. Add a `A` DNS record proxied from your domain root to 192.0.2.0
2. Create a Worker route from yourdomain.xyz/* to your worker