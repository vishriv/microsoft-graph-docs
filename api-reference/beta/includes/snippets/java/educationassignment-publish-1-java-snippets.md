---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

String string = graphClient.education().classes("11012").assignments("19002")
	.getResourcesFolderUrl()
	.buildRequest()
	.get();

```