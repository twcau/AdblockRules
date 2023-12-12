# AdblockRules
This is where you'll find the AdBlock rules I use, and some of the rulesets I've created to deal with things other lists don't focus on.

# My lists

## Allow lists
- AppleEnterpriseList: https://raw.githubusercontent.com/twcau/AdblockRules/master/AppleEnterpriseList ([AdBlock Plus Subscription Link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ftwcau%2FAdblockRules%2Fmaster%2FAppleEnterpriseList&amp;title=AppleEnterpriseList))
- Microsoft Allowed Domains: https://raw.githubusercontent.com/twcau/AdblockRules/master/MicrosoftAllowed ([AdBlock Plus Subscription Link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ftwcau%2FAdblockRules%2Fmaster%MicrosoftAllowed&amp;title=MicrosoftAllowed))

## Block lists
- MurdochList (blocks all websites affiliated with the Murdoch empire): https://raw.githubusercontent.com/twcau/AdblockRules/master/MurdochList ([AdBlock Plus Subscription Link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ftwcau%2FAdblockRules%2Fmaster%2FMurdochList&amp;title=MurdochList))
- CustomSonyTVList (stops unnecessary traffic from Smart TV's dead in their tracks): https://raw.githubusercontent.com/twcau/AdblockRules/master/CustomSonyTVList ([AdBlock Plus Subscription Link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ftwcau%2FAdblockRules%2Fmaster%2FCustomSonyTVList&amp;title=CustomSonyTVList))
- CytroxList (stops traffic associated with the surveillance-for-hire firm Cytrox and known related entities): https://raw.githubusercontent.com/twcau/AdblockRules/master/CytroxList ([AdBlock Plus Subscription Link](https://subscribe.adblockplus.org?location=https%3A%2F%2Fraw.githubusercontent.com%2Ftwcau%2FAdblockRules%2Fmaster%2FCytroxList&amp;title=CytroxList))


# Other useful lists

- [My list of lists](https://github.com/twcau/AdblockRules/blob/master/ListSources.MD) - Summary of the other lists I use for Adblocking

# How to use?

Add the web address of one or more lists as a subscription within your AdBlock client, and *shazam* - your internet experience will be that little more free of those things which abuse your privacy and suck up your data like greasy hors d'oeuvres.

# Never used AdBlock rules before?
- Explaination of AdBlock rules: https://help.getadblock.com/support/solutions/articles/6000066909-introduction-to-filter-lists

# Clients and applications that support AdBlock rules: 
Plugins are available for use with most modern web browsers, on both desktop and mobile devices:

- For desktops and laptops, I personally recommend and trust AdBlock Plus: https://adblockplus.org/
- For mobile devices (iOS, Android), AdGuard is my go-to: https://adguard.com/en/products.html
- For home networks: Pi-Hole (https://pi-hole.net/), or AdGuard Home (https://adguard.com/en/adguard-home/overview.html) to cover all devices on your home internet connection.

# Want to add something to the list?

If you know how to use Github, go forth and commit. 

And if you don't - send me a toot on Mastodon: https://mastodon.social/@twcau

# Tools used for maintaining lists

* [DeDupe Lists](http://www.textwidgets.com/dedupelist.html)
* [Rule redundancy checker](https://abpvn.com/ruleChecker/redundantRuleChecker.html)
* [Konbert large JSON to CSV converter](https://konbert.com/convert/json/to/csv)
* [Shodan](https://beta.shodan.io/) - To help identify affiliated websites of a company based on the information in their SSL certificates.
  Example: News Corp sites - (https://beta.shodan.io/search?query=ssl%3A"News+Corp") (Shodan subscription required)
