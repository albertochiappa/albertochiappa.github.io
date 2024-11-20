---
title: Auto-bidding for second-price auctions via Oracle Imitation Learning (OIL)

event: NeurIPS 2024 - Competition Track Workshops
event_url: https://nips.cc/virtual/2023/events/competition

location: Vancouver - Zoom
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: I will present our solution to the competition "Auto-Bidding in Large-Scale Auctions" by Alibaba
abstract: 'Online advertising has become one of the most successful business models of the internet era. Typically, advertisement slots are allocated through second-price auctions, where the top-N bidding advertisers secure the top-N slots and pay fees based on the next highest bids. The General Track of the 2024 NeurIPS competition "Auto-Bidding in Uncertain Environment" asked the participants to develop an automatic bidding algorithm for multi-slot second price auctions. The solution we propose consists of a teacher-student algorithm, where the teacher, which we call "oracle", has access to the complete information about the whole advertisement campaign, i.e., perfect knowledge about the future and past impression opportunities and bids. With full observability of the campaign information, finding the optimal bids can be cast as a multi-choice knapsack problem (MCKP) with a nonlinear objective function. By employing a heuristic greedy approach, the oracle algorithm can efficiently compute a near-optimal combination of advertisement slots to maximize the number of conversions, adhering to a budget and an efficiency constraint. We empirically validate that the performance of the oracle far exceeds that of bidding agents trained with offline or online reinforcement learning. This means that the bids output by the oracle can serve as a strong supervision signal for a student network. Therefore, we use behavior cloning to train a student network to imitate the bids output by the oracle policy, using exclusively the information available at the time of the decision. We call this method Oracle Imitation Learning (OIL). Despite the simplicity of the imitation approach, the auto-bidding agent trained with OIL outperforms both online and offline reinforcement learning algorithms in terms of sample efficiency, training stability, and final performance. Importantly, OIL shifts the complexity of training an auto-bidding agent from designing a sophisticated learning algorithm to enhancing the oracle’s performance. Using OIL, we ranked 1st in the official phase and 6th in the final phase of the NeurIPS 2024 Auto-bidding Challenge, competing against over 100 teams.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-14T15:30:00Z'
date_end: '2024-12-14T15:45:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Alibaba**](https://tianchi.aliyun.com/specials/promotion/neurips2024_alimama#/)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - Alibaba
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
