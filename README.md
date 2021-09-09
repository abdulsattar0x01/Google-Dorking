
# Google-Dorking
## What is a web crawler? | How web spiders work

A web crawler, or spider, is a type of bot that is typically operated by search engines like Google and Bing. Their purpose is to index the content of websites all across the Internet so that those websites can appear in search engine results.

These crawlers discover content through various means. One being by pure discovery, where a URL is visited by the crawler and information regarding the content type of the website is returned to the search engine. In fact, there are lots of information modern crawlers scrape – but we will discuss how this is used later. Another method crawlers use to discover content is by following any and all URLs found from previously crawled websites. Much like a virus in the sense that it will want to traverse/spread to everything it can.

![4nrDDa0](https://user-images.githubusercontent.com/73302708/132658637-65ab27d3-63cf-465a-955c-ab4dde46f973.png)

In the diagram above, "mywebsite.com" has been scraped as having the keywords as “Apple” “Banana" and “Pear”. These keywords are stored in a dictionary by the crawler, who then returns these to the search engine i.e. Google. Because of this persistence, Google now knows that the domain “mywebsite.com” has the keywords “Apple", “Banana” and “Pear”. As only one website has been crawled, if a user was to search for “Apple”...“mywebsite.com” would appear. This would result in the same behaviour if the user was to search for “Banana”. As the indexed contents from the crawler report the domain as having “Banana”, it will be displayed to the user.

## What is a web crawler bot?

#### Answer the questions below

1. Name the key term of what a "Crawler" is used to do

