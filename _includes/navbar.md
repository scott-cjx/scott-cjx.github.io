<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Scott CJX</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse d-lg-flex" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        {% for item in site.data.navbar.items %}
          <li class="nav-item"><a class="nav-link" href="{{ item.link }}">{{ item.name }}</a></li>
        {% endfor %}
      </ul>
    </div>
  </div>
</nav>

<!-- Offcanvas Sidebar for Mobile -->
<div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Menu</h5>
    <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
    <ul class="navbar-nav">
      {% for item in site.data.navbar.items %}
        <li class="nav-item"><a class="nav-link" href="{{ item.link }}">{{ item.name }}</a></li>
      {% endfor %}
    </ul>
  </div>
</div>

<!-- Bootstrap CSS & JS (needed for styling and toggle functionality) -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
