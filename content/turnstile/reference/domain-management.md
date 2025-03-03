---
title: Domain management
pcx_content_type: reference
weight: 2
---

# Domain management

You must specify a list of domains when creating a widget. The widget can only be used on these domains and will not work on any other domains. You can use subdomains to restrict the widgets further.

The domain should not contain a scheme `http://` or `https://`, a port `443`, or a path `/`. 

Specifying a subdomain is optional.

For example, using the `www.example.com` value will allow widgets on the following domains:
* `www.example.com`
* `abc.www.example.com:8080`

but not on the following domains:
* `example.com`
* `dash.example.com`
* `cloudflare.com`

When the widget is embedded on a domain not listed, it will show an error message.

{{<Aside type="note">}}
Enterprise Bot Management customers can remove the domain validation requirement for a widget. For more information on this feature, contact your account team.
{{</Aside>}}
