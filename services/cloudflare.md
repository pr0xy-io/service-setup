# ⛅ Cloudflare Service Guide

![pr0xy Banner](https://cdn.pr0xy.io/branding/pr0xy-github-banner.png)

Domains should have their nameservers routed to Cloudflare, providing additional benefits such as DNS hosting, DDoS protection, and other perks.

## Signing Up for Cloudflare

One can navigate to [cloudflare.com](https://www.cloudflare.com/) and `Sign up` in the upper right for an account. Once finished, it is advisable to share this organization with your developer. This can be done by going to `Manage Account` in the menu on the left-hand side, and clicking members. Then adding a member via the `Invite` button.

## Adding a Website to Cloudflare

Once logged in and an account has been selected, you can click `+ Add a site` to begin importing a website to Cloudflare. You'll start by entering the domain name, such as `pr0xy.io` and clicking `Continue`. The next page will instruct you which service to purchase, which we recommend the Cloudflare Pro plan to begin utilizing Cloudflare's benefits and ensuring maximum uptime for your site. Click `Continue` when it asks for additional DNS records, we will set those later once the nameservers have been updated. You'll be instructed to change the nameservers on your domain via your domain registrar (GoDaddy, Google, etc.). In your associated registrar, you'll set the nameservers to the following Cloudflare nameservers:

```
aliza.na.cloudflare.com
devin.ns.cloudflare.com
```

And then click `Done, check nameservers`. This may take some time. But once completed you'll be able to adjust the DNS records on your site, and enable various optimizations site wide.

## Adding pr0xy to Your Organizations Members

To give pr0xy access to your site, you'll want to add the pr0xy developer to your list of members. To do this, select `Manage Account` within the left menu of Cloudflare. Navigate to `Members` and select `Invite` to add a member via their email.
