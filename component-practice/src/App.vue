<template>
  <h1>{{ greeting }}</h1>
</template>

<script>
export default {
  name: 'app',
  data: function() {
    return {
      greeting: 'Hi, Clark!'
    };
  }
};
</script>