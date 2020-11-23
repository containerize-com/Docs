---
date: '2020-08-06'
author:
  display_name: xwiki:XWiki.farooqsheikh
draft: 'false'
toc: true
title: Choose a Right Open Source Discussion Forum
linktitle: Choose a Right Open Source Discussion Forum
menu:
  docs:
    parent: common-how-tos
lastmod: '2020-08-06'
---

# Introduction #

In this article, we will discuss how to choose a right open source discussion forum. Discussion forums can be used not only for products support but also help community to participate in product bugs. In this way, Discussion forums are a great tool to build a community of a company's products.

In order to choose an open source discussion forum, we'll base on below article which sets general guidelines for open source project selection:

[https:~~/~~/docs.containerize.com/common-how-tos/choose-a-right-open-source-product/](https://docs.containerize.com/common-how-tos/choose-a-right-open-source-product/)

# Evaluate Open Source Discussion Forum Options #

## Hunt Popular Open Source Discussion Forums ##

When we Google "Open Source Discussion Forum", some of the prominent top results include:

* Rank 1 - Discourse: https://www.discourse.org , https://github.com/discourse/discourse
* Rank 4 - Flarum: https://flarum.org , https://github.com/flarum/flarum
* Rank 5 - Vanilla: https://vanillaforums.com/en/software , https://github.com/vanilla/vanilla

When we check open source popularity on GitHub, we'll get below ranking:

* Top Most Popular - Discourse: https://github.com/discourse/discourse (Stars 28775, Forks 6505)
* 2nd Most Popular - Flarum: https://github.com/flarum/flarum (Stars 9201, Forks 1010)
* 3rd Most Popular - Vanilla: https://github.com/vanilla/vanilla (Stars 1995, Forks 675)

By looking at Google and GitHub, the ranks and popularity are same so we can conclude that Discourse is the most popular and top ranked discussion forum.

## Crosscheck Popularity and Reviews ##

In this section, we cross check popularity and reviews on some comparison and review sites.

Product Hunt:

* Discourse: https://www.producthunt.com/posts/discourse-2-0 (Upvotes 485)
* Flarum: https://www.producthunt.com/posts/flarum-5 (Upvotes 205)
* Vanilla: Not Available

Alternative To:

* Discourse: https://alternativeto.net/software/discourse/ (105 Likes)
* Flarum: https://alternativeto.net/software/flarum/ (52 Likes)
* Vanilla: https://alternativeto.net/software/vanilla/ (20 Likes)

Hacker News:

* Discourse: https://news.ycombinator.com/item?id#14247848 (218 Points)
* Falrum: https://news.ycombinator.com/item?id#14247848 (163 Points)
* Vanilla: Not Available

By looking at the above 3 review sites, the ranking is crosschecked and remains unchanged after this review.

## Compare Features and Quality ##

In this section, we'll have a look at the features and quality.

Discourse:

*  Features List: https://www.discourse.org/features
* Live Site: https://meta.discourse.org

Flarum:

*  Features List: https://flarum.org/features/
* Live Site: https://discuss.flarum.org

Vanilla:

* Features List: https://vanillaforums.com/en/features/forums/ , https://docs.vanillaforums.com/help/
* Live Site: https://vanillaforums.com/

If we compare the features and the live sites, we can conclude that above three forums provide modern and trendy features with the following high level difference:

* Discourse forums provide the most features like theming, mobile first, notifications, single sign on etc.
* Flarum is a little behind Discourse but they have more features on their roadmap e.g Single Sign on is missing at Flarum as of now.
* Vanilla offers many features but some of the features only belong to its commercial offering called Vanilla Cloud. e.g Browse through [Help Docs](https://docs.vanillaforums.com/help/) to see which features belong to Vanilla cloud only.

Based on the features review done in this section, we can keep the ranking still same. i.e Discourse at #1, Flarum at #2, Vanilla at #3. Since Vanilla offers some critical forum features at only Vanilla Cloud so we can drop Vanilla after this review as we are only interested in full open source discussion forum.

## Assess Team Repute ##

In this exercise, we'll try to assess repute of the teams behind Discourse and Flarum.

Discourse Team: https://www.discourse.org/team.html
Flarum Team: https://github.com/flarum/flarum/graphs/contributors , https://github.com/tobyzerner, http://tobyzerner.com

By looking at the Team Leads of the above projects, we can see that Discourse Team Lead (Jeff Atwood) is more experienced in the field of forum softwares being cofounder of successful community websites like Stack Overflow, where as Flarum Team lead (Toby Zerner) is relatively new in this field. Based on this assessment, we can keep Discourse at #1 and Flarum at #2.

## Extensibility Options ##

Both Discourse and Flarum provide extensibility frameworks and community contributes their extensions:

Discourse: https://www.discourse.org/plugins
Flarum: https://discuss.flarum.org/t/extensions

## Licensing Model ##

Discourse: https://github.com/discourse/discourse/blob/master/LICENSE.txt (GPL 2)
Flarum: https://github.com/flarum/flarum/blob/master/LICENSE (MIT)

If you want to monetize Discourse, then its license (GPL 2) requires you to open source your customizations as well. On the other hand, Flarum distributes its open source project with MIT so you can monetize it without obligation like open sourcing your customizations.

# Conclusion #

As long as you want to use a winner open source software for your own needs, Discourse is the best option. If you want to monetize Discourse as well, then you will have to open source your commercial offering. However, if you don't have an RoR team and want to earn money without open sourcing commercialized version of a discussion forum, Flarum may suite your needs.

# Related Articles #

* [Choose a Right Open Source Project](/common-how-tos/choose-a-right-open-source-product/)
