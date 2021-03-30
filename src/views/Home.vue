<template>
    <div class="home">
        <div class="logo">
            <img alt="Millionaire logo" src="../assets/logo.png" />
        </div>

        <Container />
    </div>
</template>

<script>
// @ is an alias to /src
import Container from "@/components/Container.vue";

export default {
  name: "Home",
  components: {
    Container,
  },
};
</script>

<style scoped lang="scss">
    
</style>
