---
layout: post
title: "How to use the Yahoo Fanstasy Sports API"
subtitle: "learning how to use an API"
date: 2021-04-21 15:45:13 -0600
background: '/img/posts/post_01/suzuki.jpg'
---
## Intro
The goal of this project is to get matchup data from your Yahoo Fantasy league. I have a fatasy hockey league with my best friends that has been running for over 10 years and we all wanted to see the historical stats. To get the data, we will first be using the Yahoo Fantasy API, then transform it from XML data to tabular data using Python.

## Creating your Yahoo app and getting your key
The first step to use the API is to create your own [Yahoo app](https://developer.yahoo.com/apps/). When you create your app, make sure that you select Fantasy Sports and Read under the API permissions.


The next step is to open your newly created app and to copy your consumer key and consumer secret to a json file that should look like this.
```
{
    "consumer_key": "[your consumer key]",
    "consumer_secret": "[your consumer secret]",
}
```

## Connect to the API in Python
After saving 