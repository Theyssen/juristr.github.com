---
type: post
title: Scale React Development with Nx
date: 2020-10-27T23:04:02+01:00
lead: Learn about scaling React development with Nx, with my free Egghead course
url: /blog/2020/10/scale-react-dev-with-nx
draft: false
image: /blog/assets/imgs/egh_scalingreactnx.png
categories:
  - reactjs
  - tooling
tags:
  - reactjs
  - tooling
comments: true
---
{{<intro>}}
I'm super happy to announce the release of my latest Egghead course on scaling React development with Nx. Let me briefly dive into what the course is about, why I targeted it specifically to React.js developers and who should watch it!
{{</intro>}}

<!--more-->

{{< postad >}}

{{<toc>}}

> **Disclaimer 1:** I actually work at Nrwl since January and was able to record this course as part of our 20% time, where we work on open source and other stuff. 
>
> **Disclaimer 2:** I've been an Nx user for much longer, even before joining Nrwl, simply because I'm convinced it helps developers in a variety of different ways to be more productive and create higher quality outcomes.

## Click to check out the course

{{<egghead-course uid="playlists/scale-react-development-with-nx-4038" lesson_img="/blog/assets/imgs/egh_scalingreactnx.png" >}}

I'm a huge fan of the Egghead illustrations, designed by Egghead's Art Directory [Maggie Appleton](https://twitter.com/Mappletons). And so I asked her about the story behind the illustration and what drove her inspiration when creating it.

Since Nrwl is themed around Narwhals. Maggie searched for some ocean-themed approach. Thus, the base of the logo represents a coral reef, as an analogy to Nx bundling together different organisms (technologies) into one cohesive ecosystem. You can think of the various sea organisms as being the different technologies around Angular, React.js and Node. Also, given Nrwl is themed around Narwhals this is really on point :smiley:.

## What's in the course?

<iframe height="200px" width="100%" frameborder="no" scrolling="no" seamless src="https://player.simplecast.com/6f83d912-2595-4d5b-9851-aaeb46232951?dark=true"></iframe>

This is a super **beginner-friendly** course, so if you never heard about Nx before, don't worry. In the course I start with showing you how to install Nx, how to generate and setup a new "Nx workspace", and I'll walk you through the various configuration options.

To have a more real world scenario, I'm actually building a small tiny React.js application and as we go, we use Nx CLI commands to make our life easier in building that app. That includes **code generation** with the so-called "schematics" that scaffold a new React application as well as Node backend application for us. The result: we don't have to worry about the actual configuration, **it just works**.

Since in the course we build multiple apps, a React.js frontend and Node backend, I'll walk you through how Nx structures such architectures into **apps** and **libs**. That's one powerful concept that helps you scale development as things get more complex.\
Another core concept is the **dependency graph** which not only allows you to visualize the structure of your workspace but also helps Nx to optimize build/test/lint runs and to make sure they're as fast as possible.

If you think that was all, then you should definitely have a look at the last set of lessons of the course, where we dive into how **affected commands** and **distributed computation caching** can help you speed up your CI and developer productivity :wink:.

## What do you mean by scaling?

In a traditional setup with tools like CRA or the Angular CLI, you tend to generate one single application and you'll probably divide that one into various folders representing your feature areas.

As your application grows in size and features, you might get more people and teams to work on it, and very soon you'll realize that it becomes difficult to scale the development, first because of the "monolithic" structure, and second because your build, test and lint times start to take increasingly more time.

While Nx works for small projects, it has been designed from the very beginning to really **shine for large monorepos**. If I would have to break it down into just a couple of points, then Nx helps to scale by

* dividing workspaces into apps and libs
* making code sharing trivial via that app & lib structure
* optimizing commands to run fast and only run when needed

## I'm a React.js dev, why should I watch this?

Nx is more than just a CLI tool that helps you kick-start your new React project. It will rather help you in the challenge of developing your project as you progress. Nx is extending its native React support, already supporting \[Next.js](https://nx.dev/latest/react/plugins/next/overview) natively, and having plugins for \[Gatsby](https://github.com/nrwl/gatsby) and \[React Native](https://github.com/nrwl/nx-react-native). 



All in all, Nx helps

* generate code and configuration, s.t. you don't have to bother about it
* combines modern tools like React, Storybook and Cypress to a cohesive and modern developer experience
* helps design scalable architectures by dividing your code into apps and libs
* understand your workspace via a powerful dependency graph tool
* optimize your command execution time, via smart commands and computation caching



Nope, Nx is a general purpose development tool, designed to help scale development especially on large monorepos. It actually emerged as an extension to the Angular CLI, but evolved to be much more than just an improved CLI on top of the Angular ecosystem. As of writing this article, Nx supports the Angular and React ecosystem out of the box, with more coming.

## I Wanna learn more!

Sure! Here are some resources you should definitely check out:

* [nx.dev documentation site](https://nx.dev)
* [Nrwl Youtube Channel](https://www.youtube.com/c/Nrwl_io/videos)
* [Nx GitHub repository](https://github.com/nrwl/nx)
* [Nx Cloud for distributed caching](https://nx.app)