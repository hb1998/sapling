---
id: s8aja
title: parseNodes
file_version: 1.1.2
app_version: 1.4.5
---

filters the nodes based on search and flattens the hierarchy
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 extension/src/webviews/service/RenderProvider.ts
```typescript
57         parseNodes(rawTree: INode = this.rawTree) {
58             this.rawTree = rawTree;
59             this.data = [];
60             this.filePathMap = new Map();
61             this.rowMap = new Map();
62             const result = this.filterData([this.rawTree]);
63             this.flattenData(result);
64         }
```

<br/>

This file was generated by Swimm. [Click here to view it in the app](/repos/Z2l0aHViJTNBJTNBcmVhY3QtY29tcG9uZW50LXRyZWUlM0ElM0FoYjE5OTg=/docs/s8aja).