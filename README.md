#  **SyncDB**

> local-first key-value store with WebRTC replication

---

### Concept

SyncDB replicates between browsers & devices without servers—perfect for small multiplayer apps, offline tools, and experiments.

### Install

```bash
npm i syncdb-core
```

### Usage

```js
import { createDB } from "syncdb-core"

const db = createDB("notes")
db.set("title", "Hello Offline Web")
db.sync()
```

### Highlights

* conflict-free merges
* peer discovery via WebRTC
* optional relay server
* JSON storage

---

MIT ©
