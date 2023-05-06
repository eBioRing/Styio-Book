# sum

{% tabs %}
{% tab title="Definition" %}
<pre><code><strong>R(k, v) +> ?(k.revenue != ~) [k.revenue: 0]
</strong></code></pre>
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="SDQL" %}
```
sum (<k, v> in R) if (k != None) then k.revenue else 0
```
{% endtab %}
{% endtabs %}