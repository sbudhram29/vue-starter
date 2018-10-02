<template>
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
              {{ msg }}
          </h1>
          <h2 class="subtitle">
            Welcome to learning Vue. We are finally on the way.
          </h2>
        </div>
       </div>
    </section>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String,
  },
};
</script>
