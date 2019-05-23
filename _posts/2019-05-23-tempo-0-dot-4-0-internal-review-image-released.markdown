---
title: Tempo 0.4.0 internal review image released
date: 2019-05-23 09:59:00 -04:00
---

Tempo has released the internal review image v0.4.0.

## Features

1. Implemented nodes discovery which enables each node can find peers automatically.

2. Several improvements.

To retrieve the image:
```
docker run -d --name tnode -p 8765:8765 chainport/tempo-node
```

If you have older version of chainport/tempo-node, use `docker pull chainport/tempo-node` to update.