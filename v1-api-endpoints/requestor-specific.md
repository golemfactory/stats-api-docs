---
description: API endpoints to query requestor specific data.
---

# Requestor Specific

{% api-method method="get" host="https://api.stats.golem.network" path="/v1/requestors" %}
{% api-method-summary %}
All Requestors
{% endapi-method-summary %}

{% api-method-description %}
Returns the total list of requestors and the amount of tasks requested
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
The requestor ID and total tasks requested is returned.
{% endapi-method-response-example-description %}

```
[{"node_id": "0x8b9b05a578c06c5c3745be61a3fdcfe0cda30224", "tasks_requested": 5316.598295295329}]
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

