# Top 100 most visited sites in the US for Whitelisting

This project provides a curated list of the Top 100 most visited websites in the US. This includes all domains that users may want to whitelist on their routers. The list is intended for those who prefer to block access to all websites except the ones they use the most. This can be useful for parental control, productivity, or minimalistic internet setups. Only primary domains are listed for simplicity.
This list was originally made to be used with [adblock-lean](https://github.com/lynxthecat/adblock-lean) but you are free to use it with whatever setup you have.

## Why Whitelist?

Whitelisting allows users to block all internet traffic except to specific domains. This enhances security by minimizing exposure to potentially harmful websites. By restricting access to only trusted domains, you reduce the risk of malware, phishing attacks, and other online threats. Furthermore, this approach promotes privacy, as it limits the data shared with less reputable sites. Not having access to every single website or IP address in the world can be beneficial, as it creates a more controlled and secure online environment, ultimately safeguarding sensitive information and maintaining user privacy.
This method can also improve focus, reduce distractions, and help manage screen time effectively.

## Domains
Google, Youtube, Amazon, TikTok, GitHub, Disney+, Netflix, Reddit, Twitter, WhatsApp, Facebook, Wikipedia, Instagram, Discord, Baidu, Yahoo, Zoom.us, Pinterest, Microsoft, Apple, LinkedIn, eBay, PayPal, Twitch, Adobe, Shopify, CNN, Telegram, ChatGPT, LinkedIn, Microsoft, Office, Weather.com, Quora, Fandom, Bing, DuckDuckGo, Live, Office, Microsoft Online, OpenWRT, Pi-hole, Temu, SoundCloud, Spotify, Steam, 4chan, Binance, Diply, Tumblr, ESPN, Walmart, Blogspot, Chase, IMDB, New York Times, Wikia (Fandom), Bank, of, America, WordPress, MSN, Wells Fargo, Best, Buy, Etsy, Target, Pandora, Breitbart, Yelp, Salesforce, Huffington, Post, Fox, News, Instructure, Dropbox, Stack Overflow, Washington, Post, Zillow, Giphy, AOL, Buzzfeed, Vice, USPS, Xfinity, Indeed, Weebly, UPS, Home Depot, Thesaurus.com, Macy's, Capital One, Groupon, Roblox, BBC, DeviantArt, Forbes, NFL, GoDaddy, Daily Mail, Kohl's, Vimeo, Quizlet, Western Journal, CNET, Stack Exchange, and Citi

## CDNs and APIs
Websites such as Cloudfront, Cloudflare, and googleapis.com will not be globally whitelisted due to their potential to host malicious software, advertisements, or other harmful content. Instead, each CDN server and googleapis domain will be added as a subdomain tailored to the specific requirements of individual websites, thereby enhancing overall security. For instance, there have been reports of storage.googleapis.com being exploited for malicious purposes. This project's approach prevents that.

## Contributing

If you think a domain should be added or removed from the list or if something isn't working properly, feel free to open an issue or submit a pull request with your suggestion.

## License

This project is licensed under the MIT License.
