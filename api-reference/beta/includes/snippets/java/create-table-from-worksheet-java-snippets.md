---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

String address = "";

boolean hasHeaders = False;

graphClient.me().drive().items("{id}").workbook().worksheets("{id|name}").tables()
	.add(address,hasHeaders)
	.buildRequest()
	.post();

```