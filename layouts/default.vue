<template>
  <div>
    <nav class="navbar is-link is-fixed-top">
      <div class="navbar-brand">
        <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
          <span />
          <span />
          <span />
        </div>
      </div>

      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#about">
            <span class="icon">
              <i class="fas fa-info" />
            </span>
            <span>About</span>
          </a>
          <a class="navbar-item" href="#services">
            <span class="icon">
              <i class="fas fa-bars" />
            </span>
            <span>Services</span>
          </a>
          <a class="navbar-item" href="#resume">
            <span class="icon">
              <i class="fas fa-file-alt" />
            </span>
            <span>Resume</span>
          </a>
          <a class="navbar-item" href="#portfolio">
            <span class="icon">
              <i class="fas fa-th-list" />
            </span>
            <span>Portfolio</span>
          </a>
          <a class="navbar-item" href="#contact">
            <span class="icon">
              <i class="fas fa-envelope" />
            </span>
            <span>Contact</span>
          </a>
        </div>
      </div>
    </nav>

    <section class="main-content">
      <nuxt />
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="section-heading">
        <p>
          <strong>Bulma Personal Template</strong> by <a href="https://mubaidr.js.org">Muhammad Ubaid Raza</a>. The
          source code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    }
  }
}
</script>
