<img src="https://files.mdwalters.ml/feedsbot.svg" width="200" height="200"></span>
# FeedsBot
FeedsBot lets you subscribe to RSS and Atom feeds on Meower!
## Functions
- Subscribe to feeds ([RSS Feed](https://www.rssboard.org/rss-specification), [Atom Feed](https://datatracker.ietf.org/doc/html/rfc5023), [JSON Feed](https://www.jsonfeed.org/version/1.1/))
- Recieve notifications when a new entry is published
- Unsubscribe from feeds
## Commands
### help
Shows a list of commands
```
@FeedsBot help
```
### subscribe
Subscribes to a feed
```
@FeedsBot subscribe [feed url]
```
### unsubscribe
Unsubscribes from a feed
```
@FeedsBot unsubscribe [feed url]
```
## Running
```bash
FB_USERNAME="[username here]"
FB_PASSWORD="[password here]"
npm install
npm run start
```
