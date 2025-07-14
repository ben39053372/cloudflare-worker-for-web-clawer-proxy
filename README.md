# cloudflare-worker-crawler-proxy

a simple script to deploy a express api proxy server to prevent IP block.

# setup 

1. setup and install wrangler cli: https://developers.cloudflare.com/workers/wrangler/install-and-update/
2. change worker name in wrangler.toml
3. run `npm run deploy`

# use case
I created 10 worker for my web crawler.
Before I use proxy, it only can call arround 50 times.
After, it can call arround 500 times without IP block.
Maybe can more than 500, I doesn't test it
