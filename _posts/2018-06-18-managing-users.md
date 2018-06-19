---
layout: post
author: mittalyashu
title: Managing Users
description: Jekyll doesn't give any power to define users role, it is just a static site generator. But there's nothing to worry about, we got some additional options for you.
date: 2018-06-18 12:58:32 +0530
category: getting-started
image: /assets/images/users.jpg
---

Jekyll doesn't give any power to define users role, it is just a static site generator. But there's nothing to worry about, we got some additional options for you.

## Code hosting platform

You must be hosting your code somewhere online to publish your blogs, so why not use the power of that platform where you can restrict the users based on certain types of roles and premissions.

Once you will invite someone to your repository, you can set roles as **Maintainer**, **Developer** or a **Reporter**. It obvious **Guests** are not permanent members and for them you can set access expiration date for them.

Different set roles have it's own specific premission and restriction, to know more about it head over the code hosting platform's help page.

## Authors.yml file

It's a good idea to ask all of your users to fill out their user profiles, including bio and social links in the `authors.yml` file. These will populate rich structured data for posts and generally create more opportunities for themes to fully populate their design.

## Content Management System

If all the above options doesn't suits your taste and want to use some kind of **CMS** _(Jekyll Admin)_, try giving a thumbs up [on this issue](https://gitlab.com/mittalyashu/jasper/issues/7).
