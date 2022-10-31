# Web Scraping
## is  task that has to be performed responsibly so that it does not have a detrimental effect on the sites being scraped

### easy giveaways that you are bot/scraper/crawler:
- Scraping too fast and too many pages, faster than a human ever can
- Following the same pattern while crawling. For example – go through all pages of search results, and go to each result only after grabbing links to them. No human ever does that.
- Too many requests from the same IP address in a very short time
- Not identifying as a popular browser. You can do this by specifying a ‘User-Agent’.
- using a user agent string of a very old browser

## Make requests through Proxies and rotate them as needed
### When scraping, your IP address can be seen. A site will know what you are doing and if you are collecting data. They could take data such as – user patterns or experience if they are first-time users.
### Multiple requests coming from the same IP will lead you to get blocked, which is why we need to use multiple addresses. When we send requests from a proxy machine, the target website will not know where the original IP is from, making the detection harder.
### Create a pool of IPs that you can use and use random ones for each request. Along with this, you have to spread a handful of requests across multiple IPs
### There are several methods that can change your outgoing IP:
- TOR
- VPNs
- Free Proxies
- Shared Proxies – the least expensive proxies shared by many users. The chances of getting blocked are high
- Private Proxies – usually used only by you, and lower chances of getting blocked if you keep the frequency low
- Data Center Proxies, if you need a large number of IP Addresses and faster proxies, larger pools of IPs. They are cheaper than residential proxies and could be detected easily
- Residential Proxies, if you are making a huge number of requests to websites that block to actively. These are very expensive (and could be slower, as they are real devices). Try everything else before getting a residential proxy

