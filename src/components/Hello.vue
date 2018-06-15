<template lang="pug">
  div
    slot
    p {{ msg }}
</template>

<script>
export default {
  data() {
    return {
      msg: 'Hello World'
    };
  }
};
</script>

