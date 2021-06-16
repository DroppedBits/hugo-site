---
title: "A Short Update"
date: 2021-06-16T06:00:00-04:00
draft: false
aliases: []
description: "We're nearly halfway through the year, and Apple's World Wide Developer Conference (WWDC, or \"Dub Dub\" for those in the know) has come and gone."
type: "news"
layout: "blog"
---

We're nearly halfway through the year, and Apple's World Wide Developer Conference (WWDC, or "Dub Dub" for those in the know) has come and gone. It's a special time of year for iOS and Mac developers, where new features of the platform are announced, along with ways to build for them. There's always more there than I can consume during the week that the conference runs, but I'm slowly catching up, and I'm really excited to see what's coming to iOS 15 and macOS 12.

Often, these new features aren't available to older versions of iOS and macOS. It may not be a feature that is visible to people _using_ the device, either, but rather a feature of the [Swift programming language][swift] that makes our code more reliable or performant.

This year, I released [Thought Detox][tdsite], written in [SwiftUI][swiftui]. For the way I think about apps, SwiftUI lets me build things faster, but as it's new, there were quite a few rough edges that needed special care. For iOS 15 and macOS 12, many new features are being added, and that will make building with SwiftUI even better—but much of that will be iOS 15 _only_.

I've also started working with a UX designer to (finally, for real) update [Per][per]. The current version hasn't been updated since iOS 9 was released nearly six years ago, so it's long overdue. Being able to focus the update only on iOS 15 and macOS 12 will make it much faster to build the update across iOS and the Mac.

Trying to support older versions is a huge undertaking for a single developer like me, so to help me understand how you approach upgrades, it'd be a huge help if you [filled out this 2-question survey][survey]!

## One More Thing

Just a quick update here: a lot of the trickiest parts of building Thought Detox —namely, the animations— are working fairly well on iPad already:

{{< tweet 1404061046575357959 >}} 

The bulk of the work right now is building a solution for you to be able to track your time spent writing on iPad and the Mac, but it's coming along!

<br>
<a href="https://apps.apple.com/us/app/thought-detox/id1534491093/"><img src="https://droppedbits.com/images/appstore-black.svg" alt="Download Thought Detox on the App Store" width="120px" style="display: block; margin: 0 auto; width: 120px;" /></a>
<br>

<!--references-->
[swift]: https://swift.org/
[swiftui]: https://developer.apple.com/documentation/swiftui
[tdsite]: https://thoughtdetox.app/
[per]: https://droppedbits.com/apps/per
[survey]: https://docs.google.com/forms/d/1_-aieBHTIrQzJ7XaR1eKhWM4cDRbLQJozX1EoIpXE68