# Shopify-Scraper
A web crawler that monitors multiple shopify based websites in real time for new products &amp; restocks. 

Important
- Must use proxies if monitiring multiple websites to avoid bans
- Make sure shopify websites /products.json isn't blocked
- Set proxies, discord webhook, & websites into the specified txt files

Required Modules
- requests
- Json
- threading
- random
- time
- datetime
- dhooks

To run with Docker run the following commands:
- cd into the main scraper directory
- run `docker build -t shopify:1.0 .`
- run  `docker run -it --rm --name shopify-scraper shopify:1.0`
- any new requirements can be added to requirements.txt