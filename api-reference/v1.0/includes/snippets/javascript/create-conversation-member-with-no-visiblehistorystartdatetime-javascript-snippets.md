---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const conversationMember = {
    '@odata.type': '#microsoft.graph.aadUserConversationMember',
    'user@odata.bind': 'https://graph.microsoft.com/v1.0/users/8b081ef6-4792-4def-b2c9-c363a1bf41d5'
};

await client.api('/chats/19:cf66807577b149cca1b7af0c32eec122@thread.v2/members')
	.post(conversationMember);

```