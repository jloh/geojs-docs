# Endpoints

{% api-method method="get" host="https://get.geojs.io" path="/v1/ip/:ip" %}
{% api-method-summary %}
Get IP
{% endapi-method-summary %}

{% api-method-description %}
Lookup IP information
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="ip" type="string" required=false %}
Specific IP to lookup
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text
8.8.8.8
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=302 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text
1.1.1.1
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

