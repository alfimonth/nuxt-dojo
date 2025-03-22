<script setup></script>

<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Dojo</NuxtLink>
        <!-- Output the page content -->
        <div>
          <slot />
        </div>

        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
