---
layout: index.njk
permalink: /
title: OSIA
description: Welcome to the Open Source Industry Australia
---
{% set feedEvents = "no" %}
{% set feedPosts = "yes" %}
{% set feedFeatured = "no" %}
{% set feedLimit = "6" %}
{% set feedColumns = "3" %}
{% include "partials/feed.njk" %}
