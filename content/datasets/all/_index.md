---
# Course title, summary, and position.
linktitle: Datasets
summary: Get more information about our datasets
weight: 1

# Page metadata.
title: Datasets
# date: "2018-09-09T00:00:00Z"
# lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  all:
    name: Datasets
    weight: 1
---
## Background

Soon after we started doing text-based personality prediction we realized that the main problem is a lack of appropriate datasets.

The main reason is that it is very hard to find the labels, especially the ones that can be trusted. This can be traced back to privacy issues and high labeling costs.

Moreover, currently available datasets have many shortcomings:
* small in number of users and/or comments;
* limited expressivity (e.g., on Twitter);
* non-anonymity (e.g., on Facebook, which makes users more reluctant to express their opinions);
* low topic diversity (e.g., forums);
* heavy bias towards personality themes (e.g., personality forums);
* no demographics.

## Our approach

We identified Reddit as a source of data that addresses most of these concerns:
* there are many users who write **a lot** of comments;
* over a million of subreddits enable users to express their opinions on a multitude of topics;
* users are anonymous which means they write about **everything**;
* the quality of writing is above average for a social media site.

## [MBTI9k]({{< ref "/datasets/all/MBTI9k.md" >}})

In our first step, we compiled a large-scale dataset by using flairs -- short descriptors used by users to introduce themselves in a particular subreddit. Users write all kinds of relevant information in their flairs and in MBTI subreddits they disclose their own MBTI type. We used this to extract personality labels for our dataset -- first of its kind on Reddit.

[MBTI9k in more detail]({{< ref "/datasets/all/MBTI9k.md" >}}).

## [PANDORA]({{< ref "/datasets/all/pandora.md" >}})

Our latest dataset -- PANDORA -- is a natural step forward. As MBTI is not seen as a relevant model in personality psychology, we introduced Big 5 labels. We also addressed the other major shortcoming which is the lack of demographic variables. These are especially important for two reasons: (1) they are often the source of biases in NLP models and (2) personality traits are much harder to infer based on text than demographics which means they have to be controlled for in order to avoid coming to wrong conclusions.

[PANDORA in more detail]({{< ref "/datasets/all/pandora.md" >}}).




## Dataset Request Form
#### Feel free to contact us if you need one of our datasets for your research

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeKVBhkYrabBiHVoC0Wd1M7kX6oPEUc_DqXG6cPhz-nF4oXPw/viewform?embedded=true" width="640" height="1944" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>