# Awesome Redirects [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> Routing a request from one URL to another.

<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Redirections">
    <img src="media/redirs-logo.png" alt="Awesome Redirects logo" width="150" height="150">
  </a>
</p>

## Contents

- [Managed Redirect Services](#managed-redirect-services)
- [CDN and Edge Redirects](#cdn-and-edge-redirects)
- [Hosting and Deployment Platforms](#hosting-and-deployment-platforms)
- [Web Servers and Reverse Proxies](#web-servers-and-reverse-proxies)
- [Open-Source Redirect and Link-Management Applications](#open-source-redirect-and-link-management-applications)
- [CMS and Ecommerce Redirect Tools](#cms-and-ecommerce-redirect-tools)
- [Testing, Auditing, and SEO Migration Tools](#testing-auditing-and-seo-migration-tools)
- [Guides](#guides)

## Managed Redirect Services

- [redirect.pizza](https://redirect.pizza/) - Managed domain redirect service with automatic HTTPS, analytics, APIs, and rule-based traffic steering.
- [redirection.io](https://redirection.io/) - Redirect management platform using an agent-based approach for applying rules on your infrastructure.
- [Urllo](https://www.urllo.com/) - Managed URL and domain redirect platform with bulk import, redirect checking, analytics, and API integrations.
- [Bitly](https://bitly.com/) - Link-management platform for branded short links, QR codes, analytics, and campaign tracking.
- [Rebrandly](https://www.rebrandly.com/) - Branded link platform for custom domains, link management, analytics, and team workflows.
- [Short.io](https://short.io/) - Branded URL shortener with custom domains, analytics, and API-driven link management.
- [BL.INK](https://www.bl.ink/) - Enterprise link-management platform with branded links, analytics, and campaign controls.
- [TinyURL](https://tinyurl.com/) - URL shortener for creating and managing short links, including branded-link options.
- [QuitURL](https://quiturl.com/) - Link-management platform combining branded short links, QR codes, bio pages, and analytics.

## CDN and Edge Redirects

- [Cloudflare](https://developers.cloudflare.com/rules/url-forwarding/) - Single and bulk redirect rules evaluated at Cloudflare's edge before requests reach the origin.
- [Amazon CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/lambda-at-the-edge.html) - Edge customization through Lambda@Edge, including generated HTTP redirect responses.
- [Fastly](https://www.fastly.com/documentation/guides/concepts/edge-state/) - Programmable edge delivery where redirect behavior can be implemented with VCL and edge logic.
- [Akamai](https://www.akamai.com/products/edge-redirector) - Edge Redirector capabilities for managing redirects at Akamai's edge network.

## Hosting and Deployment Platforms

- [Vercel](https://vercel.com/docs/routing/redirects) - Configuration redirects defined in framework configuration or `vercel.json`, including pattern and geolocation rules.
- [Netlify](https://docs.netlify.com/manage/routing/redirects/overview/) - Redirect and rewrite rules defined in `_redirects` or `netlify.toml`.
- [Cloudflare Pages](https://developers.cloudflare.com/pages/configuration/redirects/) - Redirect configuration for sites deployed on Cloudflare Pages.

## Web Servers and Reverse Proxies

- [NGINX](https://nginx.org/en/docs/http/ngx_http_rewrite_module.html) - Native `return` and `rewrite` directives for redirects, URI changes, and conditional routing.
- [Apache HTTP Server](https://httpd.apache.org/docs/2.4/mod/mod_alias.html) - `Redirect` and `RedirectMatch` for simple URL changes, with `mod_rewrite` for more complex rules.
- [Caddy](https://caddyserver.com/docs/caddyfile/directives/redir) - Caddyfile `redir` directive for simple and permanent redirects.
- [Traefik](https://doc.traefik.io/traefik/middlewares/http/redirectscheme/) - HTTP middleware for redirecting requests between schemes and entrypoints.
- [Redirect Recipes](https://github.com/redirhub/redirect-recipes#readme) - Configuration examples for Nginx, Apache, Cloudflare, Vercel, Netlify, and other redirect platforms, covering permanent redirects, regex rules, wildcard routing, geo-based routing, and query-parameter handling.

## Open-Source Redirect and Link-Management Applications

- [Shlink](https://shlink.io/) - Self-hosted URL shortener with custom domains, APIs, and link-management features.
- [YOURLS](https://yourls.org/) - Self-hosted URL shortener for creating and managing branded short links.
- [Kutt](https://github.com/thedevs-network/kutt) - Open-source, self-hostable URL shortener with analytics and custom domains.
- [Dub](https://github.com/dubinc/dub) - Open-source link-management platform with short links, analytics, and developer integrations.

## CMS and Ecommerce Redirect Tools

- [WordPress Redirection](https://redirection.me/) - WordPress plugin for managing redirects, monitoring 404 errors, and reducing redirect-chain problems.
- [Shopify](https://help.shopify.com/en/manual/promoting-marketing/seo/redirects) - Built-in URL redirect management for Shopify stores.
- [Drupal Redirect](https://www.drupal.org/project/redirect) - Drupal module for creating and managing redirects within a Drupal site.
- [Adobe Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-learn/foundation/administration/url-redirection) - Server-side and edge-level redirect options for AEM deployments.

## Testing, Auditing, and SEO Migration Tools

- [Screaming Frog SEO Spider](https://www.screamingfrog.co.uk/seo-spider/) - Website crawler for auditing redirect chains, loops, broken redirects, and migration behavior.
- [httpstatus.io](https://httpstatus.io/) - HTTP status and redirect-chain checker for inspecting response headers and destinations.
- [Google Search Console](https://search.google.com/search-console/about) - Search performance and indexing diagnostics useful for monitoring migration and redirect outcomes.
- [Redirect Path](https://redirectpath.com/) - Browser extension for viewing HTTP status codes and redirect paths while browsing.
- [Redirect Mapper](https://redirectmapper.com/) - Redirect-map generator for matching old and new URLs during website migrations.
- [FindRedirect](https://findredirect.com/) - Migration checker for validating redirects, 301 implementations, and broken destinations.
- [Redirect Tracer](https://redirecttrace.com/) - Redirect-chain and migration resource for tracing HTTP redirects and diagnosing implementation issues.
- [Redirect Checker](https://www.redirect-checker.org/) - Online checker for inspecting redirect responses, status codes, and destination URLs.

## Guides

- [MDN: Redirections in HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Redirections) - Reference on redirect status codes, permanent versus temporary semantics, and how browsers handle redirect chains and loops.
- [Google Search Central: Redirects and Google Search](https://developers.google.com/search/docs/crawling-indexing/301-redirects) - How Google treats server-side, meta refresh, and JavaScript redirects, and which to use for signal consolidation.
- [Google Search Central: Site Moves with URL Changes](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes) - Official procedure for migrating a site to new URLs while preserving search visibility.
- [Redirect Best Practices](https://github.com/redirhub/redirect-best-practices#readme) - Guide covering redirect type selection, SEO best practices, performance and edge architecture, open redirect security, and testing methodology.
- [Migration Checklists](https://github.com/redirhub/migration-checklists#readme) - Step-by-step migration guidance for preserving URL coverage, validating redirects, and avoiding SEO and traffic loss.

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.
