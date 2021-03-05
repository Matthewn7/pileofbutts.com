# [pileofbutts.com](https://pileofbutts.com)

I've had quite a bit of interest in how this was setup... It's pretty simple:

* DNS is managed with [CloudFlare](https://www.cloudflare.com/).
* Hosted on an [OVH](https://www.ovh.com/) dedi in Quebec.
* Images, GIFs, WebMs etc are uploaded via SFTP using public-key auth with [ShareX](https://getsharex.com/).
* Images are served with [NGINX](https://www.nginx.com/)
