---
title: Single Sign-On (SSO)
tags:
- Features
- Single Sign-On
category: help
menu:
  help:
    parent: features
    identifier: features-sso
aliases:
- /features/sso
---
## Single Sign-On Overview

Single sign-on (SSO) is how to let your users sign on to a third-party system (like a Vanilla Forum) without needing a separate username and password.

In broad terms, an SSO solution defines how two systems securely communicate the identity of a user that is switching between them. In the context of Vanilla, that means the forum securely talking to your site or identity provider to see if a user is signed in, and then automatically using that identity.

## Solutions We Offer

Vanilla offers three flavors of single sign-on:  [jsConnect](/help/features/sso/jsconnect) (our in-house solution), [SAML](/help/features/sso/saml), and [OAuth](/help/features/sso/oauth). SAML and OAuth are currently only available on cloud, and the latter requires services work to integrate specifically with your platform. We also offer custom SSO integrations at our highest plan tiers.

## Why jsConnect?

SSO systems are complex. Setting up your own SAML or OAuth system takes a lot of time, and generally is not feasible for small-to-medium business owners.

If you have a website that stores your user's identity and the only thing you need to integrate is a forum, jsConnect is a far simpler solution. This is because we've abstracted most of the work to our side of the connection, and provide sample code for making your side.

However, even our easier solution does require a developer on your team. A developer can typically set up the client side of jsConnect in 2-6 hours using our [technical documentation](/help/features/sso/jsconnect/overview). The only exception is **WordPress** users, for which we've developed a ready-to-go [SSO plugin](https://wordpress.org/plugins/vanilla-forums/).

Ready to learn more about jsConnect? Our [concepts overview](/help/features/sso/jsconnect) is where to head next.