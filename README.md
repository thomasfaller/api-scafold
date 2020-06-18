---
title: "API Scafold"
description: "Healthwave backend description"
---

# API Scafold

### description

- This should layout the structure of the backend services of Healthwave.
- There should be a clear separtion between API endpoints (that will eventually operate CRUD operations with our master database, with operations such as creating a client, etc.) and our webhooks endpoint that should act as pure webhooks with minimal orchestration involved.

A possible hiearchy could be the following :

<pre style="color:white; background-color: #333;">
.
├── api
│   └── v1
│       ├── customer
│       ├── member
│       ├── membership
│       ├── payment
│       └── scheme
└── webhooks
    ├── stripe
    ├── vend
    ├── woocommerce
    └── zendesk

</pre>
