# cloudflare-workers-cors

[![ddns](https://img.shields.io/badge/LICENSE-BSD3%20Clause%20Liscense-brightgreen?style=flat-square)](https://raw.githubusercontent.com/fernvenue/cloudflare-workers-cors/master/LICENSE)

**Simple CORS reverse proxy on Cloudflare Workers.**

For more information about workers please visit [Cloudflare Workers](https://workers.cloudflare.com).


## For any resource

After enabled, just paste the link to the end of the address.

`https://...workers.dev/https://raw.githubusercontent.com/fernvenue/cloudflare-workers-cors/master/main.js`

Now you can access to the resources by Cloudflare Workers, even if you use the **IPv6-Only** network.

## For a single complete site

You can use `page.js` to reverse proxy a site completely and access it through Cloudflare Workers.

Can **NOT** be use to special actions such as login.
