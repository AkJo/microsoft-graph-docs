---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IEmailAppUsageVersionsUserCountsCollectionPage getEmailAppUsageVersionsUserCounts = graphClient.reports()
	.getEmailAppUsageVersionsUserCounts('D7')
	.buildRequest()
	.get();

```