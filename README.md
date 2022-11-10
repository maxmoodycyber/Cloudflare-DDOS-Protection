# Cloudflare-DDOS-Protection
Ways to protect your website via Cloudflare through ASN blocking, geoblocking and more.

It is recommended you at least follow the Geochallenge section and the Ratelimiting sections to give yourself some protection but if you want your site to be completely protected follow Geoblocking and ASN Blocking too.




ASN Blocking - Blocks common DDoSing ASNs. The drawback of this is there is a chance (the chance is low) of users accessing your website being blocked due to them using the same ASN as these DDoSing services.

Geoblocking - Blocks entire countries that are commonly used for DDoSing. This is supposed to be customized by you. Block countries you don't care about and unblock the ones you do care about. Obviously has drawbacks but the payoff is worth it in my opinion.

Geochallenge - Challenges users from specific countries. This is another one I recommend you customize to your liking but it won't outright block users so there isn't really many drawbacks to implementing it other than it being a bit annoying sometimes.

Ratelimiting - Blocks IP addresses that are spamming requests. This basically has no drawbacks unless you are protecting a website which needs users to spam requests so use this 100%!

[GEOCHALLENGE](https://github.com/maxmoodycyber/Cloudflare-DDOS-Protection/files/9983923/Geochallenge.txt)
[RATELIMITING](https://github.com/maxmoodycyber/Cloudflare-DDOS-Protection/files/9983924/Ratelimiting.txt)
[ASN BLOCKING](https://github.com/maxmoodycyber/Cloudflare-DDOS-Protection/files/9983925/Commonly.Attacking.ASNs.txt)
[GEOBLOCKING](https://github.com/maxmoodycyber/Cloudflare-DDOS-Protection/files/9983926/Geoblocking.txt)
