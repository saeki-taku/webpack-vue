<template>
  <p>{{ message }}</p>
</template>

<script>
export default {
  data: () =>  {
    console.log('Vuejs is isnstaled');
    return {
      message: 'Hey, this is Vue',
    };
  },
};
</script>

<style scoped>
p {
  color: green;
}

</style>
