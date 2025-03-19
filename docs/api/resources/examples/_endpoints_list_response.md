<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-03-19T10:11:24Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2uWzNjmizkRQMdJqPqGijphGbts",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uWzNjmizkRQMdJqPqGijphGbts"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uWzOLAPlH9YO58B0dZZfpX9EX2",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-03-19T10:11:24Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2uWzOLAPlH9YO58B0dZZfpX9EX2",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-19T10:11:22Z",
			"hostport": "9a01c641bdf3.ngrok.paid:443",
			"id": "ep_2uWzO2PAOVdBhKxN7qLyNOm2DRx",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2uWzLOJrGawkI9KoKWuqZoLNHuP",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9a01c641bdf3.ngrok.paid",
			"tunnel": {
				"id": "tn_2uWzO2PAOVdBhKxN7qLyNOm2DRx",
				"uri": "https://api.ngrok.com/tunnels/tn_2uWzO2PAOVdBhKxN7qLyNOm2DRx"
			},
			"tunnel_session": {
				"id": "ts_2uWzO11nIlbTsAbSd7qfNzzDGOT",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2uWzO11nIlbTsAbSd7qfNzzDGOT"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-19T10:11:22Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9a01c641bdf3.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-19T10:11:20Z",
			"domain": {
				"id": "rd_2uWzNjmizkRQMdJqPqGijphGbts",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2uWzNjmizkRQMdJqPqGijphGbts"
			},
			"edge": {
				"id": "edgtls_2uWzNeg9ugaEZzDHdavO217O3yY",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2uWzNeg9ugaEZzDHdavO217O3yY"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2uWzNgaNgAwAccVEOcK132NAi2J",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-19T10:11:20Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
