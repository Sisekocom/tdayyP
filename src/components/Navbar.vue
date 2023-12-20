<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <RouterLink to="/">
          <img
            class="img-fluid w-25"
            w-25
            src="https://th.bing.com/th/id/OIP.xHbxUYxMCq9bIm3lXZotzQHaHa?w=185&h=185&c=7&r=0&o=5&dpr=1.6&pid=1.7"
            alt="logo"
          />
        </RouterLink>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <RouterLink to="/" class="nav-link "> Home </RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/about" class="nav-link "> About </RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/resume" class="nav-link "> Resume </RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/projects" class="nav-link "> projects </RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/testimonials" class="nav-link "> Testimonials </RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/contacts" class="nav-link "> Contact </RouterLink>
            </li>

          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavbarComp",
};
</script>

<style scoped></style>
