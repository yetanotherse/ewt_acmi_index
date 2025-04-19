# EWT ACMI
EWT ACMI (Elliott Waves Trading - Adaptive Crypto Market Index)

## What is ACMI
Hey everyone — I’ve been working on a side project for a few weeks now that I finally put out publicly. It’s called EWT ACMI (Adaptive Crypto Market Index), and the idea is to create a more realistic way to track overall crypto market health.

Most existing indexes include stablecoins like USDT, or synthetic tokens, or they let BTC and ETH dominate the entire index. Some are purely market cap weighted, some rebalance too infrequently, and most are black boxes with no real transparency.

So I decided to build one myself — something that excludes stablecoins, wrapped and pegged coins, and filters out low-quality or manipulated assets. It uses a hybrid weight model: 50% market cap, 30% volume, and 20% inverse volatility. BTC and ETH are capped at 15% each so they don’t completely distort the index, and everything is rebalanced weekly using the cleanest data available.

The result is something I think gives a much better feel for what’s really happening in the crypto market. You can view the live index chart here:

https://acmi.elliottwavestrading.com/

![ACMI Index](https://elliottwavestrading.com/wp-content/uploads/2025/04/Screenshot-2025-04-10-at-8.36.58%E2%80%AFPM.png?v=1744297663)

You can also compare any coin’s performance relative to the index to see if it’s actually outperforming or just riding the wave.

This is still a work in progress — it’s functional but not perfect. Sometimes a few coins are skipped if pricing data isn’t available that week, and I’m still working on UI/UX improvements, historical backfilling, and adding more advanced features over time.

If you're interested in this kind of stuff or you’ve felt the same way about the limitations of current indexes, check it out and let me know what you think. I’d love feedback and ideas from the community.

