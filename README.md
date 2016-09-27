# [pileofbutts.com](https://pileofbutts.com)

<i>Sensitive information has been removed/replaced with "[removed]" because of security concerns.</i>

I've had quite a bit of interest in how this was setup... It's actually pretty simple:

* Domain was bought with [GoDaddy](https://godaddy.com/).
* DNS is managed with [CloudFlare](https://www.cloudflare.com/).
* Hosted on an [OVH](https://www.ovh.com/) dedi in Quebec.
* Images, GIFs, WebMs etc are uploaded via SFTP using public-key auth with [ShareX](https://getsharex.com/).
* Images are served with [NGINX](https://www.nginx.com/) over <i>HTTP only</i> ([CF](https://www.cloudflare.com/) handles HTTPS and the SSL cert)

I have also provided a snippet from my NGINX conf, DNS export (BIND format), and a JSON "export" of the page-rules used on CloudFlare.
