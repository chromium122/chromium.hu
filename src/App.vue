<script setup lang="ts">
import Header from "./components/Header.vue";
import Personal from "./components/Personal.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
    <div class="top">
        <Header></Header>
        <Personal></Personal>
        <Contact></Contact>
    </div>
    <div class="bottom">
        <Footer></Footer>
    </div>
</template>

<style>
h2 {
    font-weight: normal;
    margin-bottom: 12px;
}

.highlighted {
    color: #fff;
}

p {
    color: #aaa;
}
</style>
