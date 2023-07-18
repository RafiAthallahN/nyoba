<template>
  <div>
    <header>
      <NuxtLink to="/">Home</NuxtLink>
      <nav>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products">Products</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

    <!-- output -->
    <div>
      <slot />
    </div>
  </div>
</template>
  
<style scoped>
.router-link-exact-active {
  color: aquamarine;
}
</style>