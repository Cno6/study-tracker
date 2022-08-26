<template>
  <div>
    {{ hello }}
  </div>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {
    const hello = ref('single');

    return { hello };
  },
};
</script>

<style lang="scss" scoped></style>
