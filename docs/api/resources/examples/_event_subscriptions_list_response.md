<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2025-03-19T10:11:26Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2uWzOPtDZ0S2W9RlUJeFJm9rSs8",
					"uri": "https://api.ngrok.com/event_destinations/ed_2uWzOPtDZ0S2W9RlUJeFJm9rSs8"
				}
			],
			"id": "esb_2uWzOa2uBowuLsdJYKOn0wmwk2q",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2uWzOa2uBowuLsdJYKOn0wmwk2q/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2uWzOa2uBowuLsdJYKOn0wmwk2q"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
