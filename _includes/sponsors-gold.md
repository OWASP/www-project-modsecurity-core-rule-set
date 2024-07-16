<div class="member-list">
  <div>
  {% for sponsor-gold in include.data %}
    <a href="{{ sponsor-gold.url }}" rel="sponsored">
      <img class="crs-gold-sponsor" src="{{ sponsor-gold.src }}" alt="{{ sponsor-gold.name }}" />
    </a>
  {% endfor %}
  </div>
</div>
