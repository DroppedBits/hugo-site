---
title: "Thinking About Syncing"
date: 2021-04-21T08:00:00-04:00
draft: false
aliases: []
description: "The journey to getting Thought Detox on all your devices continues."
type: "news"
layout: "blog"
---

I'm working towards the next major feature of [Thought Detox][tdsite]: making it available on the iPad and the Mac.

Well, sort of. That's more of the _end goal_ for the _actual_ next feature that I'm working on: adding another way for you to track your time writing in the app.

## Persistence

Right now, if you choose to track your writing time, the app does so by storing it as Mindful Minutes in the [Health app](https://www.apple.com/ios/health/) on your iPhone. That's a great solution, but it's _only_ available on iPhone — so I'm working on a second option for tracking this data.

(To be clear: that's the _only_ data the app stores: what time you started writing, and what time you pressed the Release button.)

The idea is this: add a very simple database that can store the same information. If you just want to track the time you spend in the app, it gets stored there. If you _also_ want to track that time as Mindful Minutes, the app will continue to do that on iPhone.

For the iPad or Mac app, you'd just have that database to track the time spent in the app — done!

## Syncing

Well, mostly done. This adds a way to track the time you spend writing without relying on an iPhone-only feature, so I can then move ahead with stand-alone iPad and Mac apps.

But there's an expectation of modern multiplatform apps: if you do something on one device, you expect to see that reflected on all your other devices. So that's the next piece of the puzzle: syncing that data between your iPhone, iPad, and Mac.

To do that, I'll be using [Apple's iCloud service][icloud] — your data stays private, visible only to you, on your own devices. But otherwise, when you release a thought on your iPhone, you should see the session tracker update on your iPad and Mac pretty much instantly.

## The Concerns

The first concern, of course, is making sure data syncs across your devices the way it's supposed to. One of the reasons this matters is to keep the database in sync with the data in Apple Health, if that's enabled.

There's more to that question, too. How much automation should there be between matching data between the synced database and Apple Health? What happens if you change your mind between wanting to use one or the other? There are a few user flows that I need to think about.

I also need to redesign the onboarding and settings sheets in the app. The former is fairly straightforward, since you only see it on first launch, but the latter is already getting a bit overloaded — it shows the last seven days of your usage, ways to get in touch with me, and various preferences. I think it's time to simplify this, and probably even move the usage stats to a separate area of the app.

## Onwards and Upwards

So that's the goal, and the plan to get there! For more on what I'm working on with Thought Detox, or to add your own suggestions, check out [the roadmap][roadmap].

Sound interesting? Get the app here:

<br>
<a href="https://apps.apple.com/us/app/thought-detox/id1534491093/"><img src="https://droppedbits.com/images/appstore-black.svg" alt="Download Thought Detox on the App Store" width="120px" style="display: block; margin: 0 auto; width: 120px;" /></a>
<br>

<!--references-->
[tdsite]: https://thoughtdetox.app/
[healthapp]: https://www.apple.com/ios/health/
[icloud]: https://www.apple.com/icloud/
[tdroadmap]: https://thoughtdetox.app/roadmap