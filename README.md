<p align="center">
  <a href="https://pi-hole.net/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_darkmode.png">
      <source media="(prefers-color-scheme: light)" srcset="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png">
      <img src="https://pi-hole.github.io/graphics/Vortex/Vortex_Vertical_wordmark_lightmode.png" width="168" height="270" alt="Pi-hole website">
    </picture>
  </a>
  <br>
  <strong>Network-wide ad blocking via your own Linux hardware</strong>
  <br>
  <br>
  <a href="https://pi-hole.net/">
    <img src="https://pi-hole.github.io/graphics/Screenshots/pihole_dashboard_v5.png" alt="Pi-hole Web interface">
  </a>
</p>

Pi-hole[®](https://pi-hole.net/trademark-rules-and-brand-guidelines/)'s Web interface (based off of [AdminLTE](https://github.com/ColorlibHQ/AdminLTE)) provides a central location to manage your Pi-hole and review the statistics generated by FTLDNS[™](https://pi-hole.net/trademark-rules-and-brand-guidelines/).

- **Easy-to-interpret**: simple graphs and beautiful colors make Pi-hole's stats easy to understand
- **Responsive**: looks great on desktop, tablets, and mobile devices
- **Useful**: control and configure your Pi-hole with our settings
- **Insightful**: use the query log, audit log, or long-term stats to gain insight into your networks activity

---

<img src="https://pi-hole.github.io/graphics/Badges/browserstack-badge.png" height="80"><br>

# Installation

The Web interface is enabled by default when you install Pi-hole.

## Post-installation: access the Web interface and gain insight into your network's activity

There are several ways to [access the dashboard](https://discourse.pi-hole.net/t/how-do-i-access-pi-holes-dashboard-admin-interface/3168):

1. `http://<IP_ADDRESS_OF_YOUR_PI_HOLE>/admin/`
2. `http://pi.hole/admin/` (when using Pi-hole as your DNS server)
3. `http://pi.hole/` (when using Pi-hole as your DNS server)

Once logged in (forgot your password?), you can view your network stats to see things like:

- the domains being queried on your network
- the time the queries were initiated
- the amount of domains that were blocked
- the upstream server queries were sent to
- the type of queries (`A`, `AAAA`, `CNAME`, `SRV`, `TXT`, etc.)

---

## Pi-hole is free, but powered by your support

There are many reoccurring costs involved with maintaining free, open source, and privacy-respecting software; expenses which [our volunteer developers](https://github.com/orgs/pi-hole/people) pitch in to cover out-of-pocket. This is just one example of how strongly we feel about our software, as well as the importance of keeping it maintained.

Make no mistake: **your support is absolutely vital to help keep us innovating!**

### Donations

Sending a donation using our links below is **extremely helpful** in offsetting a portion of our monthly expenses:

- <img src="https://pi-hole.github.io/graphics/Badges/paypal-badge-black.svg" width="24" height="24" alt="PP"> [Donate via PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3J2L3Z4DHW9UY)
- <img src="https://pi-hole.github.io/graphics/Badges/bitcoin-badge-black.svg" width="24" height="24" alt="BTC"> [Bitcoin, Bitcoin Cash, Ethereum, Litecoin](https://commerce.coinbase.com/checkout/dd304d04-f324-4a77-931b-0db61c77a41b)

### Alternative support

If you'd rather not [donate](https://pi-hole.net/donate/) (_which is okay!_), there are other ways you can help support us:

- [Patreon](https://patreon.com/pihole) _Become a patron for rewards_
- [Digital Ocean](https://www.digitalocean.com/?refcode=344d234950e1) _affiliate link_
- [Stickermule](https://www.stickermule.com/unlock?ref_id=6055890701&utm_medium=link&utm_source=invite) _earn a \$10 credit after your first purchase_
- [Pi-hole Swag Store](https://pi-hole.net/shop/) _affiliate link_
- [Amazon](https://www.amazon.com/exec/obidos/redirect-home/pihole09-20) _affiliate link_
- [DNS Made Easy](https://cp.dnsmadeeasy.com/u/133706) _affiliate link_
- Spreading the word about our software, and how you have benefited from it

### Contributing via GitHub

We welcome _everyone_ to contribute to issue reports, suggest new features, and create pull requests.

If you have something to add - anything from a typo through to a whole new feature - we're happy to check it out! Just make sure to fill out our template when submitting your request; the questions that it asks will help the volunteers quickly understand what you're aiming to achieve.

### Presentations about Pi-hole

Word-of-mouth continues to help our project grow immensely, and so we are helping make this easier for people.

If you are going to be presenting Pi-hole at a conference, meetup or even a school project, [get in touch with us](https://pi-hole.net/2017/05/17/giving-a-presentation-on-pi-hole-contact-us-first-for-some-goodies-and-support/) so we can hook you up with free swag to hand out to your audience!

---

## Getting in touch with us

While we are primarily reachable on our <a href="https://discourse.pi-hole.net/">Discourse User Forum</a>, we can also be found on a variety of social media outlets. **Please be sure to check the FAQ's** before starting a new discussion, as we do not have the spare time to reply to every request for assistance.

* **[Frequently Asked Questions](https://discourse.pi-hole.net/c/faqs)**
* **[Pi-hole Wiki](https://github.com/pi-hole/pi-hole/wiki)**
* **[Feature Requests](https://discourse.pi-hole.net/c/feature-requests?order=votes)**
* [Discourse User Forum](https://discourse.pi-hole.net/)
* [Reddit](https://www.reddit.com/r/pihole/)
* [Twitter](https://twitter.com/The_Pi_Hole)
* [Facebook](https://www.facebook.com/ThePiHole/)
* [Gitter](https://gitter.im/pi-hole/pi-hole) (Real-time chat)
* [YouTube](https://www.youtube.com/channel/UCT5kq9w0wSjogzJb81C9U0w)

# Features

## Mobile friendly interface

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/mobile-friendly.png" height="300" alt="Mobile friendly">
</p>

## Password protection

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/password_protection_v5.png" alt="Password protection">
</p>

## Detailed graphs and doughnut charts

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/piecharts.png" alt="Pie charts">
</p>

## Top lists of domains and clients

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/topdomains-clients.png" alt="Top domains/top clients">
</p>

## A filterable and sortable query log

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/query-log-sorted.png" alt="Query log">
</p>

## Long-term statistics to view data over user defined time ranges

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/long-term-stats.png" alt="Long-term stats">
</p>

## A built-in debugger

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/debug.png" alt="Debugger">
</p>

## Black and white lists

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/blacklist.png" alt="Blacklist">
  <br><br>
  <img src="https://pi-hole.github.io/graphics/Screenshots/whitelist.png" alt="Whitelist">
</p>

## The ability to easily manage and configure Pi-hole features

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/dashboard-settings.gif" alt="Settings">
</p>

## ... and all the main features of the Command Line Interface!

<p align="center">
  <img src="https://pi-hole.github.io/graphics/Screenshots/pihole-t.png" alt="Tail the log">
  <br><br>
  <img src="https://pi-hole.github.io/graphics/Screenshots/pihole-q.png" alt="Query ad lists">
</p>

## API

Full usage available [here](https://discourse.pi-hole.net/t/pi-hole-api/1863). Can be accessed at `/admin/api.php`. With either no parameters or `/admin/api.php?summary` it returns the following JSON:

```json
{
  "domains_being_blocked":243038,
  "dns_queries_today":2385,
  "ads_blocked_today":414,
  "ads_percentage_today":17.35849,
  "unique_domains":429,
  "queries_forwarded":1537,
  "queries_cached":434,
  "clients_ever_seen":5,
  "unique_clients":5,
  "status":"enabled"
}
```

[There are many more parameters](https://discourse.pi-hole.net/t/pi-hole-api/1863), such as:

- `type & version`
- `summaryRaw`
- `summary`
- `overTimeData10mins`
- `topItems`
- `getQuerySources`
- `getForwardDestinations`
- `getQueryTypes`
- `getAllQueries`
- `enable`
- `disable`
- `recentBlocked`

Together with a token it is also possible to [enable and disable (also with a set timeout) blocking via the API](https://discourse.pi-hole.net/t/is-there-an-api-command-to-disable-ad-blocking/7693).

The API returns more information (in a slightly different format if `FTL` is running) - it supports a fall-back to the "old" PHP API if `FTL` is not running. Test the type and/or version of the API by using the parameter `type` and `version`.
