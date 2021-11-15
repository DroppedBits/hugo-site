---
title: "October 2021 Updates"
date: 2021-11-15T12:00:00-05:00
draft: false
aliases: []
description: "It's the 15th of November, and you know what that means — a monthly update on how things are going at Dropped Bits HQ!"
type: "news"
layout: "blog"
---

It's the 15th of November, and you know what that means — a monthly update on how things are going at Dropped Bits HQ!

October is always an interesting month, at least here in Montreal. The city feels like it's got one foot in summer, and the other in winter; there's a sort-of-refusal to accept that the heat and daylight we've been enjoying since late May is winding down, and at the same time some excitement kicking off preparation for the first snow and the holidays.

I like preparation work. I bought a new parka, so that I can continue my walks by the lake in the depths of winter. I ordered a planner for 2022, so that I can keep on top of things. And I dug a bit deeper into getting things ready for the launch of [Per][persite] 2.0, too.

Writing the code is such a small part of launching an app. I have to rewrite the marketing page, and work on the App Store product page. I have to figure out what's going to be free in the app, and what will require an in-app purchase. I have to figure out what kind of analytics and crash reporting I want to integrate. I have press kits to assemble and tech journalists to email.

All of this while I also try to write the app itself, maintain [Thought Detox][tdsite], keep on top of the business' bookkeeping, &cet. — it's a lot, but I enjoy it.

## October In Review

There's still a fair bit of design work to be completed for Per, but there's also been some progress on the app rewrite.

I also got access to Apple's [Xcode Cloud][xcc] beta at the end of October. This allows me to automate a lot of things while I work, including running tests and releasing new versions of Per to beta testers.

Here's what the download numbers looked like for October:

- Per: 3 downloads (last month: 3)
- Thought Detox: 3 downloads (last month: 0)

Revenues and proceeds on sales are estimates based on the information I get from Apple, in US dollars.

- App Sales (what customers paid Apple): USD$9.23
- App Proceeds (what Apple pays me): USD$7.59

That's not a whole lot of money, but it's better than the zero dollars in revenues that came in last month!

## App Updates

### Thought Detox

Given the focus on Per, there were no updates to Thought Detox in October. I've been thinking about the low sales figures, and so I'm experimenting with a price drop: since November 5<sup>th</sup>, the price of Thought Detox was dropped from USD$2.99 to USD$1.99! I may bump that back up, maybe even above the original price, when I finish work on the iPad and/or Mac app. So if you haven't yet gotten the app, lock in the lower price now by [buying it on the App Store][tdappstore].

### Per

I've decided to integrate (privacy-focused) analytics into the app, which will anonymously determine things like what features people tend to use, what kinds of errors they might run into, and so on. The service I've settled on is [TelemetryDeck][analytics], because it's run by a small independent team of two whose data-privacy values align with mine. It's still in beta, but I'm excited to see it grow.

As I mentioned last month, Per 2 will be a free update for everyone. It will be [free to download on the App Store][perappstore] with a bunch of new features, some of which will require an in-app purchase to unlock.

## One More Thing

As I mentioned last month, I'm making some minor changes and fixes to the Dropped Bits website. Don't hesitate to [reach out][dbcontact] if something seems to be broken!

<!--references-->
[persite]: https://droppedbits.com/per?utm_campaign=202111update&utm_source=dbblog&utm_medium=referral
[tdsite]: https://thoughtdetox.app/?utm_campaign=202111update&utm_source=dbblog&utm_medium=referral
[perappstore]: https://apps.apple.com/app/apple-store/id922693504?pt=973725&ct=dbblog&mt=8
[tdappstore]: https://apps.apple.com/app/apple-store/id1534491093?pt=973725&ct=dbblog&mt=8
[xcc]: https://developer.apple.com/xcode-cloud/
[analytics]: https://telemetrydeck.com
[dbcontact]: https://droppedbits.com/contact-us?utm_campaign=202111update&utm_source=dbblog&utm_medium=referral