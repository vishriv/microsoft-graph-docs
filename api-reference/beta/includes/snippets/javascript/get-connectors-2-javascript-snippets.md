---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let connectors = await client.api('/print/connectors')
	.version('beta')
	.get();

```