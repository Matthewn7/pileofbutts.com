# [pileofbutts.com](https://pileofbutts.com)

<i>Sensitive information has been removed or replaced with "[removed]" because of security concerns.</i>

I've had quite a bit of interest in how this was setup... It's actually pretty simple:

* DNS is managed with [CloudFlare](https://www.cloudflare.com/).
* Hosted on an [OVH](https://www.ovh.com/) dedi in Quebec.
* Images, GIFs, WebMs etc are uploaded via SFTP using public-key auth with [ShareX](https://getsharex.com/).
* Images are served with [NGINX](https://www.nginx.com/)

I have provided a snippet from my NGINX conf, a DNS export (BIND format), and a JSON "export" of the page-rules used on CloudFlare.
