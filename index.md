---
layout: default
title: "Blog"
---


My name is Matt. I'm a full-stack startup developer based in Winnipeg.

---

## Journey to
#### **Commit HOP Demo**

Whether you're working on a tight budget or have made the decision to hone in an [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product),
you're going to face the challenge of cutting back scope, often with dramatic effect.

The technical challenge of cutting back scope is to create an **extensive solution** that leaves room for **growth without
friction**. With this, you can timeline growth into the dream scope and that is a powerful tool for generating
buy-in on your cuts.

One of these pieces that often gets cut is support for a first-class experience in both desktop and mobile. This is
especially true if mobile needs to have a solid experience with a native implementation.

Before exploring React Native, my solution here was to create a React boilerplate that sits on top of a hybrid mobile
ecosystem. This, combined with responsive layout design using [Material UI](https://mui.com), allowed me to promise a
swift path to first-class experience in the environment that had fallen to second-class priority.

For mobile-first it is:

> The functionality is there, all we need to do is comb through the experience and create larger layouts.

For desktop-first:

> We just have to wrangle with the App Store release processes and we'll be on our customers' phones.

The gap left here is that Hybrid Mobile is second-class in itself. Of all the downsides, animation performance stands
out to me the most.

#### Question: Can React Native provide frictionless growth into cross-platform experiences, as a Hybrid wrapper does?

[Commit](https://commit.dev) has given me the opportunity through the HOP (Hackathon Onboarding Project) to work with
Expo and React Native to see if I can replicate my approach here for frictionless growth into first-class cross-platform
experiences.

While I was upset to see Material UI is not supported, there are [alternatives](https://reactnativeelements.com/),
[[2]](https://akveo.github.io/react-native-ui-kitten/), [[3]](https://reactnativepaper.com/). Surprisingly though, none of
these provided the responsive layout foundation that MUI does,
[Container](https://mui.com/material-ui/react-container/#main-content) and
[Grid](https://mui.com/material-ui/react-grid/#main-content).

For this, I decided to build [react-native-responsive-layout](https://www.npmjs.com/package/@sklink/react-native-responsive-layout)
as a way to learn about any barriers to my cross-platform design aspirations.

#### Can React Native replace Hybrid in it's ability to provide frictionless growth?

I don't have a definitive answer here, though I think the project came out a success. The challenges that came up show
me that I need to dig deeper into React Native. Though, I'm inclined to think that any tradeoff in time will be minimal.

My [HOP slide deck](https://pitch.com/public/06c5f583-7c6c-4199-ae29-94204861a47f) that talks about the challenges and
solutions.

---

## News

05/04/2022: Blog online
04/28/2022: Released [react-native-responsive-layout](https://www.npmjs.com/package/@sklink/react-native-responsive-layout) for my HOP demo with Commit today!
04/20/2022: Officially started with [Commit](https://commit.dev)

[...see all news](./news)
