<template>
  <div>Hello {{ name }}!
     <InputText />
    <button @click="logout()">abc</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Vuex",
    };
  },
};
</script>
