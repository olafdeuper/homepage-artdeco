<template>
  <button>{{ text }}</button>
</template>

<script>
export default {
  props: {
    text: String,
  },
}
</script>

<style scoped>
button {
  margin: 2rem 2rem;
  background-color: var(--clr-brown-light);
  color: var(--clr-brown-dark);
  font-family: 'Limelight';
  font-size: 1rem;
  padding: 0.5rem 3rem;
  border: 0.2rem solid var(--clr-brown-dark);
  border-radius: 2.5rem;
  box-shadow:
    -0.07rem -0.001rem 0.01rem white,
    0.05rem 0.05rem 0.2rem black;
}

button:hover {
  color: var(--clr-brown-light);
  background-color: var(--clr-brown-dark);
}

button:active {
  color: var(--clr-brown-medium);
  background-color: var(--clr-brown-dark);
  box-shadow:
    -0.05rem -0.05rem 0.1rem black,
    0.05rem 0.05rem 0.1rem black,
    0.1rem 0.1rem 0.07rem white;
}
</style>
