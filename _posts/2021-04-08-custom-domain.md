---
layout: post
title: "Custom domains"
description: "FAQ about custom domains"
date: 2021-04-08 09:02:48 -0100
categories: faq custom domains
by: "noice.link"
icon: "link-2"
questions:
  - question: "How do I use a custom domain with noice.link?"
    answer: 'Put a CNAME record on your DNS pointing to "cname.noice.link" and you''re done! You should use Cloudflare and proxy the record, or you won''t have HTTPS.'
  - question: "Why won't I get HTTPS if I don't use Cloudflare?"
    answer: "To get HTTPS on a website you need to get a SSL certificate, and you need to generate one. At this moment we aren't able to do that, but maybe in future we will!"
  - question: "My custom domain doesn't work!"
    answer: "You have to wait 24 hours for the DNS changes to propagate. If you've waited 24 hours and it's still not working then join our Discord server and ask for help there!"
---
