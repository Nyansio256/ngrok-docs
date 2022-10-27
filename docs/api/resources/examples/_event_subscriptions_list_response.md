
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "id": "esb_2GjCRlhQrP4f1g0tK5YOGJk42Uj",
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2GjCRlhQrP4f1g0tK5YOGJk42Uj",
      "created_at": "2022-10-27T17:43:19Z",
      "metadata": "{\"environment\": \"staging\"}",
      "description": "ip policy creations",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2GjCRlhQrP4f1g0tK5YOGJk42Uj/sources/ip_policy_created.v0"
        }
      ],
      "destinations": [
        {
          "id": "ed_2GjCRjYMQ50ZusJNKj5yhIqQJdR",
          "uri": "https://api.ngrok.com/event_destinations/ed_2GjCRjYMQ50ZusJNKj5yhIqQJdR"
        }
      ]
    }
  ],
  "uri": "https://api.ngrok.com/event_subscriptions",
  "next_page_uri": null
}