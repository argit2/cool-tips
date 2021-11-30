# cool-tips
Repository where I compile genuine tips I have to give

- 2021/02/17 vivaldi has very low ram consumption and is very performant. 10 youtube tabs use around 1.3gb of ram. it's also a very customizable browser with lots of features, such as tab stacks, and it supports chrome extensions.
- 2021/02/17 github files and gists can be modified right in the browser. very useful when your repository consists of only a readme (such as this one) or is a single script.
- 2021/02/17 adblockers such as ublock origin allow you to make your own rules to omit elements from a page. the syntax is a extended version of css selectors that allows you to filter elements based on the content (using text or regex), and to remove a specific parent element if the child matches.
  - syntax: `site1.com, site2.com #?# parent, child:-abp-contains(/keyword/)`
  - example: `youtube.com #?# ytd-rich-item-renderer, #video-title-link > .ytd-rich-grid-media.style-scope:-abp-contains(/hololive|reaction/)` will filter videos (ytd-rich-item-renderer) on youtube.com when their titles contains "hololive" or "reaction"
  - if you want to filter for multiple keywords, i recommend using regex `/keyword1|keyword2|keyword3/` instead of creating one filter per keyword, it's much more performant
- 2021/02/17 there are custom adblock filters online, such as in filterslists.com. keep in mind that some might break websites and some are too big and heavy to be useful
- 2021/02/17 if you are already used to programming, cheatsheets for new languages and libraries and areas can be much more useful than courses and tutorials. for example, cheatsheets on python, pandas library, data science.

- big torrent sites tend to offer rss feeds of the most recent torrents. sometimes, they offer rss feeds for your custom search. torrent apps can subscribe to those feeds and for example automatically download new episodes once they are out, all according to the keywords you choose. the torrents apps are smart enough to not download the same episode twice.
- not so known google search tricks
  - `after:2020`
  - `2015..2020`
  - or operator: `( chocolate | carrot ) cake`
  - wildcards: `easy * cake recipe` should find "easy chocolate cake recipe", "easy carrot cake recipe", "easy strawberry cake recipe" and so on
  - making google actually work: `site:reddit.com` (ps: when using this one, take care with bro science, conspiracies and misinformation)
  - remove pinterest results from serach: `-site:pinterest.com`
  - `related:github.com`

## chrome extensions

- 2021/02/17 [Relative Reddit](https://chrome.google.com/webstore/detail/relative-reddit/lkkanogkeefbgmcjihgjmcginkjamkfp): scores reddit comments relative to their parent comments. this makes threads muuuch more readable, easier to find the good content. a similar feature is available on Reddit Enhancement Suite.
- DeepSearch: ctrl+f with regex

## computer science youtube channels

- [carykh](https://www.youtube.com/user/carykh/videos)
- [Code Bullet](https://www.youtube.com/channel/UC0e3QhIYukixgh5VVpKHH9Q/videos)
- [CodeParade](https://www.youtube.com/channel/UCrv269YwJzuZL3dH5PCgxUw/videos)
- [Two Minutes Papers](https://www.youtube.com/channel/UCbfYPyITQ-7l4upoX8nvctg/videos)
- [Wolfgang's channel](https://www.youtube.com/channel/UCsnGwSIHyoYN0kiINAGUKxg/videos)
- [Primer](https://www.youtube.com/channel/UCKzJFdi57J53Vr_BkTfN3uQ/videos)
- [Randy](https://www.youtube.com/channel/UCUmLRMERmJrmUtgnbFfknAg)
- [Game Maker's Toolkit](https://www.youtube.com/user/McBacon1337/videos)
- [munimuni](https://www.youtube.com/watch?v=L4f6KGgX4xI)

## 

