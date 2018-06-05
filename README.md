# wavefront-dashboards

## Description
This repository is intended as a home for curated dashboards for Wavefront created by me (@prydin) and the greater community.

## Importing a JSON-based dashboard
Dashboards are stored in JSON format. You can deploy a dashboard JSON file with the Wavefront API using the following command:

```
curl -v https://<wavefront_instance>.wavefront.com/api/v2/dashboard -d @<dashboard_file>.json \
  -H "Content-Type: application/json" -H 'Authorization: Bearer <wavefront_api_token>'
```

For more information, please see https://docs.wavefront.com/dashboards_managing.html


## Contents
tomcat.json - A richer dashboard for Tomcat application servers.
