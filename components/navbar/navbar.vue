<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a
      class="navbar-brand"
      href="#"
    >
      Navbar
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>

    <div
      id="navbarSupportedContent"
      class="collapse navbar-collapse"
    >
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <nuxt-link
            to="/"
            class="nav-link"
          >
            Home
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            to="/users"
            class="nav-link"
          >
            Users
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link
            to="/posts"
            class="nav-link"
          >
            Posts
          </nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
