<div class="member-list">
  <div>
  {% for sponsor-gold in include.data %}
    <a class="member-logo" href="{{ sponsor-gold.url }}" rel="sponsored">
      <img src="{{ sponsor-gold.url }}" alt="{{ sponsor-gold.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
