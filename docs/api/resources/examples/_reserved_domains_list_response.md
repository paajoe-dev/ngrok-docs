<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-03-19T10:11:04Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3cgcbzvh6yxmgvazk.local-ngrok-cname.com",
			"created_at": "2025-03-19T10:11:04Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uWzLlEJ64eTT5gXDDXMa0Mzxca",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uWzLlEJ64eTT5gXDDXMa0Mzxca"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2uWzLUGfHdxL18Cuciw9Glf1mtb",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2uWzLUGfHdxL18Cuciw9Glf1mtb"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3cgcbzvh6yxmgvazk.local-ngrok-cname.com",
			"created_at": "2025-03-19T10:11:02Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2uWzLlAa3aYiw6H4vav6g1seIjK",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2uWzLlAa3aYiw6H4vav6g1seIjK"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
