
```C#

GraphServiceClient graphClient = new GraphServiceClient();
var privilegedOperationEvents = await graphClient.PrivilegedOperationEvents
	.Filter("requestType eq 'Activate'")
	.Request().GetAsync();

```