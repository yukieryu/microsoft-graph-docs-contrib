---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/appCatalogs/teamsApps')
	.filter('externalId eq \'cf1ba4c7-f94e-4d80-ba90-5594b641a8ee\'')
	.get();

```