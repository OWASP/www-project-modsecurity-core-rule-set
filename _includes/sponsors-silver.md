<div class="member-list">
  <div>
  {% for sponsor-silver in include.data %}
    <a class="member-logo" href="{{ sponsor-silver.url }}" rel="sponsored">
      <img src="{{ sponsor-silver.url }}" alt="{{ sponsor-silver.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
