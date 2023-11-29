<template>
  <div class="mx-auto container text-center">
    <h2>Books</h2>
    <p>This page is the book lists page.</p>

    <ul class="my-5 ring-4">
      <li>
        <nuxt-link to="/book/detail">Book 1</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/book/detail">Book 2</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/book/detail">Book 3</nuxt-link>
      </li>
    </ul>
    <nuxt-child />
  </div>
</template>

<script>
export default {
  name: 'BookPage',
  layout: 'Book'
}
</script>
