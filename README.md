# cf-qrcode

Bug reprodcution for https://github.com/soldair/node-qrcode/issues/376.

The library doesn't work on Cloudflare event with the compatibility flags in wrangler.toml:
`compatibility_flags = ["nodejs_compat_v2"]`

Steps to reproduce:

1. `npm i`
2. Run `npm start`
3. Go to `localhost:8787`
