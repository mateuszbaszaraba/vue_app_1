<template>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <router-link tag="b-navbar-brand" to="/">CarShop</router-link>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <router-link tag="b-nav-item" to="/shop">Shop</router-link>
        <router-link tag="b-nav-item" to="/portfolio">Portfolio</router-link>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item-dropdown text="Save & Load" right>
          <b-dropdown-item href="#">Save</b-dropdown-item>
          <b-dropdown-item href="#">Load</b-dropdown-item>
        </b-nav-item-dropdown>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>