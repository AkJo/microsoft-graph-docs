
```C#

GraphServiceClient graphClient = new GraphServiceClient();
var delta = await graphClient.Me.ContactFolders["{id}"].Contacts.Delta()
	.Select("displayName")
	.Request().GetAsync();

```