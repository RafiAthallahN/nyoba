<template>
    <div>
      <header>
        <NuxtLink to="/products">Home</NuxtLink>
      </header>
  
      <!-- output -->
      <div>
        <slot />
      </div>
      <footer>
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
      </footer>
    </div>
  </template>
    
  <style scoped>
  .router-link-exact-active {
    color: aquamarine;
  }
  </style>