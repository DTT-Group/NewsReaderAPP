# News Reader App

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
Tracks what music an individual listens to, and pairs them with others based on that music. Could be potentially used as a dating app, or just meeting new friends with similar music tastes.

### App Evaluation
- **Category:** News
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as tinder or other similar apps. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Analyzes users music choices, and connects them to other users with similar choices. The user can then decide to message this person and befriend them if wanted.
- **Market:** Any individual could choose to use this app, and to keep it a safe environment, people would be organized into subscriptions.
- **Habit:** This app could be used as often or unoften as the user wanted depending on how deep their social life is, and what exactly they're looking for.


## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to have access to the news
* User can sign up for a new account
* User can subscribe to news channels
* User can view Videos with audio of the current/past news
* User can get push notifications of when new news is received

**Optional Nice-to-have Stories**

* User can favorite specific news channels and order which ones will pop up first
* Most viewed news channel pops up first
* User can unsubscribe from a channel

### 2. Screen Archetypes



### 3. Navigation

**Tab Navigation** (Tab to Screen)

* News channel Selection
* Profile 
* Account info


**Flow Navigation** (Screen to Screen)

## Wireframes
<img src="file:///Users/dariusgroves/Downloads/1000x1332.jpeg.beb1a366acc34c0eac82810600c2bbf7.large.jpeg" width=800><br>

Schema

Models

Post

Property	Type	Description
objectId	String	unique id for the user post (default field)
author	Pointer to User	image author
image	File	image that user posts
caption	String	image caption by author
commentsCount	Number	number of comments that has been posted to an image
createdAt	DateTime	date when post is created (default field)

Networking

List of network requests by screen

Home Feed Screen

{
"status": "ok",
"totalResults": 3695,
-"articles": [
-{
-"source": {
"id": null,
"name": "Cointelegraph"
},
"author": "Cointelegraph By Felipe Erazo",
"title": "Layer1 co-founder takes former business partner to court",
"description": "He claims to have spent millions of his own money, only to be tossed out of the company he co-founded.",
"url": "https://cointelegraph.com/news/layer1-co-founder-takes-former-business-partner-to-court",
"urlToImage": "https://s3.cointelegraph.com/uploads/2020-11/6de34f08-b67f-46ac-bdc5-46be08a1ab10.jpg",
"publishedAt": "2020-11-03T22:30:00Z",
"content": "Jakov Dolic, co-founder of the U.S.-based Bitcoin (BTC) mining company Layer1, has filed a lawsuit against his former business partner, Alexander Liegl.\r\nAccording to court documents filed on October… [+1370 chars]"
},
-{
-"source": {
"id": null,
"name": "Lesswrong.com"
},
"author": "AnnaSalamon",
"title": "Where do (did?) stable, cooperative institutions come from?",
"description": "Published on November 3, 2020 10:14 PM GMTThe United States has a bunch of nice things whose creation/maintenance requires coordinated effort from a large number of people across time. For example: bridges that stay up; electrical grids that provide us with p…",
"url": "https://www.lesswrong.com/posts/R4FX6wDmppvZ2JqpB/where-do-did-stable-cooperative-institutions-come-from",
"urlToImage": "https://res.cloudinary.com/lesswrong-2-0/image/upload/v1503704344/sequencesgrid/h6vrwdypijqgsop7xwa0.jpg",
"publishedAt": "2020-11-03T22:14:09Z",
"content": "The United States has a bunch of nice things whose creation/maintenance requires coordinated effort from a large number of people across time. For example: bridges that stay up; electrical grids that… [+8055 chars]"
},
-{
-"source": {
"id": "techradar",
"name": "TechRadar"
},
"author": "Anthony Spadafora",
"title": "Bitcoin mining has suddenly become far more lucrative - but maybe not for long",
"description": "Bitcoin's mining difficulty has dropped as miners have moved their rigs out of Sichuan province following the end of its rainy season.",
"url": "https://www.techradar.com/news/bitcoin-mining-has-suddenly-become-far-more-lucrative-but-maybe-not-for-long",
"urlToImage": "https://cdn.mos.cms.futurecdn.net/oFZ3HfKaDyZphnPr2xHafj-1200-80.jpg",
"publishedAt": "2020-11-03T22:11:25Z",
"content": "Since the introduction of ASIC devices back in 2012, mining bitcoin has become increasingly challenging but the cryptocurrency has now experienced its biggest mining difficulty decrease since June.\r\n… [+1529 chars]"
},
-{
-"source": {
"id": null,
"name": "Cointelegraph"
},
"author": "Cointelegraph By Turner Wright",
"title": "South Korean financial watchdog to ban privacy coins",
"description": "The amendment to South Korea’s Special Payment Act — set to be enforced starting in March 2021 — would not allow VASPs to handle privacy coins like ZEC, XMR, and DASH.",
"url": "https://cointelegraph.com/news/south-korean-financial-watchdog-to-ban-privacy-coins",
"urlToImage": "https://s3.cointelegraph.com/uploads/2020-11/630c17f0-4d8b-4faf-9fdc-08b9731601d9.jpg",
"publishedAt": "2020-11-03T22:06:08Z",
"content": "According to a Nov. 3 announcement from South Koreas Financial Services Commission, or FSC, virtual asset service providers will no longer be able to handle any digital assets that present a high mon… [+1465 chars]"
},
-{
-"source": {
"id": null,
"name": "CoinDesk"
},
"author": "Brady Dale",
"title": "Uniswap’s Retroactive Airdrop Vote Put Free Money on the Campaign Trail",
"description": "Dharma's proposal to extend Uniswap's UNI airdrop to 12,619 wallets failed to pass. But the process spoke volumes.",
"url": "https://www.coindesk.com/uniswap-dharma-retroactive-uni-airdrop-defi-governance",
"urlToImage": "https://static.coindesk.com/wp-content/uploads/2020/11/VOTE-jennifer-griffin-xePUAbiilko-unsplash-1200x628.jpg",
"publishedAt": "2020-11-03T21:52:36Z",
"content": "Governance, it is often said, is one of the most important issues in the crypto industry. But whether democracy makes blockchain products better or just devolves into fights over wealth remains an op… [+19971 chars]"
},
-{
-"source": {
"id": null,
"name": "Zerohedge.com"
},
"author": "Tyler Durden",
"title": "Stocks' Surge Suggests Trump Win, Dollar Dives As Gold Thrives",
"description": "Stocks' Surge Suggests Trump Win, Dollar Dives As Gold Thrives\n\n Tyler Durden\n \nTue, 11/03/2020 - 16:01\n\n For the second day in a row, stocks soared with Small Caps leading the way (up over5% in 2 days) followed by The Dow (some weakness into the close)...\r\n\n…",
"url": "https://www.zerohedge.com/markets/stocks-surge-signals-trump-win-dollar-dives-gold-thrives",
"urlToImage": "https://zh-prod-1cc738ca-7d3b-4a72-b792-20bd8d8fa069.storage.googleapis.com/s3fs-public/styles/max_650x650/public/2020-11/download%20%2816%29.jpg?itok=viP47Szn",
"publishedAt": "2020-11-03T21:01:09Z",
"content": "For the second day in a row, stocks soared with Small Caps leading the way (up over5% in 2 days) followed by The Dow (some weakness into the close)...\r\nAs yet another short squeeze is unleashed...\r\nS… [+2157 chars]"
},
-{
-"source": {
"id": null,
"name": "Investmentwatchblog.com"
},
"author": "alexmark",
"title": "Central bank Digital Coins are to enforce negative interest-rates",
"description": null,
"url": "https://www.investmentwatchblog.com/central-bank-digital-coins-are-to-enforce-negative-interest-rates/",
"urlToImage": null,
"publishedAt": "2020-11-03T20:15:21Z",
"content": "by Shaun Richards\r\nThe weekend just gone produced quite a lot of news. Another lockdown in the UK is in the offing and there is of course the not so small matter of tomorrows US election. But somethi… [+7775 chars]"
},
-{
-"source": {
"id": null,
"name": "Gixtools.net"
},
"author": null,
"title": "Two Charged in SIM Swapping, Vishing Scams",
"description": "Prosecutors say Jordan K. Milleson , 21 of Timonium, Md. and 19-year-old Kingston, Pa. resident Kyell A. Bryan hijacked social media and bitcoin accounts using a mix of voice phishing or “vishing” attacks and “SIM swapping,” a form of fraud that involves brib…",
"url": "https://gixtools.net/2020/11/two-charged-in-sim-swapping-vishing-scams/",
"urlToImage": null,
"publishedAt": "2020-11-03T20:03:00Z",
"content": "Two young men from the eastern United States have been hit with identity theft and conspiracy charges for allegedly stealing bitcoin and social media accounts by tricking employees at wireless phone … [+3424 chars]"
},
-{
-"source": {
"id": null,
"name": "Cointelegraph"
},
"author": "Cointelegraph By Keith Wareing",
"title": "Can Bitcoin hit $17K next? Watch these 3 key BTC price levels",
"description": "Bitcoin dominance is climbing as altcoins search for a new bottom in what may be the perfect set up for a BTC rally to new all-time highs.",
"url": "https://cointelegraph.com/news/can-bitcoin-hit-17k-next-watch-these-3-key-btc-price-levels",
"urlToImage": "https://s3.cointelegraph.com/storage/uploads/view/898756fe2a4f11967dfd80f405b8a0b4.jpg",
"publishedAt": "2020-11-03T20:02:00Z",
"content": "Bitcoin (BTC) has been on a tear and theres no escaping it. But the majority of high-cap altcoins are seemingly suffering at the hands of this bull run, leading to the question: have we had our altse… [+5749 chars]"
},
-{
-"source": {
"id": null,
"name": "newsBTC"
},
"author": "Tony Spilotro",
"title": "Bitcoin Hash Ribbons Trigger Rare Bull Market Capitulation Signal",
"description": "An important fundamental health signal of the Bitcoin network just crossed into “capitulation” territory, which in the past was associated with downside risk. However, the tool’s creator says that it wasn’t designed to give sell signals, and shouldn’t be inte…",
"url": "https://www.newsbtc.com/analysis/btc/bitcoin-hash-ribbons-trigger-rare-bull-market-capitulation-signal/",
"urlToImage": "https://www.newsbtc.com/wp-content/uploads/2020/11/bitcoin-hash-ribbon-capitulation-selloff-rare-bull-market-Depositphotos_221374698_xl-2015-scaled.jpg",
"publishedAt": "2020-11-03T20:00:57Z",
"content": "An important fundamental health signal of the Bitcoin network just crossed into “capitulation” territory, which in the past was associated with downside risk. However, the tool’s creator says that it… [+4323 chars]"
},
-{
-"source": {
"id": null,
"name": "CoinDesk"
},
"author": "Nathaniel Whittemore",
"title": "A (Not Quite) Complete History of Money, Feat. Planet Money’s Jacob Goldstein",
"description": "One of the hosts of NPR’s legendary “Planet Money” takes us on a whirlwind tour of some of the key moments of money history in the last 1,000 years.",
"url": "https://www.coindesk.com/history-planet-money-jacob-goldstein",
"urlToImage": "https://static.coindesk.com/wp-content/uploads/2020/11/Breakdown-11.3-1200x628.jpg",
"publishedAt": "2020-11-03T20:00:27Z",
"content": "One of the hosts of NPRs legendary Planet Money takes us on a whirlwind tour of some of the key moments of money history in the last 1,000 years.\r\nFor more episodes and free early access before our r… [+1105 chars]"
},
-{
-"source": {
"id": null,
"name": "Bitcoinist"
},
"author": "Cole Petersen",
"title": "Analysts Expect Ethereum to Surge to $445 as Buy-Side Demand Builds",
"description": "Ethereum is moving higher today in tandem with Bitcoin after bearing witness to some intense selling pressure yesterday The cryptocurrency has primarily been consolidating as of late, with bulls and bears being unable to spark any clear trend This has caused …",
"url": "https://bitcoinist.com/analysts-expect-ethereum-to-surge-to-445-as-buy-side-demand-builds/",
"urlToImage": "https://bitcoinist.com/wp-content/uploads/2020/11/wladislaw-peljuchno-k1Go4ziImrc-unsplash-1920x1280.jpg",
"publishedAt": "2020-11-03T20:00:16Z",
"content": "<ul><li>Ethereum is moving higher today in tandem with Bitcoin after bearing witness to some intense selling pressure yesterday</li><li>The cryptocurrency has primarily been consolidating as of late,… [+2441 chars]"
},
-{
-"source": {
"id": null,
"name": "Letstalkbitcoin.com"
},
"author": "adam@letstalkbitcoin.com (The LTB Network), The LTB Network",
"title": "WBD269 - The Bitcoin Bull Bull Bull with Michael Saylor",
"description": "In August, MicroStrategy made the bold move of purchasing 21,454 Bitcoin to add to their treasury, spending $250 million. In doing so, CEO Michael Saylor stated that he views Bitcoin as a \"dependable store of value and an attractive investment asset with more…",
"url": "https://letstalkbitcoin.com/blog/post/wbd269-the-bitcoin-bull-bull-bull-with-michael-saylor?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+TheDailyBitcoinShow+%28Let%27s+Talk+Bitcoin+Network+Feed%29",
"urlToImage": "https://letstalkbitcoin.com/files/blogs/9017-05ddf65877814ca0d9d517858e3476ba889ad88635b7435d160179bafd5964a1.jpg",
"publishedAt": "2020-11-03T19:45:00Z",
"content": "Click to download audio version\r\n&lt;iframe style=\"border: none\" src=\"//html5-player.libsyn.com/embed/episode/id/16398503/height/360/theme/legacy/thumbnail/yes/direction/backward/\"; height=\"360\" widt… [+1156 chars]"
},
-{
-"source": {
"id": null,
"name": "CoinDesk"
},
"author": "Zack Voell",
"title": "DeFi Sell-Off Continues as Index Futures Retrace to June Levels",
"description": "DeFi indices on FTX and Binance continue to plummet",
"url": "https://www.coindesk.com/defi-futures-ftx-binance-crash",
"urlToImage": "https://static.coindesk.com/wp-content/uploads/2020/11/defi-perp1.png",
"publishedAt": "2020-11-03T19:21:17Z",
"content": "Index futures for decentralized finance (DeFi) continue to collapse, erasing all gains since late June, as the sector cools off following a wild summer of speculation. \r\nOn derivatives exchange FTX, … [+1802 chars]"
},
-{
-"source": {
"id": null,
"name": "Yahoo Entertainment"
},
"author": "Zack Voell",
"title": "DeFi Sell-Off Continues as Index Futures Retrace to June Levels",
"description": "DeFi indices on FTX and Binance continue to plummet.",
"url": "https://finance.yahoo.com/news/defi-sell-off-continues-index-192117670.html",
"urlToImage": "https://s.yimg.com/uu/api/res/1.2/954mOXaq3C._zHJ03EqMFA--~B/aD02MjM7dz05NTE7c209MTthcHBpZD15dGFjaHlvbg--/https://media.zenfs.com/en/coindesk_75/478940e3fc7b8fc659a80416b502c73c",
"publishedAt": "2020-11-03T19:21:17Z",
"content": "Index futures for decentralized finance (DeFi) continue to collapse, erasing all gains since late June, as the sector cools off following a wild summer of speculation. \r\nOn derivatives exchange FTX, … [+1950 chars]"
},
-{
-"source": {
"id": null,
"name": "Krebs on Security"
},
"author": "BrianKrebs",
"title": "Two Charged in SIM Swapping, Vishing Scams",
"description": "Two young men from the eastern United States have been hit with identity theft and conspiracy charges for allegedly stealing bitcoin and social media accounts by tricking employees at wireless phone companies into giving away credentials needed to remotely ac…",
"url": "https://krebsonsecurity.com/2020/11/two-charged-in-sim-swapping-vishing-scams/",
"urlToImage": "https://krebsonsecurity.com/wp-content/uploads/2018/09/phonescam.png",
"publishedAt": "2020-11-03T18:30:54Z",
"content": "Two young men from the eastern United States have been hit with identity theft and conspiracy charges for allegedly stealing bitcoin and social media accounts by tricking employees at wireless phone … [+3802 chars]"
},
-{
-"source": {
"id": null,
"name": "Bitcoinist"
},
"author": "Cole Petersen",
"title": "Traders Express Caution Regarding Bitcoin as Election Day Arrives",
"description": "Traders have long been looking towards election day as a potential catalyst for Bitcoin volatility that helps shapes the cryptocurrency’s future trend That day is now here, and BTC is actually seeing some positive price action so far this morning Bulls are in…",
"url": "https://bitcoinist.com/traders-express-caution-regarding-bitcoin-as-election-day-arrives/",
"urlToImage": "https://bitcoinist.com/wp-content/uploads/2020/11/element5-digital-T9CXBZLUvic-unsplash-1920x1280.jpg",
"publishedAt": "2020-11-03T18:00:19Z",
"content": "<ul><li>Traders have long been looking towards election day as a potential catalyst for Bitcoin volatility that helps shapes the cryptocurrencys future trend</li><li>That day is now here, and BTC is … [+2358 chars]"
},
-{
-"source": {
"id": null,
"name": "Bitcoin Magazine"
},
"author": "Tyler Bain",
"title": "How Do Seasonal Fluctuations Really Affect Bitcoin Mining?",
"description": "Bitcoin mining just experienced one of its largest difficulty adjustments ever. But what role did changes in China’s access to cheap energy play?\nThe post How Do Seasonal Fluctuations Really Affect Bitcoin Mining? appeared first on Bitcoin Magazine.",
"url": "https://bitcoinmagazine.com/articles/how-do-seasonal-fluctuations-really-affect-bitcoin-mining",
"urlToImage": "https://bitcoinmagazine.com/wp-content/uploads/2019/09/Project_-_Sketch_1_14-1200x630-cropped.jpg",
"publishedAt": "2020-11-03T17:59:20Z",
"content": "There has been much ado made recently over supposed seasonal mining fluctuations on the Bitcoin network. \r\nThe narrative goes that, as the rainy season in China comes to a halt around the August to O… [+9580 chars]"
},
-{
-"source": {
"id": null,
"name": "Tech.co"
},
"author": "Jack Turner",
"title": "Bitdefender Warns of Zoom Sextortion Scam",
"description": "A new scam has appeared, threatening to blackmail Zoom users - we explain how it works, and why it's nothing to worry about\nThe post Bitdefender Warns of Zoom Sextortion Scam appeared first on Tech.co.",
"url": "https://tech.co/news/zoom-sextortion-scam",
"urlToImage": "https://images.tech.co/wp-content/uploads/2020/11/03110543/zoomscam-1.jpg",
"publishedAt": "2020-11-03T17:40:31Z",
"content": "The global pandemic has had devastating effects on many companies this year. But for one, video-messaging service Zoom, it's been nothing short of a springboard to worldwide recognition.\r\nOf course, … [+1750 chars]"
},
-{
-"source": {
"id": null,
"name": "Malwarebytes.com"
},
"author": "Malwarebytes Labs",
"title": "Maze ransomware gang announces retirement",
"description": "<table>\n<tr>\n<td></td>\n</tr>\n<tr>\n<td>On November 1, the cybercriminals behind Maze ransomware announced their retirement. Is this a reason to go all out and celebrate? We're afraid not.\r\n\nCategories: \r\n\n<ul>\n<li>Ransomware</li>\n</ul>\nTags: egregorMazeransom.…",
"url": "https://blog.malwarebytes.com/ransomware/2020/11/maze-ransomware-gang-announces-retirement/",
"urlToImage": "https://blog.malwarebytes.com/wp-content/uploads/2020/05/Maze_ransom.jpg",
"publishedAt": "2020-11-03T17:38:45Z",
"content": "The threat actors behind Maze ransomware have announced their retirement. On November 1, they posted the retirement announcement on the website where they would normally name and shame their victims … [+2735 chars]"
}
]
}
  
Profile Screen
(Read/GET) Query logged in user object
(Update/PUT) Update user profile image  
  
An API Of News

Base URL - https://newsapi.org

HTTP Verb	Endpoint	Description
GET	/news	get all news
GET	/news/?name=name	return specific character by name
