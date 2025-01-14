---
title: "Hello World"
date: 2024-01-31
draft: false
description: "Hello world, a new beginning."
---

> History doesn't repeat itself but it often rhymes.
>
> -- Mark Twain

## A new beginning

I have the very same feeling but twelve years later..

A different context, society, personal circumstances.. but the same hunger feeling of learning new technologies, opening new horizons, and new job opportunities for this new stage. I don't know where this path goes, but I know it is time to explore it.

Like years ago, after finishing my studies and my first experiences as a professional developer, I'm starting a blog.

By that time, I had it clear I wanted to learn Drupal and, by the way, sort the ideas I learned on the path. Today it is not that clear, but the only way is starting this path.

## From Wordpress to Hugo

My first blog was done in Wordpress. I already had some experience with PHP and I was influenced by the extended idea of "If you want a blog, Wordpress it is the perfect tool that", it was the perfect match for someone like me who is not really experienced in design or CSS. The decision was made: A Wordpress site, I'd buy a domain/hosting and thanks to already free themes I'd have my blog ready to expose anything that could be interesting for others like me on their way of learning Drupal.

Like those days, I had a need: Starting a blog. Nowadays there are tons of technologies in the market to fulfill my need:

* CMS: Drupal, Wordpress, etc..
* Online blogging platforms: [Medium](https://medium.com/) or [dev.to](https://dev.to/)
* Job-related social Networks:[Linkedin](https://www.linkedin.com) or [Xing](https://www.xing.com/)
* Static sites

Finally, Thanks to the Drupal Community in Slack, I discovered [Hugo](https://gohugo.io/ "Hugo official site") and with it, I had the opportunity of being in contact with a static site generator tool.

## Why Hugo?

By building my site in Hugo, I covered all my requirements one by one:

### Own my content

I'd own my content and not any other platform would get the benefits, if any, with ads, etc.. At the same time, I wouldn't lose my content in case of business closure, hacking, etc..

### Built-in a different technology out of Drupal.

Don't take me wrong, I love Drupal. However, as professional developers, we need to be always aware of what's new in terms of languages, paradigms, and technology. Hugo is a static site generator, which is a new approach for me. I've heard [Jamstack](https://jamstack.org/) approach or tools like [Tome](https://tome.fyi/) or [Jekyll](https://jekyllrb.com/). Unfortunately, I've never had the opportunity to play around with them. Now it is my chance.

### Simple and easy to be set up.

Hugo is a consolidated tool; it has tons of available [themes](https://themes.gohugo.io/) and a [Getting started guide](https://gohugo.io/getting-started/) really easy to follow. In addition, there are already several Docker images like [Hugomods/hugo](https://hugomods.com/docs/docker/) which make it really simple to have Hugo running locally without installing anything extra out of Docker.

### Cheap

Thanks to this new approach, I don't have the need to have my server or database; therefore, I no longer need to have hosting to locate my blog. Nowadays, there are plenty of options to host your static site for free like: [Netlify](https://www.netlify.com/) or [Github Pages](https://pages.github.com/). Hugo can be hosted easily on any of them. You can know more about Hosting and deployment Hugo at https://gohugo.io/hosting-and-deployment/

### Using modern strategies for deployment.

Hugo already provides a command to [deploy your Hugo project to Google Cloud, AWS, or Azure](https://gohugo.io/hosting-and-deployment/hugo-deploy/). But you can define your deployment pipeline on many other platforms. In my case, I'm using Github Pages and by using [Github Actions](https://docs.github.com/en/actions) I can build & deploy new updates to my site as soon as I push anything new to my main branch. There is not any need to build locally and having an additional artifacts repository to serve as a source for my site.

## You can do the same

Following, as a summary, you have a collection of links which were useful for me to set up this blog. I hope you like them:

* [Hugo official site](https://gohugo.io/)
* [Hugo's Getting started guide](https://gohugo.io/getting-started/)
* [Hugo's themes list](https://themes.gohugo.io/)
* [Hugo Blowfish theme (my choice)](https://themes.gohugo.io/themes/blowfish/)
* [Hugomods/Hugo Docker image](https://hugomods.com/docs/docker/)
* [Deploy Hugo to GitHub pages via Actions](https://gohugo.io/hosting-and-deployment/hosting-on-github/)