---
title: Tempo 0.4.0 internal review image released
date: 2019-05-23 09:59:00 -04:00
tags:
- tempo
---

Tempo has released the review image v0.4.0. This image is for internal evaluation only. To gain support please contact info#tempo.world.

## Changes

* Updated API for account ledgers, transactions and balances.
* Transaction validating optimization.
* Node discovery.

To retrieve the image:
```
docker run -d --name tnode -p 8765:8765 chainport/tempo-node
```

If you have older version of chainport/tempo-node, use `docker pull chainport/tempo-node` to update.
