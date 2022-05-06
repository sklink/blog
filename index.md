---
layout: default
title: "Blog"
---


Random learnings and thoughts while working as a full-stack startup developer.
{: style="color:gray; font-style: italic; text-align: center;"}

---

## Building for Frictionless Growth
### *First-Class Native Mobile and Desktop Web*

Whether you're working on a tight budget or have decided to hone in an [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product){:target="_blank"},
you're going to face the challenge of cutting back scope, often with dramatic effect.

The technical challenge of cutting back scope is to create an **extensible solution** that leaves room for **growth without
friction**. With this, you can timeline growth into the dream scope, which is a powerful tool for generating
buy-in on your cuts.

One of these pieces that often gets cut is support for a first-class experience on both desktop and mobile. This is
especially true if mobile needs to have a solid user experience with a native implementation.

Before exploring React Native, my solution here was to create a React boilerplate that sits on top of a hybrid mobile
ecosystem. This, combined with responsive layout design using [Material UI (MUI)](https://mui.com){:target="_blank"}, allowed me to promise a
swift path to first-class experience in the environment that had fallen to second-class priority.

The gap left here is that Hybrid Mobile is second-class in itself. Of all the downsides, animation performance stands
out to me the most.

#### Question: Can React Native provide frictionless growth into cross-platform experiences, as a Hybrid wrapper does?

[Commit](https://commit.dev){:target="_blank"} has given me the opportunity through the HOP (Hackathon Onboarding Project) to work with
Expo and React Native to see if I can replicate my approach here for frictionless growth into first-class cross-platform
experiences.

While my crutch, MUI, is not supported, there are [alternatives](https://reactnativeelements.com/){:target="_blank"},
[[2]](https://akveo.github.io/react-native-ui-kitten/){:target="_blank"}, [[3]](https://reactnativepaper.com/){:target="_blank"}.
Surprisingly though, none of these provided the responsive layout foundation that MUI does,
[Container](https://mui.com/material-ui/react-container/#main-content){:target="_blank"} and
[Grid](https://mui.com/material-ui/react-grid/#main-content){:target="_blank"}.

For this, I decided to build [react-native-responsive-layout](https://www.npmjs.com/package/@sklink/react-native-responsive-layout){:target="_blank"}
as a way to learn about any barriers to my cross-platform design aspirations.

#### Answer: Likely... though some trade-offs. Come back later for a comprehensive answer!

I don't have a definitive answer here, though I think the project came out a success. The challenges that came up
demonstrated that I need to dig deeper into React Native. Though, I'm inclined to think that any tradeoff in time for a
native experience will be minimal.

My [HOP slide deck](https://pitch.com/public/06c5f583-7c6c-4199-ae29-94204861a47f){:target="_blank"} talks about
the challenges and solutions.

