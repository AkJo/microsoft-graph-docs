---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

boolean securityEnabledOnly = True;

graphClient.directoryObjects("{object-id}")
	.getMemberGroups(securityEnabledOnly)
	.buildRequest()
	.post();

```