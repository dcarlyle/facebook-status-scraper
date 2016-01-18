# Facebook Status Scraper
Scrapes/crawls/culls a Facebook handle's **statuses** as well as each status' **comments** and each comment's **replies**.

### Usage:

##### To crawl Facebook posts from ``leehsienloong`` starting from ``2015-09-01`` to ``2015-09-12``:
```bash
$ python FacebookStatusScraper.py -p leehsienloong -s 2015-09-01 -e 2015-09-12
```

##### In general:
```bash
$ python FacebookStatusScraper.py -p <facebook_id> -a <your fb app_id> -t <your fb app_secret> -s <start-date> -e <end-date> -S <use-simple-mode>
```

BTW, you should get your own ``app_id`` and ``app_secret`` from [https://developers.facebook.com/apps/](https://developers.facebook.com/apps/ "Facebook for Developers").

### Output:

##### The script outputs a CSV of the Facebook Handle (in the *output* folder).
- Check out [this sample output](https://github.com/jovianlin/facebook-status-scraper/blob/master/output/mokyingren_2016-01-14_120009_fb_page_feed.csv "mokyingren sample output") from the Facebook page of Mok Ying Ren \(``mokyingren``\). It is the "extended" scrape which contains (i) the comments to his posts and (ii) the replies to the comments (to his posts).
- Also, check out [this sample output](https://github.com/jovianlin/facebook-status-scraper/blob/master/output/TheStraitsTimes_ListOfStatusIDs_2016-01-14_115954_fb_page_feed.csv "TheStraitsTimes sample output") from the Facebook page of The Straits Times \(``TheStraitsTimes``\). 
 
### More Examples can be found from the ``.ipynb`` files:
- [Example 1](https://github.com/jovianlin/facebook-status-scraper/blob/master/examples/Example%201%20-%20Crawl%20Statuses%20Only%20(Simple%20Mode).ipynb)
- [Example 2](https://github.com/jovianlin/facebook-status-scraper/blob/master/examples/Example%202%20-%20Crawl%20Statuses%2C%20Comments%2C%20and%20Replies%20(Normal%20Mode).ipynb)
- [Example 3](https://github.com/jovianlin/facebook-status-scraper/blob/master/examples/Example%203%20-%20Crawl%20from%20a%20list%20of%20Status%20IDs.ipynb)


