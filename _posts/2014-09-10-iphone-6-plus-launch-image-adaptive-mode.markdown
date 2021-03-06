---
layout: post
title: "How to Add a Launch Image for the iPhone 6 (Plus)"
category: ios
rank: top
excerpt: A quick guide on how to add a launch image in Xcode for the iPhone 6, 7, and 8.
---

Use the following steps to enable the new high resolution displays for iPhone 6 (and Plus). To get it to break out of the adaptive mode, you need to force it to use a high resolution Launch Image.

1. In Xcode, Click on your Assets file (Images.xcassets) in the left sidebar. It should open in the main pane.
2. In the left sidebar of the main pane (where `AppIcon`, `LaunchImage`, etc. are), right click
3. Select `New Launch Image`
4. Add your new launch images as normal. If you want something quick and easy to use, [Paul Haddad](https://twitter.com/tapbot_paul/status/509539689775517696) recommends taking a screenshot in the iPhone 6 simulator and using that, or [@_DavidSmith has created some default ones](https://twitter.com/_davidsmith/status/509500836293378048).
5. Change the `Launch Images Source` from your Target's settings.

Here's a screenshot of the main pane where you create a new launch image file.

![Screenshot of how to add a launch image for the iPhone 6 Plus to an existing project in xcode](http://i.imgur.com/DQAfJT7.png "Screenshot: Add an iPhone 6 Plus launch image in Xcode")