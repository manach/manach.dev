---
layout: "@layouts/BlogPostLayout.astro"
title: 30 days of webdev, day 3
description: Hyperfocus and a couple long fights
publishDate: Monday, Oct 17, 2022
image: "@images/tailwindLogo.png"
imageAlt: The Tailwind CSS logo
---

Day 3 was a battle. 

When I'm debugging or working on some other problem with a clearly-defined endpoint, I have a hard time taking breaks if I feel like that endpoint is one I should reach easily. This can lead to marathon sessions with little consideration given for things like eating, drinking, and other basic bodily functions. It's not healthy but I have to admit that I love it.

#### Rabbit Hole: OBS

I had the idea that it might be nice to stream this project. So I tried to get OBS set up. This led to a longish problem-solving rabbit hole when OBS's "Mac OS Screen Capture" didn't work, and I finally settled on just using "Display Capture". I resisted it because it's marked as deprecated in the app, but then I found that Mac OS Screen Capture is actually in beta. It seems like an odd choice to deprecate a feature when its replacement is in beta (and clearly not working for at least some users), but I don't really know what I'm talking about so I won't judge.

#### Rabbit Hole: Using Tailwind to style dynamically-generated HTML

Since Tailwind uses inline stying, it's not immediately apparent how to get it to style pages generated dynamically from Markdown files. After a whole lot of digging I found [Tailwind Typography](https://tailwindcss.com/docs/typography-plugin), an official Tailwind plugin designed to do exactly what I was looking for. I don't know why it took me so long to find it, but I know I'm not the only one: I nearly copied another developer's approach to the problem and used Sass just for my blog posts. Anyway, that took a long time but it was super satisfying to find an official plugin that did exactly what I wanted. It works great, too.

#### Rabbit Hole: Learning enough CSS to get everything to look the way I wanted

This is going to be an ongoing problem, I think. Once I got Typography set up, it immediately solved my styling issues within the blog posts themselves, and then I spent another couple hours styling the blog post template and the list-of-blog-posts page. I'm not sure whether I'm going to detour and do a CSS course, but right now it feels like no.

*\*\*\*update: after spending another hour fiddling, it feels a step closer to yes*

#### Takeaways

* I definitely spent more time than my Maffetone-method guideline today, but it was fun and rewarding to get it done.
* I'll have to watch out for my perfectionism when I'm prototyping and remember that refactoring is the fastest way to code.
  * I *really* need to watch this. I'm not good enough at CSS yet to be fast, and it makes me crazy when I can't get things to look the way I want. Pomodoros are probably a starting point.
* I need to keep an eye out for good workflow rules like this in general.
* I want to start using a pomodoro timer again.

#### Tomorrow

Tomorrow I'd like to get the navbar and footer both set and styled, with responsive mobile-first design. Should be fun!
