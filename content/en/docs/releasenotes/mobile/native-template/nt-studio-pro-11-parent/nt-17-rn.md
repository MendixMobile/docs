---
title: "Native Template 17"
url: /releasenotes/mobile/nt-17-rn/
weight: 8
description: "Native Template 17"
---

## 19.0.0

**Release date: Apr 20, 2026**

- We upgraded the core stack to React Native `0.83.4` and aligned related React dependencies.
- We upgraded multiple React Native ecosystem dependencies for compatibility and stability (including CLI, navigation, animation, media, and platform modules).
- We migrated from `react-native-vector-icons` to the scoped `@react-native-vector-icons/*` package set.
- We updated `.gitignore` to more precisely exclude `node_modules` directories in specific locations.
- We added a new dependency for `@shopify/flash-list` to support the migration from FlatList to FlashList.
- We upgraded `react-native-tab-view` from 3.5.2 to 4.3.0.
- Fix the iOS builds crashing when building with Xcode 26.

## 17.0.2 {#1702}

**Release date: January 12, 2026**

### Improvements

* We updated `mendix-native` to v0.3.1, enabling session cookie persistence and restoration on iOS.

## 17.0.1 {#1701}

**Release date: December 24, 2025**

### Improvements

* We changed `NSAppTransportSecurity` in **production** versions of projects to false. For **dev** testing, we added **Info-dev.plist**.

## 17.0.0 {#1700}

**Release date: December 22, 2025**

### Improvements

* We updated the native-template for compatibility with React v19 and React Native v0.78. This brings performance, stability improvements, and new features.
* We updated the version of mendix-native to v0.3.0 to fix iOS native file system issue.
* We improved the styling when edge-to-edge mode is enabled.
