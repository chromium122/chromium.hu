<template>
    <div>
        <h2>personal info</h2>

        <p>I'm <span class="highlighted">{{ age }} years old</span></p>
        <p><span class="highlighted">5+ years</span> of programming experience</p>
        <p>I code in <span class="highlighted">js</span> using <span class="highlighted">vue</span></p>
        <p>based in <span class="highlighted">Baranya, Hungary</span></p>
        <p>I speak <span class="highlighted">English and Hungarian</span></p>
    </div>
</template> 

<style scoped>
div {
    flex: 1;
}
p {
    color: #aaa;
    padding-bottom: 6px;
}
</style>

<script lang="ts" setup>
import { AgeFromDateString } from "age-calculator";
const age = new AgeFromDateString("2007-10-26").age;
</script>