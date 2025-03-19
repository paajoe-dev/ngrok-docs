<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-19T10:11:30Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2uWzP7PQ3OtIobSJo2ZnH9j6LfL",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uWzP7PQ3OtIobSJo2ZnH9j6LfL"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2uWzNj5cpM5WrJRk7ihRL4tNQNP",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2uWzNj5cpM5WrJRk7ihRL4tNQNP"
				},
				"enabled": true
			},
			"created_at": "2025-03-19T10:11:19Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2uWzNeg9ugaEZzDHdavO217O3yY",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2uWzNeg9ugaEZzDHdavO217O3yY"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
