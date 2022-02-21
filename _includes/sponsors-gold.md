<div class="member-list">
  <div>
  {% for sponsor-gold in include.data %}
    <a class="member-logo" href="{{ sponsor.url }}" rel="sponsored">
      <img src="{{ sponsor.url }}" alt="{{ sponsor.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
