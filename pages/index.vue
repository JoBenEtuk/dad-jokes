<template>
  <div>
    <h2>Welcome to the site with the best corny dad jokes in the world</h2>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Welcome To Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
