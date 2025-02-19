<footer class="bg-dark text-white py-4 mt-5">
  <div class="container">
    <div class="row">
      {% for column in site.data.footer.columns %}
        <div class="col-md-4">
          <h5>{{ column.title }}</h5>
          <ul class="list-unstyled">
            {% for link in column.links %}
              <li><a href="{{ link.url }}" class="text-white">{{ link.name }}</a></li>
            {% endfor %}
          </ul>
        </div>
      {% endfor %}
    </div>
    <hr class="border-light">
    <p class="text-center">{{ site.data.footer.copyright }}</p>
  </div>
</footer>

<!-- Bootstrap CSS & JS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
