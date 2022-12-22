```
 _       __               __         
| |     / /___ __________/ /__  ____ 
| | /| / / __ `/ ___/ __  / _ \/ __ \
| |/ |/ / /_/ / /  / /_/ /  __/ / / /
|__/|__/\__,_/_/   \__,_/\___/_/ /_/ 
```

Warden is a local development environment manager, specializing in PHP applications with special features for Magento, Laravel, Shopware, Symfony, and Wordpress.

# Install via Homebrew

```bash
brew install wardenenv/warden/warden
warden svc up
```

# Minimal Dependencies
<p>Requires only <a class="link" href="https://brew.sh" target="_blank">Homebrew</a>, <a href="https://docs.docker.com/install/" class="link" target="_blank">Docker</a>, and <a href="https://docs.docker.com/compose/install/" class="link" target="_blank">Docker Compose</a> to get started, and <a href="https://mutagen.io/" class="link" target="_blank">Mutagen</a> on macOS (for Magento 2 file sync).</p>

# Feature List
<ul class="list--indented">
    <li>Traefik for SSL termination and routing/proxying requests into the correct containers.</li>
    <li>Portainer for quick visibility into what's running inside the local Docker host.</li>
    <li>Dnsmasq to serve DNS responses for <code>.test</code> domains eliminating manual editing of <code>/etc/hosts</code></li>
    <li>An SSH tunnel for connecting from Sequel Pro or TablePlus into any one of multiple running database containers.</li>
    <li>Warden issued wildcard SSL certificates for running https on all local development domains.</li>
    <li>Full support for Magento 1, Magento 2, Laravel, and custom project environment configurations on macOS and Linux.</li>
</ul>

# Gold Sponsors
[![Sansec.io](https://warden.dev/img/sponsors/sansec.svg)](https://www.sansec.io/)

Support Warden Development on <a href="https://opencollective.com/warden" rel="me" class="link">OpenCollective</a> or <a href="https://github.com/sponsors/wardenenv" rel="me" class="link">Github Sponsors</a>

# Community

* <a href="https://phpc.social/@warden" rel="me">Fediverse</a>
* <a href="https://discord.gg/dckp5HZgcu" rel="me">Discord</a>
