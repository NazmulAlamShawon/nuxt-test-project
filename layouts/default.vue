<template>
  <div class="m-5 p-5">
    <header>
      <nav>
        <ul class="flex">
          <li class="mr-3 "><NuxtLink to="/">Home</NuxtLink></li>
          <li class="mr-3"><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/blog">Blogs</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <div>
      <slot />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
