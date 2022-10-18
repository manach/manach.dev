---
layout: "@layouts/BlogPostLayout.astro"
title: 30 days of webdev, day 4 
description: There, I fixed it
publishDate: Tuesday, Oct 18, 2022
image: "../../assets/dogComputer.jpg"
imageAlt: A golden retriever sitting at a computer, looking happy and confident
---

I fixed the image problems. I learned several things:

* MOST IMPORTANT--npm run dev != npm run build && serve dist
* Markdown files cannot use components. It appears that Astro layout files which wrap markdown files can't either.
* Import aliases in markdown frontmatter in Astro will work for the layout field, but not for the image field. I believe this means import aliases only work for the layout field, but I haven't checked this yet.
* .mdx files support components and imports. I haven't decided whether the learning benefits and performance benefits re: image optimization are important enough to me to migrate. They're not today, that's for sure.

I may do the navbar and footer today. I might not. Right now it's break time. 

<div class="flex items-center justify-center">
  <img class="prose prose-img:max-w-full h-auto object-center" src="../../assets/wolverines.jpg" alt="A young white man in secondhand camo stands on a ridgeline, brandishing an AK-47. The caption reads, 'Wolverines!'" />
</div>

<!-- ![A young white man in secondhand camo stands on a ridgeline, brandishing an AK-47. The caption reads, "Wolverines!"](../../assets/wolverines.jpg) -->