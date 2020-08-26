<template>
  <section>
    <p class="claps">{{ claps }}</p>
    <button class="clap-btn" @click="clap" title="Clap for MDX">👏</button>
  </section>
</template>

<script>
export default {
  data() {
    return {
      claps: 0,
    };
  },
  methods: {
    clap() {
      this.claps += 5;
    },
  },
};
</script>

<style>
.claps {
  font-size: 3rem;
  color: #f0ab1f;
}

.clap-btn {
  padding: 1rem;
  border-radius: 100%;
  font-size: 2.5rem;
  cursor: pointer;
  border: 1px solid #f0ab1f;
  box-shadow: -4px -1px 18px -10px rgba(0, 0, 0, 0.75);
}

.clap-btn:focus {
  outline: none;
}
</style>